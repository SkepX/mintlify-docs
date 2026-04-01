## Base URLs

- Production: `https://api.ascend.trade`
- Masumi preview: `https://masumi-ascend-preview-mc952.ondigitalocean.app`
- Local: `http://localhost:8090`

## Endpoint map (from `openapi.yaml`)

### Markets / Prices (public)
- `GET /v1/markets`
- `GET /v1/markets/{slug}`
- `GET /v1/markets/{slug}/rolling`
- `GET /v1/markets/{slug}/ascend-comparison`
- `GET /v1/markets/{slug}/volume`
- `GET /v1/events/{slug}?range=...`
- `GET /v1/ticker/{id}`

### Orderbook (public)
- `GET /v1/orderbook/{slug}`

### Leaderboard (public)
- `GET /v1/leaderboard?limit=...&range=...`

### Accounts / Positions / Orders (authenticated in this repo)
- `GET /v1/auth/accounts` — API key only; lists all addresses + balances for that key
- `POST /v1/accounts`
- `GET /v1/accounts/{address}`
- `GET /v1/positions/{address}`
- `GET /v1/positions/pnl/{address}`
- `POST /v1/order`
- `POST /v1/order/close`
- `POST /v1/order/cancel`
- `POST /v1/order/closeAll`
- `GET /v1/orders/{client_order_id}?type=MARKET|LIMIT`
- `GET /v1/orders/{client_order_id}/close`
- `GET /v1/orders/{order_id}/cancel`

