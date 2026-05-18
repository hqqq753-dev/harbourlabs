# harbourlabs.co

Static website for Harbour Labs LLC, hosted on GitHub Pages at https://harbourlabs.co.

## Files

- `index.html` — home (hero, products, contact)
- `privacy.html` — privacy policy
- `terms.html` — terms of service
- `404.html` — not-found page
- `robots.txt`, `sitemap.xml` — SEO basics
- `CNAME` — custom domain config for GitHub Pages
- `.nojekyll` — disables GitHub's Jekyll processing

## Editing

Open the HTML files in any editor. No build step.

To publish a change:

```
git add .
git commit -m "describe the change"
git push
```

GitHub Pages rebuilds within ~60 seconds.

## Domain

Custom domain `harbourlabs.co` is set via the `CNAME` file. DNS at Namecheap:

- Apex (`@`) → A records: 185.199.108.153, .109.153, .110.153, .111.153
- `www` → CNAME to `hqqq753-dev.github.io.`
