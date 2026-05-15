# PROJECT_STATE.md

## Project

Green Apple

## Current stage

Bootstrap initialized.

## Current goal

Create a repo-native AI project structure where ChatGPT, Codex, and other AI runtimes can coordinate through repository files.

## Accepted decisions

- Repository is the single source of truth.
- Agents are stored as portable role files in `agents/`.
- Work state is stored in `PROJECT_STATE.md`.
- Next handoff is stored in `NEXT_TASK.md`.
- Architecture and decisions are stored in `docs/`.
- Research outputs are stored in `research/`.
- Agent activity is logged in `logs/`.

## Current structure

- `AGENTS.md` — global repo contract.
- `PROJECT_STATE.md` — current project state.
- `NEXT_TASK.md` — next task handoff.
- `agents/` — agent role files.
- `docs/` — architecture and specification.
- `research/` — open-source and market research.
- `logs/` — agent run logs and decision logs.

## Known problems

- Project product goal is not defined yet.
- No architecture exists yet.
- No source code exists yet.

## Do not change

- Do not treat this repository as a finished application.
- Do not implement code before architecture is created.

## Next required action

Run Pre-Research Agent or Architect Agent depending on the chosen product goal.
