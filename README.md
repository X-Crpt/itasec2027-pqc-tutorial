# Practical Post-Quantum Cryptography — ITASEC 2027 Tutorial

Website of the half-day tutorial **"Practical Post-Quantum Cryptography: From Hardware/Software Design to Secure Implementation"** at [ITASEC 2027](https://itasec.it/) (Siena, 8–12 February 2027), organized by [EDGE Group](https://edge-group-polito.github.io/) and [SMILIES](https://www.smilies.polito.it/), Politecnico di Torino.

Live site: https://x-crpt.github.io/itasec2027-pqc-tutorial/

## Structure

```
index.html        single-page site (HTML + inline CSS, no build step)
img/edge.png      EDGE Group logo
img/smilies.svg   SMILIES logo
img/favicon.png   favicon (from the EDGE logo)
.nojekyll         serve files as-is, skip Jekyll
```

## Editing

- Program times, tutorial date and speakers are in `index.html` (search for `TBD`).
- Colors are defined once in the `:root` block at the top of the `<style>`:
  SMILIES navy `#2B388F`, SMILIES cyan `#26A9E0`, EDGE indigo `#323070`.
- Fonts: Montserrat (headings) and Source Sans 3 (body), from Google Fonts.

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

GitHub Pages serves the `main` branch root (Settings → Pages → Deploy from a branch → `main` / `/ (root)`).
Every push to `main` redeploys the site in about a minute.
