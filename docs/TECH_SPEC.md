# TECH_SPEC.md

## Status

MVP technical specification initialized.

## Product goal

Create a landing page for selling green apples.

## User story

As a visitor, I want to quickly understand the green apple offer, see why the apples are worth buying, and have a clear way to contact or purchase.

## Functional requirements

### FR-001 — Static landing page

Create a one-page static website.

### FR-002 — Hero section

The page must include:

- Main headline
- Short value proposition
- Primary call-to-action

### FR-003 — Benefits section

The page must show 3-4 benefits of green apples, such as freshness, crisp taste, healthy snack, and simple ordering.

### FR-004 — Product offer section

The page must show a simple offer for green apples.

Example content can be placeholder text until final business details are provided.

### FR-005 — Contact / purchase call-to-action

The MVP must include a clear CTA button or contact block.

Because no real payment/contact channel is confirmed, use placeholder CTA text such as:

`Order now` / `Contact us`.

### FR-006 — Responsive layout

The page must be readable on desktop and mobile.

## Non-functional requirements

- Keep implementation simple.
- Avoid frameworks.
- Avoid build step.
- Avoid backend.
- Avoid external dependencies.
- Keep files understandable for future AI agents.

## MVP scope

Files to create:

- `index.html`
- `styles.css`

Optional only if needed:

- `script.js`

## Out of scope

- Shopping cart
- Stripe or payment processing
- Database
- Inventory tracking
- Authentication
- Admin dashboard
- Delivery logic

## Interfaces

No API interfaces in MVP.

## Data model

No application data model in MVP.

## Error handling

No runtime error handling required beyond valid HTML/CSS.

## Test requirements

Manual checks:

- Open `index.html` locally.
- Confirm content is visible.
- Confirm mobile responsive layout.
- Confirm CTA is visible.
- Confirm no broken references to missing local files.

## Codex implementation tasks

1. Read `AGENTS.md`, `PROJECT_STATE.md`, `NEXT_TASK.md`, `docs/ARCHITECTURE.md`, and this file.
2. Create `index.html` and `styles.css`.
3. Implement a clean static landing page for green apples.
4. Keep the design simple, bright, and product-focused.
5. Do not add backend or dependencies.
6. Update `PROJECT_STATE.md`, `NEXT_TASK.md`, and `logs/agent_runs.md` after implementation.
