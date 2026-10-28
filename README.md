# RELX Pod Finder

A one-page RELX pod compatibility chart and pod finder for [PodX](https://podx.ae), live at **https://relx-pod-compatibility.netlify.app**.

Pick a RELX device to see whether RELX Pod Pro and Pod Pro 2 fit it, then browse every compatible pod in stock with Dubai prices. Includes a Pod Pro vs Pod Pro 2 comparison, a monthly cost calculator, an embeddable chart (`?embed=chart`) and an FAQ.

## Files

- `index.html` — the whole site: markup, styles and script
- `robots.txt`, `sitemap.xml` — for search engines
- `netlify.toml` — Netlify publish settings and headers
- `favicon.svg`

## Editing

Prices, URLs and the WhatsApp number live in `CONFIG` at the top of the script in `index.html`. Devices and verdicts live in `DEVICES`.

The compatibility chart is also written into the HTML as a static table, so search engines can read it without JavaScript. When you change a verdict in `DEVICES`, update that table too. When content changes, update `<lastmod>` in `sitemap.xml`.

## Deploy

```bash
netlify deploy --prod --dir .
```
