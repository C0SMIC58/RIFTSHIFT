RIFTSHIFT — GITHUB PAGES SITE V1

This folder is ready to deploy as the root of the GitHub repository:
C0SMIC58/RIFTSHIFT

EXPECTED PUBLIC URL
https://c0smic58.github.io/RIFTSHIFT/

WHAT IS INCLUDED
- Full public game website
- /game/ game overview
- /play/ browser-test launcher
- Actual V18.8.9 browser game under /browser/
- /download/ Windows download page
- Actual V18.8.9 desktop ZIP under /downloads/
- /updates/, /media/, /lore/, /faq/
- robots.txt + sitemap.xml + .nojekyll
- SEO/Open Graph metadata
- Custom 404

HOW TO PUBLISH WITH GITHUB PAGES
1. Open the C0SMIC58/RIFTSHIFT repository on GitHub.
2. Upload the CONTENTS of this folder to the repository root (not the outer folder itself).
3. Commit the changes to the main branch.
4. Open repository Settings -> Pages.
5. Under Build and deployment, select Deploy from a branch.
6. Choose branch: main and folder: /(root), then Save.
7. Wait for GitHub Pages deployment to complete.
8. Open: https://c0smic58.github.io/RIFTSHIFT/

GOOGLE SEARCH
Once the site is public, Google can crawl it because robots.txt and sitemap.xml are included. Indexing is not instant. Later, Google Search Console can be used to request indexing and submit the sitemap.

CUSTOM DOMAIN LATER
Do not add a CNAME file until you actually own the domain. When you buy a domain, GitHub Pages can keep serving the same site under the custom domain.


SCALE FIX UPDATE:
- The Play page now uses a near-full-height game viewport instead of a forced 16:9 card.
- A Fullscreen Test button is included.
- The embedded game detects the website iframe and keeps class/menu/upgrade UI at readable scale instead of shrinking the class screen down aggressively.
