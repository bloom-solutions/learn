---
layout: default
title: Multisig
parent: Securing your Bitcoin
nav_order: 4
---

# What is multisig?

Multisig is short for multi-signature. A multisig wallet may require more than
one signature to spend from that wallet.

Going back to our bank check example, you can open joint bank accounts. These
accounts have many people written as account holders. The bank is also told
by these account holders how many must sign the checks for the check to be
valid.

<figure markdown=1>
![](/assets/images/3-of-5.png)
<figcaption>Any three of the five signers can spend Bitcoin from this wallet.</figcaption>
</figure>

With Bitcoin multisig, you can currently have up to 20 signers[^1], though most people
aren't like to need that many.

The common setups are 2-of-3 and 3-of-5.

# Why multiple signers?

Why would you want this kind of setup?

- **Minimize fraud**. Perhaps you're running a business and want to decrease the
temptation that the business partners may have to steal money.
- **Convenience**. If one of the three business partners are away you can still get
two of the business partners to sign a check.
- **Reduce points of failure**. With a 3-of-5 setup, you can lose up to *two* of the
keys and you will still have enough keys to access your funds.

# No bank

Bank analogies are great because more people are aware about how they work.
However, the analogy stops being useful at a certain point.

With banks, there's more trust required than there is with Bitcoin.
You trust the people accepting the check and handling your account.

With Bitcoin multisig, *there are no people to trust*. The keys used to unlock
or sign the transaction simply fit (or don't fit).

[^1]: https://bitcoin.stackexchange.com/a/28092
