GALAXY BEYOND 0.22.9 — PACCHETTO PWA

- index.html corrisponde alla build 0.22.9 con i tre intermezzi illustrati incorporati.
- manifest.webmanifest, service worker e icone sono pronti per GitHub Pages.
- assets/menu-bg.webp e le due icone sono gli unici file esterni richiesti dal gioco.
- Fullscreen e orientamento landscape mantenuti.
- La cache del service worker è versionata come galaxy-beyond-0.22.9.

PUBBLICAZIONE SU GITHUB PAGES

1. Carica nella root del repository tutto il contenuto di questa cartella.
2. In GitHub apri Settings > Pages.
3. Seleziona Deploy from a branch, poi il branch principale e la cartella /(root).
4. Salva e attendi la pubblicazione dell'indirizzo del gioco.

Per una release futura, sostituisci index.html e aggiorna sia la versione del
manifest sia il nome CACHE in sw.js, così i dispositivi ricevono la nuova build.
