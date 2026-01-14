# Countries-App
Build it up bottom-up

## Playwright note
If Playwright cannot find or click the SVG countries during local runs, start the dev server on a different port (e.g. `python -m http.server 4173`) and use `click(force=True)` after waiting for `path.country` with `state="attached"` to bypass visibility timing issues.
