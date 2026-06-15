# James Boltach #7 — Player Profile

A single-page travel baseball player profile for James Boltach (Class of 2032, PCLL Lightning 11U).

Static site — no build step, no dependencies, no JavaScript.

## Files
- `index.html` — the full page (markup + inline CSS)
- `images/` — optimized WebP photos referenced by the page

## Running locally
Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying
Upload `index.html` and the `images/` folder together (relative paths handle the rest). Works on any static host — GitHub Pages, Vercel, Netlify, etc.

**Before going live:** in the `<head>` of `index.html`, replace the `YOUR-DOMAIN.com` placeholder in the `og:image` and `twitter:image` tags with the real deployed domain, so shared-link previews show the photo. (Look for the comment that flags it.)

## Notes
- The page is set to `noindex` so it stays out of search engines (reachable only via a direct link).
- Stats are stamped "current as of 2026 Season."
