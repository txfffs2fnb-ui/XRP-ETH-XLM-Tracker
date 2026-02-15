# XRP-ETH-XLM Tracker

## Projekt-Übertragung von Netlify Fluffy-cucurucho

Dieses Repository dient zur Übertragung des Codes vom Netlify-Projekt "fluffy-cucurucho-89bdb1" zu GitHub.

## Netlify Projekt-Informationen

**Projekt-Name:** fluffy-cucurucho-89bdb1  
**Projekt-ID:** f173242b-736e-4225-92c7-92a12c8c9671  
**Deploy-ID:** 699189cd4cfd884dc076a077  
**Status:** Pausiert (Credit-Limit überschritten)  
**Letztes Update:** 15. Februar 2026, 12:15 PM  

## Datei-Struktur von Fluffy-cucurucho

Das Netlify-Projekt enthält folgende Dateien (insgesamt 16 Dateien, 1.2 MB):

### Haupt-Dateien
- **bs.html** (1.5 KB) - Hauptseite
- **index.html** (vorhanden im Repository)

### CSS-Dateien
- **bootstrap-dt3mkrgk.css** (385.5 KB)
- **katex-apyugzjm.css** (31.4 KB)
- **mapbox-gl-b9eh9olo.css** (35.6 KB)
- **steprenderer-bsdpyzhk.css** (136 B)
- **usefirsttimebookmark-dkrvdmh9.css** (1.3 KB)

### JavaScript-Dateien
- **fbevents.js** (348.1 KB)
- **loader.min.js** (1.8 KB)
- **meta.js** (532 B)
- **ntp.html-bzk0ybft.js** (2 KB)
- **9554678841295205** (158.5 KB)
- **vcd15cbe7772f49c399c6a5babf22c1241717689176015** (19.5 KB)

### Assets
- **favicons** (827 B)
- **favicons(1)** (1.7 KB)
- **favicons(2)** (1.7 KB)
- **maxresdefault.jpg** (200.1 KB)

## Übertragungsschritte

### Option 1: Manuelle Übertragung

1. **Dateien von Netlify herunterladen:**
   - Gehe zu: https://app.netlify.com/projects/fluffy-cucurucho-89bdb1/deploys/699189cd4cfd884dc076a077
   - Scrolle zum "Deploy file browser"
   - Klicke auf "Download" bei jeder benötigten Datei

2. **Dateien zu GitHub hochladen:**
   - Erstelle entsprechende Ordner in diesem Repository
   - Lade die Dateien über GitHub Web-Interface oder Git hoch

3. **Verzeichnisstruktur erstellen:**
   ```
   XRP-ETH-XLM-Tracker/
   ├── README.md
   ├── index.html
   ├── bs.html
   ├── css/
   │   ├── bootstrap-dt3mkrgk.css
   │   ├── katex-apyugzjm.css
   │   ├── mapbox-gl-b9eh9olo.css
   │   ├── steprenderer-bsdpyzhk.css
   │   └── usefirsttimebookmark-dkrvdmh9.css
   ├── js/
   │   ├── fbevents.js
   │   ├── loader.min.js
   │   ├── meta.js
   │   └── ntp.html-bzk0ybft.js
   ├── assets/
   │   ├── images/
   │   │   └── maxresdefault.jpg
   │   └── icons/
   │       ├── favicons
   │       ├── favicons(1)
   │       └── favicons(2)
   └── macro-tripple-tracker_files/
   ```

### Option 2: Netlify CLI

```bash
# Installiere Netlify CLI
npm install -g netlify-cli

# Login
netlify login

# Download des Deployments
netlify deploy:download --site fluffy-cucurucho-89bdb1
```

## Deployment

### GitHub Pages
Dieses Repository kann direkt über GitHub Pages bereitgestellt werden:
1. Gehe zu Settings > Pages
2. Wähle Branch: main
3. Wähle Ordner: / (root)
4. Speichern

### Netlify (neu)
Um das Projekt wieder auf Netlify zu deployen:
1. Verbinde dieses GitHub Repository mit Netlify
2. Build-Einstellungen:
   - Build Command: (leer)
   - Publish Directory: /

## Nächste Schritte

- [ ] bs.html Datei von Netlify herunterladen und zu GitHub hochladen
- [ ] CSS-Dateien organisieren und in /css/ Ordner verschieben
- [ ] JavaScript-Dateien organisieren und in /js/ Ordner verschieben
- [ ] Assets (Bilder, Icons) in /assets/ Ordner verschieben
- [ ] HTML-Dateien überprüfen und Pfade anpassen
- [ ] GitHub Pages aktivieren
- [ ] Tests durchführen

## Notizen

- Das ursprüngliche Netlify-Projekt ist derzeit pausiert aufgrund überschrittener Credit-Limits
- Die Dateien sind über den Deploy File Browser verfügbar
- Manuelle Deploys wurden verwendet (keine automatische Git-Integration)
- Letztes Deployment: Heute um 9:54 AM

## Kontakt

Owner: Steel X3  
Netlify Team: ralf-stolte
