---
description: 90% of every payment is burned. 10% funds the project. Here's where every token goes.
---

# Burn and Treasury

<!-- TODO: add burn address, treasury multisig address and signer setup once deployed. -->

## The split

Every token Vigil receives from monthly access is split the same way, automatically:

| Share | Where it goes | What it's for |
| --- | --- | --- |
| **90%** | Burn address | Removed from circulating supply forever |
| **10%** | Project treasury | Development, infrastructure, security and operations |

The split is enforced by the payment contract. No one on the team can change where the 90% goes by hand.

## Worked example

One account pays 100 USDT worth of tokens for one month:

* **90 USDT worth** is burned
* **10 USDT worth** goes to the treasury

Across many accounts, the numbers add up:

| Active accounts | Monthly usage | Burned (90%) | Treasury (10%) |
| --- | --- | --- | --- |
| 100 | 10,000 USDT | 9,000 USDT | 1,000 USDT |
| 1,000 | 100,000 USDT | 90,000 USDT | 10,000 USDT |
| 10,000 | 1,000,000 USDT | 900,000 USDT | 100,000 USDT |

*Illustrative numbers only. Values are shown in USDT equivalent at the time of each payment.*

## What the treasury pays for

The 10% keeps Vigil running and improving:

* **Infrastructure** — servers, market data and the watchers that run 24/7
* **Development** — new markets, triggers and features
* **Security** — audits, monitoring and bug bounties
* **Operations** — support, community and the [Sentinel Program](../sentinel-program/about-the-sentinel-program.md)

## How you can verify it

* **On-chain.** Every burn and every treasury transfer happens on-chain and can be checked by anyone.
* **Public addresses.** The burn address and treasury address will be published here and on our official channels.
* **Monthly report.** Each month we'll publish total tokens received, burned, and sent to the treasury, with transaction links.

| Address | Value |
| --- | --- |
| Burn address | TBA |
| Treasury | TBA |
| Payment contract | TBA |

{% hint style="warning" %}
Burning reduces the number of tokens in circulation. It does not guarantee any price or value. See [Beta Disclaimer](../community/beta-disclaimer.md).
{% endhint %}
