# Øst Betongentreprenør og Anlegg AS - Website

## Project
Single-page static website for a construction company based in Vikersund/Buskerud.
Deployed on Netlify from GitHub repo `surandib/ost-betong-website` (master branch).

## Tech
- Static HTML + inline CSS + inline JS (single `index.html`)
- No build step, no frameworks
- Google Fonts: Antonio (hero h1), Plus Jakarta Sans (headings), DM Sans (body)

## Structure
- **Hero:** Background image (image2.jpg), Antonio font title, green pulsing check icons, CTA buttons
- **Våre tjenester:** 3 service cards with images (betong, snekker, anlegg), bullet-point lists, no emoji icons
- **Om oss:** Centered layout with logo, company description from ost-betongent.no
- **Hvorfor velge oss:** Extended company pitch, centered text
- **Kontakt:** Contact info (clickable tel/mailto) + form (not functional yet), centered header
- **Footer:** Copyright, address, contact info

## Images
All images in root directory, referenced by filename in index.html:
- image1.jpg - Betongstøping (tjenestekort)
- image2.jpg - Målebånd/tre (hero bakgrunn, konvertert fra AVIF)
- image3.jpg - Drill/boring (ubrukt)
- image4.jpg - Trestendere (ubrukt)
- image5.jpg - Hammer/riving (ubrukt)
- image6.jpg - Gravemaskin (anlegg tjenestekort)
- image7.jpg - Snekker bolter tre (snekker tjenestekort)
- image8.jpg - Folk ser på tegninger (ubrukt)
- logo.png - Firmalogo (navbar + om oss + favicon)
- favicon.png - Generert fra logo.png

## Theme
- Light/dark toggle (single sun/moon icon button in navbar)
- Light mode default on desktop, dark mode default on mobile
- Om oss section uses dark bg (#1A1F2B) in both modes
- Accent: orange (#E85D26) in both modes
- Secondary CTA (Send melding): green (#2E7D32)
- Check icon pulse: green (#2E7D32)
- Navbar: transparent in light mode (white bg when scrolled), solid dark in dark mode

## SEO
- Meta description + keywords + Open Graph tags
- Proper page title
- lang="nb" (Norwegian Bokmål)
- Favicon from company logo

## Key decisions
- No emoji icons on service cards (images are enough)
- Navbar transparent in light mode, solid dark box in dark mode
- Navbar links switch to dark text when scrolled down in light mode
- `tel:` links open phone app on mobile
- Sticky call bar on mobile (bottom) rings directly
- Mobile hamburger menu has no duplicate phone link
- Content/copy taken from ost-betongent.no
- Contact form exists but has no backend yet (needs implementation)

## Known TODOs
- Contact form backend (Netlify Forms, Formspree, or similar)
- Organization number in footer (required by Norwegian law)
- JSON-LD structured data for local business SEO
- Privacy policy (required if form collects personal data)
