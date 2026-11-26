# CanLua68 homepage

This repository serves the official CanLua68 homepage at https://canlua.io.vn/.
The CNAME file assigns that domain to this GitHub Pages site.

## Repository responsibilities

- Edit homepage content and SEO in index.html in this repository.
- Homepage styles and logos are owned here under assets/.
- favicon.ico, robots.txt and sitemap.xml are served at the domain root.
- Privacy policy pages stay in the separate privacy-policy repository and
  remain available at https://canlua.io.vn/privacy-policy/app-can-lua/ and
  the other existing /privacy-policy/ routes.
- The homepage copy in the privacy-policy repository declares this root URL
  as canonical. Make future homepage changes here.

## Local preview

Serve the repository root with a static HTTP server so root-relative asset
URLs resolve correctly.

## Release checks

1. Commit and push the homepage changes to the branch used by GitHub Pages.
2. Wait for the Pages deployment and check https://canlua.io.vn/.
3. Check /favicon.ico, /robots.txt and /sitemap.xml on the domain.
4. In Search Console for canlua.io.vn, submit https://canlua.io.vn/sitemap.xml.
   If the homepage is already indexed, use URL Inspection to check the
   selected canonical and optionally request a recrawl after the update.
5. Keep sitemap.xml updated when public policy pages are added or removed.

Preserve CNAME and google2e5512bfb11e6647.html. Homepage changes do not require
moving the privacy-policy repository or changing DNS.

Structured data describes the Android application without inventing app
prices, ratings or reviews.
