# Bitcoin Universe

Products, protocols, and open infrastructure for digital artifacts on Bitcoin, Dogecoin, and Zcash. Built on our own nodes and indexers, documented in the open, verifiable end to end.

**Documentation home: [docs.bitcoinuniverse.io](https://docs.bitcoinuniverse.io)**

## Products

| Product | What it is | Documentation | Live |
| --- | --- | --- | --- |
| **Core** | Explorer, portfolio, and marketplace across every supported protocol | [docs-core](https://github.com/bitcoinuniverseio/docs-core) | [bitcoinuniverse.io](https://bitcoinuniverse.io) |
| **Wallet** | Browser wallet for Bitcoin digital artifacts | [docs-wallet](https://github.com/bitcoinuniverseio/docs-wallet) | |
| **Inscribe** | Creation studio for inscriptions, tokens, and mints | [docs-inscribe](https://github.com/bitcoinuniverseio/docs-inscribe) | [inscribe.bitcoinuniverse.io](https://inscribe.bitcoinuniverse.io) |
| **StampDEX** | Trading venue for Bitcoin Stamps assets | [docs-stampdex](https://github.com/bitcoinuniverseio/docs-stampdex) | |
| **Zerdinals and Z-Runes** | Digital-artifact record on Zcash | [docs-zerdinals-and-zrunes](https://github.com/bitcoinuniverseio/docs-zerdinals-and-zrunes) | [zrunes.io](https://zrunes.io) |
| **Forked Felines** | Collection with on-chain artwork and provenance | [forked-felines-docs](https://github.com/bitcoinuniverseio/forked-felines-docs) | [forked-felines.art](https://forked-felines.art) |
| **Drops** | Media-first artifacts using the OP_DROP carrier | [drops-protocol-docs](https://github.com/bitcoinuniverseio/drops-protocol-docs) | |

## Protocols

Specifications we author, implement, or index. Each repository is the specification's home.

| Chain | Protocols |
| --- | --- |
| Bitcoin | [op-drop](https://github.com/bitcoinuniverseio/op-drop) · [brc-20](https://github.com/bitcoinuniverseio/brc-20) · [runes](https://github.com/bitcoinuniverseio/runes) · [src-20](https://github.com/bitcoinuniverseio/src-20) · [src-101](https://github.com/bitcoinuniverseio/src-101) · [alkanes](https://github.com/bitcoinuniverseio/alkanes) · [atomicals-and-arc-20](https://github.com/bitcoinuniverseio/atomicals-and-arc-20) · [tap](https://github.com/bitcoinuniverseio/tap) · [block-20](https://github.com/bitcoinuniverseio/block-20) · [dust-20](https://github.com/bitcoinuniverseio/dust-20) · [op-return](https://github.com/bitcoinuniverseio/op-return) · [mezcal](https://github.com/bitcoinuniverseio/mezcal) · [ordex](https://github.com/bitcoinuniverseio/ordex) · [chainbloom](https://github.com/bitcoinuniverseio/chainbloom) · [witness-circles](https://github.com/bitcoinuniverseio/witness-circles) · [tandem](https://github.com/bitcoinuniverseio/tandem) · [patina](https://github.com/bitcoinuniverseio/patina) |
| Dogecoin | [tap-on-doge](https://github.com/bitcoinuniverseio/tap-on-doge) |
| Archived | [sentry](https://github.com/bitcoinuniverseio/sentry) |

## Infrastructure and source

| Repository | Role |
| --- | --- |
| [bitcoin-indexer](https://github.com/bitcoinuniverseio/bitcoin-indexer) | Multi-protocol Bitcoin indexer |
| [mempool](https://github.com/bitcoinuniverseio/mempool) | Explorer fork powering Universe chain views |
| [ord-dogecoin](https://github.com/bitcoinuniverseio/ord-dogecoin) | Ordinals implementation for Dogecoin |
| [btc_stamps](https://github.com/bitcoinuniverseio/btc_stamps) | Bitcoin Stamps indexer |
| [stampchain.io](https://github.com/bitcoinuniverseio/stampchain.io) | Stamps explorer and API |
| [alkanes-rs](https://github.com/bitcoinuniverseio/alkanes-rs) | Alkanes metaprotocol implementation in Rust |
| [index-witness-circles](https://github.com/bitcoinuniverseio/index-witness-circles) | Witness Circles indexer |
| [index-tandem](https://github.com/bitcoinuniverseio/index-tandem) | Tandem indexer |
| [tandem-verifier-rs](https://github.com/bitcoinuniverseio/tandem-verifier-rs) | Independent Tandem verifier in Rust |
| [index-patina](https://github.com/bitcoinuniverseio/index-patina) | Patina indexer |
| [universe-ci-actions](https://github.com/bitcoinuniverseio/universe-ci-actions) | Shared CI actions for every Universe repository |

## Start here

- **Use a product**: [docs.bitcoinuniverse.io](https://docs.bitcoinuniverse.io)
- **Build on an API**: each product's documentation links its API reference and schemas
- **Implement a protocol**: open the protocol repository; the specification and test vectors live there
- **Report a bug**: open an issue on the matching repository
- **Report a vulnerability**: use private vulnerability reporting, never a public issue. See [SECURITY.md](https://github.com/bitcoinuniverseio/.github/blob/main/SECURITY.md)

Everything on these chains is real and irreversible. Our documentation states risk before action; if a page tells you something unsafe, that is a bug we want reported.
