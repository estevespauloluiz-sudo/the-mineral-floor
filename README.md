# Critical Minerals & Green Industrialisation — *The Mineral Floor*

Bilingual (EN / PT) interactive scrollytelling reconstructing the mineral base of the green transition as three distinct geographies — where critical minerals are **held** (reserves), where they are **mined** (production), and where they are **refined** — and mapping those minerals onto the six green value chains: solar PV, wind, low-carbon hydrogen, green steel, EVs and grid modernisation.

Part of the IPR & Green Industrialisation research programme, Equal International. Companion piece to *The Patent Walls*.

## Live site

https://estevespauloluiz-sudo.github.io/the-mineral-floor/

This repository holds the archival edition of the piece, without the Equal International logo in the header. The original edition remains at https://estevespauloluiz-sudo.github.io/mineral-floor/.

## Coverage

The narrative is organised in three interactive sections:

- **Part I · The mineral base** — a guided scroll (lithium → cobalt → refining) followed by an explorer of **sixteen critical minerals**. Selecting a mineral reveals its share of world reserves, of 2024 mine production, and of refining capacity, side by side. The distance between the first bar and the last is the argument.
- **Part II · Minerals in the six chains** — for each value chain: which minerals it draws on, the component or technology each one enables, and an indicative reading of how much of the chain's material value the minerals carry.
- **Part III · The geography of the chain** — a world map with a chain × stage selector (Extraction → Refining → Components → Final product), showing where each stage physically happens, with illustrative leading hubs.

Closes with a synthesis coda (*Three walls, read together*) and a bilingual Methods & Sources section.

## Data & sources

Reserves and 2024 mine-production figures are from the **USGS Mineral Commodity Summaries 2025**. Refining/processing concentration figures are from the **IEA Global Critical Minerals Outlook 2024 and 2025** (CC BY 4.0). Value-share figures in Part II are indicative, order-of-magnitude estimates — see the in-page Methods section.

## Technical

Single self-contained HTML file. D3 v7, the TopoJSON client and the world basemap are vendored inline, and the Inter and Playfair Display fonts are bundled in `vendor/`, so the piece renders offline and under strict content-security policies with no external script, font or data fetch. Scroll-step detection uses the native `IntersectionObserver`. Bilingual EN/PT via an in-page toggle. WCAG 2.2 AA target: skip link, visible focus, semantic landmarks, `prefers-reduced-motion` respected, and readable without JavaScript.

## How to cite

Esteves, P. (2026). *The Mineral Floor: Critical Minerals, Green Technology and the Right to Industrialise* [Interactive scrollytelling]. Intellectual Property Regimes and Green Industrialisation research programme. Brighton: Equal International.

<!-- After the first Zenodo release, add the DOI badge and DOI here. -->

## Attribution

Equal International — IPR & Green Industrialisation research programme.

Author: Paulo Esteves — Associate Professor, PUC-Rio; Senior Fellow, Equal International.

Version 1.0, July 2026.

## Licence

Content: CC BY 4.0. Third-party components keep their own licences. See [LICENSE.md](LICENSE.md).
