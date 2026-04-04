# Ascend Documentation

---

## Intro

# Start Here


A lot of action happens before a particular event outcome is even finalized. Narratives and opinions shift as new information emerges. With old trading models your only option for participation was indirect. Buy a stock, sell an option, wait for the outcome.

With Ascend, you now have the opportunity to trade on the probability of a particular outcome in real-time. Perpetually, with leverage.

## What is Ascend?

Ascend is an **events perpetuals platform** that enables **leveraged trading on probability prices**.


  [Image: Ascend Platform]


Traders take directional positions on **prediction percentages** across **outcomes, metals, commodities, stocks, and crypto**, using a **perpetual market structure** with **continuous pricing** and **deterministic settlement mechanics**. Markets on Ascend express exposure through **LONG / SHORT positions on probabilities**, while offering the **depth, flexibility, and tooling of a modern perpetuals exchange**.


## How Ascend Works


  #### Choose a Market
    Select an **outcome market** expressed as a percentage, covering **outcomes, metals, commodities, stocks, or crypto**.

    Each market represents the current probability price.

    Trade the probability you think the market is mispricing.
  

  #### Long or Short the Probability %
    Take a **LONG** position if you believe the probability will move higher, or a **SHORT** position if you believe it will move lower.

    Set your **position size and leverage** within the market's margin framework.

    Your exposure scales with leverage, while risk is governed by explicit market rules.
  

  #### Trade the Move
    As the probability price moves in your favor, **PnL scales with your leveraged exposure**.

    Positions update continuously, and you can **close or adjust at any time**, settling according to deterministic market mechanics.
  



<Card
  title="Next: Vision"
  icon="arrow-right"
  href="/start-here/vision"
>
  Understand why prediction perpetuals are the future of outcome markets

---

# 'Vision'


Ascend is built on a simple idea: **markets work best when outcomes can be traded freely, continuously, and at scale**.

Outcome prices are signals. They tell you what people collectively think will happen. When these signals are liquid and actively traded, they become one of the most reliable forms of market intelligence you can find.

Prediction markets have already proven this. They beat polls in elections. They anticipated macro data before official releases. They priced geopolitical risk faster than any other instrument. But despite being more accurate, they remain limited. Narrow participation. Constrained design. No scale.

That changes now.


## What Is Broken Today

Prediction markets work. But they hit real limits.


  #### Liquidity disappears outside headline events
    Presidential elections get millions in volume. But a Fed rate decision next month? A company hitting its earnings target? These markets exist on Polymarket and Kalshi, but orderbooks are thin. Try placing 50,000 USDC and slippage destroys your entry. Professional traders cannot deploy real size, so they stay away. The signal never forms.
  

  #### Positions are frozen until resolution
    You buy YES at 0.50 because you think there is an 80% chance. You might be right. But that capital is stuck until the event resolves. Could be 6 months. Could be a year. And if new information pushes your conviction to 95%, there is no efficient way to add exposure. Binary payoffs cap what you can do with strong conviction.
  

  #### No way to manage risk
    In traditional markets, you hedge. You scale in and out. You react to new information. In prediction markets, you bet and wait. News shifts probability by 20 points? You sell at whatever the thin orderbook offers, or you hold and hope.
  

  #### Sophisticated traders stay out
    Market makers and quant traders make markets efficient. They provide liquidity, tighten spreads, and arbitrage mispricings. But without leverage and proper risk tools, they stick to traditional derivatives. Prediction markets lose the participants who would make them most accurate.
  


The result: prediction markets function as **passive betting pools** when they could be **active trading venues**.


<Card
  title="Next: Core Concepts"
  icon="arrow-right"
  href="/core-concepts/outcome-probabilities"
>
  Understand how outcome probabilities work on Ascend

---

## Core Concepts

# 'Outcome Probabilities'


On Ascend, every market is priced as a probability between 0% and 100%.

This probability represents the market's collective assessment of how likely something is to happen. It is not an opinion. It is not a prediction from a single source. It is the aggregated result of continuous trading activity across all participants.

When you see a price of 62%, it means the market currently assigns a 62% likelihood to that outcome. When you see 35%, the market thinks it is less likely. When you see 88%, the market thinks it is highly probable.

You are not buying or selling an asset. You are taking a position on whether that probability will move up or down.


## Price Movement Is the Signal

Probability prices move as new information arrives and traders reassess.


  #### Price rising: 55% → 68%
    The market is becoming more confident this outcome will happen. Traders are buying YES, pushing the price up. New information may have increased the perceived likelihood.
  

  #### Price falling: 72% → 58%
    The market is becoming less confident. Traders are selling YES or buying NO. Something changed the collective expectation.
  

  #### Price stable: 64% → 65% → 63%
    No major new information. The market has reached temporary consensus around this probability.
  


Your PnL comes from these movements. If you go LONG at 55% and the price rises to 68%, you profit. If it drops to 45%, you lose. The final event resolution matters for settlement, but you can trade in and out based on probability movement alone.


## Why Percentages?

Percentages work because they are universal.

<Check>A 70% probability means the same thing whether you are trading an election, a Fed decision, or a crypto price target</Check>
<Check>No need to understand contract mechanics or notional values</Check>
<Check>Directional trading is intuitive: higher percentage means more likely, lower means less likely</Check>

This abstraction lets you focus on one question: **Where do I think this probability is going?**


## What Happens at Resolution?

When an event resolves, the probability snaps to its final value.

The winning outcome settles at **100%**. All other outcomes settle at **0%**.

If you are LONG on the winning outcome, your position settles at maximum value. If you are LONG on a losing outcome, it settles at zero.

But remember: you do not have to hold until resolution. You can exit anytime based on probability movement.


Resolution follows predefined rules announced at market creation. There is no discretionary judgment. The same inputs always produce the same settlement.



---

# 'Directional Outcome Trading'


On Ascend, you do not trade ownership of an asset or a fixed event contract. You take positions on how a probability will move over time.

This means you can express conviction in either direction:

<Check>**LONG** if you believe the probability will increase</Check>
<Check>**SHORT** if you believe the probability will decrease</Check>

Leverage allows you to scale exposure relative to posted margin, amplifying gains and losses according to market rules.


## SHORT Positions

A SHORT position expresses the view that a probability will decrease.


  ### Example: SHORT 68% → 60%
    You enter SHORT at 68%. The probability falls to 60%. You profit from the 8 point move.
  

  ### Example: SHORT 52% → 45%
    You enter SHORT at 52%. The probability falls to 45%. You profit from the 7 point move.
  


If the probability falls, a SHORT position gains.

If the probability rises, a SHORT position loses.


## Symmetric Exposure

LONG and SHORT positions on Ascend are structurally symmetric.

| Property | LONG | SHORT |
|----------|------|-------|
| Profits when | Probability rises | Probability falls |
| Loses when | Probability falls | Probability rises |
| Margin rules | Same | Same |
| Risk framework | Same | Same |
| Mark price reference | Same | Same |

This ensures fair and consistent exposure regardless of direction. No side has a structural advantage.


## Why This Matters

Leveraged LONG and SHORT trading on probabilities enables:

<Check>**Active participation** in prediction markets, not passive betting</Check>
<Check>**Scalable expression of conviction** through leverage</Check>
<Check>**Continuous price discovery** around changing probabilities</Check>

This is the core mechanic that transforms prediction markets into perpetual trading venues.


---

# 'PnL & Leverage Basics'


On Ascend, you profit or lose based on how the probability price moves relative to your entry price. This is scaled by your position size and leverage.


PnL updates continuously as prices change. You do not have to wait for event resolution to see gains or losses.



## PnL Examples


  #### LONG position, probability rises
    You open LONG at 50% with position size 1,000 USDC notional.

    Probability rises to 58%.

    ```
    PnL = +1 × 1,000 × (0.58 − 0.50)
        = +1 × 1,000 × 0.08
        = +80 USDC
    ```

    You are up 80 USDC.
  

  #### LONG position, probability falls
    You open LONG at 50% with position size 1,000 USDC notional.

    Probability falls to 44%.

    ```
    PnL = +1 × 1,000 × (0.44 − 0.50)
        = +1 × 1,000 × (−0.06)
        = −60 USDC
    ```

    You are down 60 USDC.
  

  #### SHORT position, probability falls
    You open SHORT at 65% with position size 1,000 USDC notional.

    Probability falls to 58%.

    ```
    PnL = −1 × 1,000 × (0.58 − 0.65)
        = −1 × 1,000 × (−0.07)
        = +70 USDC
    ```

    You are up 70 USDC.
  

  #### SHORT position, probability rises
    You open SHORT at 65% with position size 1,000 USDC notional.

    Probability rises to 72%.

    ```
    PnL = −1 × 1,000 × (0.72 − 0.65)
        = −1 × 1,000 × 0.07
        = −70 USDC
    ```

    You are down 70 USDC.
  



## Leverage Example

You have 100 USDC and want to go LONG at 50%.

<Tabs>
  <Tab title="5x Leverage">
    **Position notional:** 100 × 5 = 500 USDC

    Probability rises from 50% to 55% (5 point move).

    ```
    PnL = 500 × 0.05 = +25 USDC
    ```

    Return on margin: 25%
  </Tab>
  <Tab title="10x Leverage">
    **Position notional:** 100 × 10 = 1,000 USDC

    Probability rises from 50% to 55% (5 point move).

    ```
    PnL = 1,000 × 0.05 = +50 USDC
    ```

    Return on margin: 50%
  </Tab>
  <Tab title="20x Leverage">
    **Position notional:** 100 × 20 = 2,000 USDC

    Probability rises from 50% to 55% (5 point move).

    ```
    PnL = 2,000 × 0.05 = +100 USDC
    ```

    Return on margin: 100%
  </Tab>
</Tabs>

The same 5 point move produces 25, 50, or 100 USDC depending on leverage. This works in both directions. Losses scale the same way.


## Mark-to-Market

Positions are continuously marked to the mark price.

This means:

<Check>PnL updates in real time as probabilities move</Check>
<Check>Your equity (margin + unrealized PnL) changes constantly</Check>
<Check>Risk checks run against current mark price, not entry price</Check>

You always know where you stand. No waiting for settlement to see your position value.


<Card
  title="Next: Perpetual Market Structure"
  icon="arrow-right"
  href="/core-concepts/perpetual-market-structure"
>
  Learn how perpetual markets work without expiry

---

# 'Perpetual Market Structure'


Traditional prediction markets work like bets. You buy a position, wait for the event, and settle. The contract expires. The market closes.

Ascend works differently.

Markets on Ascend are **perpetual**. They do not expire on a fixed date. Positions persist until you close them or the market reaches its defined settlement condition. You can enter, adjust, or exit at any time.

This is the same structure used by the largest crypto derivatives exchanges, applied to prediction markets.


## Persistent Positions

Once you open a position, it remains active until one of three things happens:


  #### You close it
    You decide to exit. You take your PnL and move on.
  
  #### Risk conditions trigger closure
    If margin requirements are no longer met, the system may reduce or close your position to protect market integrity.
  
  #### The market settles
    The underlying event resolves and all positions settle at the final probability.
  


Until one of these occurs, your position stays open. You are not forced out by a calendar.


## Price Alignment Mechanisms

Perpetual markets need a way to stay anchored to reality. Without expiry forcing convergence, prices could drift from true probability levels.

Ascend solves this with two mechanisms:

<Tabs>
  <Tab title="Oracle Anchoring">
    Probability prices are sourced from external prediction markets and oracles. The **Index Price** represents the best available estimate of the true probability at any moment.

    Ascend does not invent prices. It references them.
  </Tab>
  <Tab title="Funding">
    When the traded price diverges from the Index Price, funding payments transfer between LONG and SHORT positions.

    If traders push the price too high, LONGs pay SHORTs. If traders push the price too low, SHORTs pay LONGs.

    This creates a continuous incentive to keep prices aligned with external signals.
  </Tab>
</Tabs>

These mechanisms allow perpetual markets to track probability accurately without requiring forced settlement.


## How Ascend Remains a Perp Despite Resolution

Some prediction markets do resolve. Elections happen. Decisions get announced. Events conclude.

Does resolution break the perpetual model?

No. Here is why:


  #### Perpetual until resolved
    Markets trade continuously right up until the resolution condition is met. There is no arbitrary expiry date forcing closure before the event.
  

  #### Not bound to timestamps
    Traditional contracts expire on a specific date regardless of whether the event has occurred. Ascend markets expire only when the actual outcome is known.
  

  #### No expiry cycles
    There are no quarterly expiries, no contract migrations, no liquidity fragmentation. One market, one orderbook, continuous trading.
  


Resolution is an endpoint, not an expiry. The market remains perpetual in structure even if it eventually settles.


<Card
  title="Next: Market Types"
  icon="arrow-right"
  href="/core-concepts/market-types"
>
  Learn about the different types of markets on Ascend

---

# 'Market Types'


Ascend supports three types of markets, each designed for different trading needs. All three share the same perpetual infrastructure, margin system, and orderbook mechanics. The difference is in what they track and how they settle.


### How Outcome Markets Work

Each outcome is priced as a probability between 0% and 100%.

- 0% means the market considers this outcome impossible
- 100% means the market considers this outcome certain
- Prices in between reflect the market's confidence level

You can go LONG (betting probability rises) or SHORT (betting probability falls) with leverage.


### Settlement

Outcome markets settle when the event resolves:

- Resolution source confirms the outcome
- Winning outcome settles at 100%
- Losing outcomes settle at 0%
- All positions close and PnL is finalized

You can exit anytime before settlement. You don't have to wait for the event.


### The Problem with Fixed Windows

Traditional prediction platforms handle recurring events with separate contracts:

- Each hour/day is a new contract
- When one expires, you must manually re-enter the next
- Liquidity fragments across time windows
- Profitable traders waste time and gas re-entering

This creates friction and splits liquidity.


### What Rolls Forward

When a position rolls:

- **Preserved:** Direction (LONG/SHORT), leverage setting
- **Updated:** Entry price (to new window's opening), margin (adjusted for realized PnL)
- **Realized:** PnL from completed window (added to your balance)


### Why Rolling Markets Matter

| Traditional | Rolling |
|-------------|---------|
| Re-enter every window | Position persists |
| Liquidity fragments | Liquidity concentrates |
| Manual management | Automatic continuation |
| Miss windows = miss opportunities | Always positioned |

Rolling markets turn recurring predictions into continuous exposure.


### What You're Trading

In macro markets, you trade a probability, not the underlying asset.

**Example:**

Market: "Gold bullish sentiment"

- Current price: 62%
- This means the market assigns 62% probability to gold having upward pressure

You're not buying gold. You're taking a position on whether the probability of gold strength will rise or fall.

If you think gold sentiment will increase, go LONG. If you think it will decrease, go SHORT.


### Rolling Probabilities for Macro

Macro markets use the same rolling mechanism as crypto directional markets:

- Probability prices evolve continuously
- Positions persist indefinitely by default
- Periodic checkpoints may realize PnL
- No forced expiry

You maintain exposure to macro directional probabilities without managing contract rolls.


## Comparison

| Feature | Outcome Markets | Rolling Markets | Macro Markets |
|---------|-----------------|-----------------|---------------|
| What you trade | Event probability | Recurring direction | Asset sentiment |
| Settlement | When event resolves | Each time window | Rolling / continuous |
| Position persistence | Until settlement | Rolls automatically | Rolls automatically |
| Typical timeframe | Days to months | Hours to days | Days to months |
| Examples | Elections, Fed decisions | Hourly BTC up/down | Gold, S&P sentiment |


<Card
  title="Next: Index & Oracle Design"
  icon="arrow-right"
  href="/pricing-oracles/index-oracle-design"
>
  Learn how external probability sources anchor Ascend markets

---

## Pricing & Oracles

# 'Index & Oracle Design'


Ascend does not invent probabilities. Every probability price on the platform is anchored to external sources through the Index Price.

The Index Price represents the best available estimate of the true probability at any moment. It is derived from real prediction markets, oracle feeds, and external data sources. This design ensures that Ascend markets remain grounded in actual market information rather than internal speculation.


## Oracle Sources

Each market defines its oracle sources at creation. The sources depend on the market type.

<Tabs>
  <Tab title="Event Markets">
    For elections, policy decisions, and discrete outcomes:

    - Polymarket prices
    - Kalshi prices
    - Other regulated prediction venues

    These platforms already price thousands of outcomes with real liquidity. Ascend references them rather than recreating the signal.

    **Example:** A market on "Who will win the 2028 election?" might pull prices from both Kalshi and Polymarket, where thousands of traders have already expressed their views.
  </Tab>
  <Tab title="Asset-Linked Markets">
    For crypto, equities, metals, and commodities:

    - Directional sentiment oracles
    - Spot price feeds from major exchanges
    - Composite probability indicators

    These oracles translate asset price expectations into probability format.

    **Example:** A market on "Will BTC be above $100k by end of month?" might reference sentiment data from multiple crypto prediction sources combined with options flow data.
  </Tab>
  <Tab title="Composite Markets">
    For markets that combine multiple signals:

    - Weighted baskets of prediction sources
    - Cross-referenced oracle inputs
    - Custom aggregation logic per market

    No single source dominates. The Index Price reflects consensus across inputs.

    **Example:** A macro market on "US recession in 2025?" might combine prediction market prices, bond yield signals, and economic indicator oracles.
  </Tab>
</Tabs>


## Aggregation Logic

The Index Price is computed as a weighted average of valid oracle inputs.

```
Index Price = Σ (weight × oracle price)
```

Where:

- Each oracle provides a probability and timestamp
- Weights are assigned based on liquidity depth, historical accuracy, and update frequency
- All weights sum to 1

**Example:**

A Fed rate cut market has three oracle sources:

| Source | Price | Weight |
|--------|-------|--------|
| Kalshi | 64% | 0.5 |
| Polymarket | 62% | 0.4 |
| Oracle C | 68% | 0.1 |

```
Index Price = (0.5 × 64) + (0.4 × 62) + (0.1 × 68)
            = 32 + 24.8 + 6.8
            = 63.6%
```

Kalshi has the highest weight because it has the deepest liquidity. Oracle C has low weight because it has less trading activity.


## Update Cadence

Index Prices update whenever:

- One or more oracle inputs publish new data
- A minimum time threshold is reached
- Market-specific update conditions are satisfied

All updates are timestamped and recorded. The update frequency depends on the underlying oracle infrastructure and market parameters.

For fast-moving markets, updates may happen every few seconds. For slower markets, updates may be less frequent.


## Why Oracle-Sourced Pricing Matters

Oracle-sourced pricing gives Ascend several advantages:

- **Credibility**: Prices reflect real market consensus, not internal opinion
- **Interoperability**: Ascend markets connect to the broader prediction ecosystem
- **Decentralization**: No single venue controls price formation
- **Transparency**: Oracle sources and weights are defined at market creation

This design allows Ascend to offer leveraged trading on probabilities while maintaining the integrity that prediction markets require.


---

# 'Mark Price System'


The Mark Price is the internal reference price used for all critical trading operations on Ascend. It determines your unrealized PnL, margin requirements, and liquidation thresholds.

While the Index Price reflects external oracle data, the Mark Price applies smoothing and stabilization to protect traders from short-term noise and sudden spikes. This separation is fundamental to operating leveraged prediction perpetuals safely.


## How the Mark Price Is Constructed

The Mark Price is derived from the Index Price through three layers:


  #### Smoothing (EMA Filter)
    An Exponential Moving Average dampens short-term fluctuations in the Index Price.

    ```
    Mark_t = Mark_t-1 + λ × (Index_t − Mark_t-1)
    ```

    Where:
    - Mark_t-1 is the previous Mark Price
    - Index_t is the current Index Price
    - λ is the smoothing factor (between 0 and 1)

    **What λ means in practice:**

    | λ Value | Behavior | Use Case |
    |---------|----------|----------|
    | 0.1 | Very slow, very stable | Low-volatility event markets |
    | 0.5 | Balanced | Most markets |
    | 0.9 | Fast, less smoothing | High-frequency markets |

    Lower λ means more stability and slower reaction. Higher λ means faster response to Index changes. Each market defines its own λ based on expected volatility.
  
  #### Price Clamping
    The Mark Price is constrained to stay within a defined range of the Index Price.

    ```
    If |Mark − Index| > Clamp Limit:
        Mark = Index ± Clamp Limit
    ```

    This prevents the Mark Price from drifting too far from reality while still providing stability. Clamp limits are market-specific and defined in percentage terms (e.g. ±1%).

    **Why clamping matters:**

    Without clamping, a very low λ could cause the Mark Price to lag far behind during a sustained move. A trader could enter at 50%, watch the Index move to 70%, but see their Mark Price stuck at 55%. The clamp ensures Mark stays within a reasonable distance of truth.
  
  #### Precision Rounding
    The final Mark Price is rounded according to market precision rules (e.g. 2 decimal places).

    This ensures consistent PnL calculation, deterministic settlement, and alignment between the UI and trading engine.
  



## Example: Clamp Triggered

Now assume a sudden Index spike:

- Index Price = 72.0% (sudden jump)
- Previous Mark Price = 60.5%
- λ = 0.5
- Clamp Limit = ±1.0%

**Step 1: Apply EMA**

```
Mark_raw = 60.5 + 0.5 × (72.0 − 60.5)
         = 60.5 + 5.75
         = 66.25
```

**Step 2: Check Clamp**

```
|66.25 − 72.0| = 5.75
5.75 > 1.0 → Clamp triggered
```

The Mark Price would be 5.75% away from the Index, which exceeds the 1% clamp limit.

**Apply Clamp:**

```
Mark = Index − Clamp Limit
     = 72.0 − 1.0
     = 71.0
```

**Final Mark Price = 71.0%**

The clamp pulled the Mark Price closer to the Index, ensuring it does not lag too far behind during a large move.


## Mark Price Behavior in Different Conditions


  #### Normal trading
    The Mark Price tracks the Index Price closely with slight smoothing. Traders experience stable PnL that reflects genuine market movement.

    **Example:** Index moves from 60% to 62% over 5 minutes. Mark Price follows, reaching 61.8% in the same period.
  

  #### Sudden Index spike
    The EMA filter slows the Mark Price response. If the spike is temporary, the Mark Price may never fully reach the spike level before the Index returns to normal.

    **Example:** Index spikes from 60% to 75% for 30 seconds, then returns to 62%. Mark Price rises to maybe 65%, then settles back to 62%. No liquidations triggered by the spike.
  

  #### Sustained Index move
    The Mark Price converges toward the new Index level over time. The clamp ensures it cannot lag too far behind during sustained moves.

    **Example:** Index moves from 60% to 80% over 10 minutes and stays there. Mark Price follows, staying within 1% of Index throughout the move.
  

  #### Oracle irregularity
    If oracle data becomes stale or erratic, the Mark Price maintains stability based on recent valid data. The clamp prevents extreme divergence.

    **Example:** One oracle goes offline. Index Price recalculates with remaining sources. Mark Price continues smoothly without sudden jumps.
  



## Why This Matters

The Mark Price system allows Ascend to:

- Anchor markets to external truth through the Index Price
- Protect traders from noise and manipulation through smoothing
- Maintain stable, continuous trading even during volatile probability updates
- Apply perpetual-style risk management to probability markets

Without this separation, leveraged prediction markets would be vulnerable to the same issues that plague thin liquidity venues: flash crashes, manipulation, and unfair liquidations.

The Mark Price makes leveraged prediction perpetuals viable.


---

## Risk & Margin

# 'Margin Model'


Every position on Ascend is backed by margin. Margin is the capital you commit to a trade. It enables leveraged exposure, absorbs losses, and defines the boundary of your risk.

Understanding margin is essential to managing positions effectively.


## Initial Margin

Initial Margin (IM) is the capital required to open a position.

It is determined by your position size and selected leverage:

```
Initial Margin = Position Notional / Leverage
```

**Example:**

You want to open a 1,000 USDC notional position at 10x leverage.

```
Initial Margin = 1,000 / 10 = 100 USDC
```

You post 100 USDC to control 1,000 USDC of exposure.


  ### Lower leverage (5x)
    1,000 USDC position requires 200 USDC margin. More cushion against adverse moves.
  

  ### Higher leverage (20x)
    1,000 USDC position requires only 50 USDC margin. Less room for error.
  



## Position Equity

Your position equity represents the real-time value of your position. It fluctuates constantly as prices move.

```
Equity = Initial Margin + Unrealized PnL − Accrued Funding
```

Where:

- Initial Margin is what you posted when opening the position
- Unrealized PnL changes as the Mark Price moves
- Accrued Funding is the net funding paid or received

**Example: Price moves in your favor**

You open a LONG position with 100 USDC margin. The probability moves up, generating +30 USDC unrealized PnL. You have paid 2 USDC in funding.

```
Equity = 100 + 30 − 2 = 128 USDC
```

Your position equity is now 128 USDC.

**Example: Price moves against you**

Same position, but the market moves against you by 30 USDC instead:

```
Equity = 100 + (−30) − 2 = 68 USDC
```

Your equity dropped to 68 USDC.


## Isolated Margin

Ascend uses isolated margin at the position level.

This means:

- Each position has its own margin
- Risk is fully contained within each position
- One position cannot draw collateral from another
- Losses on one position do not affect others

**Example:**

You have two positions:

| Position | Margin | Status |
|----------|--------|--------|
| BTC directional LONG | 100 USDC | Healthy |
| Election outcome SHORT | 50 USDC | Near liquidation |

If the election position gets liquidated, you lose at most 50 USDC. Your BTC position is completely unaffected.

This isolation makes risk predictable. You always know the maximum you can lose on each trade.


## Managing Your Margin

You can actively manage margin on open positions:


  #### Add margin
    Deposit additional margin to increase your equity buffer. This moves your liquidation price further away from the current price.

    **When to use:** Your position is under pressure but you believe the market will reverse.
  

  #### Remove margin
    Withdraw excess margin from a profitable position. This frees up capital for other trades.

    **When to use:** Your position is healthy and you want to deploy capital elsewhere.
  

  #### Reduce position
    Close part of your position to lower your maintenance margin requirement and improve your margin ratio.

    **When to use:** You want to reduce risk without closing entirely.
  



<Card
  title="Next: Liquidation Logic"
  icon="arrow-right"
  href="/risk-margin/liquidation-logic"
>
  Learn when and how positions get liquidated

---

# 'Liquidation Logic'


Liquidation is a protective mechanism that closes positions when they no longer have sufficient margin to absorb further losses. It protects the market from negative equity and ensures the system remains solvent.

Liquidation is not punitive. It is a mechanical safety process that applies equally to all positions.


## Liquidation Price

The liquidation price is the probability level at which your position hits the liquidation threshold.

**For a LONG position:**

```
Liquidation Price = Entry Price − (Initial Margin − Maintenance Margin) / Position Size
```

**For a SHORT position:**

```
Liquidation Price = Entry Price + (Initial Margin − Maintenance Margin) / Position Size
```

The difference between Initial Margin and Maintenance Margin represents how much loss your position can absorb before liquidation.


## Example: SHORT Position Liquidation

You open a SHORT position:

- Entry Price: 60%
- Position Notional: 1,000 USDC
- Initial Margin: 100 USDC (10x leverage)
- Maintenance Margin: 25 USDC (2.5% rate)

**Calculate liquidation price:**

```
Liquidation Price = 0.60 + (100 − 25) / 1,000
                  = 0.60 + 0.075
                  = 67.5%
```

**What happens as price rises:**

| Mark Price | Unrealized PnL | Equity | Margin Ratio | Status |
|------------|----------------|--------|--------------|--------|
| 60% | 0 | 100 USDC | 4.0 | Healthy |
| 63% | −30 USDC | 70 USDC | 2.8 | Healthy |
| 65% | −50 USDC | 50 USDC | 2.0 | Caution |
| 67% | −70 USDC | 30 USDC | 1.2 | Warning |
| 67.5% | −75 USDC | 25 USDC | 1.0 | Liquidation |

At 67.5%, the SHORT position hits the liquidation threshold.


## Partial vs Full Liquidation

Depending on market configuration, Ascend may use different liquidation approaches:

<Tabs>
  <Tab title="Partial Liquidation">
    The system gradually reduces your position size to restore equity above maintenance margin.

    **How it works:**

    1. A portion of your position is closed
    2. This realizes some loss but frees up margin
    3. If equity recovers above maintenance, liquidation stops
    4. If not, another portion is closed

    **Example:**

    Your 1,000 USDC position hits liquidation. The system closes 400 USDC worth. Your new position is 600 USDC with lower maintenance requirement. If equity is now healthy, the remaining 600 USDC stays open.

    **Benefit:** You may keep part of your position if the market stabilizes.
  </Tab>
  <Tab title="Full Liquidation">
    The entire position is closed at once.

    **When it happens:**

    - Equity cannot be restored through partial liquidation
    - Market conditions require immediate risk reduction
    - Position size is too small to partially liquidate efficiently

    **Example:**

    Your 200 USDC position hits liquidation. Partial liquidation is not practical at this size. The full position is closed and remaining margin (minus fees) is returned.

    **Outcome:** Position is fully closed. You receive any remaining margin.
  </Tab>
</Tabs>


## What the Insurance Fund Does

Sometimes a position moves so fast that it cannot be liquidated before equity goes negative. The insurance fund covers these shortfalls.

**Example:**

- Your equity hits 25 USDC (liquidation threshold)
- Before liquidation executes, price moves further
- Position closes at −10 USDC equity (negative)
- Insurance fund covers the 10 USDC shortfall

The insurance fund is built from:

- Liquidation fees
- A portion of trading fees
- Protocol reserves

This ensures counterparties are always made whole, even in extreme conditions.


## Key Points

- Liquidation triggers when equity ≤ maintenance margin
- Mark Price is used for liquidation checks (not Index Price)
- Partial liquidation may preserve some of your position
- Liquidation fees apply and fund the insurance pool
- You can avoid liquidation by managing leverage, margin, and position size

Liquidation is a last resort. Active position management keeps you in control.


---

## Market Mechanics

# 'Funding & Price Alignment'


Funding is a continuous mechanism that keeps the traded price aligned with the external reference price. Without funding, perpetual markets could drift away from reality since there is no expiry date forcing convergence.

On Ascend, funding transfers value between LONG and SHORT positions based on how far the Mark Price has diverged from the Index Price. This creates a natural incentive for prices to stay anchored to external probability signals.


## The Two Prices

Funding is calculated from the relationship between two prices:

| Price | What It Represents |
|-------|-------------------|
| Index Price | External reference from oracles. The "true" probability. |
| Mark Price | Internal trading price. Smoothed and stabilized. |

When these prices diverge, funding kicks in to push them back together.


## Who Pays Whom

The funding direction depends on which price is higher:

<Tabs>
  <Tab title="Mark > Index (LONGs pay)">
    The traded price is higher than external reality suggests.

    - LONGs pay funding to SHORTs
    - This discourages new LONG positions
    - It encourages traders to SHORT, pushing price down
    - Price converges back toward Index

    **Example:** Mark is 64%, Index is 62%. LONGs are paying for the premium.
  </Tab>
  <Tab title="Mark < Index (SHORTs pay)">
    The traded price is lower than external reality suggests.

    - SHORTs pay funding to LONGs
    - This discourages new SHORT positions
    - It encourages traders to go LONG, pushing price up
    - Price converges back toward Index

    **Example:** Mark is 58%, Index is 62%. SHORTs are paying for the discount.
  </Tab>
  <Tab title="Mark ≈ Index (minimal funding)">
    Prices are aligned.

    - Funding rate is near zero
    - Neither side pays significant funding
    - Market is in equilibrium

    **Example:** Mark is 62.1%, Index is 62%. Funding is negligible.
  </Tab>
</Tabs>


## Funding Intervals

Funding accrues continuously but is applied at regular intervals:

- Intervals are defined per market (e.g. every hour, every 8 hours)
- The funding rate shown is typically the rate per interval
- Payments are automatically added to or deducted from your equity

**Example:**

A market has hourly funding. The current funding rate is 0.01% per hour.

- Over 24 hours, you would pay/receive approximately 0.24% of your position notional
- This assumes the rate stays constant (it fluctuates based on price divergence)


## Funding During Different Conditions


  #### Normal markets
    Mark and Index stay close. Funding rates are small. Neither side pays much.

    **Example:** Mark oscillates between 61.8% and 62.2% around a 62% Index. Funding flips between small positive and negative values.
  

  #### Strong directional bias
    Many traders pile into one side. Mark diverges from Index. The crowded side pays heavy funding.

    **Example:** Breaking news makes everyone go LONG. Mark rises to 68% while Index is 64%. LONGs pay 0.05% per hour to SHORTs. This eventually attracts SHORTs and rebalances the market.
  

  #### Low activity periods
    Few trades occur. Mark stays close to Index. Funding rates naturally approach zero.

    No artificial pressure is introduced. The market remains fair even when quiet.
  



## Key Points

- Funding transfers value between LONGs and SHORTs based on price divergence
- LONGs pay when Mark > Index; SHORTs pay when Mark < Index
- Payments are proportional to position notional
- Funding accrues continuously and applies at regular intervals
- Heavy funding on one side signals a crowded trade


---

# 'CLOB & Matching'


Ascend uses a Central Limit Order Book (CLOB) for price discovery and trade execution. Traders place bids and offers at specific probability prices, and the matching engine pairs compatible orders.

This is the same orderbook model used by major exchanges. No AMM, no bonding curves, no protocol-owned liquidity. Just traders trading with each other.


## Order Types

Ascend supports standard order types:

<Tabs>
  <Tab title="Limit Orders">
    You specify a price and size. Your order rests on the book until:

    - It gets matched with an incoming order
    - You cancel it
    - It expires (if you set a time limit)

    **Example:** You place a limit order to LONG 500 USDC at 62%. Your order sits on the bid side. If someone comes in willing to SHORT at 62% or lower, you get filled.

    **Use when:** You want a specific price and are willing to wait.
  </Tab>
  <Tab title="Market Orders">
    You specify only size. Your order executes immediately at the best available price.

    **Example:** You place a market order to LONG 500 USDC. The best ask is 64%. You get filled at 64%.

    **Use when:** You want to enter or exit immediately and accept the current price.
  </Tab>
</Tabs>


## Partial Fills

Orders can be partially filled when available liquidity is insufficient.

**Example:**

You place a market order to LONG 1,000 USDC. The orderbook looks like:

| Price | Ask Size |
|-------|----------|
| 64% | 400 USDC |
| 65% | 300 USDC |
| 66% | 500 USDC |

Your order fills across multiple price levels:

- 400 USDC at 64%
- 300 USDC at 65%
- 300 USDC at 66%

Total: 1,000 USDC filled at an average price of approximately 64.9%.

This is called "walking the book." Large orders may experience slippage if liquidity is thin.


## Order Validation

Every order is validated before being accepted:


  #### Margin check
    You must have sufficient margin to cover the position if the order fills. Orders that would exceed your available margin are rejected.
  

  #### Leverage check
    The resulting position must stay within the market's maximum leverage. Orders that would create excessive leverage are rejected.
  

  #### Price bounds
    Orders at extreme prices (far from current market) may be rejected or flagged. This prevents fat-finger errors and manipulation.
  

  #### Size limits
    Orders must meet minimum size requirements and cannot exceed maximum position limits.
  



## Why CLOB for Prediction Markets

The orderbook model provides:

- **Transparent pricing**: All bids and offers are visible
- **Fair execution**: Price-time priority treats everyone equally
- **No slippage from curves**: You trade at discrete prices, not along a bonding curve
- **Real depth**: You can see exactly how much liquidity exists at each price level
- **Professional compatibility**: Market makers and algorithmic traders can participate using familiar infrastructure

This is what allows Ascend to attract the liquidity that prediction markets need.


<Card
  title="Next: Settlement & Resolution"
  icon="arrow-right"
  href="/market-mechanics/settlement-resolution"
>
  Learn how markets resolve and positions settle

---

# 'Settlement & Resolution'


While Ascend markets trade continuously like perpetuals, many prediction markets are tied to real-world events that eventually resolve. When an event outcome becomes known, the market settles and all positions are finalized.

Settlement is deterministic, transparent, and rule-based. The same inputs always produce the same outcomes.


## Resolution Sources

Each market defines its resolution sources at creation. These are the authorities that determine the final outcome.

<Tabs>
  <Tab title="Official Sources">
    Government announcements, regulatory filings, official results.

    **Examples:**
    - Federal Reserve press releases for rate decisions
    - State election boards for election results
    - SEC filings for corporate events

    These are considered highest reliability.
  </Tab>
  <Tab title="Prediction Market Consensus">
    Resolution based on how major prediction markets resolve.

    **Examples:**
    - Polymarket resolution
    - Kalshi resolution
    - Multiple platform consensus

    Used when Ascend references external prediction markets.
  </Tab>
  <Tab title="Oracle Networks">
    Decentralized oracle systems that aggregate multiple data sources.

    **Examples:**
    - Chainlink data feeds
    - UMA optimistic oracle
    - Custom oracle implementations

    Used for asset-linked and composite markets.
  </Tab>
</Tabs>


## Settlement Process

When resolution occurs:


  #### Resolution triggered
    The resolution source confirms the outcome. This may happen immediately (election called) or after a delay (official certification).
  
  #### Final price set
    The settlement price is set based on resolution criteria. For binary markets, this is 0% or 100%.
  
  #### Positions settled
    All open positions are closed at the settlement price. PnL is calculated using entry price vs settlement price.
  
  #### Balances updated
    Final PnL is applied to trader balances. Margin is released. The market transitions to settled state.
  



## Exiting Before Settlement

You do not have to hold until settlement. You can close your position at any time before resolution.

**Why exit early:**

- Lock in profits if the price has moved in your favor
- Cut losses if conviction has changed
- Free up margin for other trades
- Avoid settlement uncertainty

**Example:**

You went LONG at 55%. Price rises to 72% as the event approaches. You can:

- Hold until settlement and hope for 100%
- Close now and take the 17 point profit

If you close at 72%, your PnL is locked in regardless of the final outcome.


## Edge Cases


  #### Ambiguous outcomes
    Resolution criteria are designed to avoid ambiguity. If an edge case occurs that criteria do not clearly address, the market may use a fallback resolution mechanism defined at creation.

    **Example:** A market on "Will X happen by Dec 31?" might specify that the resolution source's timezone is UTC, eliminating ambiguity.
  

  #### Delayed resolution
    Some events take time to resolve (recounts, appeals, verification). Markets remain open for trading until official resolution. Prices may converge toward the expected outcome during this period.
  

  #### Voided markets
    In rare cases, a market may be voided if the underlying event is canceled or resolution becomes impossible. Voided markets return all traders to their entry state. No profit or loss is realized.

    **Example:** An election market where the election is postponed indefinitely.
  



## Deterministic Settlement

Settlement on Ascend is fully deterministic:

- The same resolution input always produces the same settlement price
- The same position always produces the same PnL
- No discretionary intervention is required
- All calculations are transparent and verifiable

This ensures fairness and predictability for all participants.


---

# 'Edge Cases'


## Binary Compression Near Extremes

As probability prices approach 0% or 100%:

- Marginal price movement becomes asymmetrical
- Small probability changes can have outsized impact
- Liquidity naturally thins near extremes

Ascend handles this by:

- Applying consistent tick sizing
- Maintaining symmetric LONG / SHORT mechanics
- Preserving deterministic PnL behavior


## Sudden Truth Revelation

Some events resolve instantaneously and unambiguously.

Examples:

- Official results released
- Market-moving announcements

Behavior:

- Index Price updates immediately
- Mark Price converges deterministically
- Settlement proceeds according to predefined rules

No discretionary delay is introduced.


## Oracle Irregularities

### Stale Oracle Data

If one or more oracle sources stop updating:

- Stale inputs are excluded from Index Price calculation
- Remaining valid sources continue to contribute
- Mark Price smoothing limits sudden jumps

If insufficient valid sources remain, the market may enter a **restricted state** until updates resume.


<Card
  title="Back to Start"
  icon="arrow-left"
  href="/start-here/what-is-ascend"
>
  Return to the beginning


---

## $ASCEND

# Tokenomics


## $ASCEND Utility

$ASCEND is the native utility token powering Ascend Markets, an events perpetuals platform.

It plays a central role in aligning traders, liquidity providers, and long term protocol participants.


## Exclusive Market Access

$ASCEND holders receive **exclusive access to select markets, modes, and features**:


  #### Early Access
    Early access to newly launched prediction and event perpetual markets.
  

  #### High-Conviction Markets
    Exclusive high conviction markets with limited participation.
  

  #### Advanced Trading Modes
    Higher leverage presets, special settlement windows, and more.
  

  #### Experimental Markets
    Invitation-only experimental markets before public rollout.
  



## Rewards & Incentives Allocation

| Ecosystem | Allocation | $ASCEND Tokens |
|-----------|------------|---------------|
| Cardano + Midnight | 50% | 1,100,000 |
| Solana | 20% | 440,000 |
| EVM (ETH + L2s) | 20% | 440,000 |
| Other (BTC, HYPE, etc.) | 10% | 220,000 |
| **Total** | **100%** | **2,200,000** |


Incentives are allocated across ecosystems based on strategic alignment and trading activity. Cardano and Midnight receive a foundational allocation, while Solana, EVM, and other ecosystems are incentivized based on participation and growth potential.


---

