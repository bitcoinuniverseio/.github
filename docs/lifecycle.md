# Lifecycle and availability terminology

Every Bitcoin Universe repository, documentation page, status card, and capability claim uses these terms with exactly these meanings. Do not invent synonyms.

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

- Code existing in a repository is never evidence that a capability is released. Capability claims come from release evidence and capability manifests.
- `unavailable` is never rendered as an empty result. `unknown` is never rendered as zero.
- Every `deprecated` claim names the replacement and the window. Every `archived` surface names its replacement or states that none exists.
