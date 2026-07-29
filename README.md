# jhansi.io website

Static site for jhansi.io — plain HTML and CSS, no build step, no framework, no JavaScript.
Serve from GitHub Pages (`jhansi-io/jhansi-io.github.io`).

| File | Purpose |
|---|---|
| `index.html` | the whole site (styles are inline + a small <style> block in the head) |
| `og.png` | 1200x630 social share card |
| `favicon.ico` | legacy fallback for `/favicon.ico` requests (16/32/48) |
| `assets/` | favicons, app icons, web manifest, logo marks (from the brand bundle) |
| `CNAME` | custom domain |

## Local preview

```
python3 -m http.server 8000
```

## Brand

Colours, type and the mark come from the jhansi brand bundle (`07-design-system/tokens.css`):
Manrope + JetBrains Mono, runtime purple `#5632F5`, verified green `#08BE7B`, slate-900 `#03091B`.
The purple is one value and is never tinted; on dark surfaces use `#9C87F9` for small functional text.

## Maintenance

The Done / Now / Next list in the closing section is the only part that goes stale.
Update it when a tier boundary is reached, not every commit.
