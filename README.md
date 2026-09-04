# Stickman

Single-page sales/landing site for **The Stickman Blueprint** — a guide on building a faceless, AI-animated stickman YouTube channel.

## Contents

- [`index.html`](index.html) — the entire site (markup, styles, and a small vanilla-JS countdown timer), self-contained with no build step or dependencies.

## Running locally

Just open [`index.html`](index.html) in a browser, or serve the directory with any static file server, e.g.:

```sh
npx serve .
```

## Deploying

This is a static file, so it can be hosted as-is on GitHub Pages, Netlify, Vercel, or any static host — point it at `index.html`.

## Notes

- The checkout button links to the product's Selar page.
- The countdown timer stores a per-visitor 24-hour deadline in `localStorage` and falls back gracefully (in-memory, for that page view) if storage is unavailable.
