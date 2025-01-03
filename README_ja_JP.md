<h1 align="center">
  <img src="https://i.imgur.com/DDkfI9i.png" alt="Pepecoin" width="300"/>
  <br/><br/>
  Pepecoin Core [PEP, Ᵽ]
</h1>

言語を選択: [EN](./README.md) | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | [FR](./README_fr_FR.md) | JA | [DE](./README_de_DE.md)

Pepecoinは、2013年のオリジナルのDogecoinのシベ（Shibe）の1人によって作られた、コミュニティ重視の暗号通貨です。Pepecoinは1つの目的のために作られました。それは、オリジナルのDogecoinコミュニティのように、新しく楽しいコミュニティを作ることです。

それ以前のすべてのバージョンとは異なり、Pepecoinはレイヤー1のコインです。これにより、流動性プールを使い果たすこともなく、ウォレットをブラックリストに登録することもなく、複雑なスマートコントラクトもありません。Pepecoinはシンプルなブロックチェーンです。

Pepecoin Coreソフトウェアは、誰でもPepecoinブロックチェーンネットワークでノードを運営できるようにし、作業証明（PoW）にScryptハッシュメソッドを使用しています。これは、Dogecoin Core、Bitcoin Core、および他の暗号通貨から適応されたものです。

Pepecoinネットワークで使用されるデフォルトの手数料に関する情報については、[手数料の推奨](doc/fee-recommendation.md)を参照してください。

**ウェブサイト:** [pepecoin.org](https://pepecoin.org)

## Dogecoinとの違い

PepecoinはDogecoinのフォークです。親しみやすさのために、PepecoinはDogecoinにできるだけ似せるようにします。

変更点:

* アドレスが`P`で始まり、`D`ではありません
* BIPS機能はブロック1000から始まります
* AuxPowはブロック42,000から開始（チェーンID: 63）
* Pepecoin用のテーマ付きGUI

## 使用方法 💻

Pepecoin Coreを使用するための第一歩として、[インストールガイド](INSTALL.md)と[はじめに](doc/getting-started.md)のチュートリアルをご覧ください。

Pepecoin Coreが提供するJSON-RPC APIは自己文書化されており、`pepecoin-cli help`を使用して閲覧できます。各コマンドの詳細情報は、`pepecoin-cli help <command>`で表示できます。代わりに、[Bitcoin Coreのドキュメント](https://developer.bitcoin.org/reference/rpc/)をご覧ください - これは同様のプロトコルを実装しています。

### ポート

Pepecoin Coreは、デフォルトで`33874`ポートを使用して、"mainnet"ブロックチェーンの同期と新しいトランザクションやブロックの情報取得に必要なピアツーピア通信を行います。また、JSONRPCポートも開放可能で、デフォルトでは`33873`ポートがmainnetノードに使用されます。RPCポートをインターネットに公開しないことを強く推奨します。

| 機能     | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   33874 |   44874 |   18444 |
| RPC      |   33873 |   44873 |   18332 |

## 継続的な開発 💻

Pepecoin Coreはオープンソースで、コミュニティ主導のソフトウェアです。開発プロセスは公開されており、誰でもソフトウェアを確認、議論、開発に参加できます。

主な開発リソース:

* [GitHub Projects](https://github.com/pepecoinppc/pepecoin/projects)は、今後のリリースに向けた計画中および進行中の作業を追うために使用されます。
* [GitHub Discussions](https://github.com/pepecoinppc/pepecoin/discussions)は、Pepecoin Coreソフトウェアの開発、基盤となるプロトコル、およびPEP資産に関連する計画された機能や未計画の機能について議論するために使用されます。
* [PepecoinDev subreddit](https://www.reddit.com/r/pepecoindev)

### バージョン戦略
バージョン番号は```major.minor.patch```のセマンティクスに従います。

### ブランチ
このリポジトリには3種類のブランチがあります:

- **master:** 安定版で、最新の*major.minor*リリースの最新バージョンが含まれています。
- **maintenance:** 安定版で、まだアクティブにメンテナンス中の以前のリリースの最新バージョンが含まれています。形式: ```<version>-maint```
- **development:** 不安定で、計画されたリリースに向けた新しいコードが含まれています。形式: ```<version>-dev```

*masterとmaintenanceのブランチはリリースによってのみ変更されます。計画されたリリースには必ず開発ブランチがあり、プルリクエストはこれらのブランチに送信する必要があります。maintenanceブランチは**バグ修正のみ**に使用され、新機能は最も高いバージョンの開発ブランチに送信してください。*

## 貢献 🤝

バグを見つけた場合やソフトウェアに問題がある場合は、[issueシステム](https://github.com/pepecoinppc/pepecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+)を使って報告してください。

[貢献ガイド](CONTRIBUTING.md)を参照して、Pepecoin Coreの開発にどのように参加できるかをご確認ください。よくある[ヘルプを求めるトピック](https://github.com/pepecoinppc/pepecoin/labels/help%20wanted)では、あなたの貢献が大きな影響を与え、非常に感謝されます。

## コミュニティ 🐸

さまざまなソーシャルメディアでコミュニティに参加できます。最新の情報をチェックしたり、人々と出会ったり、議論したり、最新のミームを探したり、Pepecoinについて学んだり、ヘルプを求めたり、プロジェクトを共有したりできます。

以下は参加する場所です:

* [Reddit](https://www.reddit.com/r/pepecoin)
* [Discord](https://pepecoin.org/discord)
* [Telegram](https://t.me/PepecoinGroup)
* [Twitter/X](https://twitter.com/PepecoinNetwork)

## よくある質問 ❓

Pepecoinに関する質問がありますか？答えはすでに[FAQ](doc/FAQ.md)や[Q&Aセクション](https://github.com/pepecoinppc/pepecoin/discussions/categories/q-a)にあるかもしれません！

## ライセンス ⚖️
Pepecoin CoreはMITライセンスの下でリリースされています。詳細は[COPYING](COPYING)を参照するか、[opensource.org](https://opensource.org/licenses/MIT)をご覧ください。
