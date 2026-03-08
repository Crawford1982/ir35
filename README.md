# ir35guide.co.uk

Static site for the [IR35 Calculator](https://ir35guide.co.uk): free UK contractor take-home pay calculator for 2025/26 and 2026/27 tax years. Inside vs outside IR35, umbrella, perm vs contract, day rate / hourly / annual converter.

## Structure

- **index.html** — Main calculator and homepage
- **blog.html** — Blog index
- **blog/** — Articles (April 2026 changes, inside vs outside take-home, CEST)
- **privacy.html**, **terms.html** — Legal pages
- **404.html** — Custom not-found (Netlify)
- **_headers** — Security and cache headers (Netlify)
- **sitemap.xml**, **robots.txt** — SEO
- **favicon-32x32.png**, **og-image.png** — Favicon and social share image

## Run locally

Open `index.html` in a browser, or use a static server (e.g. `npx serve .`).

## Deploy (Netlify)

1. Connect this repo to Netlify.
2. **Build command:** leave empty (static site).
3. **Publish directory:** `.` (root).
4. Optional: add custom domain and set up **hello@ir35guide.co.uk** (e.g. Cloudflare Email Routing).

See **DEPLOY.md** for post-launch checklist (Search Console, sitemap, etc.).

## License

Private / all rights reserved unless otherwise stated.
