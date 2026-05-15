# AGENTS.md

This repository is the single source of truth for the Green Apple project.

## Mandatory reading order

Every AI runtime must read these files before work:

1. `AGENTS.md`
2. `PROJECT_STATE.md`
3. `NEXT_TASK.md`
4. The selected role file in `agents/`
5. Relevant files in `docs/`, `research/`, and `logs/`

## Global rules

- Do not guess missing requirements.
- Do not work outside the repository contract.
- Do not change accepted decisions without updating `docs/DECISIONS.md`.
- Do not modify production code unless the selected agent role allows it.
- After each work session, update `PROJECT_STATE.md`, `NEXT_TASK.md`, and the relevant log file.
- If blocked, write the blocker in `NEXT_TASK.md`.
- Prefer MVP-first execution over over-engineering.

## Default workflow

1. Pre-Research Agent writes `research/`.
2. Architect Agent writes `docs/` and Codex task packets.
3. Draft Coder may create implementation drafts when explicitly assigned.
4. Codex implements and tests in the repository.
5. Reviewer audits changes and records findings.
6. Librarian saves reusable patterns and lessons.
