# Zynpixa Site

Landing page and privacy policy for **Zynpixa – Photo Tools** (Android app).

Static HTML/CSS, no build step, no dependencies. Hosted via GitHub Pages.

## Files

- `index.html` — landing (hero, features, how-to, credits, honest limits)
- `privacy.html` — privacy policy
- `styles.css` — shared stylesheet (brand tokens, light + dark via `prefers-color-scheme`)
- `icon.png` — app icon
- `feature.png` — Open Graph preview image

## Preview locally

```bash
python3 -m http.server 8080 --bind 127.0.0.1
```

Then open <http://localhost:8080/>.
