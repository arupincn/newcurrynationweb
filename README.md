# Curry Nation website

Product pages for [currynation.in](https://currynation.in): Brand-led, Founder-led, Performance-led and Design-led growth products, styled after the Curry Nation site.

Preview: https://chimerical-klepon-e96e27.netlify.app

## What's here

- `site/` is the finished website: plain HTML pages with their images. Upload this folder to any static host (Netlify, Vercel, GitHub Pages) to publish it.
- `src/` is what generates `site/`:
  - `build.py` builds every page
  - `parts/` holds the package data (`pkgs.py`), the FAQs (`faqs.py`) and the stylesheets
  - `assets/` holds the photos, award images and case-study images

## Making changes

1. Edit the text in `src/parts/pkgs.py` (packages and prices), `src/parts/faqs.py` (FAQs) or `src/build.py` (everything else).
2. Rebuild with `python3 src/build.py`. This rewrites `site/`.
3. Publish the new `site/` folder.

## Pages

| Page | File |
| --- | --- |
| Home | `index.html` |
| Commodity to Brand (all Brand-led packages) | `brand-led.html` |
| Brand Audit | `brand-audit.html` |
| Brand Positioning | `brand-positioning.html` |
| Challenger Workshop for Leadership | `leadership-workshop.html` |
| Challenger Workshop for Business | `challenger-workshop.html` |
| Founder Authority System | `founder-visibility.html` |
| Growth Lab (Performance-led) | `performance.html` |
| Design-led | `design.html` |

`cxo-audit.html` redirects old links to the Leadership workshop page.
