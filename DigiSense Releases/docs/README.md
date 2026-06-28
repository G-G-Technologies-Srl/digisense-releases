# Podz.AI — Presentation site / Landing page

Static, bilingual (IT/EN) landing page for **Podz.AI**, the agentic runtime of the **DigiSense** project.

## Contents

- `index.html` — single, self-contained page (inline HTML + CSS + JS, no external dependencies).
- `download.html` — download page with automatic client-platform detection.
- `assets/` — brand assets (logo, symbol, icons).
- `.nojekyll` — disables Jekyll processing on GitHub Pages.

## Sections

- Hero + overview (models · agents · applications)
- Layered runtime architecture
- Autonomous Pod agent (Hermes / OpenClaw style)
- Releases / changelog (Podz.AI only: latest + previous)

## Language

IT/EN switch in the top right. The language is detected from the browser and stored in `localStorage`.

## Download page

`download.html` fetches the latest Podz.AI release from the GitHub API, detects the visitor's OS and
architecture, and recommends the matching package. If the platform is not recognized it shows all
architectures. A local fallback (v1.0.18) keeps the page working when the API is unreachable.

## Publishing on GitHub Pages

In the repository settings: **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/docs`.
The site is served from the `docs/` folder.

## Real data

Content and releases are aligned with the official repository
[`G-G-Technologies-Srl/digisense-releases`](https://github.com/G-G-Technologies-Srl/digisense-releases):

- v1.0.18 (latest), v0.0.1 (first release).
- Download buttons link to `releases/latest`.
- Official tagline: *Your AI. Your data. Your machine.*
- © G&G Technologies Srl — DigiSense is a registered trademark.
