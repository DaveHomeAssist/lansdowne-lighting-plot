# Lansdowne Theatre — Lighting Plot

An interactive, single-page lighting plot for **Lansdowne Theatre** (31 N. Lansdowne Ave, Lansdowne, PA) — a clickable SVG diagram plus full DMX patch table for the venue's grandMA2 / sACN rig (5 universes, 51 fixtures).

Live at: https://davehomeassist.github.io/lansdowne-lighting-plot/

## What's here

| Path | What it is |
|---|---|
| `index.html` | The entire app — self-contained HTML/CSS/JS. Renders an SVG stage plot (US2 and FOH electrified pipes, empty non-electric pipes, FOH Opposite/balcony position) and a full patch table. Click a fixture or table row to inspect its channel, universe, DMX address, mode, and position. |
| `lansdowne-theatre-logo-official.png` | Venue logo, used as the Open Graph / social share image. |
| `og-card.svg` | Social-preview card source. |
| `favicon.svg` | Site favicon. |
| `LICENSE` | All-rights-reserved notice. |

## How to view

Open `index.html` directly in a browser, or visit the GitHub Pages deployment above. No build step, server, or dependencies — it's a static, self-contained page (fonts are pulled from Google Fonts via CDN).

The patch data (fixture types, channels, universes, DMX addresses) is hard-coded in the `<script>` block at the bottom of `index.html`, sourced from the venue's master patch sheet.
