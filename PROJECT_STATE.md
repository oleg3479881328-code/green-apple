# PROJECT_STATE.md

## Project

Green Apple

## Current stage

Static landing page redesigned into fruit-market commercial MVP draft.

## Current product goal

Create a vivid fruit-market style landing page for selling green apples.

## Current MVP goal

Build a static one-page website that clearly presents fresh green apples, explains the 3-ruble offer, compares it with a 5-ruble example market price, shows key benefits, and provides a call-to-action for purchase/contact.

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
- Visual direction is now fruit-market abundance: vivid colors, produce-stall feeling, price tags, and direct commercial offer.

## Current structure

- `AGENTS.md` — global repo contract.
- `PROJECT_STATE.md` — current project state.
- `NEXT_TASK.md` — next task handoff.
- `index.html` — redesigned static landing page draft.
- `styles.css` — fruit-market visual styles.
- `agents/` — agent role files.
- `docs/` — architecture and specification.
- `research/` — open-source and market research.
- `logs/` — agent run logs and decision logs.

## Current implementation status

- `index.html` exists and was redesigned for a fruit-market commercial offer.
- `styles.css` exists and was redesigned with vivid market colors, price-card styling, dense fruit-stall composition, responsive layout, and no external dependencies.
- MVP sections included: hero, direct offer, market price comparison, benefits, freshness/trust, and contact/purchase CTA.
- Commercial example offer added: fresh green apples for 3 rubles each.
- Market comparison added: 5-ruble example price versus 3-ruble Green Apple offer.
- Implementation uses plain HTML and CSS.
- No backend, database, payment processing, framework, build step, or external scripts were added.

## Known problems

- Real purchase/contact mechanism is not selected yet.
- CTA uses placeholder email `hello@example.com`.
- Manual browser verification has not been run in the user's local environment.
- Codex has not yet validated the redesigned implementation.
- Final real business details are still placeholders/examples.

## Do not change

- Do not treat this repository as a finished application.
- Do not add backend, database, payment processing, or complex ordering logic in MVP.
- Do not over-engineer the first implementation.

## Next required action

Run Codex to verify the redesigned static landing page locally, check desktop/mobile layout, confirm CSS loading, inspect accessibility/readability, and update project state/logs after verification.
