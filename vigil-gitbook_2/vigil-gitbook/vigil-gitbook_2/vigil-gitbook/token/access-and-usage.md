---
description: Using Vigil costs 100 USDT worth of tokens per month. Here's how that works.
---

# Access and Usage

<!-- TODO: confirm price source (oracle / TWAP window), billing date rules and grace period before publishing. -->

## The monthly cost

**Each Vigil account uses 100 USDT worth of tokens per month.**

The price is fixed in dollars, not in tokens. That means:

* You always pay the same dollar value, whatever the token price is.
* The **number** of tokens you pay changes with the token price.

## How many tokens you pay

At billing time, Vigil divides 100 USDT by the current token price.

`tokens due = 100 USDT ÷ token price`

| Token price | Tokens due for one month |
| --- | --- |
| $0.01 | 10,000 |
| $0.05 | 2,000 |
| $0.10 | 1,000 |
| $0.50 | 200 |
| $1.00 | 100 |

*Example prices only. They are not a forecast.*

The token price is taken from a time-averaged market price at the moment of billing, so a single spike or dip can't change your cost much.

## How to pay

{% stepper %}
{% step %}
### Hold tokens in your connected wallet

Keep enough tokens in the wallet you connected to Vigil to cover the next month.
{% endstep %}

{% step %}
### Approve the monthly payment

In **Settings → Plan**, approve Vigil to take the monthly amount. You'll see the exact token amount before you confirm.
{% endstep %}

{% step %}
### Vigil renews each month

On your billing date, the payment is taken and split automatically: 90% burned, 10% to the project. See [Burn and Treasury](burn-and-treasury.md).
{% endstep %}
{% endstepper %}

## If your balance is too low

* You'll get a reminder a few days before your billing date.
* If the payment fails, your watches are **paused, not deleted**. Top up and they resume where they left off.
* Vigil never sells your other assets to pay for access.

## During the Closed Beta

The token launches before the Closed Beta opens, so the Beta is paid in the token from day one: the same 100 USDT worth per month, with the same 90% burn. See [Access During the Beta](../closed-beta-guide/subscriptions-during-the-beta.md).

{% hint style="danger" %}
Vigil will only ever ask you to approve the exact monthly amount, inside the app. We will **never** ask you to send tokens to a personal wallet, a DM link or a "support" address.
{% endhint %}
