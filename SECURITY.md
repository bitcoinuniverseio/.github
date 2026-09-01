# Security

This policy applies to every public repository in the `bitcoinuniverseio` organization unless a repository carries its own SECURITY.md.

## Reporting a vulnerability

1. Use GitHub private vulnerability reporting on the affected repository (Security tab, "Report a vulnerability").
2. Include what you found, where, the impact you believe it has, and steps to reproduce. A proof of concept helps; destructive demonstrations do not.

Do not open a public issue for a vulnerability. Do not put secrets, private keys, or personal data in any report. Do not test against other people's assets: everything on these chains is real and irreversible.

## What to expect

You will get an acknowledgement, an assessment, and credit in the fix's release notes if you want it. There is no bug bounty program at this time; this file will change if that changes.

## Scope notes

- Documentation problems that could cause loss (a wrong claim, an unsafe instruction) are security reports too.
- Protocol specification flaws belong in a private report against the protocol repository.
- Infrastructure and service issues affecting live products belong in a private report against this organization.
