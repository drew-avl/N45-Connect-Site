# N45 Connectivity static site

A self-contained one-page marketing site for N45 Connectivity.

## Files

- `index.html` — page structure, content, metadata, and structured data
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and current-year handling
- `favicon.svg` — browser icon
- `brand-mark.svg` — standalone brand mark
- `og-image.png` — social sharing image
- `robots.txt` and `sitemap.xml` — search engine discovery
- `Caddyfile.example` — example Caddy configuration with HTTPS redirect and security headers

## Deploy

Upload the contents of this folder to the document root for `n45connect.com`. No build process, database, or server-side runtime is required.

An example production configuration is included as `Caddyfile.example`.

## Before launch

1. Confirm `n45connect.com` is registered and points to the web server.
2. Create and test `drew@n45connect.com`.
3. Confirm `(828) 515-1530` is the correct public number.
4. Review carrier agreement requirements before adding carrier names or logos.
5. Replace the canonical and Open Graph domain if a different domain is selected.
