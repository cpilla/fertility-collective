# The Fertility Collective — website

A single static page. No build step, no dependencies (fonts load from Google's CDN).

## Files
- `index.html` — the whole site. Offerings are organised into four tabs (Fertility · Pregnancy & Birth · Postpartum · Women's Wellness); each has a deep link (`#fertility`, `#pregnancy`, `#postpartum`, `#wellness`).
- `images/` — drop `logo.png` and `jacqui.jpg` here (see the note file inside)
- `CNAME` — the custom domain (`thefertilitycollective.net`). Delete this file if you don't want a custom domain.
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Two settings to edit (top of `index.html`, in the CONFIG block)
- `window.FORM_ENDPOINT` — Web3Forms endpoint for the contact form. Empty = the contact form opens the visitor's email app pre-filled (works with zero setup).
- `window.SHEET_CSV_URL` — the Google Sheet that drives every date box (one column per series, matched by header text). See "How to update class dates.md". Empty = the dates written in the HTML are used.

## Local preview
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

See the chat for full step-by-step hosting instructions.
