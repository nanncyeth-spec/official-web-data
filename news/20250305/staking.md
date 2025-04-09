# Guide to HSK Staking: Maximizing Your Returns

**Date:** March 5, 2025  
**Category:** User Guide  
**Impact Level:** Medium

## Overview

Since the launch of HSK staking, we have received valuable feedback from our users. Based on those suggestions, we're committed to continually improving the staking product's rewards and user experience.

This article will explain the economic structure, exchange rate mechanism, and the relationship between HSK and stHSK in the staking system. If you have any further questions, feel free to comment — we value your input and will keep improving.

---

![Your Assets, Your Rewards!](https://cdn.jsdelivr.net/gh/HashkeyHSK/official-web-data@main/img/20250305-1.webp)

## Overview of HashKey Chain's Staking Economic Model

The HashKey Chain staking system offers an innovative new model, where staking generates a foundational transparent and efficiently circulating asset: stHSK. This section will explain how this economic model works and how it can maximize your staking returns.

---

## stHSK: A Token That Automatically Accumulates Rewards

stHSK tokens are minted when HSK is staked. Users can redeem the equivalent amount of stHSK tokens based on the current exchange rate. These stHSK tokens have three key features:

- **Automatic Value Growth:** The value of stHSK increases as staking rewards accumulate.
- **Liquidity & Transferability:** As an ERC-20 token, stHSK can be freely transferred and used for DeFi protocols.
- **No Manual Claiming Needed:** Your rewards are automatically reflected in the increasing value of stHSK, eliminating the need for additional operations.

---

## Revenue Sources & Distribution Mechanism

### Revenue Sources

The staking rewards in the HashKey Chain staking system primarily come from block rewards. The system uses an Annual Reward Budget (ARB), which is equally distributed across each block over time.

### Exchange Rate Mechanism

The system calculates the exchange rate between HSK and stHSK using the following formula:

> 1 stHSK = Total Staked HSK Pool / Total stHSK Supply

- When new stHSK tokens are minted into the staking pool, the total stHSK supply increases, while the total stHSK supply remains unchanged.
- As a result, the value of each stHSK increases, reflecting the accumulated rewards.

### Base Annual Percentage Rate (APR) Calculation

The base APR is dynamically calculated using this formula:

> Base APR = (Annual Reward Budget / Total Staked HSK) * 10,000 (basis points)

For example, if the Annual Reward Budget is 1,200,000 HSK and the total staked HSK is 12,000,000 HSK, then:

> (1,200,000 / 12,000,000) * 10,000 = 1,000 basis points = 10%

If you choose flexible staking (no lockup period), your expected annual return is approximately 10%.

---

![Your Voice Matters - We're Always Listening](https://cdn.jsdelivr.net/gh/HashkeyHSK/official-web-data@main/img/20250305-2.webp)

---

## Staking Options & Reward Enhancements

### 1. Fixed-Term Staking

Lock-up period options: 30 days, 90 days, 180 days, 365 days

APR Boost:  
**Base APR + APR Boost = Additional Incentives**

Lock-up period options:

- 30-day lock-up: +1% (No additional incentive)
- 90-day lock-up: +2.75%
- 180-day lock-up: +4.5%
- 365-day lock-up: +7.5%

Example: If the Base APR is 10%, then a 365-day lock-up provides an additional +7.5%, bringing total APR to 17.5%.

### 2. Maximum APR Limits

To maintain the sustainability of the system, different lock-up periods have corresponding upper limits:

- 30-day lock-up: Up to 12.0%
- 90-day lock-up: Up to 15.0%
- 180-day lock-up: Up to 18.0%
- 365-day lock-up: Up to 20.0%

If the base APR fluctuates over time, the system automatically adjusts it to stay within the limit.

### 3. Early Unlocking Mechanism

If users request an early withdrawal and unbonding, bonus rewards will be forfeited, and a penalty fee will be applied.

The penalty fee is redistributed into the reward pool, benefiting long-term stakers.

---

## How to Maximize Your HSK Staking Returns

### Strategy 1: Long-Term Locking for Higher APR

A 365-day lock-up provides an extra 7.5% boost, significantly increasing your annual return.

### Strategy 2: Staggered Locking ("Yield Ladder")

Divide your HSK into different lock-up periods to create a staggered reward structure.  
This strategy balances liquidity and high returns by ensuring regular maturity periods.

### Strategy 3: Use stHSK in DeFi for Dual Rewards

- White-listed stHSK can be used in DeFi protocols, allowing you to earn additional yield.
- This enables a dual-income strategy:
  1. Earn staking rewards from HashKey Chain
  2. Earn third protocol rewards from using stHSK

---

## Real-Time Monitoring of Your Staking Performance

Use the following functions to track your staking status:

- `getCurrentExchangeRate()` – Check the current stHSK to HSK exchange rate
- `getStakingStatusReport()` – View detailed staking statistics and current APR
- `getHistoricalAPR()` – Retrieve base APR and min/max APR for each lock-up period

---

## Final Thoughts

The HashKey Chain staking model provides flexible and competitive earning solutions. From its structure through stHSK automatic yield-enhancement design to various lock-up incentives and DeFi integrations, it's a well-rounded approach to maximizing staking rewards.

With real-time monitoring, liquidity, high returns, and the option to combine staking strategies into multiple "growth paths," this system allows you to customize a staking model that fits your needs.

---

*For more information about HSK staking, please contact the HashKey Chain support team.*

— HashKey Chain Team

