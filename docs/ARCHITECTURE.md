# ARCHITECTURE.md

## Status

MVP architecture initialized.

## Mission

Create a simple static landing page for selling green apples.

## MVP boundary

In scope:

- One-page static landing page.
- Clear hero section.
- Product benefits section.
- Simple product/offer section.
- Call-to-action section.
- Basic responsive layout.
- Lightweight styling.

Out of scope:

- Backend.
- Database.
- Payment processing.
- Inventory management.
- User accounts.
- Delivery automation.
- Admin panel.

## System modules

### Static frontend

Responsible for the visible landing page.

Suggested files:

- `index.html`
- `styles.css`
- optional `script.js` only if needed

### Content sections

Required page sections:

1. Hero section
2. Benefits section
3. Product offer section
4. Trust/freshness section
5. Contact or purchase call-to-action

## Data flow

No dynamic data flow in MVP.

User opens page → reads offer → clicks call-to-action.

## External dependencies

MVP should avoid external dependencies unless necessary.

Preferred:

- Plain HTML
- Plain CSS
- Minimal JavaScript only if needed

## Storage model

No storage in MVP.

## Runtime model

Static site served by browser or GitHub Pages.

## Security constraints

- No secrets in repository.
- No payment logic in MVP.
- No external scripts unless explicitly approved.

## Testing strategy

Manual MVP checks:

- Page opens in browser.
- Layout works on desktop width.
- Layout works on mobile width.
- Call-to-action is visible.
- No broken local links.

## Deployment assumptions

The first deployment target can be GitHub Pages after the static files exist.
