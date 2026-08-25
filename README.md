# GMC Technology Website — Complete Prototype v2

A polished responsive static website built from the supplied GMC Technology catalogue.

## Included
- Premium responsive homepage
- Product catalogue with search + family filter
- URL-based category filtering
- Reusable product detail pages
- Application-led navigation
- Custom-solutions pathway
- Technical enquiry workflow
- Sticky product enquiry CTA
- Responsive mobile navigation
- Structured product data in `data/products.json`
- Catalogue PDF and catalogue-derived product imagery
- SEO basics: titles, descriptions, sitemap and robots file
- Content-review checklist for pre-publication verification

## Run
Use a local HTTP server because the product catalogue loads JSON via `fetch()`.

`python -m http.server 8000`

Then open `http://localhost:8000/`.

## Before production
1. Replace catalogue-derived image crops with original high-resolution product photography where available.
2. Verify all specifications, models and contact information against current GMC records.
3. Connect the enquiry form to a secure backend.
4. Add legal/privacy pages and production analytics as required.
5. Confirm image and catalogue usage rights.
6. Add final structured-data/schema markup and production-domain canonical URLs.
