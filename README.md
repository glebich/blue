# Blue Phone

Landing page for the Blue Phone: a Pixel running BlueOS, an AI-driven mobile operating system.

- Static site, one page: `index.html`.
- No build step. Fonts and images are embedded in the HTML; open the file in a browser or serve the repo root.
- `assets/brand/hero-bg.png` is the hero background photo. The page references it as a relative URL; the `Fetch design assets` GitHub Actions workflow downloads it from the URL listed in `tools/assets.txt` and commits it.
- `assets/design/` holds real UI screenshots for the features section, fetched the same way.

Deployed with GitHub Pages from the repo root.
