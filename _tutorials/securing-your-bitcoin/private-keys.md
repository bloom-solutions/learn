---
layout: default
title: Private Keys
parent: Securing your Bitcoin
nav_order: 4
last_modified_date: 2022-06-26
---

# What are private keys?

A private key is like a very long random password. Very long.
Impossible-to-guess long.

Just like when you sign a check, the private key is your arm that knows the
movements to write the signature.

Well, it's a better than a signature. Someone can look at your signature and
learn how to copy it. With a private key, when you sign something you
don't make your private key public. A private key is the one that can turn the
locking mechanism of the transaction so it is now open and can send your bitcoin.

No other key can do that.

## Unlocking a transaction

To be more secure, you can keep your private key in some other computer
dedicated to signing. You don't play games on it, or download random apps.
Best if the computer is completely offline.

Whenever you want to sign a transaction, you:

- **prepare it** on a computer that is online
- **copy** that transaction to a computer that is offline and has your private key
- **sign** it
- **copy** the signed transaction back to the online computer so you can broadcast it to the Internet

Sounds complicated? That's because it is. That's how it used to be done for
a many that wanted to keep their keys secure.

Fortunately, in the last 6 years, it has gotten easier to do this with the help
of what is called hardware wallets.
