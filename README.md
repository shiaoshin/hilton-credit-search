# Hilton · Credit Explorer

Static front end for Hilton Amex property/venue credit datapoints. Data is loaded at runtime from a GitHub Gist JSON export (produced by `hilton-credit-crawler`).

## Live site (GitHub Pages)

**https://shiaoshin.github.io/hilton-credit-search/**

Use that URL in the browser. The repo root on GitHub (`github.com/.../hilton-credit-search`) is only the source — it does not render the app.

### If the page looks empty

- Wait a few seconds for the Gist JSON to load (status pill should show **LIVE**).
- Hard refresh (cache): `Cmd+Shift+R` (Mac) / `Ctrl+Shift+R` (Windows).
- Open the browser devtools **Console** for errors (network blocked, ad blockers, etc.).

## Data

Bundled `DATA_URL` in `index.html` points at the raw Gist file. Update that URL if the Gist id changes.
