# diogofreire-dev.github.io

My personal portfolio: who I am, the projects I've built and how to reach me.

Live at **https://diogofreire-dev.github.io/**.

## How it's built

- Plain HTML and CSS, written by hand. No framework and no build step, so GitHub Pages serves the files exactly as they are in the repo.
- No third-party requests (no web fonts, analytics or CDNs). That keeps the page fast and lets the Content Security Policy in `index.html` allow only `'self'`.
- Light and dark themes follow the visitor's system setting through `prefers-color-scheme`.
- `.nojekyll` tells GitHub Pages to skip Jekyll, since there is nothing for it to build.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
