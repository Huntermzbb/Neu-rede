# Goethe B2 · Mein Lehrer Pro

Offline-fähige Lern-App (PWA) für das Goethe-Zertifikat B2.

## Dateien
- `index.html` – die App
- `manifest.webmanifest` – Name, Farben, Icons
- `sw.js` – Offline-Cache (Service Worker)
- `icon-192.png`, `icon-512.png` – App-Icons
- `icon-maskable-192.png`, `icon-maskable-512.png` – Icons für Android (runde/abgerundete Formen)
- `apple-touch-icon.png` – iPhone-Icon
- `favicon-16.png`, `favicon-32.png`, `favicon.ico` – Browser-Tab
- `.nojekyll` – GitHub Pages soll die Dateien unverändert ausliefern

## Veröffentlichen mit GitHub Pages
1. Neues Repository erstellen (z. B. `goethe-b2`).
2. **Alle** Dateien (auch `.nojekyll`) in den Hauptordner hochladen.
3. Settings → Pages → Source: *Deploy from a branch* → Branch `main`, Ordner `/ (root)` → Save.
4. Nach 1–2 Minuten ist die App unter `https://DEIN-NAME.github.io/goethe-b2/` erreichbar.

## Auf dem Handy installieren
- iPhone (Safari): Teilen → *Zum Home-Bildschirm*.
- Android (Chrome): Menü → *App installieren*.

## Update
Nach jeder Änderung an `index.html` in `sw.js` die Zeile `const VERSION = 'goethe-b2-pro-v1'` auf `v2`, `v3` … erhöhen.
