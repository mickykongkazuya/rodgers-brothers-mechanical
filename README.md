# Rodgers Brothers Mechanical

Marketing website for Rodgers Brothers Mechanical — heating, cooling, installation
and 24/7 repair in the Philadelphia area.

The site is a single self-contained static page (`index.html`). All page imagery is
embedded inline (base64), so the page renders with no external requests. The
`imgpack/` folder contains the original source assets (logos, hero photos, job
photos) for future edits.

## Deploy

Static site — no build step. Hosted on Vercel:

```bash
vercel --prod
```
