# Renoweet Website Package

## Files
- `index.html` — public website.
- `projects.js` — project portfolio data and compressed project photos.
- `website-manager.html` — private local Website Manager. Do **not** publish this file to the public GitHub Pages repository.

## Updating projects
1. Keep `website-manager.html` and a copy of the current `projects.js` together in a private folder on your computer.
2. Open `website-manager.html` in Edge/Chrome.
3. Add/edit/delete projects and upload photos. Photos are resized to max 1600 px and JPEG-compressed before storage.
4. Click **Export projects.js**.
5. Replace only `projects.js` in the public GitHub repository.
6. GitHub Pages will publish the updated portfolio.

The public site has no admin login and cannot edit content. This keeps the public website simple and avoids storing GitHub credentials in browser code.

Default Website Manager PIN: `2468`. The PIN is local to that browser and is not server authentication. Keep the manager file private.


SEO UPDATE
- Public street address removed; website uses service-area positioning.
- Added canonical, robots, OpenGraph/Twitter metadata and service-area structured data.
- Added robots.txt and sitemap.xml.
- Added six Amsterdam service landing pages.
- Google review meta initialized at 5.0 / 1 review; add actual Google review text in Website Manager when available.
- Upload all folders/files in this package to the website root. Keep website-manager.html private/off the public site.
