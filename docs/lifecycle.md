# Lifecycle and availability terminology

Every Bitcoin Universe repository, documentation page, status card, and capability claim uses these terms with exactly these meanings. Do not invent synonyms.

This file is the version repositories are held to. The portal publishes the reader-facing version of the same vocabulary at [How to read our status](https://docs.bitcoinuniverse.io/status/); the two are kept in agreement, and a difference between them is a bug worth reporting.

The five component-lifecycle values below are also the exact enum of the `lifecycle` field in every `docs.manifest.json`, and the eight data and service states are the values products and APIs return.

## Component lifecycle

| State | Meaning |
| --- | --- |
| `stable` | Released, supported, and safe to rely on. Breaking changes follow a deprecation window. |
| `beta` | Released for real use, still changing. Breaking changes may arrive with short notice. |
| `experimental` | Exists and may run, but is not released for reliance. May change or disappear without notice. |
| `deprecated` | Still works, replacement named, removal date or window published. |
| `archived` | Frozen. No changes, no support, kept for reference with a named replacement where one exists. |

## Data and service states

| State | Meaning |
| --- | --- |
| `healthy` | Serving current data within its freshness target. |
| `delayed` | Serving, but behind its freshness target. |
| `stale` | Serving old data; the source has not updated within its tolerated window. |
| `degraded` | Partially serving; some capabilities down or unreliable. |
| `unavailable` | Not serving. This is never the same as "empty". |
| `unsupported` | The capability does not exist for this chain, network, or version. |
| `unknown` | We cannot currently determine the state. Never presented as zero or empty. |
| `empty` | Queried successfully and there is genuinely nothing. |

## Hard rules

- **Code presence is never availability.** Code existing in a repository is never evidence that a capability is released. A capability is claimed only when release evidence backs it: a released version, a capability manifest, and a validated contract.
- **Unavailable is never empty.** If a source is down, a reader sees that the source is down, not a blank list.
- **Unknown is never zero.** A balance we cannot read shows as unreadable, never as `0`.
- **Freshness is measured, not asserted.** Live status derives from bounded public endpoints, and every status card shows when it last updated. Those endpoints are declared per repository in `docs.manifest.json` under `statusSources`, and the portal's aggregated status is built only from endpoints declared there.
- **Every state change names its destination.** A `deprecated` claim names the replacement and the removal window. An `archived` surface names its replacement or states plainly that none exists, and its manifest carries the `archived` object with `date`, `reason`, and `replacement`, where `replacement` may be `null` only when nothing genuinely replaced it.
