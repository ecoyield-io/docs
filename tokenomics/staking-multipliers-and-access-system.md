# Staking, Multipliers & Access System

EcoYield’s staking model is designed to reward long-term commitment while keeping access to new projects open and fair.

It does two things at once:

1. Boosts yields for wallets that stake $EYE alongside LP tokens.
2. Controls access to early project raises through a two-stage system.

### 1. Staking & Yield Boosts

When investors fund projects, they receive LP tokens (their share of the vault). By staking $EYE tokens in the same wallet, they can boost their yield and improve their access score.

#### Staking Multipliers

Locking $EYE for longer multiplies its effect on the score:

| Lock Period | Multiplier |
| ----------- | ---------- |
| 1 month     | ×1.0       |
| 3 months    | ×1.5       |
| 6 months    | ×2.5       |
| 12 months   | ×4.0       |

This ensures short-term stakers still benefit, but long-term lockers gain a bigger edge without creating runaway inflation.

2\. Eye Power Ratio (Fairness Check)



EcoYield balances cash (LP tokens) and staked $EYE to prevent gaming:

* If EYE Power ÷ LP Tokens < 5%, the wallet is treated as LP-only → it earns its normal project yield but no boost.
* If EYE Power ÷ LP Tokens > 100%, any excess $EYE is not counted.



This keeps the system fair: whales can’t dominate by over-staking, and small LPs can still gain priority through staking for longer periods.

***

### 3. Stake Score

Your Stake Score decides two things:

* How much boosted yield you get.
* How much priority you get in future project allocations.\


Formula: Score = (LP Tokens^0.55) × (Effective EYE Power^0.45)\


### 4. Two-Stage Access System

Every new project raise is split into two stages:

#### Stage 1: Core Pool (Priority Access)

* Reserved for existing LPs and $EYE stakers.
* Allocation is distributed pro-rata by Stake Score.
* Example: if you hold 10% of the total Stake Score, you’re entitled to 10% of the Stage-1 allocation.
* Any unused allocation rolls into Stage-2.

#### Stage 2: Public Pool (Open Access)

* Open to new LPs and the wider market.
* Allocations distributed pro-rata by cash contributed.
* Existing LPs/stakers can also participate here, but on equal terms with new entrants.

This ensures:

* Long-term backers get rewarded.
* New investors can always enter.
* The DAO can adjust the Stage-1 / Stage-2 split (e.g. 70/30, 50/50) depending on demand.

***

### 5. Why This Matters

* Fair system: Rewards both early believers and new entrants.
* Sustainable growth: Prevents “whale games” while keeping TVL flowing in.
* Aligned incentives: Higher Stake Scores → higher yield boosts + better access.

In short: _Stake $EYE, boost your APY, and secure first access to the next wave of yield-generating projects._

***
