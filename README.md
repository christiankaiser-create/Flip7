# Flip 7 Zähler

Einfacher Punkte-Zähler für Flip 7 in großer Runde. Eine `index.html`, kein Build, läuft direkt im Handy-Browser
und lässt sich als App auf den Home-Bildschirm legen (PWA, offline-fähig).

- Pro Runde bei jedem Spieler die Punkte eintippen, „Runde eintragen“.
- Rangliste sortiert sich automatisch, Ziel standardmäßig 200 (einstellbar).
- Verlauf aller Runden, letzte Runde zurücknehmen, neues Spiel.
- Spielstand bleibt am Gerät gespeichert.

## Auf dem iPhone installieren

1. Die GitHub-Pages-URL in Safari öffnen.
2. Teilen-Symbol → „Zum Home-Bildschirm“.
3. Die App startet ab dann im Vollbild mit eigenem Icon, auch ohne Internet.

## Hosting

Der Workflow in `.github/workflows/pages.yml` veröffentlicht das Repo bei jedem Push über GitHub Pages.
Einmalig unter *Settings → Pages → Source* auf **GitHub Actions** stellen.
