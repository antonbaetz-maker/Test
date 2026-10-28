# Zähler – iPhone-Web-App

Zwei Zähler („G+“ und „Kumiko“) mit + und −, ein Datumsfeld, ein Notizfeld und ein
Button „Alles zurücksetzen“. Alle Werte werden auf dem Gerät gespeichert und bleiben
beim Schließen und erneuten Öffnen erhalten. Die App funktioniert auch offline.

## Auf das iPhone bringen

1. Auf GitHub: **Settings → Pages → Build and deployment → Source: „GitHub Actions“**.
2. Unter **Actions** den Workflow „Deploy to GitHub Pages“ starten (oder einen Commit pushen).
3. Die Adresse öffnen, die der Workflow anzeigt (z. B. `https://antonbaetz-maker.github.io/Test/`),
   und zwar **in Safari** auf dem iPhone.
4. Teilen-Symbol → **„Zum Home-Bildschirm“**. Fertig, die App hat jetzt ein eigenes Symbol.

Hinweis: Die Daten liegen lokal in der App auf dem iPhone. Wenn du die App vom
Home-Bildschirm löschst, sind auch die Werte weg.

## Dateien

- `index.html` – die komplette App (Oberfläche und Logik)
- `manifest.webmanifest`, `icons/` – Name und Symbol für den Home-Bildschirm
- `sw.js` – Service Worker für den Offline-Betrieb
