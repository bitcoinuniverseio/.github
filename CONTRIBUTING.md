# Contributing

Thank you for improving Bitcoin Universe. This file covers what every repository in the organization has in common; a repository's own CONTRIBUTING.md adds specifics.

## Ground rules

1. **One focused change per pull request**, with the reasoning in the description.
2. **`develop` is the working branch** unless the repository states otherwise. Production refs are protected and promoted by release process, not by direct pushes.
3. **CI must pass.** Checks are not advisory; a red check is a blocker, not a suggestion.
4. **State risk before action** in any documentation you touch. Never describe planned behavior as live.
5. **Nothing private**: no internal hostnames, IPs, ports, credentials, seed phrases, or operational tooling in code, docs, examples, screenshots, or fixtures.
6. **No secrets in issues or PRs.** Vulnerabilities go through [SECURITY.md](SECURITY.md), privately.

## Documentation changes

All public documentation feeds the portal at [docs.bitcoinuniverse.io](https://docs.bitcoinuniverse.io). Each repository owns its content and declares it in a root `docs.manifest.json`; the portal builds from pinned commits, so a merged docs change reaches the portal through an automated update PR on [docs-platform](https://github.com/bitcoinuniverseio/docs-platform).

Writing rules for documentation:

- Plain, specific, confident. Say "unknown" rather than guessing.
- Availability claims defer to status data, never to prose.
- No marketing filler, no unsupported superlatives.
- Task guides need: outcome, prerequisites, steps, what can go wrong, how to recover, how to verify.
- Every image needs real alt text.

## Code changes

- Match the existing style of the file you are editing.
- Add or update tests for every changed behavior where meaningful.
- Keep changes surgical; do not reformat or refactor code you are not fixing.

## Where to start

Issues labeled `good first issue` or `documentation` are the intended entry points. If you want to make a larger change, open an issue first so the approach is agreed before you invest the work.
