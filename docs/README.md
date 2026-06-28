# Podz.AI — Presentation site

Static, bilingual (IT/EN) landing page for **Podz.AI**, the local-first AI of the **DigiSense** project.

**Live site:** https://g-g-technologies-srl.github.io/digisense-releases/

## Contents

- `index.html` — single, self-contained landing page (inline HTML + CSS + JS; only Google Fonts loaded externally).
- `download.html` — download page with automatic client-platform detection (latest release via GitHub API + local fallback).
- `assets/` — brand assets: animated logo lockups, symbol, app icons, and the social card `og-card.png`.
- `sitemap.xml`, `robots.txt`, `.nojekyll` — SEO and GitHub Pages support.

## Sections (index.html)

Hero with a rotating agent demo (law firm, accounting firm, SME/contracts, patent office, in-house legal, production, HR) · How it works (3 steps) · Compliance (GDPR, EU data sovereignty, AI Act) · Features · Architecture · Pod agent · Releases · FAQ.

## Language & theme

IT/EN language toggle and light/dark theme, both persisted in `localStorage`. Respects `prefers-color-scheme` and `prefers-reduced-motion`.

## SEO & social

Italian-optimized `title`/`description`/`keywords`, full Open Graph + Twitter Card with a dedicated 1200×630 social image (`assets/og-card.png`), JSON-LD (`Organization`, `WebSite`, `SoftwareApplication`, `FAQPage`), plus `sitemap.xml` and `robots.txt`.

## Publishing on GitHub Pages

In the repository settings: **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/docs`.

## Notes

Absolute URLs (canonical, Open Graph, sitemap) point to `https://g-g-technologies-srl.github.io/digisense-releases/`. If a custom domain is used, update them accordingly.

© G&G Technologies Srl — DigiSense is a registered trademark.
