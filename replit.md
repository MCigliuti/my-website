# Pain Care At Home™ — Landing Page

Patient-facing landing page for paincareathome.com. Static HTML — no build step required.

## How to run

The site is served by Python's built-in HTTP server:

```
python3 -m http.server 5000 --directory site
```

Configured as the "Start application" workflow on port 5000.

## Project structure

```
site/
  index.html          — full single-page site
  images/             — hero, section, and portrait photos (compressed JPEG)
  favicon.svg
  favicon-32.png
  apple-touch-icon.png
  README.md           — original deploy notes
PainCareAtHome_site.zip   — original zip import (can be kept as backup)
index.html.html           — duplicate HTML file from import (unused)
```

## Stack

- Pure static HTML/CSS/JS — no framework, no build step
- Fonts: Lora + Poppins via Google Fonts
- Payments: Square payment links (live)
- Booking: Calendly (paincareathome/20min)
- Contact form: Google Forms

## Deployment target

Intended to deploy to Vercel pointed at the `site/` folder, or any static host.
See `site/README.md` for Vercel deploy instructions.

## User preferences

- Keep existing structure and stack — do not restructure or migrate
- All edits go to `site/index.html`
