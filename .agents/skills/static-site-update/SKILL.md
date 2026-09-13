---
name: static-site-update
description: Update CDN dependencies (Bootstrap, Bootstrap Icons, Google Fonts) on this static site while preserving constraints. Use when the task involves bumping CDN versions, fixing SRI hashes, or touching index.html head assets.
---

# Static Site Update

Constraints (from `AGENTS.md`): static site, no build step, no bundler, no vendored CDN code.
Tokens stay in `assets/css/style.css`. Preserve semantic HTML5, ARIA labels,
heading hierarchy (single `h1`), and `prefers-reduced-motion`. Keep `.nojekyll`;
Pages deploys from `main` root.

## Checklist

1. Check latest versions at `getbootstrap.com` (CSS + JS bundle) and
   `icons.getbootstrap.com` (Icons). Do not bump blindly from memory.
2. Always update version URL and `integrity` (SRI) hash together.
   Stale SRI blocks the file in browsers. Canonical 5.3.8 hashes:
   - CSS: `sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB`
   - JS bundle: `sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI`
3. Load Google Fonts via `<link>` with `preconnect` in `index.html`,
   never via CSS `@import` after other rules (browsers ignore it).
4. Keep one `h1` per page; match CSS selectors if a heading level changes.
5. Verify: open `index.html` in a browser, check hero, links, responsive
   layout, keyboard navigation. No build or test command applies.
