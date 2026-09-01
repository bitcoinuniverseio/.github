# Security

This policy applies to every public repository in the `bitcoinuniverseio` organization unless a repository carries its own SECURITY.md.

## Reporting a vulnerability

Report privately. Never in a public issue, pull request, commit message, discussion, or social post: all of those give an attacker the same head start they give us.

**Route 1, preferred: GitHub private vulnerability reporting.** Open the affected repository, go to the Security tab, and choose "Report a vulnerability". The thread is private to the maintainers until an advisory is published, and it stays with you until the issue is resolved.

**Route 2, if that repository does not offer it.** Private vulnerability reporting is enabled per repository. If the Security tab shows no "Report a vulnerability" option, or the repository is archived and therefore read-only, email **bitcoinuniversecorp@gmail.com** with the repository or product name in the subject line. This route always works.

Either way, tell us:

- what you found and where, naming the repository, page URL, API route, or component;
- what you expected instead, and why the difference matters;
- the smallest steps that reproduce it;
- the commit, released version, or deployed build you tested, if you know it.

A clear description is enough. No proof of exploitation is needed, and we would rather you stop at the point where you are confident than go further to demonstrate impact.

## What never belongs in a report

Seed phrases, private keys, mnemonics, wallet files, API tokens, session cookies, database credentials, or anyone's personal data. None of them are needed to reproduce a defect, and they cannot be un-sent. If reproducing an issue looks like it requires a secret, say so and we will find another way.

Do not test against other people's assets, addresses, or funds. Everything on these chains is real and irreversible.

## What to expect

You will get an acknowledgement, an assessment, and credit in the fix's release notes if you want it. There is no bug bounty program at this time; this file will change if that changes.

## Scope notes

- **Documentation is in scope.** A wrong claim or an unsafe instruction that could cause loss is a security report, not a typo. Use the same private route.
- **Protocol specification flaws** belong in a private report against the protocol repository that owns the specification.
- **Infrastructure and service issues** affecting live products belong in a private report against this organization.
- **Archived repositories** are frozen and run nowhere. If a flaw you found in archived material also affects something still running, report it against the running component instead.
- If you are not sure where a report belongs, send it anyway and say so. It will be routed.
