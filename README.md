# The Guide to Guitar Mastery — installable book

This repo holds only the **built** interactive book, served by GitHub Pages so it
can be installed on an iPad (Safari → Share → **Add to Home Screen**). It works
fully offline after the first load: the fonts are inlined and a service worker
caches the page.

**This is generated output.** The source — the Python engine that computes and
asserts every chord, scale and progression — lives in the private
`guitar-atlas` repo (`pwa/`). Rebuild with `python pwa/build_book.py`, then copy
`pwa/book/` here.

Files: `index.html` (the whole app, fonts inlined), `manifest.webmanifest`,
`sw.js` (offline cache), `icon-*.png`, `.nojekyll` (serve files as-is).
