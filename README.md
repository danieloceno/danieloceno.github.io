# danieloceno.github.io

Personal site — [danieloceno.github.io](https://danieloceno.github.io/).

Single-page static portfolio. `index.html` + `styles.css`, no framework, no build step,
no tracking. Only JS on the page is the footer UTC clock.

## Local preview

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

GitHub Pages serves `main` from the repo root automatically (user-page repo).
Merge to `main` → live. `.nojekyll` keeps Jekyll out of the way.
