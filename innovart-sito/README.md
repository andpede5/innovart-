# Innovart Festival — sito

Sito del festival Innovart (San Sebastiano Curone, Val Curone). Sito statico: solo HTML, font e immagini, nessun server e nessun database.

## Contenuto
- `index.html` — versione italiana
- `en.html` — versione inglese (si genera da `index.html` con lo script `make_en.py`, conservato nel progetto Claude "innovart web site")
- `img/` — foto (tutte di Alice Fois)
- `fonts/` — Bricolage Grotesque, Newsreader (SIL Open Font License 1.1), Satoshi
- `js/matter.min.js` — motore fisico per i blocchi della home
- `favicon.svg`, `apple-touch-icon.png` — icona del sito
- `.nojekyll` — dice a GitHub Pages di pubblicare i file così come sono

## Pubblicazione
GitHub Pages: Settings → Pages → Source "Deploy from a branch" → branch `main`, cartella `/ (root)`.

## Prima di aggiornare
- Se cambi un testo in `index.html`, aggiorna anche `en.html`.
- Non usare le foto non autorizzate (cartella `ASSET_DA_AUTORIZZARE`).
- Il sito non usa cookie né statistiche: se se ne aggiungono, va aggiornata la pagina Privacy (#privacy) e serve un banner per il consenso.
