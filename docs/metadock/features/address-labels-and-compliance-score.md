---
title: Address Labels and Compliance Score
description: How to Use MetaSleuth
---

## Enhanced Address Labels

**MetaDock** identifies deposit addresses of CEXs, scammer and hacker addresses, and other addresses we collected and verified (especially those not tagged by the blockchain explorers). It helps users better understand the participants of transactions and track the flow of funds.

*BTC.com and top EVM-compatible blockchains* are supported. 

## CEX Deposit Addresses

MetaDock identifies several addresses on *BTC.com* as `Binance Wallets`. This makes the identification of CEX transfers easier. 

- Try this [address](https://explorer.btc.com/btc/address/19aaLsPkiJuFZck7U4mryKFiUg633UJDhm)

![img1](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2FdEW7Rz7LOPaqR9UMygCU%2F8fcea16c-174f-447f-bf8e-a6691329e28e.png?alt=media&token=f4896fff-de70-4d9e-86b3-59e1f5661f19)

## Proxy Contract Labels

**For proxy contracts, MetaDock gives you a hook to their implementation contracts in the label**, which means you can simply click on the latter half of the label, and dirrectly turn to the implementation contract!

![img2](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2FIHyJ4BOydMarz7tGYefa%2FCleanShot%202023-06-18%20at%2012.02.10%402x.png?alt=media&token=b5d580e8-b1be-4116-96ff-e475c8d98d83)

## Other Address Labels

![img3](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2F3x8MpWiG5zc08sEq1jCq%2Fimage.png?alt=media&token=cf1fbd4e-5812-48aa-89a8-20a1142f8372)

**MetaDock** also provides **additional labels on \*scan and replaces some addresses with meaningful name tags**. Try these addresses: [1](https://etherscan.io/address/0xbefe4f86f189c1c817446b71eb6ac90e3cb68e60) [2](https://etherscan.io/address/0x792a0ac6c73a9882c9fa2becc832ccbf3fe37183#tokentxns)

🎉Note that, MetaDock does not collect and upload users' private tags.

## Address Compliance Score

**MetaDock** provides the *address compliance score* to help **estimate the likelihood of an address associated with illegal activities**. Specifically, an address will fall into one of the 5 categories:

- **No risk**: almost impossible to be associated with illegal activities;

- **Low risk**: the low possibility of being associated with illegal activities;

- **Medium risk**: the medium probability of being associated with illegal activities;

- **High risk**: the high probability of being associated with illegal activities;

- **Critical risk**: those who are involved in illegal activities.

Note that the compliance scores are provided for reference only and do not constitute any investment advice. Learn more about the methodology to calculate the risk scores.

*Top EVM-compatible blockchains* are supported. Try this [address](https://etherscan.io/address/0xba399a2580785a2ded740f5e30ec89fb3e617e6e)

![img3 Address Compliance Score](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2FibthWnhB7hvhEZlNrGy4%2Fimage.png?alt=media&token=a8d562b9-a5c8-4696-80b1-9a8c5c7d1c6f)

## Function Signatures

MetaDock provides a more comprehensive function signature library to complement the *scan's signature parsing. 

- [Click to try](https://etherscan.io/txs?block=15758642)
![img4](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2FZT4GJnSYMEfPbatxEryD%2Fimage.png?alt=media&token=feac2a75-7e4d-4d55-99b6-8b40ff3efd95)
  
For example, MetaDock replaces the function signature `0x13d79a0b` with `settle`， which makes more sense for users.