# harbourlabs.co

Static website for Harbour Labs LLC, hosted on GitHub Pages at https://harbourlabs.co.

## Files

- `index.html` — home (hero, currently, recent, company, contact)
- `about.html` — about the studio
- `products.html` — full product list (Dinnrd + upcoming)
- `journal.html` — studio updates / blog
- `press.html` — press kit (descriptions, facts, brand colors)
- `contact.html` — full contact details
- `privacy.html` — privacy policy
- `terms.html` — terms of service
- `404.html` — not-found page
- `robots.txt`, `sitemap.xml` — SEO basics
- `CNAME` — custom domain config for GitHub Pages
- `.nojekyll` — disables GitHub's Jekyll processing

## Editing

Open any HTML file in an editor. No build step.

To publish a change:

```
git add .
git commit -m "describe the change"
git push
```

GitHub Pages rebuilds within ~60 seconds.

## Adding a journal entry

Open `journal.html`. Copy the existing `<article class="entry">…</article>` block and paste a new one above it. Update the date, title, and body. Commit, push.

Optionally update the homepage `#recent` section to point at the newest entry.

## Domain

Custom domain `harbourlabs.co` is set via the `CNAME` file. DNS at Namecheap:

- Apex (`@`) → A records: 185.199.108.153, .109.153, .110.153, .111.153
- `www` → CNAME to `hqqq753-dev.github.io.`
