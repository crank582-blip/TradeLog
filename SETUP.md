# TradeLog — App Setup Anleitung

## Dateien in diesem Paket
- `tradelog.html` — die App
- `manifest.json` — PWA Konfiguration
- `sw.js` — Service Worker (Offline-Support)
- `icon-192.png` — App Icon (klein)
- `icon-512.png` — App Icon (groß)

---

## Option 1: Netlify (empfohlen, kostenlos, 5 Minuten)

1. Gehe auf **netlify.com** → kostenlos registrieren
2. Dashboard → "Add new site" → "Deploy manually"
3. Alle 5 Dateien in den Upload-Bereich ziehen
4. Fertig — du bekommst eine URL wie `tradelog-xyz.netlify.app`

### App auf dem Handy installieren (Android):
1. URL im Chrome öffnen
2. Chrome Menü (⋮) → "Zum Startbildschirm hinzufügen"
3. Die App erscheint mit Icon auf dem Homescreen
4. Funktioniert danach auch offline

### App auf dem Handy installieren (iPhone):
1. URL in Safari öffnen
2. Teilen-Button → "Zum Home-Bildschirm"
3. App erscheint mit Icon

---

## Option 2: GitHub Pages (kostenlos)

1. GitHub Account erstellen
2. Neues Repository erstellen (z.B. "tradelog")
3. Alle 5 Dateien hochladen
4. Settings → Pages → Branch: main → Save
5. URL: `deinname.github.io/tradelog/tradelog.html`

---

## Verkauf über Gumroad

1. **gumroad.com** → kostenlosen Account erstellen
2. Neues Produkt → "Digital Product"
3. Alle 5 Dateien als ZIP hochladen
4. Preis setzen (empfohlen: 9–19 €)
5. Produktseite mit Screenshots der App füllen
6. Veröffentlichen — Gumroad übernimmt Zahlungsabwicklung

---

## Play Store (über PWABuilder)

Sobald die App auf Netlify läuft:
1. **pwabuilder.com** aufrufen
2. Deine Netlify-URL eingeben
3. "Android" → "Generate Package"
4. APK herunterladen
5. Play Console ($25 einmalig) → App hochladen

---

## Hinweis zum AI Coach

Die AI-Analyse benötigt eine Internetverbindung (Anthropic API).
Alle anderen Features (Journal, Kalkulator, Stats, Kalender) funktionieren vollständig offline.
