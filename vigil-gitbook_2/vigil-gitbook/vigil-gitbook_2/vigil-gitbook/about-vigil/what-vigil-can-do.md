---
description: The full loop — watch, decide, act, report — from one conversation.
---

# What Vigil Can Do

Most trading tools do one part of the job. Vigil runs the whole loop, from a single conversation.

{% hint style="info" %}
Vigil is in Closed Beta. Anything on this page may change, and some features may reach a small group first.
{% endhint %}

<!-- TODO: before publishing, confirm every venue, number and feature on this page matches the live product. -->

## What you actually get

| You want… | Vigil gives you… |
| --- | --- |
| **To not miss it** | 24/7 watches on the conditions you define |
| **To act on it** | A real order, placed inside your limits |
| **To stay safe** | Hard caps, cooldowns and a one-tap pause |
| **To understand it** | A log entry for every decision, with the reason |
| **To think it through** | Market context and answers in chat |

## Two modes: chat and watch

**In chat,** Vigil is your analyst. Ask about a token, a level or your portfolio, and it pulls the data and explains what it sees.

**On watch,** after you confirm a plan card, Vigil runs that plan unattended. Same knowledge, different job: instead of answering you, it waits for your conditions and acts on them.

A running watch has two parts:

* **When it wakes** — on a schedule ("every 15 minutes", "every day at 9 AM") or on an event (a new listing, a watched wallet moving)
* **How often it checks** — every 1, 5 or 15 minutes, set per watch
* **What it checks** — price, percentage moves, indicators like RSI, volume, funding, or any combination ("buy only if BTC breaks 72k **and** volume is above average")

{% hint style="warning" %}
Watches check on a cadence, not tick by tick. A price that spikes through your level and back between two checks can be missed. For hard exits, use an exchange-native stop where available.
{% endhint %}

## Triggers

| Trigger | Example |
| --- | --- |
| Price level | "If SOL drops below 140…" |
| Crossing | "When BTC breaks up through 72k…" |
| Percentage move | "If ETH moves 5% in an hour…" |
| Indicator | "When 4h RSI goes under 30…" |
| New listing | "Any new token with over $250k liquidity…" |
| Wallet | "When this wallet buys…" |
| Behavior | "After two losing trades in a row…" |
| Time | "Every morning at 9 AM…" |

## Actions

| Action | Example |
| --- | --- |
| Buy / sell | "Buy $200 of SOL" |
| Scale in or out | "Sell half at 165, the rest at 180" |
| Stop / take profit | "Stop at 132, take profit at 165" |
| Trailing stop | "Exit if it drops 8% from its high" |
| DCA | "Buy $50 every day for 30 days" |
| Alert only | "Just tell me, don't trade" |
| Pause | "Stop me from trading for 4 hours" |

## Guardrails

| Guardrail | What it does |
| --- | --- |
| Max size per trade | No single order can go above it |
| Hard cap (max loss per day) | All trading stops once it's reached |
| Max trades per day | Caps how often Vigil can act |
| Confirm mode ("Ask me first") | Vigil asks for your tap before every order |
| Tilt guard (cooldown) | Two losses in a row pauses all trading, 4 hours by default |

Guardrails always win. If an action would break one, Vigil skips it and logs why. See them work on a real example in [Guardrails in Action](guardrails-in-action.md).

## Markets

<!-- TODO: replace with the real list of supported venues and chains. -->

| Market | What Vigil can do |
| --- | --- |
| Spot | Buy, sell, DCA, scaled entries and exits |
| Perpetual futures | Long, short, leverage within your caps, stops and targets |
| New listings | Filter, alert, and optionally buy small size |

## Market context

Vigil doesn't act blind. In chat and inside running watches it can use:

* **Prices and technicals** — live and historical prices, common indicators
* **On-chain activity** — wallet flows, large transfers, holder counts
* **Token checks** — liquidity, holder concentration, contract red flags
* **Funding and positioning** — funding rates, open interest, liquidations
* **News and sentiment** — headlines and social signals, filtered for you

## Reports

* **Instant alerts** when a trigger fires, an order fills, or a guardrail blocks a trade
* **Morning summary** of what Vigil watched, did and skipped overnight
* **Full log** for every decision — see [Managing Your Watches](../closed-beta-guide/managing-your-watches.md)

## Security and control

<!-- TODO: confirm custody model and wallet provider before publishing. -->

| | |
| --- | --- |
| **Your funds** | Assets stay in your own wallet. Vigil has no pooled account. |
| **Trading permissions only** | Vigil can place trades. It has no path to withdraw or send funds elsewhere. |
| **You confirm** | No plan runs without your explicit approval. |
| **Everything is logged** | You can see why every action happened. |

## What's coming next

* More markets and data sources
* Backtesting — test a plan on history before it goes live
* More ways to share and reuse plans

Follow us on [X](../community/community-and-links.md) for updates.
