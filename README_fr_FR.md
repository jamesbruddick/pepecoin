<h1 align="center">
  <img src="https://i.imgur.com/DDkfI9i.png" alt="Pepecoin" width="300"/>
  <br/><br/>
  Pepecoin Core [PEP, Ᵽ]
</h1>

Sélectionner la langue : [EN](./README.md) | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | FR | [JA](./README_ja_JP.md) | [DE](./README_de_DE.md)

Pepecoin est une cryptomonnaie axée sur la communauté, créée par l'un des membres originaux de Dogecoin de 2013. Elle a été créée dans un but précis : créer une nouvelle communauté amusante, tout comme la communauté Dogecoin originale.

Contrairement à toutes les versions précédentes, Pepecoin est une pièce de couche 1. Cela signifie qu'il n'y a pas de pools de liquidité à vider, pas de portefeuilles sur liste noire et pas de contrats intelligents compliqués. Pepecoin est une blockchain simple.

Le logiciel Pepecoin Core permet à quiconque d'exploiter un nœud sur les réseaux blockchain de Pepecoin et utilise la méthode de hachage Scrypt pour la preuve de travail (PoW). Il est adapté de Dogecoin Core, Bitcoin Core et d'autres cryptomonnaies.

Pour plus d'informations sur les frais par défaut utilisés sur le réseau Pepecoin, veuillez consulter la [recommandation de frais](doc/fee-recommendation.md).

**Site Web :** [pepecoin.org](https://pepecoin.org)

## Différences avec Dogecoin

Pepecoin est un fork de Dogecoin. Pour des raisons de familiarité, nous essayerons de garder Pepecoin aussi similaire que possible à Dogecoin.

Modifications :

* Les adresses commencent par `P` au lieu de `D`
* Les fonctionnalités BIPS commenceront à partir du bloc 1000
* AuxPow commence au bloc 42 000 (ID de chaîne : 63)
* Interface graphique avec un thème Pepecoin

## Utilisation 💻

Pour commencer votre aventure avec Pepecoin Core, consultez le [guide d'installation](INSTALL.md) et le tutoriel [démarrer](doc/getting-started.md).

L'API JSON-RPC fournie par Pepecoin Core est auto-documentée et peut être consultée avec `pepecoin-cli help`, tandis que des informations détaillées pour chaque commande peuvent être consultées avec `pepecoin-cli help <commande>`. Sinon, consultez la [documentation de Bitcoin Core](https://developer.bitcoin.org/reference/rpc/) qui implémente un protocole similaire pour obtenir une version consultable.

### Ports

Pepecoin Core utilise par défaut le port `33874` pour la communication pair-à-pair nécessaire à la synchronisation de la blockchain "mainnet" et à la mise à jour des nouvelles transactions et blocs. De plus, un port JSONRPC peut être ouvert, par défaut sur le port `33873` pour les nœuds mainnet. Il est fortement recommandé de ne pas exposer les ports RPC sur Internet public.

| Fonction  | mainnet | testnet | regtest |
| :-------- | ------: | ------: | ------: |
| P2P       |   33874 |   44874 |   18444 |
| RPC       |   33873 |   44873 |   18332 |

## Développement continu 💻

Pepecoin Core est un logiciel open-source et piloté par la communauté. Le processus de développement est ouvert et visible publiquement ; chacun peut voir, discuter et travailler sur le logiciel.

Principales ressources de développement :

* [GitHub Projects](https://github.com/pepecoinppc/pepecoin/projects) est utilisé pour suivre les travaux planifiés et en cours pour les prochaines versions.
* [GitHub Discussions](https://github.com/pepecoinppc/pepecoin/discussions) est utilisé pour discuter des fonctionnalités, planifiées ou non, liées au développement de Pepecoin Core, des protocoles sous-jacents et de l'actif PEP.
* [PepecoinDev subreddit](https://www.reddit.com/r/pepecoindev)

### Stratégie de version
Les numéros de version suivent la sémantique ```major.minor.patch```.

### Branches
Il existe 3 types de branches dans ce dépôt :

- **master :** Stable, contient la dernière version du dernier *major.minor*.
- **maintenance :** Stable, contient la dernière version des versions précédentes encore sous maintenance active. Format : ```<version>-maint```
- **development :** Instable, contient le nouveau code pour les versions prévues. Format : ```<version>-dev```

*Les branches master et maintenance sont uniquement modifiables par des versions de sortie. Les versions prévues auront toujours une branche de développement et les pull requests doivent y être soumises. Les branches de maintenance sont uniquement destinées aux **corrections de bugs**, veuillez soumettre de nouvelles fonctionnalités sur la branche de développement avec la version la plus élevée.*

## Contribuer 🤝

Si vous trouvez un bug ou rencontrez un problème avec ce logiciel, veuillez le signaler via le [système de tickets](https://github.com/pepecoinppc/pepecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Consultez le [guide de contribution](CONTRIBUTING.md) pour savoir comment vous pouvez participer au développement de Pepecoin Core. Il existe souvent des [sujets recherchant de l'aide](https://github.com/pepecoinppc/pepecoin/labels/help%20wanted) où vos contributions auront un grand impact et seront très appréciées.

## Communautés 🐸

Vous pouvez rejoindre les communautés sur différents réseaux sociaux. Pour voir ce qui se passe, rencontrer des gens, discuter, trouver le dernier mème, apprendre à connaître Pepecoin, demander ou offrir de l'aide, ou partager votre projet.

Voici quelques endroits à visiter :

* [Reddit](https://www.reddit.com/r/pepecoin)
* [Discord](https://pepecoin.org/discord)
* [Telegram](https://t.me/PepecoinGroup)
* [Twitter/X](https://twitter.com/PepecoinNetwork)

## Questions fréquentes ❓

Vous avez une question sur Pepecoin ? Une réponse se trouve peut-être déjà dans la [FAQ](doc/FAQ.md) ou dans la section [Q&A](https://github.com/pepecoinppc/pepecoin/discussions/categories/q-a) du forum de discussion !

## Licence ⚖️
Pepecoin Core est publié sous les termes de la licence MIT. Voir le fichier [COPYING](COPYING) pour plus d'informations ou consultez [opensource.org](https://opensource.org/licenses/MIT)
