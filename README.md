# rematechservices.com

A static website for Rema Technology Services LLC. It is plain HTML and CSS, with no build step.

| Page | File |
|---|---|
| Home | `index.html` |
| Services (IT and Clearly Cloud VoIP) | `services.html` |
| Software list | `software.html` |
| Company Bulletin product page | `company-bulletin.html` |

Shared styles are in `css/style.css`. The logo is `img/rema-logo.webp`, and the triangle mark is `img/mark.svg` (also used as `favicon.svg`).
The header and footer are repeated in each page, so a nav change needs editing in all four files.

## Preview locally

    python3 -m http.server 5500

## Publish

Upload everything in this folder to any static host, such as Azure Static Web Apps, Cloudflare Pages, Netlify, GitHub Pages or an IIS site.
Then point `rematechservices.com` at it.
