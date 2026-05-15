# NEXT_TASK.md

## Assigned agent

Draft Coder Agent running on ChatGPT.

## Goal

Create the first implementation draft for the Green Apple static landing page MVP before handing final integration to Codex.

## Input files to read

- `AGENTS.md`
- `PROJECT_STATE.md`
- `NEXT_TASK.md`
- `agents/draft_coder.md`
- `docs/ARCHITECTURE.md`
- `docs/TECH_SPEC.md`
- `docs/DECISIONS.md`

## Files allowed to edit

- `index.html`
- `styles.css`
- `README.md`
- `PROJECT_STATE.md`
- `NEXT_TASK.md`
- `logs/agent_runs.md`

## Files forbidden to edit

- `agents/` unless explicitly requested.
- `docs/ARCHITECTURE.md` unless implementation reveals a real architecture issue.
- `docs/TECH_SPEC.md` unless implementation reveals a real specification issue.

## Expected output

A clean first draft of a static one-page landing page for selling green apples.

Required draft files:

- `index.html`
- `styles.css`

Required page sections:

- Hero section
- Benefits section
- Product offer section
- Freshness/trust section
- Contact or purchase CTA section
- Responsive layout

## Constraints

- No backend.
- No database.
- No payment processing.
- No frameworks.
- No build step.
- No external scripts.
- Keep MVP simple.
- Treat this as a draft that Codex must later verify and refine.

## Definition of done

- `index.html` exists.
- `styles.css` exists.
- Page content matches `docs/TECH_SPEC.md`.
- `PROJECT_STATE.md` is updated.
- `NEXT_TASK.md` points to Codex for verification, cleanup, and final integration.
- `logs/agent_runs.md` is updated.
