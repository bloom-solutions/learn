---
layout: default
title: Hardware Wallets
parent: Securing your Bitcoin
nav_order: 4
last_modified_date: 2022-06-26
---

# What is a hardware wallet?

Hardware wallets were made to more easily keep your private key away from the
Internet. It is a specialized computer that _should not_ go online that contains
your private key.

<figure>
<img src="/assets/images/coldcard.jpg" alt="Coldcard" style="max-height:400px;"/>
<figcaption markdown="1">
[Coldcard](https://coldcard.com/) is a Bitcoin hardware wallet.
</figcaption>
</figure>

An alternative to using a factory-made hardware wallet would be to have a phone
or computer that has Bitcoin software to sign transactions, but **before** the
private key is generated, it is taken offline.

With a hardware wallet, you can sign transactions by plugging the wallet to
your computer, and the software on the computer will ask the hardware wallet
to sign the transaction.

On the hardware wallet, you will be shown some information about the
transaction, such as the address you're sending to and the amount.

[BTC Sessions](https://twitter.com/btcsessions) has a lot of good content
about Bitcoin wallets. See him talk about another wallet, Trezor, here:

<div class="iframe-container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/TtlgE2Fx3m8?start=329" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

# So... it's a signing device?

If you're thinking "hardware wallet" isn't a good name, you're onto something.
It doesn't store any money or keep track of balances like a wallet does. It
merely contains a private key and can sign transactions given to it.

If you call it "signing device", you'll get some positive looks from people
who've been in the space for a while.

# List of signing devices

Here are the signing devices some of us at BloomX are familiar with and have fairly high degree of confidence:

| Signing Device                    | Coin support                                                                                       |
| ---                               |                                                                                                    |
| [Coldcard](https://coldcard.com/) | Bitcoin only                                                                                       |
| [Trezor](https://trezor.io)       | [1000+ coins](https://trezor.io/coins/); [Bitcoin-only firmware](https://shop.trezor.io/btc-only/) |
| [Ledger](https://www.ledger.com/) | [1000+ coins](https://www.ledger.com/supported-crypto-assets)                                      |

There are others which we have tried but are discontinued, not updated, or have known vulnerabilities:

| Signing Device                            | Coin support | Notes                                                                                                                   |
| ---                                       |              |                                                                                                                         |
| [KeepKey](https://shapeshift.com/keepkey) | 40+          | [Relative easy private key extraction](https://blog.kraken.com/post/3245/flaw-found-in-keepkey-crypto-hardware-wallet/) |
| Cobo Vault                                |              | Discontinued                                                                                                            |

And there are others which we have not tried ourselves but are worth mentioning:

| Signing Device                                                           | Coin support                                                                                                                                                    | Notes                                                                                                                                      |
| ---                                                                      | ---                                                                                                                                                             |                                                                                                                                            |
| [Keystone Essential](https://shop.keyst.one/products/keystone-essential) | [1000+](https://support.keyst.one/about-keystone); [Bitcoin-only firmware](https://support.keyst.one/changelog/keystone-firmware-btc-only)                      | [Spiritual successor to Cobo Vault](https://blog.keyst.one/leaving-cobo-to-continue-the-cobo-vault-legacy-29bb2f8f026e); very easy signing |
| [BitBox](https://shiftcrypto.shop/en)                                    | [Dozens](https://shiftcrypto.shop/en/products/bitbox02-multi-edition-2/); [Bitcoin-only edition](https://shiftcrypto.shop/en/products/bitbox02-bitcoin-only-4/) |                                                                                                                                            |
| [Foundation Passport](https://foundationdevices.com/)                    | Bitcoin only                                                                                                                                                    |                                                                                                                                            |
| [SeedSigner](https://seedsigner.com/)                                    | Bitcoin only                                                                                                                                                    | [Open source](https://github.com/SeedSigner/seedsigner), [DIY](https://github.com/SeedSigner/seedsigner#shopping-list)                     |

# Why do I see some Bitcoin only devices?

Some hardware makers decided to focus on one cryptoasset only, and their reasoning is that it is
- easier to keep the devices secure since there are less features
- devote more time to develop more advanced Bitcoin features such as [seed xor](https://seedxor.com) or, although we haven't covered it yet, better multisig support[^1].

[^1]: [Keystone](https://support.keyst.one/advanced-features/multi-signature) and [Coldcard](https://coldcard.com/docs/multisig) have implemented advanced multsig features.
