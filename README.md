# harbourlabs.co

Static website for Harbour Labs LLC, hosted on GitHub Pages at https://harbourlabs.co.

## Structure

- `index.html` — home (hero, about, products, contact)
- `contact.html` — contact details
- `privacy.html` — company privacy policy
- `terms.html` — terms of service
- `404.html` — not-found page
- `robots.txt`, `sitemap.xml` — SEO basics
- `CNAME` — custom domain config for GitHub Pages
- `.nojekyll` — disables GitHub's Jekyll processing

## Deploy

Pushes to `main` are published automatically by GitHub Pages.

To edit locally, just open the HTML files in your editor — no build step.

## Domain

Custom domain `harbourlabs.co` is set via the `CNAME` file. DNS:

- Apex (`@`) → A records pointing to GitHub Pages:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- `www` → CNAME to `<github-username>.github.io`
