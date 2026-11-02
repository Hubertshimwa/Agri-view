# Agri View Rwanda

Agri View Rwanda presents agricultural statistics, crop profiles, practical field notes and sector updates for people working in and with Rwanda's agriculture sector.

## Run locally

Requirements: Node.js 20.19 or later.

```bash
npm install
npm run dev
```

Build and preview the production site with:

```bash
npm run build
npm run preview
```

## Site content

- Responsive home, data explorer, insights, crop directory, crop profiles, guides, news and sources pages.
- National farmer-practice indicators from NISR Season A and Season B 2026.
- Crop production and yield from NISR Season B 2025.
- NAEB coffee export figures and dated tea sector data.
- Crop search, data filters, accessible tables, CSV downloads, dark mode and accordion photo galleries.

Statistics retain their source, unit and reference period. Farm output, farmer practices and exports describe different measures and are presented separately. The source register is maintained in `src/data.js` and on the Sources page.

## Photography

Crop photography and its attribution are recorded in `src/data.js`, `public/asset-manifest.json` and the Sources page. Creative Commons images link to their source and licence. Supplied photographs are credited as provided to Agri View.

## Design and accessibility

Light mode is the default. Visitors can switch to dark mode, which is saved locally. Navigation, crop search, filters, galleries and data tables support keyboard use. Reduced-motion preferences are respected.
