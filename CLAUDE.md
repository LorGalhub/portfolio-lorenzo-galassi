# Portfolio — Lorenzo Galassi

## Obiettivo
Sito portfolio one-page, statico, in italiano. Il CV è la fonte di verità: il sito lo rispecchia e mostra i lavori. **Nessun fronzolo**: niente animazioni decorative, niente parallax, niente librerie UI, niente dark mode toggle, niente cookie banner (non servono tracker).

## Stack
- HTML + CSS + JS vanilla, nessun framework e nessuna build step
- Struttura: `index.html`, `style.css`, eventuale `script.js` minimo
- Responsive mobile-first
- Deploy previsto su hosting statico (GitHub Pages / Netlify): tutto deve funzionare aprendo `index.html`

## Assets (cartella `/assets/`)
- `/assets/cv/CV_Lorenzo_Galassi.pdf` — CV scaricabile (linkato nel sito)
- `/assets/cv/foto.jpg` — foto profilo (estratta dal CV)
- `/assets/svs/` — 3 screenshot del progetto SVS (già sfocati per privacy: mostrarli così come sono, in una galleria semplice, senza lightbox complessi)
- Per i video YouTube: usare thumbnail cliccabili che aprono YouTube in nuova tab (thumbnail via `https://img.youtube.com/vi/VIDEO_ID/hqdefault.jpg`). NON usare iframe embed: più leggeri, niente consensi cookie.

## Struttura della pagina

### 1. Hero
- Nome: **Lorenzo Galassi**
- Titolo: **Learning & Digital Content Specialist**
- Sottotitolo: Content Strategy • Produzione Multimediale • Live Events • Project Coordination
- Contatti: Livorno (LI) · +39 329 7427116 · l-ivor@hotmail.it
- Foto profilo
- Executive summary (dal CV): professionista della comunicazione digitale con oltre dieci anni di esperienza nella progettazione, produzione e coordinamento di contenuti editoriali, produzioni live ed eventi internazionali. Collaborazioni con The Pokémon Company International e Nintendo su produzioni ufficiali e progetti digitali ad alto impatto.

### 2. Numeri di impatto
- 4.000.000+ visualizzazioni complessive
- 1.300.000+ audience complessiva
- 12.000+ spettatori live contemporanei

### 3. Portfolio — ORDINE VINCOLANTE (stesso ordine del CV)

**3.1 SVS Gestione Servizi — Responsabile della Formazione (2023–2025)**
Progettazione e realizzazione di percorsi formativi, corsi e contenuti multimediali per clienti e personale operativo (ASL e trasportatori di Toscana e Lazio).
→ Mostrare i 3 screenshot in `/assets/svs/`.

**3.2 The Pokémon Company International & Nintendo — Streaming & Content Operations (2016–2019)**
Produzione e coordinamento di dirette sui canali YouTube di Cydonia (258.000 iscritti), oltre 1,6M di visualizzazioni, pianificazione editoriale, collaborazioni con Nintendo Italia e partner commerciali (eBay, NordVPN).
→ Playlist: https://www.youtube.com/playlist?list=PLHJG6DL69O4g3XmF89krsmRW3D34qld3P

**3.3 Pokémon World Championships 2022 — Social Media & Content Coordinator**
Coordinamento della copertura social, regia e fotografia delle dirette durante il torneo mondiale. Oltre 12.000 spettatori contemporanei su Twitch (canale Cydonia & Chiara, 189.000 iscritti). Re-uploads:
- https://www.youtube.com/watch?v=WdB9GJoY3Ks
- https://www.youtube.com/watch?v=ibn_cup3JuI
- https://www.youtube.com/watch?v=sOS4q75VI-s
- https://www.youtube.com/watch?v=E68_cd4kwX4

**3.4 Bello Figo — "Trombo a Facoltà" — Regista e Producer (2019)**
Regia e produzione del videoclip, oltre 1,5M di visualizzazioni (canale da 691.000 iscritti).
→ https://www.youtube.com/watch?v=3KN8MwIAcH0

**3.5 Canale Francesco Pardini — Content Creator (2017–2019)**
Produzione e montaggio di contenuti video dedicati al mondo Pokémon, oltre 185.000 visualizzazioni (canale da 172.000 iscritti).
→ LINK: `TODO_LINK_PARDINI` (placeholder, da sostituire)

**3.6 Canale personale — progetto editoriale Pokémon**
Ideazione e sviluppo di un progetto editoriale su YouTube: produzione completa dei contenuti, gestione community, analisi delle performance (6.000 iscritti, 600.000 visualizzazioni).
→ LINK: `TODO_LINK_CANALE_PERSONALE` (placeholder, da sostituire)

### 4. Esperienza sintetica / CV
- Nintendo — Event Specialist & Trainer (2014–2018): gestione eventi promozionali, reclutamento, formazione staff
- Formazione: Università degli Studi di Milano-Bicocca, Scienze della Comunicazione
- Lingue: Italiano · Inglese C1 · Spagnolo B1
- Competenze: Content Strategy, Storytelling, Produzione Video, Live Streaming, Project Management, Community Management
- Esperienze complementari: Euronics (2025–oggi), Esselunga (2024–2025), BRT (2021–2023)
- Bottone: **Scarica il CV (PDF)**

### 5. Footer
Contatti ripetuti + link mail. Niente form di contatto.

## Design
- Sobrio e professionale, sfondo bianco, tanta aria
- Accent: blu scuro istituzionale coerente con CV e screenshot SVS (indicativo: `#1e3a8a` / `#16307a`), un solo colore d'accento
- Tipografia: system font stack oppure una sola famiglia (es. Inter) con pesi diversi; titoli grandi, corpo leggibile
- Le sezioni portfolio hanno tutte lo stesso layout ripetuto (titolo, periodo, descrizione breve, media): la coerenza È il design
- Hover discreti sui link/thumbnail, nient'altro in movimento
- Accessibilità di base: alt text, focus visibile, contrasto sufficiente

## Cosa NON fare
- Non inventare contenuti, testimonianze o progetti non presenti in questo file
- Non cambiare l'ordine delle sezioni portfolio
- Non aggiungere librerie esterne (no Bootstrap, no Tailwind CDN, no jQuery)
- Non usare iframe YouTube
- Non rimuovere i placeholder `TODO_LINK_*`: lasciarli visibili nel codice finché non vengono forniti i link
