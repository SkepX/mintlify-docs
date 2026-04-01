---
name: ascend-trading-api
description: Guides an agent to use the Ascend Trading API safely (markets, orderbook, positions, accounts, orders). Use when the user asks to call Ascend endpoints, place/cancel/close orders, fetch positions/PnL, or work with Ascend auth (x-api-key or wallet intent signatures).
---

# Ascend Trading API

## Quick start (how to operate)

- **Base URLs** (no trailing slash; use one consistently for `ASCEND_API_URL` / requests):
  - **Production**: `https://masumi-ascend-preview-mc952.ondigitalocean.app`
- **Prefer read-only first**: fetch market + orderbook + balance before placing orders.
- **Auth modes**
  - **Public endpoints**: no auth (examples: `GET /v1/markets`, `GET /v1/orderbook/{slug}`, `GET /v1/events/{slug}`, `GET /v1/ticker/{id}`, `GET /v1/leaderboard`).
  - **Agent discovery**: `GET /v1/auth/accounts` with `x-api-key` returns all linked addresses and balances (no address in the request).
  - **API key auth (common in this repo)**: send `x-api-key: <ASCEND_API_KEY>` for account- or order-related endpoints.
  - **Wallet intent signatures (required for some flows)**: some endpoints validate a deterministic “intent JSON” signed by the wallet (see `openapi.yaml` and signature middleware patterns in `src/`).

## Core workflow templates

### Market research (no auth)

1. `GET /v1/markets`
2. `GET /v1/markets/{slug}`
3. `GET /v1/events/{slug}?range=1D|1W|1M|ALL`

### Place an order (authenticated)

Before opening:
- Confirm **wallet address**, **chain_type**, and **available balance**.
- Pull current `mark_price` and/or orderbook to sanity-check the side and (for limit) trigger price.

Then:
- `POST /v1/order`
- Poll: `GET /v1/orders/{client_order_id}?type=MARKET|LIMIT`
- Monitor: `GET /v1/positions/{address}`

### Close / cancel

- **Close position**: `POST /v1/order/close` then poll `GET /v1/orders/{client_order_id}/close`
- **Cancel limit**: `POST /v1/order/cancel` then poll `GET /v1/orders/{order_id}/cancel`

## Safety rules (always follow)

- **Never trade without explicit user intent**: if the user asks for analysis only, do not place orders.
- **Validate limit logic** (probabilities are 0–1):
  - **YES LIMIT**: `trigger_price <= mark_price`
  - **NO LIMIT**: `trigger_price >= mark_price`
- **Rate limits**: expect `429` and honor `Retry-After` when present.
- **Address ownership**: under API-key auth, the server may reject addresses not owned by the API key (403).

## Output format (what to return to the user)

When the user asks for a trade, respond with:

```markdown
## Proposed action
- Side: YES|NO
- Type: MARKET|LIMIT (trigger_price if LIMIT)
- Margin: <number>
- Leverage: <number>
- Market: <slug>
- Address / chain: <address> / <chain_type>

## Pre-trade checks
- mark_price: <value>
- orderbook summary: best bid/ask + depth note
- balance check: <value>
- risk notes: liquidation/profit targets if returned by API

## Execution (only if user asked to execute)
- open order result: <success/client_order_id>
- polling outcome: accepted|error|timeout
```