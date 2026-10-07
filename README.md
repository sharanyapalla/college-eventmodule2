# Utsav 2026 – College Event Portal

Frontend-only festival website built with HTML5, CSS3 and vanilla JavaScript. No backend, database, API or framework.

## Run
Open `index.html` in a browser, or use VS Code Live Server. Font Awesome and Google Fonts load from CDNs (internet needed for icons and fonts; the site still works without them).

## Pages
index (home, stats, countdown, announcements), events (search, filter, sort, details), registration, schedule (day and category filters, live/up-next highlighting), gallery (filters, lightbox), contact.

## Structure
- `css/` style.css (base, layout), components.css (cards, forms, modals), responsive.css (breakpoints)
- `js/` data.js (all sample events, announcements, gallery), main.js (nav, footer, countdown, cards), plus one script per page
- `images/` empty folders for your own photos. The demo uses gradient tiles and icons instead of images.

## Customise
Edit `js/data.js` to change the festival date, events, announcements and gallery. The nav and footer are generated in `main.js`, so change them once for every page.

## Notes
Registration and contact forms only validate and show a success message. Nothing is stored or sent.
