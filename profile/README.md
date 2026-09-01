# Bitcoin Universe

Products, protocols, and open infrastructure for digital artifacts on Bitcoin, Dogecoin, and Zcash. We run our own nodes and indexers, publish the specifications we implement, and document what is actually released rather than what is planned.

**Documentation home: [docs.bitcoinuniverse.io](https://docs.bitcoinuniverse.io)**

As of 1 September 2026 the estate covers 3 chains, 7 products, and 41 protocol dossiers, across 38 repositories that publish a documentation manifest and 25 documentation sites that are live. [Documentation health](https://docs.bitcoinuniverse.io/status/documentation-health/) publishes the current manifest coverage, per-repository lifecycle, and every gap we have not closed yet.

## Start here

| You want to | Go to |
| --- | --- |
| Understand what this is | [What Bitcoin Universe is](https://docs.bitcoinuniverse.io/start/what-bitcoin-universe-is/) |
| Stay safe before you sign anything | [Safety in sixty seconds](https://docs.bitcoinuniverse.io/start/safety/) |
| Find the right path for you | [Choose your path](https://docs.bitcoinuniverse.io/start/choose-your-path/) |
| Use a product | [Product catalog](https://docs.bitcoinuniverse.io/products/) |
| Implement or index a protocol | [Protocol Atlas](https://docs.bitcoinuniverse.io/protocols/) |
| Build against an API | [Developer overview](https://docs.bitcoinuniverse.io/developers/) and the [interface directory](https://docs.bitcoinuniverse.io/developers/interfaces/) |
| Know which chains and networks are covered | [Chains and networks](https://docs.bitcoinuniverse.io/chains/) |
| Check whether something is up | [Live status](https://docs.bitcoinuniverse.io/status/live/) |
| Ask a question in plain language | [Ask Universe](https://docs.bitcoinuniverse.io/ask/) |

Machine-readable: [`/ecosystem.json`](https://docs.bitcoinuniverse.io/ecosystem.json) describes the estate, and [`/llms.txt`](https://docs.bitcoinuniverse.io/llms.txt) is the entry point for automated readers.

## Products

| Product | What it is | Documentation | Live |
| --- | --- | --- | --- |
| **Core** | Explorer, portfolio, and marketplace across every supported protocol | [docs site](https://bitcoinuniverseio.github.io/docs-core/) · [portal](https://docs.bitcoinuniverse.io/products/core/) | [bitcoinuniverse.io](https://bitcoinuniverse.io) |
| **Wallet** | Self-custody browser wallet for Bitcoin digital artifacts, built to make approvals readable | [docs site](https://bitcoinuniverseio.github.io/docs-wallet/) · [portal](https://docs.bitcoinuniverse.io/products/wallet/) | Not publicly released |
| **Inscribe** | Creation studio for inscriptions, tokens, collections, and mints, with cost shown before you commit | [docs site](https://bitcoinuniverseio.github.io/docs-inscribe/) · [portal](https://docs.bitcoinuniverse.io/products/inscribe/) | [inscribe.bitcoinuniverse.io](https://inscribe.bitcoinuniverse.io) |
| **StampDEX** | Trading venue for Bitcoin Stamps and SRC-20, with its own order and settlement model | [docs site](https://bitcoinuniverseio.github.io/docs-stampdex/) · [portal](https://docs.bitcoinuniverse.io/products/stampdex/) | [stampdex.fun](https://stampdex.fun) |
| **Zerdinals and Z-Runes** | Digital artifacts and fungible tokens native to Zcash, with the ZordiScan explorer | [docs site](https://bitcoinuniverseio.github.io/docs-zerdinals-and-zrunes/) · [portal](https://docs.bitcoinuniverse.io/products/zerdinals-and-zrunes/) | [zrunes.io](https://zrunes.io) |
| **Forked Felines** | The KNOT HEADS companion collection, drawn whole and inscribed whole on Bitcoin | [docs site](https://docs.forkedfelines.art) · [portal](https://docs.bitcoinuniverse.io/products/forked-felines/) | [forkedfelines.art](https://forkedfelines.art) |
| **Drops** | Media-first artifacts and Drop Pacts, carried in an OP_DROP Taproot leaf | [docs site](https://bitcoinuniverseio.github.io/drops-protocol-docs/) · [portal](https://docs.bitcoinuniverse.io/products/drops/) | Not publicly released |

## Protocols

The [Protocol Atlas](https://docs.bitcoinuniverse.io/protocols/) is the map: it carries a dossier for every protocol Universe implements, indexes, or documents, including the ones whose specification lives outside this organization. Each dossier records what the protocol is, which Universe surface supports which action, and the stated reason for anything unsupported.

The repositories below are the specification homes we own. Each publishes a specification, a guide, indexer semantics, test vectors, and a client-side validator or decoder.

### Bitcoin

[BRC-20](https://bitcoinuniverseio.github.io/brc-20/) ·
[Runes](https://bitcoinuniverseio.github.io/runes/) ·
[SRC-20](https://bitcoinuniverseio.github.io/src-20/) ·
[SRC-101](https://bitcoinuniverseio.github.io/src-101/) ·
[Alkanes](https://bitcoinuniverseio.github.io/alkanes/) ·
[Atomicals and ARC-20](https://bitcoinuniverseio.github.io/atomicals-and-arc-20/) ·
[TAP](https://bitcoinuniverseio.github.io/tap/) ·
[BLOCK-20](https://bitcoinuniverseio.github.io/block-20/) ·
[DUST-20](https://bitcoinuniverseio.github.io/dust-20/) ·
[Mezcal](https://bitcoinuniverseio.github.io/mezcal/) ·
[OP_RETURN family](https://bitcoinuniverseio.github.io/op-return/) ·
[OP_DROP](https://bitcoinuniverseio.github.io/op-drop/) ·
[Drops](https://bitcoinuniverseio.github.io/drops-protocol-docs/) ·
[Ordex](https://bitcoinuniverseio.github.io/ordex/) ·
[ChainBloom](https://bitcoinuniverseio.github.io/chainbloom/) ·
[Witness Circles](https://bitcoinuniverseio.github.io/witness-circles/) ·
[Tandem](https://bitcoinuniverseio.github.io/tandem/) ·
[Patina](https://bitcoinuniverseio.github.io/patina/)

### Dogecoin

[TAP on Doge](https://bitcoinuniverseio.github.io/tap-on-doge/) ·
[Doginals, DRC-20, and Dunes](https://github.com/bitcoinuniverseio/ord-dogecoin)

### Zcash

[Zerdinals and Z-Runes](https://bitcoinuniverseio.github.io/docs-zerdinals-and-zrunes/)

Protocols we index but do not author, including Ordinals, Bitcoin Stamps, DMT, Bitmap, CAT-20, CAT-721, and rare sats, have their dossier in the [Atlas](https://docs.bitcoinuniverse.io/protocols/) with attribution to the specification that owns them.

### Archived

[sentry](https://github.com/bitcoinuniverseio/sentry) is frozen: the SCIT/1 protocol was retired without a successor, and its specification and vectors are preserved there as a public record. [docs-index-doge-tap](https://github.com/bitcoinuniverseio/docs-index-doge-tap) is frozen and replaced by the [TAP on Doge](https://bitcoinuniverseio.github.io/tap-on-doge/) documentation.

## Indexers and infrastructure

| Repository | Role |
| --- | --- |
| [bitcoin-indexer](https://github.com/bitcoinuniverseio/bitcoin-indexer) | Multi-protocol Bitcoin indexer covering Ordinals, BRC-20, and Runes |
| [mempool](https://github.com/bitcoinuniverseio/mempool) | Block and mempool explorer for Bitcoin, Dogecoin, and Zcash that also reads the asset protocols carried on them |
| [ord-dogecoin](https://github.com/bitcoinuniverseio/ord-dogecoin) | Ordinals indexer, HTTP API, and explorer for Dogecoin |
| [btc_stamps](https://github.com/bitcoinuniverseio/btc_stamps) | Bitcoin Stamps indexer |
| [stampchain.io](https://github.com/bitcoinuniverseio/stampchain.io) | Stamps explorer and API |
| [alkanes-rs](https://github.com/bitcoinuniverseio/alkanes-rs) | Alkanes metaprotocol implementation in Rust |
| [index-witness-circles](https://github.com/bitcoinuniverseio/index-witness-circles) | Independent Witness Circles indexer |
| [index-tandem](https://github.com/bitcoinuniverseio/index-tandem) | Tandem indexer, API, and signed agreement service |
| [tandem-verifier-rs](https://github.com/bitcoinuniverseio/tandem-verifier-rs) | Independent Tandem verifier in Rust and PostgreSQL |
| [index-patina](https://github.com/bitcoinuniverseio/index-patina) | Independent Patina indexer and read API |
| [universe-ci-actions](https://github.com/bitcoinuniverseio/universe-ci-actions) | Shared GitHub Actions for Universe CI |
| [docs-platform](https://github.com/bitcoinuniverseio/docs-platform) | The documentation portal, design system, content schemas, search, and release tooling |

Live explorer: [explorer.bitcoinuniverse.io](https://explorer.bitcoinuniverse.io).

## How we work

Every public repository declares its documentation in a root `docs.manifest.json`. The portal ingests only from repositories with a valid manifest, pinned to exact commits, so a page can always name the source repository and commit it came from.

| Standard | Where |
| --- | --- |
| Lifecycle and availability vocabulary | [docs/lifecycle.md](https://github.com/bitcoinuniverseio/.github/blob/main/docs/lifecycle.md) and [how to read our status](https://docs.bitcoinuniverse.io/status/) |
| Documentation conventions | [docs/conventions.md](https://github.com/bitcoinuniverseio/.github/blob/main/docs/conventions.md) |
| Contribution ground rules | [CONTRIBUTING.md](https://github.com/bitcoinuniverseio/.github/blob/main/CONTRIBUTING.md) |
| Code of conduct | [CODE_OF_CONDUCT.md](https://github.com/bitcoinuniverseio/.github/blob/main/CODE_OF_CONDUCT.md) |
| Where documentation content comes from | [Source provenance](https://docs.bitcoinuniverse.io/status/provenance/) |
| Whether the documentation itself is healthy | [Documentation health](https://docs.bitcoinuniverse.io/status/documentation-health/) |
| What changed recently | [Changelog](https://docs.bitcoinuniverse.io/changelog/) |

Three rules do most of the work. Code existing in a repository is never evidence that a capability is released. `unavailable` is never rendered as an empty result, and `unknown` is never rendered as zero. Freshness is measured from a declared public endpoint, never asserted in prose.

## Getting help and reporting problems

| Situation | Route |
| --- | --- |
| A question about a product | [Getting help](https://docs.bitcoinuniverse.io/support/), then [SUPPORT.md](https://github.com/bitcoinuniverseio/.github/blob/main/SUPPORT.md) |
| Documentation that is wrong, unclear, or unsafe | Open a documentation issue on the matching repository. That counts as a bug and we want it. |
| A bug in something released | Open an issue on the repository that owns it |
| A security vulnerability | Privately, never in a public issue. Follow [SECURITY.md](https://github.com/bitcoinuniverseio/.github/blob/main/SECURITY.md). |

Everything on these chains is real and irreversible. Our documentation states the risk before the action; if a page tells you something unsafe, that is a security report, not a typo.
