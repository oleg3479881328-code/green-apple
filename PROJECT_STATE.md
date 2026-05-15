# PROJECT_STATE.md

## Project

Green Apple

## Current stage

Architecture initialized for MVP landing page.

## Current product goal

Create a simple landing page for selling green apples.

## Current MVP goal

Build a static one-page website that clearly presents green apples, explains the offer, shows key benefits, and provides a call-to-action for purchase/contact.

## Accepted decisions

- Repository is the single source of truth.
- Agents are stored as portable role files in `agents/`.
- Work state is stored in `PROJECT_STATE.md`.
- Next handoff is stored in `NEXT_TASK.md`.
- Architecture and decisions are stored in `docs/`.
- Research outputs are stored in `research/`.
- Agent activity is logged in `logs/`.
- Green Apple product direction is a landing page for selling green apples.
- MVP must stay static and simple before adding backend, payments, inventory, or delivery logic.

## Current structure

- `AGENTS.md` — global repo contract.
- `PROJECT_STATE.md` — current project state.
- `NEXT_TASK.md` — next task handoff.
- `agents/` — agent role files.
- `docs/` — architecture and specification.
- `research/` — open-source and market research.
- `logs/` — agent run logs and decision logs.

## Known problems

- No source code exists yet.
- Brand style is not defined yet.
- Final copywriting is not approved yet.
- Purchase/contact mechanism is not selected yet.

## Do not change

- Do not treat this repository as a finished application.
- Do not add backend, database, payment processing, or complex ordering logic in MVP.
- Do not over-engineer the first implementation.

## Next required action

Run Codex to implement a static landing page MVP according to `docs/ARCHITECTURE.md`, `docs/TECH_SPEC.md`, and `NEXT_TASK.md`.
