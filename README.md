# RedCow Camp 2026 — Sito Web

Landing page ufficiale del RedCow Camp 2026, summer camp sportivo a Sergnano (CR).

## Struttura del progetto

```
redcow-camp/
├── index.html        ← Pagina principale (tutto il sito)
├── img/
│   ├── about.jpg     ← Foto sezione "Chi siamo"
│   ├── calcio.jpg    ← Foto card Calcio
│   ├── strada.jpg    ← Foto card Calcio di Strada
│   ├── padel.jpg     ← Foto card Padel
│   ├── tennis.jpg    ← Foto card Tennis
│   └── kit.jpg       ← Foto sezione Kit
└── README.md
```

## Come pubblicare su GitHub Pages

1. Crea un account su [github.com](https://github.com) se non ce l'hai
2. Clicca **"New repository"** e chiamalo `redcow-camp-2026`
3. Carica tutti i file (index.html + cartella img/) tramite **"Add file → Upload files"**
4. Vai in **Settings → Pages**
5. Sotto "Source" seleziona **"Deploy from a branch"**, branch **main**, cartella **/ (root)**
6. Clicca **Save** — dopo 1-2 minuti il sito sarà live su:
   `https://TUO-USERNAME.github.io/redcow-camp-2026/`

## Come sostituire le immagini

Le immagini nella cartella `img/` sono placeholder. Per sostituirle con foto reali:

1. Prepara le tue foto (idealmente JPG, almeno 800px di larghezza)
2. Rinominale esattamente come quelle esistenti:
   - `about.jpg` → foto ragazzi al campo (sezione Chi siamo)
   - `calcio.jpg` → foto allenamento calcio
   - `strada.jpg` → foto calcio di strada / parco
   - `padel.jpg` → foto campi da padel
   - `tennis.jpg` → foto campi da tennis
   - `kit.jpg` → foto abbigliamento sportivo / kit
3. Sostituisci i file nella cartella `img/`
4. Ricarica i file su GitHub

## Come modificare il form di iscrizione

Il form è ospitato su Google Forms. Per aggiornare il link nel sito:
1. Apri `index.html` con un editor di testo
2. Cerca `docs.google.com/forms`
3. Sostituisci il vecchio URL con il nuovo (usa Trova e Sostituisci — ci sono più occorrenze)

## Note tecniche

- Sito completamente **self-contained**: funziona senza dipendenze esterne
- **Zero librerie JavaScript** — tutto vanilla HTML/CSS/JS
- La mappa usa **Google Maps Embed** (si carica quando c'è internet)
- Compatibile con Chrome, Safari, Firefox, Edge — mobile e desktop
