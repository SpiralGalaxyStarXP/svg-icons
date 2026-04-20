# SVG Icon Pack — 204 Icons

A comprehensive set of clean, stroke-based SVG icons across 6 categories.

## Categories

| Category | Count | Examples |
|---|---|---|
| UI / App Controls | ~80 | home, search, lock, camera, settings, toggle... |
| Arrows & Directional | ~25 | all 4 arrows, chevrons, corners, skip, shuffle... |
| Social & Media | ~12 | rss, hash, thumbs-up, trending, activity... |
| Weather & Nature | ~16 | sun, moon, cloud variants, wind, flame, waves... |
| E-commerce & Finance | ~22 | cart, wallet, receipt, dollar, coins, truck... |
| Files, Dev & Misc | ~49 | file, folder, terminal, code, git, database... |

## Usage

All icons use `currentColor` — set CSS `color` to tint them:

```html
<!-- As <img> -->
<img src="icons/home.svg" width="24" height="24" style="color: #333;" />

<!-- Inline for full CSS control -->
<svg ...><path .../></svg>

<!-- In CSS background -->
.icon { background-image: url('icons/search.svg'); }
```

## Specs

- **ViewBox**: `0 0 24 24`
- **Stroke width**: `1.5px`
- **Stroke caps**: `round`
- **Stroke joins**: `round`
- **Fill**: `none` (stroke-only)
- **Color**: `currentColor` (inherits from CSS)

## License

MIT — free for personal and commercial use. No attribution required.
