# Mo – Next Level Barbershop

Statische, GitHub-Pages-kompatible Website (HTML + CSS, minimales Vanilla JS für Mobile-Menü).

## Projektstruktur

```text
.
├─ index.html
├─ assets/
│  ├─ css/
│  │  └─ styles.css
│  └─ images/
│     ├─ mo-hero.svg
│     ├─ mo-01.svg
│     └─ ...
└─ README.md
```

## Lokale Vorschau

```bash
python3 -m http.server 8000
```

Dann öffnen: `http://localhost:8000`

## GitHub Pages

- **Settings → Pages**
- **Source:** Deploy from a branch
- **Branch:** `main` / `(root)`
- Speichern und Deployment abwarten.

## Eigene Fotos verwenden

Die Seite ist auf lokale Bilder unter `assets/images/` vorbereitet.

Ersetze diese Dateien einfach 1:1 mit den echten Shop-Fotos:

- `mo-hero.svg`
- `mo-01.svg` bis `mo-10.svg`

Du kannst dabei auch auf `.jpg` / `.webp` wechseln – dann nur die Dateiendungen in `index.html` anpassen.
