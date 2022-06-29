---
layout: default
title: Electrum
parent: Multisig Wallets
nav_order: 2
last_modified_date: 2022-06-28
---

# Electrum

<figure markdown=1>
![Electrum](/assets/images/electrum.jpg)
<figcaption markdown=1>
[Electrum](https://electrum.org) is a wallet that has been around a long time in the Bitcoin space.
</figcaption>
</figure>

## Transaction management

Electrum allows you to build a transaction, signing it, and sending that partially signed file to your co-signers.

<figure markdown=1>
![Electrum](/assets/images/electrum/tx-builder.gif)
<figcaption markdown=1>
Electrum's transaction builder.
</figcaption>
</figure>

## Decent signing device support

As you can see below, you can connect hardware wallets to Electrum.

<figure markdown=1>
![Electrum multisig wallet with Ledger](/assets/images/electrum/hardware-wallets.gif)
<figcaption markdown=1>
This wallet is a 2-of-3 and has a connected Ledger as one of the signers.
</figcaption>
</figure>

We've been able to get Electrum to work with hardware wallets that are connected directly. We haven't, however, been able to get it to work with wallets that are air-gapped (not connected directly, but rather by QR code or SD card).
