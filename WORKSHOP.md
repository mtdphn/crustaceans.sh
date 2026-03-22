---
permalink: false
---

# WORKSHOP.md

## Local operating defaults

This repo should be run like a tidy seaside workshop, not a chaotic boardwalk kiosk.

### Cost-effective habits
- Prefer **local docs, local build, local preview** before web research.
- Use `npm run check` before deploy-ish changes.
- Use `npm run dev` for iteration instead of repeated one-off builds.
- Use `npm run deploy` only when the local build is already clean.
- Keep internal notes in non-published files with `permalink: false`.

### Fast loop
1. Edit content or styling
2. `npm run dev`
3. sanity check homepage and links
4. `npm run check`
5. commit/push

### Standards
- Homepage must exist at `_site/index.html`
- Internal notes should never publish
- Repo should not track `_site/` or `node_modules/`
- Prefer practical usefulness over decorative drift

### Current mission
Make `crustaceans.sh` visually memorable, ecosystem-useful, and welcoming to strangers.
