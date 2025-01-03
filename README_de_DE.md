<h1 align="center">
  <img src="https://i.imgur.com/DDkfI9i.png" alt="Pepecoin" width="300"/>
  <br/><br/>
  Pepecoin Core [PEP, Ᵽ]
</h1>

Sprache auswählen: [EN](./README.md) | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | [FR](./README_fr_FR.md) | [JA](./README_ja_JP.md) | DE

Pepecoin ist eine auf die Gemeinschaft ausgerichtete Kryptowährung, die von einem der ursprünglichen Dogecoin-Mitglieder aus dem Jahr 2013 erstellt wurde. Sie wurde mit einem einzigen Ziel geschaffen: eine neue und unterhaltsame Gemeinschaft zu schaffen, die der ursprünglichen Dogecoin-Gemeinschaft ähnelt.

Im Gegensatz zu allen früheren Iterationen ist Pepecoin eine Layer-1-Münze. Das bedeutet, es gibt keine Liquiditätspools zum Abziehen, keine gesperrten Wallets und keine verwirrenden Smart Contracts. Pepecoin ist eine einfache Blockchain.

Die Pepecoin Core-Software ermöglicht es jedem, einen Knoten im Pepecoin-Blockchain-Netzwerk zu betreiben und verwendet die Scrypt-Hashing-Methode für Proof of Work. Sie ist eine Anpassung von Dogecoin Core, Bitcoin Core und anderen Kryptowährungen.

Für Informationen zu den Standardgebühren, die im Pepecoin-Netzwerk verwendet werden, lesen Sie bitte die [Gebührenempfehlung](doc/fee-recommendation.md).

**Website:** [pepecoin.org](https://pepecoin.org)

## Unterschiede zu Dogecoin

Pepecoin ist ein Fork von Dogecoin. Um die Vertrautheit zu bewahren, werden wir versuchen, Pepecoin so ähnlich wie möglich zu Dogecoin zu gestalten.

Änderungen:

* Adressen beginnen mit `P` statt mit `D`
* BIPS-Funktionen beginnen ab Block 1000
* AuxPow beginnt bei Block 42.000 (Chain ID: 63)
* GUI mit Pepecoin-Design

## Nutzung 💻

Um mit Pepecoin Core zu beginnen, lesen Sie die [Installationsanleitung](INSTALL.md) und das [Tutorial "Erste Schritte"](doc/getting-started.md).

Die von Pepecoin Core bereitgestellte JSON-RPC-API ist selbstdokumentierend und kann mit `pepecoin-cli help` durchsucht werden, während detaillierte Informationen zu jedem Befehl mit `pepecoin-cli help <command>` angezeigt werden können. Alternativ können Sie die [Bitcoin Core-Dokumentation](https://developer.bitcoin.org/reference/rpc/) einsehen, die ein ähnliches Protokoll implementiert.

### Ports

Pepecoin Core verwendet standardmäßig den Port `33874` für die Peer-to-Peer-Kommunikation, die zum Synchronisieren der "Mainnet"-Blockchain und zum Abrufen neuer Transaktionen und Blöcke erforderlich ist. Zusätzlich kann ein JSONRPC-Port geöffnet werden, der standardmäßig auf Port `33873` für Mainnet-Knoten eingestellt ist. Es wird dringend empfohlen, RPC-Ports nicht im öffentlichen Internet freizugeben.

| Funktion  | mainnet | testnet | regtest |
| :-------- | ------: | ------: | ------: |
| P2P       |   33874 |   44874 |   18444 |
| RPC       |   33873 |   44873 |   18332 |

## Laufende Entwicklung 💻

Pepecoin Core ist ein Open-Source-Softwareprojekt, das von der Gemeinschaft vorangetrieben wird. Der Entwicklungsprozess ist offen und öffentlich einsehbar; jeder kann den Code sehen, diskutieren und daran arbeiten.

Wichtige Entwicklungsressourcen:

* [GitHub-Projekte](https://github.com/pepecoinppc/pepecoin/projects) wird verwendet, um geplante und laufende Arbeiten für kommende Releases zu verfolgen.
* [GitHub-Diskussionen](https://github.com/pepecoinppc/pepecoin/discussions) wird verwendet, um über Funktionen zu diskutieren, sowohl geplante als auch ungeplante, die mit der Entwicklung der Pepecoin Core-Software, den zugrunde liegenden Protokollen und dem PEP-Asset zusammenhängen.
* [PepecoinDev Subreddit](https://www.reddit.com/r/pepecoindev)

### Versionsstrategie
Versionsnummern folgen dem Schema ```major.minor.patch```.

### Zweige
Es gibt 3 Arten von Zweigen in diesem Repository:

- **master:** Stabil, enthält die neueste Version des letzten *major.minor* Release.
- **maintenance:** Stabil, enthält die neueste Version früherer Releases, die noch aktiv gewartet werden. Format: ```<version>-maint```
- **development:** Instabil, enthält neuen Code für geplante Releases. Format: ```<version>-dev```

*Die master- und maintenance-Zweige sind ausschließlich durch Releases veränderbar. Geplante Releases haben immer einen Development-Zweig, und Pull Requests sollten gegen diesen Zweig eingereicht werden. Maintenance-Zweige sind nur für **Fehlerbehebungen** gedacht, bitte reichen Sie neue Funktionen gegen den Development-Zweig mit der höchsten Version ein.*

## Mitwirken 🤝

Wenn Sie einen Fehler finden oder Probleme mit dieser Software haben, melden Sie diese bitte über das [Fehlerbehebungssystem](https://github.com/pepecoinppc/pepecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Bitte lesen Sie [die Anleitung zur Mitwirkung](CONTRIBUTING.md), um zu erfahren, wie Sie an der Entwicklung von Pepecoin Core teilnehmen können. Es gibt oft [Themen, die Hilfe suchen](https://github.com/pepecoinppc/pepecoin/labels/help%20wanted), bei denen Ihre Beiträge großen Einfluss haben werden und sehr geschätzt werden.

## Gemeinschaften 🐸

Sie können den Gemeinschaften auf verschiedenen sozialen Medien beitreten. Um zu sehen, was passiert, Menschen zu treffen, zu diskutieren, das neueste Meme zu finden, mehr über Pepecoin zu lernen, Hilfe zu suchen oder anzubieten oder Ihr Projekt zu teilen.

Hier sind einige Orte, die Sie besuchen können:

* [Reddit](https://www.reddit.com/r/pepecoin)
* [Discord](https://pepecoin.org/discord)
* [Telegram](https://t.me/PepecoinGroup)
* [Twitter/X](https://twitter.com/PepecoinNetwork)

## Häufig gestellte Fragen ❓

Haben Sie eine Frage zu Pepecoin? Eine Antwort ist vielleicht schon in der [FAQ](doc/FAQ.md) oder im [Q&A-Bereich](https://github.com/pepecoinppc/pepecoin/discussions/categories/q-a) des Diskussionsforums zu finden!

## Lizenz ⚖️
Pepecoin Core wird unter den Bedingungen der MIT-Lizenz veröffentlicht. Weitere Informationen finden Sie in [COPYING](COPYING) oder auf [opensource.org](https://opensource.org/licenses/MIT).
