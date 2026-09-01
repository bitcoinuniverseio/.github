# Documentation conventions

These conventions bind every public `bitcoinuniverseio` repository. The portal at [docs.bitcoinuniverse.io](https://docs.bitcoinuniverse.io) enforces most of them in CI.

## Ownership model

- Each repository owns its documentation content and declares it in a root `docs.manifest.json` (schema: [docs-platform `packages/content-schema`](https://github.com/bitcoinuniverseio/docs-platform)).
- The portal ingests content from exact pinned commits recorded in `sources.lock.json`. It never follows a moving branch.
- Facts live in exactly one place. Shared terminology (chains, networks, address types, fee terms, status states) comes from shared typed data, not per-repo prose.

## Truth rules

1. The default documentation view describes the latest verified stable public release, not the newest commit.
2. Every capability claim traces to release evidence: a released version, a capability manifest, a validated API contract, or an exact source commit.
3. Where code exists but is not released, say so explicitly.
4. Availability language uses the exact states in [lifecycle.md](lifecycle.md).
5. Every page records its source repository, source commit, applicable version, lifecycle state, and last-verified time.

## Writing rules

- Plain, specific, confident. State the risk before the action.
- Say "unknown" rather than guessing. Never present planned behavior as live.
- No marketing filler, fake urgency, or unsupported superlatives.
- No long dash characters (U+2014).
- Task guides include: who it is for, outcome, prerequisites, network and version, safety implications, exact steps, expected result, verification, and recovery.
- Diagrams need a text alternative. Images need real alt text.

## Safety rules

- Never publish internal hostnames, IPs, ports, credentials, admin routes, private topology, or secrets.
- Never include live credentials in screenshots or examples.
- Never ask for, accept, or demonstrate seed phrases or private keys anywhere.
- Examples run against fixtures, testnets, or safe read-only endpoints; live-mainnet write examples require explicit confirmation language.

## README standard

Every active public repository's README communicates: identity and purpose, lifecycle, supported chains and networks, current public release, documentation link, quickstart, security notes, contribution and support paths, license, and upstream attribution where the repository derives from another project. Upstream-derived repositories state the original project, its license, the Universe-specific purpose, material changes, and where to report which kind of issue.
