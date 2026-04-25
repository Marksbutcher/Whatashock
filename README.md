# Whatashock

> A live, sourced answer to the most tired argument in energy policy.

A standing rebuttal to the recurring discovery that the wind sometimes drops and the sun sets every night. Built because explaining grid balancing in 280 characters, every time, is an inefficient use of human attention.

## Pages

- **`index.html`** — main page. Live UK grid mix from the National Grid ESO Carbon Intensity API, country-level records, six-card explainer of how grids actually balance, an honest section on the four problems that genuinely are hard, and a closer.
- **`wall.html`** — the Wall of Helpful Insights. Twelve composite-archetype LinkedIn posts, each answered in one line. No real people, no fake quotes attributed to anyone — composite archetypes only.

## Tech

Two static HTML files. No build step, no framework, no dependencies beyond Google Fonts (Space Grotesk, JetBrains Mono). Live data is fetched client-side from the [Carbon Intensity API](https://carbonintensity.org.uk) — free, public, no key required. Refreshes every five minutes.

The reason the live panel is UK-only: every other major grid API (ENTSO-E, EIA, AEMO, Electricity Maps) requires an API key or paid access, which can't run from a static page without a backend proxy. Treated honestly on the page.

## Deploy

Drop into Cloudflare Pages, Netlify, or GitHub Pages and point a domain at it. Nothing else required.

## Sources

- National Grid ESO — [carbonintensity.org.uk](https://carbonintensity.org.uk)
- ENTSO-E — [transparency.entsoe.eu](https://transparency.entsoe.eu)
- AEMO — [aemo.com.au](https://aemo.com.au)
- EIA Open Data — [eia.gov/opendata](https://www.eia.gov/opendata/)
- Electricity Maps — [app.electricitymaps.com](https://app.electricitymaps.com)
- Ember — [ember-energy.org](https://ember-energy.org)
- IEA — [iea.org](https://www.iea.org)
- IRENA — [irena.org](https://www.irena.org)
- BloombergNEF — [about.bnef.com](https://about.bnef.com)

Sister site: [ukcarbon.posetiv.co.uk](https://ukcarbon.posetiv.co.uk)

## Built by

[Posetiv](https://posetiv.co.uk). No tracking. No ads. No nonsense.
