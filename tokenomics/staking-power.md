# Staking Power

EcoYield’s staking mechanism balances fairness and incentives. Yield Tokens can boost their project yield and access priority on future vaults by staking $EYE - but with built-in checks to prevent abuse. The system uses a calculated Stake Score to determine yield boosts and project access.

* EYE Power Ratio ensures wallets aren’t unfairly weighted by oversized $EYE stakes.
* Stake Score blends Yield Tokens and $EYE power to rank contributors fairly.

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### Eye Power Ratio (Fairness Check)

EcoYield balances cash (Yield Tokens) and staked $EYE to prevent gaming:

* If EYE Power ÷ Yield Tokens < 5%, the wallet is treated as Yield Token-only → it earns its normal project yield but no boost.
* If EYE Power ÷ Yield Tokens > 100%, any excess $EYE is not counted.



This keeps the system fair: whales can’t dominate by over-staking, and small Yield Tokens can still gain priority through staking for longer periods.

***

### Stake Score

Your Stake Score decides two things:

* How much boosted yield you get.
* How much priority you get in future project allocations.\


Formula: Score = (Yield Tokens^0.55) × (Effective EYE Power^0.45)

***

### Why it Matters

* Fair for All Sizes: Prevents whales from crowding out smaller investors while still rewarding meaningful, long-term participation.
* Boosted Yield = Higher Returns: Stakers earn more from the same vault through fair boosts tied to their score.
* Future Access Advantage: Higher scores unlock early access and larger allocations in upcoming EcoYield projects — incentivising $EYE loyalty and sustained support.

