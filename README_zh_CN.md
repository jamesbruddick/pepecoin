<h1 align="center">
  <img src="https://i.imgur.com/DDkfI9i.png" alt="Pepecoin" width="300"/>
  <br/><br/>
  Pepecoin Core [PEP, Ᵽ]
</h1>

选择语言：[EN](./README.md) | CN | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | [FR](./README_fr_FR.md) | [JA](./README_ja_JP.md) | [DE](./README_de_DE.md)

Pepecoin 是一个以社区为中心的加密货币，由 2013 年的原始 Dogecoin shibes 之一创建。它的创建目的是为了建立一个像原始 Dogecoin 社区一样全新的、有趣的社区。

与之前所有版本不同，Pepecoin 是一个 Layer 1 的币种。这意味着没有流动性池可供抽取，没有黑名单钱包，也没有复杂的智能合约。Pepecoin 是一个简单的区块链。

Pepecoin Core 软件允许任何人运营 Pepecoin 区块链网络中的节点，并使用 Scrypt 哈希方法进行工作量证明。它是从 Dogecoin Core、Bitcoin Core 以及其他加密货币中改编而来。

有关 Pepecoin 网络默认费用的信息，请参考 [费用推荐](doc/fee-recommendation.md)。

**网站：** [pepecoin.org](https://pepecoin.org)

## Dogecoin 的差异

Pepecoin 是 Dogecoin 的一个分支。为了便于熟悉，我们将尽量保持 Pepecoin 与 Dogecoin 的相似性。

更改：

* 地址以 `P` 开头，而不是 `D`
* BIPS 特性将从第 1000 块开始
* AuxPow 从第 42,000 块开始（链 ID：63）
* 界面以 Pepecoin 为主题

## 使用 💻

要开始使用 Pepecoin Core，请查看 [安装指南](INSTALL.md) 和 [入门教程](doc/getting-started.md)。

Pepecoin Core 提供的 JSON-RPC API 是自文档化的，可以通过 `pepecoin-cli help` 浏览，而每个命令的详细信息可以通过 `pepecoin-cli help <command>` 查看。或者，请参阅 [Bitcoin Core 文档](https://developer.bitcoin.org/reference/rpc/) —— 它实现了类似的协议 —— 以获得可浏览版本。

### 端口

Pepecoin Core 默认使用端口 `33874` 进行点对点通信，该通信用于同步“主网”区块链并获取新交易和区块的信息。此外，还可以打开 JSONRPC 端口，主网节点的默认端口为 `33873`。强烈建议不要将 RPC 端口暴露到公共互联网。

| 功能 | 主网 | 测试网 | 回归测试 |
| :--- | ---: | ---: | ---: |
| P2P  | 33874 | 44874 | 18444 |
| RPC  | 33873 | 44873 | 18332 |

## 持续开发 💻

Pepecoin Core 是一个开源且社区驱动的软件。开发过程是开放且公开可见的，任何人都可以查看、讨论和参与该软件的开发。

主要开发资源：

* [GitHub 项目](https://github.com/pepecoinppc/pepecoin/projects) 用于跟踪即将发布的版本的计划和进行中的工作。
* [GitHub 讨论区](https://github.com/pepecoinppc/pepecoin/discussions) 用于讨论与 Pepecoin Core 软件的开发、底层协议以及 PEP 资产相关的特性，计划和非计划的内容。
* [PepecoinDev Reddit](https://www.reddit.com/r/pepecoindev)

### 版本策略
版本号遵循 ```major.minor.patch``` 语义。

### 分支
此存储库中有 3 种类型的分支：

- **master：** 稳定版，包含最新版本的最新 *major.minor* 版本。
- **maintenance：** 稳定版，包含仍在维护中的旧版本的最新版本。格式：```<version>-maint```
- **development：** 不稳定版，包含计划发布的新代码。格式：```<version>-dev```

*Master 和 maintenance 分支仅可通过发布进行修改。计划发布总会有一个开发分支，拉取请求应提交到这些分支。维护分支仅用于 **修复 bug，** 请将新功能提交到版本最高的开发分支。*

## 贡献 🤝

如果您发现了 bug 或在使用此软件时遇到问题，请通过 [问题系统](https://github.com/pepecoinppc/pepecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+) 报告。

请参阅 [贡献指南](CONTRIBUTING.md)，了解如何参与 Pepecoin Core 的开发。经常有 [寻求帮助的主题](https://github.com/pepecoinppc/pepecoin/labels/help%20wanted)，您的贡献将产生重大影响，并受到高度赞赏。

## 社区 🐸

您可以加入不同社交媒体平台上的社区，了解最新动态，结识人们，讨论问题，找到最新的表情包，了解 Pepecoin，给予或寻求帮助，分享您的项目。

以下是一些可以访问的地方：

* [Reddit](https://www.reddit.com/r/pepecoin)
* [Discord](https://pepecoin.org/discord)
* [Telegram](https://t.me/PepecoinGroup)
* [Twitter/X](https://twitter.com/PepecoinNetwork)

## 常见问题 ❓

你有关于 Pepecoin 的问题吗？答案可能已经在 [FAQ](doc/FAQ.md) 或 [讨论区的 Q&A 部分](https://github.com/pepecoinppc/pepecoin/discussions/categories/q-a) 中！

## 许可证 ⚖️
Pepecoin Core 是根据 MIT 许可证发布的。请参阅 [COPYING](COPYING) 获取更多信息，或查看 [opensource.org](https://opensource.org/licenses/MIT)
