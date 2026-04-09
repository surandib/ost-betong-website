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
- **Våre tjenester:** 3 service cards with images (betong, snekker, anlegg), bullet-point lists
- **Om oss:** Centered layout with logo, company description
- **Hvorfor velge oss:** Extended company pitch, centered text
- **Kontakt:** Contact info + form, centered header
- **Footer**

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
- logo.png - Firmalogo (navbar + om oss)

## Theme
- Light/dark toggle (sun/moon icon in navbar)
- Light mode default on desktop, dark mode default on mobile
- Om oss section uses dark bg (#1A1F2B) in both modes
- Accent: orange (#E85D26), buttons green (#2E7D32) for secondary CTA
- Check icon pulse: green (#2E7D32)

## Key decisions
- No emoji icons on service cards (images are enough)
- Navbar transparent in light mode, solid dark box in dark mode
- Navbar links switch to dark text when scrolled in light mode
- `tel:` links open phone app on mobile
- Content/copy taken from ost-betongent.no
