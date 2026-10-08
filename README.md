# FreeToolHub — static 100-tool website

This package is a complete static website with 100 tool pages, shared CSS/JS, SEO metadata, robots.txt and sitemap.xml.

## Important
A website cannot be guaranteed to rank "easily"; Google ranking depends on many factors and takes time. The package includes crawlable pages, descriptive titles/meta descriptions, internal links and a sitemap structure. Google recommends submitting a sitemap and validating structured data where applicable. See Google Search Central.

## Hosting
Upload the contents of this folder to any static host (GitHub Pages, Cloudflare Pages, Netlify, Vercel static hosting, shared hosting, etc.).

## One unavoidable publishing detail
Replace `YOUR-DOMAIN-HERE.com` in `sitemap.xml` and `robots.txt` with your actual domain before submitting the sitemap to Search Console. The tools themselves do not require API keys.

## Notes
- Most calculators, text tools, converters and generators are self-contained.
- Image tools use browser Canvas APIs.
- The QR generator in this build uses a public QR image service because a QR encoder is not included as a local dependency; therefore QR input is sent to that service.
- Some specialized file formats (for example HEIC) depend on browser support.
- No login or database is required.
