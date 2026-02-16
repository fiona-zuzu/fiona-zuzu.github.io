# Fiona Zuzu — GitHub Pages site

This repository serves as Fiona Zuzu’s canonical online portfolio and digital archive.

The website is live at: [https://fiona-zuzu.github.io/](https://fiona-zuzu.github.io/)_

## Overview

This repository contains the official portfolio site for Fiona Zuzu.

It is a minimal, single-page GitHub Pages site featuring:

- Artist bio with automatic age update
- Responsive gallery with lightbox
- Canvas print storefront link
- Instagram integration
- Contact section
- Structured data (JSON-LD)
- SEO files (`robots.txt`, `sitemap.xml`)
- LLM guidance file (`llms.txt`)
- Auto-updating copyright year
- Custom favicon

---

## What’s included
- `index.html` — single landing page
- `styles.css` — separate stylesheet
- `robots.txt`, `sitemap.xml`, `llms.txt` — crawl + LLM hints
- `/assets` — images + favicon

## Deployment

This site is deployed via GitHub Pages:

**Settings → Pages → Deploy from branch → main / (root)**

Because the repository name matches the username (`fiona-zuzu.github.io`), it publishes to:

https://fiona-zuzu.github.io/

---

## Updating Content

### Add New Artwork
1. Upload the new image to `/assets`
2. Add a new `<figure>` block inside the Gallery section in `index.html`
3. Commit changes

### Artist Age
The artist’s age updates automatically via a small script in `index.html`.

### Copyright Year
The footer year updates automatically.

---

## SEO & Indexing

- Canonical URL: https://fiona-zuzu.github.io/
- Sitemap: https://fiona-zuzu.github.io/sitemap.xml
- Robots: https://fiona-zuzu.github.io/robots.txt
- LLM guidance: https://fiona-zuzu.github.io/llms.txt

---

## Notes

- Filenames are case-sensitive.
- If you rename images, update references in `index.html`.
- Favicons are stored in `/assets` and referenced in the `<head>`.
