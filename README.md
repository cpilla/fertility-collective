# The Fertility Collective — website

A single static page. No build step, no dependencies (fonts load from Google's CDN).

## Files
- `index.html` — the whole site
- `images/` — drop `logo.png` and `jacqui.jpg` here (see the note file inside)
- `CNAME` — the custom domain (`thefertilitycollective.net`). Delete this file if you don't want a custom domain.
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Two settings to edit (top of `index.html`, in the CONFIG block)
- `window.BOOKING_URL` — paste Jacqui's Google Calendar booking link. Every "Book" button opens it. Empty = buttons scroll to the contact form.
- `window.FORM_ENDPOINT` — optional Formspree endpoint. Empty = the contact form opens the visitor's email app pre-filled (works with zero setup).

## Local preview
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

See the chat for full step-by-step hosting instructions.
