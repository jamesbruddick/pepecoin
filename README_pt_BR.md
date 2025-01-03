<h1 align="center">
  <img src="https://i.imgur.com/DDkfI9i.png" alt="Pepecoin" width="300"/>
  <br/><br/>
  Pepecoin Core [PEP, Ᵽ]
</h1>

Selecione o idioma: [EN](./README.md) | [CN](./README_zh_CN.md) | PT | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | [FR](./README_fr_FR.md) | [JA](./README_ja_JP.md) | [DE](./README_de_DE.md)

Pepecoin é uma criptomoeda focada na comunidade, criada por um dos membros originais do Dogecoin de 2013. Ela foi criada com um único propósito: criar uma nova e divertida comunidade, assim como a comunidade original do Dogecoin.

Diferente de todas as versões anteriores, Pepecoin é uma moeda de camada 1. Isso significa que não existem pools de liquidez para drenagem, não há carteiras em listas negras e nem contratos inteligentes confusos. Pepecoin é uma blockchain simples.

O software Pepecoin Core permite que qualquer pessoa opere um nó nas redes blockchain da Pepecoin e utiliza o método de hash Scrypt para Prova de Trabalho. Ele é adaptado do Dogecoin Core, Bitcoin Core e outras criptomoedas.

Para informações sobre as taxas padrão utilizadas na rede Pepecoin, consulte a [recomendação de taxas](doc/fee-recommendation.md).

**Site:** [pepecoin.org](https://pepecoin.org)

## Diferenças do Dogecoin

Pepecoin é um fork do Dogecoin. Para facilitar a familiaridade, tentaremos manter o Pepecoin o mais semelhante possível ao Dogecoin.

Alterações:

* Endereços começam com `P` em vez de `D`
* Os recursos do BIPS começarão no bloco 1000
* AuxPow começa no bloco 42.000 (ID da cadeia: 63)
* GUI com tema Pepecoin

## Uso 💻

Para começar sua jornada com o Pepecoin Core, veja o [guia de instalação](INSTALL.md) e o tutorial de [primeiros passos](doc/getting-started.md).

A API JSON-RPC fornecida pelo Pepecoin Core é auto-documentada e pode ser navegada com `pepecoin-cli help`, enquanto informações detalhadas para cada comando podem ser vistas com `pepecoin-cli help <comando>`. Alternativamente, veja a [documentação do Bitcoin Core](https://developer.bitcoin.org/reference/rpc/) - que implementa um protocolo similar - para uma versão navegável.

### Portas

Por padrão, o Pepecoin Core usa a porta `33874` para comunicação peer-to-peer necessária para sincronizar a blockchain "mainnet" e ficar informado sobre novas transações e blocos. Além disso, uma porta JSONRPC pode ser aberta, que por padrão é a porta `33873` para nós mainnet. É altamente recomendável não expor portas RPC para a internet pública.

| Função   | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   33874 |   44874 |   18444 |
| RPC      |   33873 |   44873 |   18332 |

## Desenvolvimento contínuo 💻

Pepecoin Core é um software de código aberto e desenvolvido pela comunidade. O processo de desenvolvimento é aberto e publicamente visível; qualquer pessoa pode ver, discutir e trabalhar no software.

Recursos principais de desenvolvimento:

* [GitHub Projects](https://github.com/pepecoinppc/pepecoin/projects) é usado para acompanhar o trabalho planejado e em andamento para os próximos lançamentos.
* [GitHub Discussions](https://github.com/pepecoinppc/pepecoin/discussions) é usado para discutir recursos, planejados e não planejados, relacionados ao desenvolvimento do software Pepecoin Core, aos protocolos subjacentes e ao ativo PEP.
* [PepecoinDev subreddit](https://www.reddit.com/r/pepecoindev)

### Estratégia de versão
Os números de versão seguem a semântica ```major.minor.patch```.

### Branches
Há 3 tipos de branches neste repositório:

- **master:** Estável, contém a versão mais recente do último *major.minor* lançado.
- **maintenance:** Estável, contém a versão mais recente de versões anteriores que ainda estão em manutenção ativa. Formato: ```<version>-maint```
- **development:** Instável, contém novos códigos para lançamentos planejados. Formato: ```<version>-dev```

*As branches master e maintenance são exclusivamente mutáveis por meio de lançamento. Lançamentos planejados sempre terão uma branch de desenvolvimento e pull requests devem ser submetidos nessas branches. Branches de manutenção existem apenas para **correções de bugs**, por favor, envie novas funcionalidades para a branch de desenvolvimento com a versão mais alta.*

## Contribuindo 🤝

Se você encontrar um bug ou tiver problemas com esse software, por favor, reporte através do [sistema de issues](https://github.com/pepecoinppc/pepecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Veja o [guia de contribuição](CONTRIBUTING.md) para saber como você pode participar do desenvolvimento do Pepecoin Core. Frequentemente, há [tópicos buscando ajuda](https://github.com/pepecoinppc/pepecoin/labels/help%20wanted) onde suas contribuições terão grande impacto e serão altamente apreciadas.

## Comunidades 🐸

Você pode participar das comunidades em diversas redes sociais. Para ver o que está acontecendo, conhecer pessoas e discutir, encontrar memes novos, aprender sobre Pepecoin, pedir ou oferecer ajuda, ou compartilhar seu projeto.

Aqui estão alguns lugares para visitar:

* [Reddit](https://www.reddit.com/r/pepecoin)
* [Discord](https://pepecoin.org/discord)
* [Telegram](https://t.me/PepecoinGroup)
* [Twitter/X](https://twitter.com/PepecoinNetwork)

## Perguntas Frequentes ❓

Você tem alguma dúvida sobre o Pepecoin? Talvez a resposta já esteja na [FAQ](doc/FAQ.md) ou na seção de [Q&A](https://github.com/pepecoinppc/pepecoin/discussions/categories/q-a) do fórum de discussões!

## Licença ⚖️
Pepecoin Core é lançado sob os termos da licença MIT. Veja o [COPYING](COPYING) para mais informações ou consulte [opensource.org](https://opensource.org/licenses/MIT)
