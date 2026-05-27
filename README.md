# Best Yacht Cleaning

Nationwide yacht cleaning, detailing, and maintenance — single-page marketing site.

## Stack

Plain HTML / CSS / JS — no build step.

- `index.html` — page markup + JSON-LD schema
- `styles.css` — navy + gold nautical theme
- `main.js` — reveal-on-scroll, phone formatter, lead form handler

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8080
```

## Lead form

Form posts are stubbed. Wire the `fetch` call in `main.js` to your endpoint (Formspree, Make.com, HubSpot, etc.).
