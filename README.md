# Mo – Next Level Barbershop

Minimalistische, moderne Onepager-Website für einen Barbershop – umgesetzt mit **HTML + CSS** und minimalem Vanilla JavaScript (nur Navigation/Scroll-Verhalten).

## Projektstruktur

```bash
.
├─ index.html
├─ assets/
│  ├─ css/
│  │  └─ styles.css
│  └─ img/
└─ README.md
```

## Lokale Vorschau

1. Repository klonen oder Dateien herunterladen.
2. Projektordner öffnen.
3. `index.html` direkt im Browser öffnen.

Optional mit lokalem Server (empfohlen):

```bash
python3 -m http.server 8000
```

Dann aufrufen: `http://localhost:8000`

---

## GitHub Pages Deployment (Schritt-für-Schritt)

### 1) Neues GitHub-Repository erstellen

- Auf GitHub ein neues Repository anlegen (z. B. `mo-nextlevel`).
- Optional: Haken bei „Add a README“ entfernen, falls du dieses Projekt direkt pushen möchtest.

### 2) Projekt lokal mit Git initialisieren (falls nötig)

```bash
git init
git add .
git commit -m "Initial commit: Mo Next Level Barbershop onepager"
```

### 3) Remote Repository verbinden

```bash
git branch -M main
git remote add origin https://github.com/<dein-user>/<dein-repo>.git
git push -u origin main
```

### 4) GitHub Pages aktivieren

1. Auf GitHub in dein Repository gehen.
2. **Settings** öffnen.
3. Im linken Menü **Pages** auswählen.
4. Unter **Build and deployment** bei **Source**: `Deploy from a branch` wählen.
5. Branch `main` und Ordner `/ (root)` auswählen.
6. **Save** klicken.

### 5) Live-URL prüfen

- Nach kurzer Zeit erscheint die veröffentlichte URL, z. B.:
  `https://<dein-user>.github.io/<dein-repo>/`
- Die URL steht auch im **Pages**-Bereich der Repository-Einstellungen.

### 6) Änderungen veröffentlichen

Nach Anpassungen lokal committen und pushen:

```bash
git add .
git commit -m "Update content/design"
git push
```

GitHub Pages deployed automatisch neu.

---

## Anpassungstipps

- **Telefonnummer** in `index.html` bei `href="tel:+430000000000"` ändern.
- **Adresse/Öffnungszeiten** im Bereich `#standort` anpassen.
- **Google Maps Embed** im `iframe src` durch eigenen Embed-Link ersetzen.
- **Instagram-Link** (`https://instagram.com/mo_nextlevel`) aktualisieren.
- **Bilder**: Aktuell Picsum-Placeholder. Eigene Bilder in `assets/img/` ablegen und Bildpfade ersetzen.
