# AGENTS.md — Universe (organization)

This file is the global rule set for every repository in the `bitcoinuniverseio` organization (Universe). Each repo also has its own `AGENTS.md` for local startup, commands, and owners. The repo file wins on local paths and commands; this file wins on invariants.

Keep this file short. Put long guides in the owning repo and leave a pointer here.

## What every Universe agent does

1. Initialize before writing code: read that repo’s `PROGRESS.md` or session boot file (such as `BOOT.md`), `DECISIONS.md`, `feature_list.json` if present, and `git log --oneline -5`. Record the exact HEAD sha. Run `./init.sh` when the repo has one.
2. Work on one feature at a time (WIP=1).
3. Do not mark a feature done because code was added. Done means verification evidence is recorded.
4. Leave a clean handoff: update progress, decisions, verification notes, and the feature list; delete leftovers (debug logs, temp files, commented-out code, stray TODOs).
5. If `./init.sh` verification fails, fix the baseline before any new feature work.

## Definition of done

Feature complete = end-to-end verification passed, not “code is written.”

1. Unit tests pass.
2. Integration tests pass.
3. End-to-end flow verification passes.

Do not start level 2 if level 1 failed. Do not start level 3 if level 2 failed.

## Diagnostic loop

A failure is a harness defect, not “the model being dumb again.” Name the layer, fix it, and do not fail that way again:

- task_specification
- context_provision
- execution_environment
- verification_feedback
- state_management

Append one JSON line per task to the repo’s diagnostic log (`diagnostics/log.jsonl` or `.agents/harness/diagnostics/log.jsonl`): task, ok, layer (if failed), detail, fix.

## Golden rules

- Prefer the shared utility package over hand-rolled helpers.
- Do not YOLO-guess data structures. Validate boundaries or use typed SDKs.
- Prefer durable repo files over chat summaries.
- The implementer does not grade itself. An independent check (reviewer, `selfcheck`, or a separate verifier) must pass.
- Do not mix Universe product surfaces with Grupo Open / Open Group branding.

## Loops

- `/goal` = one big task, runs until an independent checker says it is done (or max turns).
- `/loop` = one small action, repeats on an interval (watch, poll, recurring check).
- Turn-based chat is fine for small work. Event-driven automation handles PRs, CI, and issues.

## Cleanup

Before ending a session: startup path still works, verification still runs, progress is honest, no half-finished step is undocumented, next session can run without a manual repair.
