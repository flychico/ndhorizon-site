# ndhorizon.com

Static site for ND Horizon (New Dawn Horizon Holding, LLC) — business operations & growth consulting, South Florida.

## Structure
- Flat HTML pages, one per route (clean URLs handled by `_redirects` on Netlify / `vercel.json` on Vercel)
- `assets/` — images and static files
- `sitemap.xml` / `robots.txt` — SEO

## Deploy
Hosted on Netlify, linked to this repo. Every push to `main` deploys automatically.
No build step: publish directory is the repo root.

## Adding a page
1. Create `page-name.html` (copy an existing page for header/footer/styles)
2. Add clean-URL rules to `_redirects` and `vercel.json`
3. Add the URL to `sitemap.xml`
4. Add nav/footer links across pages
5. Push — then request indexing in Google Search Console
