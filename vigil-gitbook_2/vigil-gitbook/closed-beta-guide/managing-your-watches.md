---
description: See, change, pause or stop everything Vigil is doing for you.
---

# Managing Your Watches

A **watch** is a plan that Vigil is running for you, 24/7.

## Your watch list

Your home for everything that's live:

* **Active watches** — every plan currently running
* **P\&L** — per watch and across your account
* **Total balance** — your overall account value

## Inside a watch

Tap any watch to see:

* Its state: **waiting**, **active**, **paused**, **done** or **stopped**
* Open positions and conditions still pending
* The full log of every signal it saw and every action it took
* Your original words and the plan card you confirmed

Vigil is never a black box. If you want to know why it did something, the answer is one tap away.

## Reading the log

```
07:30  › plan confirmed · 3 triggers · max risk $500
13:05  › match: liquidity > $250k · holders > 1,200 · waiting for your OK
22:40  › paused: 2 losses today · cooldown 4h
03:15  › filled 0.42 ETH @ 2,310 · stop set 2,240
```

| Event | Meaning |
| --- | --- |
| Confirmed | You approved the plan card |
| Matched | A trigger condition was met |
| Filled | An order was executed |
| Skipped | An action was blocked, usually by a guardrail |
| Paused | A cooldown or cap stopped trading |

## Change, pause or stop

From any watch you can:

* **Edit** — change the plan. You'll confirm a new card before it takes effect.
* **Pause** — stop new actions. Open positions stay as they are.
* **Stop** — end the watch for good.

**Pause all** stops every watch at once.

## Confirm mode and Auto mode

| Mode | How it works | Best for |
| --- | --- | --- |
| **Confirm** | Vigil prepares the order and waits for your tap | New plans, bigger sizes |
| **Auto** | Vigil executes on its own, inside your caps | Plans you've tested and trust |

## One position, one driver

A position is managed by one driver at a time: you, or a watch.

* While a watch manages a position, you can't change it by hand. Stop the watch first to take it back.
* A position you opened yourself can be handed to a watch.

This stops you and Vigil from working against each other.

## Notifications

Vigil alerts you when:

* A position opens
* A position closes (stop, target or exit)
* A guardrail blocks a trade or pauses trading
* Something needs your attention

Alerts arrive in-app, as push notifications or by email. Change them in **Settings**.

## Known limits during the Beta

* **Long, complex plans may hit edge cases.** Please report anything odd.
* **No card on-ramp yet.** Fund your wallet with USDC from another wallet or exchange.
* **Small tokens can be illiquid.** Expect slippage on very small caps.
* **Text only.** Vigil can't read images or screenshots yet.

Found another one? Tell us in [Feedback and Support](feedback-and-support.md).
