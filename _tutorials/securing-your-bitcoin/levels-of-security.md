---
layout: default
title: Levels of Security
parent: Securing your Bitcoin
nav_order: 7
last_modified_date: 2022-07-05
---

# {{ page.title }}

Now that you have an idea of what software wallets, hardware wallets /
signing devices, keys, then you're ready to think about what level of security
is appropriate for you.

As discussed in
[Security vs. Convenience](/tutorials/securing-your-bitcoin/security-vs-convenience/),
there are multiple factors, but we have a general recommendation:

| Value                        | Scheme                    |
|------------------------------|---------------------------|
| Wallet (~ ₱10,000)           | Single sig, software      |
| Vacation (~ ₱400,000)        | Single sig, hardware      |
| Car (~ ₱1 million)           | 2 of 2 multisig, hardware |
| House (~ ₱15 million)        | 2 of 3 multisig, hardware |
| Small island (~ ₱50 million) | 3 of 5 multisig, hardware |
| Castle (~ ₱1 billion)        | 4 of 6 multisig, hardware |
| Fortune (above ₱3 billion)   | 5 of 8 multisig, hardware |

It's too much work to have a 2 of 3 multisig if you're storing ₱5,000 worth.
If you have billions of Pesos, however, you want to make sure that:

- if something happens to you, your heirs can still access it but you don't
want to give them control before then
- if there's a fire/flood in one place where you have some / one private keys,
you don't lose access to your funds
- you can't access your funds easily in case you're forced to by someone else

You can go on and on, such as thinking about "decoy wallets", so
that in case you're being held up by a theif, then you can see send them
some crypto but not the whole stash.

The types of setup are endless. This is why we recommend that you take it a
step at a time.
