# 地址标签和合规评分

## 增强型地址标签

**MetaDock** 可以识别 CEX 的存款地址、骗子和黑客地址，以及我们收集和验证的其他地址（尤其是那些未被区块链浏览器标记的地址）。它帮助用户更好地了解交易参与者并跟踪资金流动。

支持 *BTC.com* 和顶级 EVM 兼容的区块链。

## CEX 存款地址

MetaDock 将 *BTC.com* 上的几个地址标识为 `Binance 钱包`。这使得识别 CEX 转账变得更容易。

- 试试这个 [地址](https://explorer.btc.com/btc/address/19aaLsPkiJuFZck7U4mryKFiUg633UJDhm)

![img1](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2FdEW7Rz7LOPaqR9UMygCU%2F8fcea16c-174f-447f-bf8e-a6691329e28e.png?alt=media&token=f4896fff-de70-4d9e-86b3-59e1f5661f19)

## 代理合约标签

对于代理合约，MetaDock 在标签中提供了它们的实现合约的钩子，这意味着您只需点击标签的后半部分，就可以直接转到实现合约！

![img2](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2FIHyJ4BOydMarz7tGYefa%2FCleanShot%202023-06-18%20at%2012.02.10%402x.png?alt=media&token=b5d580e8-b1be-4116-96ff-e475c8d98d83)

## 其他地址标签

![img3](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2F3x8MpWiG5zc08sEq1jCq%2Fimage.png?alt=media&token=cf1fbd4e-5812-48aa-89a8-20a1142f8372)

**MetaDock** 还在 \*scan 上提供了额外的标签，并用有意义的名称标记了一些地址。试试这些地址：[1](https://etherscan.io/address/0xbefe4f86f189c1c817446b71eb6ac90e3cb68e60) [2](https://etherscan.io/address/0x792a0ac6c73a9882c9fa2becc832ccbf3fe37183#tokentxns)

🎉请注意，MetaDock 不会收集和上传用户的私有标签。

## 地址合规评分

**MetaDock** 提供了 *地址合规评分*，以帮助估计与非法活动相关的地址的可能性。具体而言，一个地址将被归为以下5个类别之一：

- **无风险**：几乎不可能与非法活动相关联；

- **低风险**：与非法活动相关的可能性较低；

- **中等风险**：与非法活动相关的概率中等；

- **高风险**：与非法活动相关的概率较高；

- **严重风险**：涉及非法活动的地址。

请注意，合规评分仅供参考，不构成任何投资建议。了解更多关于计算风险评分的方法。

支持顶级 EVM 兼容的区块链。试试这个 [地址](https://etherscan.io/address/0xba399a2580785a2ded740f5e30ec89fb3e617e6e)

![img3 地址合规评分](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2FibthWnhB7hvhEZlNrGy4%2Fimage.png?alt=media&token=a8d562b9-a5c8-4696-80b1-9a8c5c7d1c6f)

## 函数签名

MetaDock 提供了一个更全面的函数签名库，以补充 *scan 的签名解析。

- [点击试试](https://etherscan.io/txs?block=15758642)
![img4](https://3379259938-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FwxbNGlBc5Kji1KaYLlhe%2Fuploads%2FZT4GJnSYMEfPbatxEryD%2Fimage.png?alt=media&token=feac2a75-7e4d-4d55-99b6-8b40ff3efd95)

例如，MetaDock 将函数签名 `0x13d79a0b` 替换为 `settle`，这对用户来说更有意义。
