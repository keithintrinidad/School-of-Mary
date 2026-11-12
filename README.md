# In the School of Mary

A student’s guide to the mysteries of the Rosary, the Seven Sorrows of Our Lady, and four companion chaplets, as an installable, offline-ready web app with the full booklet as a downloadable PDF.

Live at: https://keithintrinidad.github.io/School-of-Mary/

## Files
- `index.html`: the whole app (content, styles and script in one file)
- `sw.js`: service worker; caches everything on first visit so the app opens without a connection
- `manifest.json` and `icons/`: install-to-home-screen support
- `In-the-School-of-Mary.pdf`: the printable booklet

When you change any file, bump `CACHE` in `sw.js` (and `VERSION` in `index.html`) so installed copies update.

## Credits and licence
Built by Claude using material provided by and under the guidance of Keith Francis.

Licensed under CC BY-NC-SA 4.0: https://creativecommons.org/licenses/by-nc-sa/4.0/
