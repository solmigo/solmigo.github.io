# solmigo.io

Landing page + privacy policy for **Solmigo**, an independent mobile app & game studio.

Static site (plain HTML/CSS/JS) hosted on **GitHub Pages**, served at **https://solmigo.io**.

## Files
- `index.html` — landing page
- `privacy.html` — app-store-compliant privacy policy
- `styles.css` — shared styles (warm-dark theme, Space Grotesk, amber accent)
- `favicon.svg` — sun mark
- `CNAME` — custom domain (`solmigo.io`)
- `robots.txt`, `sitemap.xml` — SEO
- `.nojekyll` — serve files as-is (skip Jekyll)
- `IMAGES-TO-GENERATE.md` — optional social/icon images to add later

## Local preview
Any static server works, e.g.:
```
python3 -m http.server 8000
```
then open http://localhost:8000

## Deploy
Push to `main`. In **repo → Settings → Pages**, set Source = "Deploy from a branch",
Branch = `main` / `/ (root)`. The custom domain is configured via the `CNAME` file;
enable **Enforce HTTPS** once the certificate is issued.

## Note
The privacy policy is standard boilerplate tailored to how our apps behave
(local storage + Google AdMob, no accounts). Review it before relying on it legally.
