# PAHADI Discord Landing Website 🇮🇳

A responsive, premium Himalayan-themed landing page for your Discord community.

## Files
- `index.html` — page content, SEO metadata, Open Graph metadata, structured data
- `style.css` — responsive styling and visuals
- `script.js` — mobile navigation and current year
- `robots.txt` and `sitemap.xml` — search engine discovery helpers (update URLs before publishing)

## Before publishing
1. Replace every `YOUR-USERNAME` and `YOUR-REPOSITORY` in `index.html`, `robots.txt`, and `sitemap.xml` with your GitHub username and repository name.
2. If you use a custom domain later, update the canonical URL, Open Graph URL, JSON-LD URL, and sitemap.
3. The Discord invite is already set to `https://discord.gg/pahadi`.
4. The website uses a few remote Unsplash images and Google Fonts. Internet access is needed for those assets to load.

## Publish free with GitHub Pages
1. Sign in at https://github.com/ and create a **public** repository, for example `pahadi-community`.
2. Upload `index.html`, `style.css`, `script.js`, `robots.txt`, and `sitemap.xml` to the repository root. You can upload `assets/` too if you add your own files.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then press **Save**.
6. Wait for GitHub Pages to publish. Your URL will be `https://YOUR-USERNAME.github.io/pahadi-community/`.
7. Replace the placeholders in the SEO files with that exact URL and commit the changes. (If the repository is named `YOUR-USERNAME.github.io`, the URL is `https://YOUR-USERNAME.github.io/`.)
8. Open the published site on your phone and test every Join Discord button.

## Google indexing
1. Add the published website to Google Search Console: https://search.google.com/search-console/
2. Use URL Inspection to request indexing of the homepage.
3. Submit `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/sitemap.xml` in Search Console.
4. Keep the title and description relevant, and share the page on genuine social profiles and relevant community listings.
5. Indexing and search rankings are not guaranteed and may take time.

## Notes
- Current server counts are intentionally not hard-coded because they change over time and cannot be reliably live-updated without a trusted Discord widget/API.
- Replace generic gallery images with your own licensed Pahadi photos if you want a more authentic brand.
