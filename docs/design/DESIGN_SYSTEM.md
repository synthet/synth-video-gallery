# Design system (Driftara Video)

Canonical palette, labels, and status colors live in the sibling package **[@synthet/synth-photo-design](https://github.com/synthet/synth-photo-design)** (`../image-scoring-ui`).

## Consumption

| Layer | File |
|-------|------|
| Shared tokens | `src/styles/tokens.css` → `@import '@synthet/synth-photo-design/tokens.css'` |
| App layout/spacing | `src/styles/tokens.local.css` |
| Shell layout | `src/styles/layout.css` |
| Global utilities | `src/index.css` |

## UX spec

Visual language matches **image-scoring-gallery**: VS Code Dark+, dense layout, flat `#007acc` accents. See [image-scoring-gallery FRONTEND_UX_SPEC.md](https://github.com/synthet/image-scoring-gallery/blob/main/docs/design/FRONTEND_UX_SPEC.md).

Full contract: [image-scoring-ui DESIGN_SYSTEM.md](https://github.com/synthet/image-scoring-ui/blob/main/docs/DESIGN_SYSTEM.md).

## CI

```bash
npm run design:check
```
