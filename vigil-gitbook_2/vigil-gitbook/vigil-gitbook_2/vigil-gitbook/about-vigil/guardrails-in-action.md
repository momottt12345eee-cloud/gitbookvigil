---
description: One rough night, replayed with and without Vigil's guardrails.
---

# Guardrails in Action

This is a simulated example. It shows how Vigil's guardrails behave on a bad night. The numbers are illustrative, not real results.

## The night

A trader runs a plan from 18:00 to 06:00. The market chops, two trades lose in a row, and later there are two tempting "chase" entries into falling candles.

| | Without guardrails | With Vigil's guardrails |
| --- | --- | --- |
| Result at 06:00 | **−$520** | **−$300** (all three on) |
| Saved | — | **$220** |

## What each guardrail did

| Time | Event | Guardrail |
| --- | --- | --- |
| 21:00 | First losing trade | — |
| 22:30 | Second losing trade in a row, night reaches −$300 | **Hard cap** stops trading for the rest of the night |
| 22:30 | Two losses in a row | **Tilt guard** would pause trading for 4 hours. The cap already stopped the night |
| 23:00 / 01:00 | Chase entries into falling candles | Never placed. With only **Confirm mode** on, they would wait for your tap, and at that hour no tap means they're skipped |
| 06:00 | Night closes at −$300 | Every decision is in the log |

## Each guardrail on its own

| Only this one on | Result at 06:00 |
| --- | --- |
| Hard cap | −$300 |
| Tilt guard | −$350 |
| Confirm mode | −$200 |
| None | −$520 |

Each one catches a different kind of bad night. The hard cap sets a floor. The tilt guard stops revenge trading. Confirm mode stops trades you wouldn't take awake.

## How to set them

| Guardrail | Setting | Default |
| --- | --- | --- |
| Hard cap | Max loss per day, in dollars | $300 |
| Tilt guard | Losses in a row, pause length | 2 losses, 4 hours |
| Confirm mode | Auto or Ask me first | Ask me first while you learn |

Guardrails are set in **Settings** and can be changed per watch. See [Managing Your Watches](../closed-beta-guide/managing-your-watches.md).

{% hint style="warning" %}
Guardrails limit how much a bad night can cost. They don't prevent losses. Read the [Beta Disclaimer](../community/beta-disclaimer.md).
{% endhint %}
