GALAXY BEYOND 0.20.3 — PWA BUILD

CONTENUTO
- index.html              gioco 0.20.3
- manifest.webmanifest    installazione come web app
- sw.js                   cache offline / aggiornamento
- icons/                  icone 192 e 512 px

MODIFICHE 0.20.3
- autosalvataggio meta-progressione e impostazioni in localStorage
- codice manuale di salvataggio mantenuto come backup/trasferimento
- fix CSS: aggiunta variabile --lime usata dagli stati selezionati
- debug opzionale: aggiungi ?debug=1 all'URL
- diagnostica debug: FPS, nemici, proiettili, particelle, stato save
- strumenti debug: invulnerabilità, pulizia arena, +1000 bulloni, onda successiva, salva
- ottimizzazione grafica non invasiva: culling di proiettili/particelle fuori schermo
- DPR adattivo sui device con risorse limitate
- manifest + service worker + icone per PWA installabile e cache offline

NOTA PWA
La PWA non può essere installata correttamente aprendo index.html come file://.
Va pubblicata/servita via HTTPS. Per sviluppo locale vanno bene localhost o 127.0.0.1.

TEST LOCALE DA PC
Nella cartella del gioco:
  python -m http.server 8080
poi apri:
  http://localhost:8080/
Debug:
  http://localhost:8080/?debug=1

SU ANDROID
Dopo la pubblicazione HTTPS, apri l'URL con Chrome o Samsung Internet e usa
"Installa app" / "Aggiungi alla schermata Home" (la dicitura varia col browser).
