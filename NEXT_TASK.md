# NEXT_TASK.md

## Assigned agent

Codex in VS Code.

## Goal

Verify, clean up, and finalize the first static landing page MVP draft created by Draft Coder Agent.

## Input files to read

- `AGENTS.md`
- `PROJECT_STATE.md`
- `NEXT_TASK.md`
- `index.html`
- `styles.css`
- `docs/ARCHITECTURE.md`
- `docs/TECH_SPEC.md`
- `docs/DECISIONS.md`
- `logs/agent_runs.md`

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
- Backend, database, payment, inventory, or framework files.

## Current implementation draft

Created files:

- `index.html`
- `styles.css`

Included sections:

- Hero section
- Benefits section
- Product offer section
- Freshness/trust section
- Contact or purchase CTA section
- Responsive layout

## Codex verification tasks

1. Open `index.html` locally.
2. Confirm `styles.css` loads correctly.
3. Confirm the page is readable on desktop width.
4. Confirm the page is readable on mobile width.
5. Confirm all section links work.
6. Confirm there are no broken local references.
7. Check HTML validity and basic accessibility.
8. Improve only obvious issues without changing MVP scope.
9. Keep the project static: no backend, no database, no payment processing, no framework, no build step, no external scripts.
10. Update `PROJECT_STATE.md`, `NEXT_TASK.md`, and `logs/agent_runs.md` after verification.

## Definition of done

- Landing page opens locally.
- `index.html` and `styles.css` are valid for MVP.
- Responsive layout is checked.
- CTA is visible.
- No missing local assets or scripts.
- `PROJECT_STATE.md` records verified implementation status.
- `NEXT_TASK.md` points to the next real task after verification.
- `logs/agent_runs.md` records the Codex verification run.
