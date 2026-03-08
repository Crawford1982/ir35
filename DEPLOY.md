# ir35guide.co.uk — Deploy Checklist

**Source:** This repo. Connect to Netlify; publish directory = root, no build command.

## Key files (all in repo root or blog/)
| File | Purpose |
|------|--------|
| `index.html` | Calculator + homepage |
| `blog.html`, `blog/*.html` | Blog |
| `privacy.html`, `terms.html` | Legal |
| `404.html` | Custom 404 |
| `_headers` | Security headers (Netlify) |
| `sitemap.xml`, `robots.txt` | SEO |

## Before deploying
1. **GA4**: Property is set; Measurement ID is in index.html (`G-N961MFHTCS`). Loads only after cookie consent.

2. **Email**: Set up hello@ir35guide.co.uk (Cloudflare Email Routing is free)

## After deploying
1. Google Search Console → add property → verify via DNS TXT record
2. Submit sitemap: https://ir35guide.co.uk/sitemap.xml
3. Request indexing on the homepage

## Sitemap content (create as sitemap.xml)
```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://ir35guide.co.uk/</loc>
    <lastmod>2026-03-08</lastmod>
    <changefreq>monthly</changefreq>
    <priority>1.0</priority>
  </url>
  <url>
    <loc>https://ir35guide.co.uk/privacy.html</loc>
    <lastmod>2026-03-08</lastmod>
    <changefreq>yearly</changefreq>
    <priority>0.2</priority>
  </url>
</urlset>
```

## Week 1 submissions
- [ ] r/ContractorUK — "built a free IR35 calculator for the April 2026 changes"
- [ ] r/UKPersonalFinance
- [ ] DevHunt.org
- [ ] Uneed.best
- [ ] Fazier.com
- [ ] toolfolio.io

## Affiliate programme applications
- Qdos: https://www.goqdos.com/commercial-services (mention "affiliate partnership")
- Kingsbridge: contact via kingsbridge.co.uk
- SJD Accountancy: has affiliate scheme, search "SJD affiliate"
- Carbon Ads: https://carbonads.net (apply at ~5k visits/month)

## Next content (write in order)
1. IR35 reform April 2026: what the small company changes mean
2. Inside vs outside IR35: real numbers at your day rate
3. Why HMRC's CEST tool gets it wrong
