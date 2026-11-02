# AGRI VIEW
## Updated Codex Master Prompt

### Rwanda Agriculture Intelligence & Knowledge Platform

**Version 2.0 | Prepared 1 November 2026 | Light mode first | React**

Use this prompt with the Agri View project repository and the supplied crop photos, NISR infographic and reference video. Inspect the existing project and files before making changes. Then build a complete, usable website. Do not stop after a landing page or a static visual mockup.

<!-- pagebreak -->

# 1. Mission and product

You are a senior product designer and React engineer. Build **Agri View**, an independent Rwanda agriculture website for farmers, cooperatives, agronomists, extension workers, agribusinesses, researchers, students, journalists, policymakers and the public.

**Purpose:** Make Rwanda agricultural statistics easier to find and understand, then connect the numbers to useful crop knowledge, practical planning notes and dated sector updates.

**Tagline:** See Rwanda's harvest clearly.

Agri View may take inspiration from the editorial polish, motion and component craft of [React Bits](https://reactbits.dev/), but must have its own Rwanda agriculture identity, information design and writing. Do not clone the React Bits site.

## First release

Build a responsive, light-first website with working routes for Home, Explore, Crops, Insights, Tips & Guides, News and Sources. Include an individual page for every crop in the initial crop list in Section 5. Make search, filters, season views, chart tables, navigation, theme control and image galleries work.

The first release is a locally managed information site. Do not add login, payments, ecommerce, intrusive advertising or a backend unless the repository already requires one. Show the last verified date for the local data snapshot. Do not imply that a manually maintained page is a live data feed.

## How to begin

1. Inspect the repository, current routes, scripts, dependencies and supplied assets.
2. Summarize the existing state and the implementation sequence briefly.
3. Create or adapt the site structure without discarding useful working code.
4. Build all agreed pages and interactions, then provide run, build and handover instructions.

Ask a question only when a missing decision blocks implementation. Otherwise choose the simplest sound option and record material assumptions.

<!-- pagebreak -->

# 2. Visual direction and interaction

## Brand

Use an open, editorial visual system that feels locally grounded in Rwanda's hills, terraces, fields and crop diversity. Light mode must be the first-visit default, with no dark flash. A dark theme is optional, and if included it must be fully tuned and saved only after the visitor selects it.

Use warm off-white surfaces, agricultural greens, deep green or navy text, and restrained seasonal accents: blue for Season A, cyan or green for Season B, and amber for Season C. Define colors as central CSS variables. Add a quiet contour-line or field-row texture. Protect readability and contrast.

Typography should feel clear and contemporary. Use a sans-serif family for body text, with an expressive but readable display face for selected headings and figures. Use Lucide icons consistently. Do not use emoji as interface icons.

## Design cues from supplied references

The supplied video shows an animated build of a Seasonal Agriculture Survey 2025 infographic. Carry forward its useful information cues: numbered sections, distinct season colors, donut charts for shares, horizontal bars for land and crop output, concise interpretation callouts, and visible source footnotes. Recompose them as a responsive website; do not reproduce a single dense poster as the whole experience.

Use authentic supplied crop photos where they fit. Include an understated **monochrome black-and-white crystal sphere** or data-lens motif in the hero or Insights page, as an original CSS or SVG treatment. Keep it small, quiet and decorative. It must not carry meaning by itself or reduce chart readability. Respect reduced-motion settings.

## React Bits and original components

Use React Bits as a source of component ideas, not a requirement to install or copy every effect. Candidate patterns include a pill navigation, staggered mobile menu, Bento cards, Count Up, Scroll Reveal, Accordion Gallery, Stepper, tooltips and subtle topography. Check the current official component documentation, API, dependencies and source license before copying any component code.

The current free React Bits background catalog includes an **Orb**, described as a glowing colored ring. Do not invent an import named "Crystal Ball" or assume that Orb is the requested monochrome sphere. Build the black-and-white sphere as an original lightweight CSS or SVG element unless an exact suitable component is verified. Avoid paid or Pro-only components unless specifically authorized. If React Bits source is reused, preserve required notices and comply with its current license, including the Commons Clause restriction against selling or redistributing the components themselves.

Motion should support orientation or feedback. Keep it short, avoid scroll hijacking and forced delays, pause off-screen animation where practical, and provide static fallbacks. Every animation must respect `prefers-reduced-motion`.

<!-- pagebreak -->

# 3. Verified data snapshot

Use the figures below as a dated implementation baseline, not as timeless facts. Reopen the official source pages and tables before production release. Every rendered statistic needs a value, unit, reference period, geography, source title, organization and direct URL. Keep publication or update date when the source provides it.

## Latest national snapshot available on 1 November 2026

NISR Season A 2026 covers September 2025 to February 2026. NISR reports 1.376 million hectares used for agriculture, about 58% of total land. Farmers using improved seeds: 37.0%; organic fertilizer: 90.2%; inorganic fertilizer: 67.2%; pesticides: 46.9%; irrigation: 14.4%; agroforestry: 53.4%; mechanical equipment: 1.7%; at least one anti-erosion measure: 92.4%.

NISR Season B 2026 covers March to June 2026. The survey covered all 30 districts and 1,200 segments, with 505 large-scale farmers. NISR reports 1.414 million hectares used for agriculture, about 59% of total land. Farmers using improved seeds: 20.9%; organic fertilizer: 81.3%; inorganic fertilizer: 57.5%; pesticides: 39.1%; irrigation: 13.1%; agroforestry: 58%; mechanical equipment: 1.8%.

State the denominator. Farmer practice percentages are percentages of farmers, not of land or plots. Survey figures are estimates. Do not treat the A and B percentages as one annual average.

## Crop production baseline: NISR Season B 2025

Use this as a dated 2025 crop baseline. It is not a 2026 production estimate.

| Crop or category | Production, metric tonnes | Yield, tonnes per hectare |
| --- | ---: | ---: |
| Banana, all types | 1,166,247 | 12.4 |
| Cassava | 852,541 | 14.4 |
| Sweet potato | 652,515 | 8.1 |
| Irish potato | 314,093 | 6.8 |
| Beans | 240,721 | 0.7 |
| Vegetables | 181,272 | 9.2 |
| Sorghum | 125,656 | 1.2 |
| Maize | 117,711 | 1.3 |
| Paddy rice | 72,976 | 4.1 |
| Fruits | 29,798 | 5.3 |
| Wheat | 11,667 | 1.3 |

NISR reports banana subcategories in the same release: cooking banana 527,109 tonnes at 17.2 tonnes per hectare; dessert banana 154,315 tonnes at 11.2 tonnes per hectare; banana for beer 484,822 tonnes at 9.8 tonnes per hectare. Do not add these to the all-banana total.

## Export-crop figures: separate measures

NAEB reported 23,860 tonnes of unroasted green coffee exported in calendar year 2025, with export revenue above US$148.6 million. Label this as **coffee exports**, not national farm production.

NAEB's Rwanda Tea page reports 40,003 tonnes of made tea by June 2024, and US$114.8 million from exports of 38,467.7 tonnes of made tea in FY2023/24. Keep the metrics and their different periods visibly separate. Do not present them as current 2026 production.

<!-- pagebreak -->

# 4. Accuracy, sources and advice

Truth before decoration. Never invent statistics, rankings, district data, prices, crop calendars, advice, citations, dates or news.

- Keep national and district data distinct. Do not add a district ranking or map unless the source reports compatible district-level values and the year is visible.
- Keep farmer percentages, land shares, harvested area, production, yield, farm-gate prices, export volumes and export revenue separate.
- Do not compare crops with unlike units or seasons. Do not interpolate a missing year silently.
- Use an unavailable state and source link when a value is absent. Never use zero to mean missing.
- Label each statement as official statistics, official announcement, research finding, editorial summary or Agri View analysis.
- Do not promise yield, profit or investment return. Value added per hectare is not profit.
- Crop advice must link to current RAB, MINAGRI or other credible agronomic guidance and explain local variation. Encourage consultation with a RAB extension worker or sector agronomist.
- Do not provide pesticide dosage or mixing instructions without a current verified product label and competent official guidance.
- Recheck current weather information at Meteo Rwanda. Never make a live weather claim from a stored snapshot.

## Source hierarchy

1. **NISR** reports and tables for land use, crop area, production, yield and farmer practices.
2. **MINAGRI** for policies, programmes and ministry announcements.
3. **RAB** for crop research, extension, seed and fertilizer guidance, pests, diseases and technical advice.
4. **NAEB** for export crops, coffee, tea, horticulture and export performance.
5. **Meteo Rwanda** for dated weather and climate information.
6. FAO, CGIAR, universities and peer-reviewed research for supplementary context, clearly marked as supplementary.

Create a source register with title, publisher, direct URL, date, reference period, table or page, unit, geography, notes and last verification date. Read the original report or table rather than relying on a search snippet. If two official sources conflict, show their dates and definitions instead of silently reconciling them.

<!-- pagebreak -->

# 5. Navigation, crops and page requirements

## Navigation

Use a sticky, responsive header with: Home, Explore, Crops, Insights, Tips & Guides, News and Sources. Crops must have a desktop menu grouped by crop family and a mobile expandable submenu. Include an accessible site search, English / Kinyarwanda interface structure and a light / dark control. If translations are incomplete, label them as under review; do not imply that unreviewed translation is final.

Support direct routes such as `/explore`, `/crops`, `/crops/maize`, `/crops/coffee`, `/guides`, `/news` and `/sources`. All menu, card and breadcrumb links must work. Close menus on Escape and after navigation. Make controls keyboard operable and at least 44 by 44 CSS pixels on touch screens.

## Initial crop directory

Group crops by food staples, roots and tubers, legumes and oilseeds, export crops, and horticulture. Include searchable pages for:

1. Maize
2. Beans
3. Cassava
4. Irish potato
5. Sweet potato
6. Banana, with cooking, dessert and beer subtypes only where the source supports them
7. Paddy rice
8. Sorghum
9. Coffee
10. Tea
11. Soybean
12. Wheat
13. Vegetables
14. Fruits and horticulture

Show data coverage honestly. A crop page can say that a requested indicator is not in the selected release. Do not imply that equal data depth exists for every crop.

## Home

- Headline: "Rwanda's agriculture, explained through data and practical knowledge."
- Explain who the platform serves. Provide clear calls to Explore data and Browse crops.
- Show selected national statistics with period, unit, source and last checked date.
- Feature authentic crop photos, a small verified news list and one useful practical note.
- Show a separate 2025 crop-output panel and 2026 national-practice panel.
- Include a source link near each data group.

## Explore

Provide clearly separate 2026 farmer-practice and 2025 Season B crop-output views. Show unit, period, source and a short explanation for every chart. Add a readable table alternative and explain survey methods and limits.

## Crops index

Provide crop search and filters by family, season and source coverage. Do not offer district filtering unless the selected source provides district-level data for that crop and period.

<!-- pagebreak -->

# 6. Crop pages, tips and news

## Crop page template

Each crop route should follow one shared, data-driven template:

1. Crop name, group, accurate photo and short overview.
2. Production, yield, area or export metrics only when published, each with a date, period, unit and source.
3. Trend charts only for comparable observations. Do not interpolate silently.
4. District distribution only when a dated official district source supports it.
5. Separate farm production, farm-gate price, wholesale market information and export statistics.
6. Crop calendar, varieties and inputs only from verified technical sources; explain regional variation.
7. Practical growing information only when supported by RAB, MINAGRI or credible agronomic sources.
8. Opportunities and challenges labeled as Agri View analysis.
9. Accessible image gallery with alt text, caption and credit status.
10. Original sources, related crops and relevant guides.

## Tips & Guides

Organize by topic: soil, seeds, fertilizer, water, pests and diseases, erosion, climate, harvest, storage, marketing, cooperatives and agribusiness. Allow audiences such as smallholders, cooperatives, extension workers, youth, agribusinesses, students and policymakers.

Every guide needs a clear audience, steps, applicability, safety notes, source and review date. Separate official recommendations from Agri View planning ideas. Do not present generic records or planning prompts as crop-specific agronomic instructions.

## News

Curate dated official updates about policy, crop production, exports, weather, research and farmer organizations. Each item needs publisher, date, a short factual summary and a direct original link. Verify material claims against the original announcement or report. If the feed is not live, label it as a reviewed snapshot.

## Sources and about

State that Agri View is independent and is not an official publication of NISR, MINAGRI, RAB or NAEB. Explain the data method, limitations, update history, correction process and photo credits. Include a source register with direct links.

<!-- pagebreak -->

# 7. Supplied assets and image gallery

Inspect the exact local files before assigning crop identity. The supplied crop photographs are:

- `Coffee 2.jpg`: farmer harvesting coffee cherries.
- `cofee.png`: a farmer inspecting flowering coffee plants.
- `tea.jpg`: tea workers carrying harvested leaves through a plantation.
- `maise.jpg`: farmer holding maize cobs.
- `cassava plants.jpg`: cassava field landscape.
- `WhatsApp Image 2026-11-01 at 16.25.02.jpeg`: NISR Seasonal Agriculture Survey 2025 infographic reference.
- `WhatsApp Video 2026-11-01 at 16.25.37.mp4`: animated build of the same infographic.

These are provisional visual identifications. Do not infer district, variety, date or image author from the pixels. Maintain an asset manifest with file, description, alt text, credit, licence or permission status, crop association and public-use approval. If rights are unknown, mark them as pending before deployment.

## Accordion gallery

- On wide screens, use elegant expanding image panels if the text remains readable.
- On mobile, use stacked tap-to-expand cards. Never make a caption or image hover-only.
- Buttons must expose expanded state and work by keyboard with Enter or Space.
- Include descriptive alt text, visible caption and credit status.
- Lazy-load below-the-fold photos and set image dimensions to avoid layout shift.
- Never reuse a photo to imply a different crop, crop stage or location.

<!-- pagebreak -->

# 8. Technical and accessibility requirements

## Architecture

Use React with Vite, following the existing repository convention. Prefer TypeScript when starting a fresh project. Keep pages, reusable UI, crop content, data observations, news, source records, translations and image credits in separate modules.

Store statistics as structured records, never inline chart literals. A record should include indicator, value, unit, crop when relevant, season, year, geography, source organization, source title, source URL, publication or update date, reference period, table or page, notes and last verified date. Keep explicit `null` for unavailable observations. Add a schema or validation layer to catch missing provenance and invalid units.

Use semantic routes, responsive CSS tokens and a small component set. Add a data adapter so future NISR tables can be updated without rewriting page components. Avoid unneeded packages and animation frameworks.

## Accessibility, performance and SEO

- Support 360 CSS pixels and larger without horizontal page overflow.
- Aim for WCAG 2.2 AA: readable contrast, semantic headings, keyboard navigation, visible focus, named controls and accessible chart alternatives.
- Do not rely on color alone; label seasons and units.
- Support reduced motion. Keep essential content readable without animation.
- Optimize supplied images and lazy-load noncritical media.
- Provide loading, empty, error and unavailable states.
- Add unique titles and descriptions, useful crop URLs, sitemap and robots files when appropriate.
- Measure performance rather than claiming a Lighthouse score that was not measured.

<!-- pagebreak -->

# 9. Delivery phases and acceptance

## Delivery phases

**0. Repository audit:** inspect the existing application and supplied files.

**1. Research and data:** verify the source pages, write the source register, define data structures and record image rights status.

**2. Design shell:** implement light-first tokens, navigation, mobile menu, crop menu, search and responsive layout.

**3. Pages:** build Home, Explore, crop index and crop details, Insights, Tips & Guides, News and Sources.

**4. Interactions:** implement filters, season views, chart table alternatives, image accordion, theme preference and restrained components.

**5. Quality checks:** run available type checks, lint, production build, key route checks, responsive review and accessibility review. Fix issues found.

**6. Handover:** report completed pages, commands, sources, data limitations and image-credit items awaiting clearance.

## Acceptance checklist

- [ ] Light mode is the first-visit default; the theme toggle works and persists.
- [ ] Main, mobile and Crops navigation work by mouse, keyboard and touch.
- [ ] All 14 crop routes work, including direct navigation.
- [ ] 2025 crop production and 2026 farmer practices remain in separate, correctly labeled views.
- [ ] Every statistic carries period, unit and source information.
- [ ] Export figures are not presented as farm production.
- [ ] Missing data is shown as unavailable, never as zero.
- [ ] Charts have text or table alternatives.
- [ ] Search, filters, source links and image galleries work.
- [ ] Images have useful alt text and a rights-status manifest.
- [ ] Official advice is sourced; Agri View interpretation is labeled.
- [ ] Kinyarwanda strings needing native review are tracked honestly.
- [ ] Reduced-motion preference is respected; essential content works without animation.
- [ ] No horizontal overflow at 360 CSS pixels.
- [ ] Run and data-update instructions are in the README.

<!-- pagebreak -->

# 10. Official source links

- NISR Seasonal Agricultural Survey: [survey archive](https://www.alpha.statistics.gov.rw/data-sources/surveys/Seasonal-Agricultural-Survey)
- NISR SAS Season A 2026: [official release](https://www.alpha.statistics.gov.rw/statistical-publications/agriculture-environment/seasonal-agricultural-survey-season-2026)
- NISR SAS Season B 2026: [official release](https://www.alpha.statistics.gov.rw/statistical-publications/agriculture-environment/seasonal-agricultural-survey-season-b-2026)
- NISR SAS Season B 2025: [official release and table](https://www.alpha.statistics.gov.rw/data-sources/surveys/Seasonal-Agricultural-Survey/Seasonal-Agricultural-Survey/seasonal-agricultural-survey-season-b-2025)
- NISR SAS 2025 annual report: [PDF report](https://www.statistics.gov.rw/sites/default/files/documents/2025-12/SAS%202025%20Final%20report.pdf)
- MINAGRI: [official website](https://www.minagri.gov.rw/)
- RAB crop research and extension: [Crop Innovation & Tech Transfer](https://www.rab.gov.rw/rw/agriculture-development/crop-innovation-tech-transfer)
- NAEB 2025 coffee exports: [official update](https://www.naeb.gov.rw/publications/news/rwanda-coffee-export-revenues-hit-record-150m-in-2025)
- NAEB tea information: [About Rwanda Tea](https://www.naeb.gov.rw/rwanda-tea/about-rwanda-tea)
- Meteo Rwanda: [weather and climate information](https://www.meteorwanda.gov.rw/)
- React Bits free component catalog: [React Bits](https://reactbits.dev/)
- React Bits current source license: [license terms](https://github.com/DavidHDev/react-bits/blob/main/LICENSE.md)

Reopen every source before production publishing. Link to the exact report, table or story used, not only an institution homepage. Keep a dated update history and show the original publication period beside each figure.
