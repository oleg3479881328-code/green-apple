# PROJECT_STATE.md

## Project

Green Apple

## Current stage

Static landing page draft created.

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
- `index.html` — static landing page draft.
- `styles.css` — landing page styles.
- `agents/` — agent role files.
- `docs/` — architecture and specification.
- `research/` — open-source and market research.
- `logs/` — agent run logs and decision logs.

## Current implementation status

- `index.html` exists.
- `styles.css` exists.
- MVP sections included: hero, benefits, product offer, freshness/trust, and contact/purchase CTA.
- Implementation uses plain HTML and CSS.
- No backend, database, payment processing, framework, build step, or external scripts were added.

## Known problems

- Brand style is still draft-level and not final.
- Final copywriting is not approved yet.
- Real purchase/contact mechanism is not selected yet.
- CTA uses placeholder email `hello@example.com`.
- Manual browser verification has not been run in the user's local environment.
- Codex has not yet validated or refined the draft.

## Do not change

- Do not treat this repository as a finished application.
- Do not add backend, database, payment processing, or complex ordering logic in MVP.
- Do not over-engineer the first implementation.

## Next required action

Run Codex to verify the static landing page draft, test it locally, clean up any issues, and prepare final MVP integration according to `docs/ARCHITECTURE.md`, `docs/TECH_SPEC.md`, and `NEXT_TASK.md`.
