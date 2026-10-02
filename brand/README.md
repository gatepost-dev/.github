# Gatepost brand

The mark has four nested bands and one teal square. The bands stand for the state, LGA, district
and area segments of a postcode. The teal square is the unit, one building.

## Colours

| Colour     | Hex       | Use                                                               |
| ---------- | --------- | ----------------------------------------------------------------- |
| Teal       | `#0B8574` | The unit square only.                                             |
| Near-black | `#0E1513` | Bands and wordmark on light backgrounds. Background of the icons. |
| White      | `#FFFFFF` | Bands and wordmark on dark backgrounds.                           |

## Font

The wordmark is "gatepost" in lower case, set in Overpass SemiBold with -0.01 em letter spacing.
The social card uses Overpass Regular for its line of text.

Overpass is free under the SIL Open Font License 1.1. The lockup files hold the wordmark as
outlines, so they work without the font.

## Size

The mark sits on a 32-unit grid, and every edge falls on a whole unit.

- Show the mark at 16 px or larger.
- Use a multiple of 16 px (16, 32, 48, 64) for the sharpest edges.
- Show the lockup at 20 px high or larger.

## Clear space

Keep the space around the mark empty for at least the width of the teal square. That is one
quarter of the mark's height, on every side. The same rule applies to the lockup.

## Files

| File                           | Use it for                                              |
| ------------------------------ | ------------------------------------------------------- |
| `gatepost-mark.svg`            | The mark on light backgrounds.                          |
| `gatepost-mark-dark.svg`       | The mark on dark backgrounds.                           |
| `gatepost-lockup.svg`          | README and docs headers on light backgrounds.           |
| `gatepost-lockup-dark.svg`     | README and docs headers on dark backgrounds.            |
| `gatepost-favicon.svg`         | The website favicon. Its bands turn white in dark mode. |
| `favicon-16.png`               | The favicon for browsers that do not read SVG favicons. |
| `favicon-32.png`               | The same, at 32 px.                                     |
| `apple-touch-icon-180.png`     | The icon that iOS shows on the home screen.             |
| `gatepost-avatar-1024.png`     | The GitHub org avatar.                                  |
| `gatepost-avatar-512.png`      | The npm org avatar, and other small avatar slots.       |
| `gatepost-social-1280x640.png` | The GitHub social preview, set in each repo's settings. |

The avatars put the mark at 62.5% of the square. A circle crop or a rounded-square crop cuts
nothing.

In a GitHub README, let the lockup follow the reader's theme:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="gatepost-lockup-dark.svg">
  <img src="gatepost-lockup.svg" alt="gatepost" height="40">
</picture>
```

On a website, link the favicons like this:

```html
<link rel="icon" href="favicon-32.png" sizes="32x32">
<link rel="icon" href="gatepost-favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="apple-touch-icon-180.png">
```

## Rules

- Do not stretch, rotate, outline or recolour the mark.
- Gatepost is unofficial. Do not put the mark next to the NIPOST logo or in NIPOST's colours.
