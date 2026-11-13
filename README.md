# ⛑️ QuickAid – Erste Hilfe

Offline-fähiger Erste-Hilfe-Leitfaden für den Notfall, direkt im Browser: [mvs2-bot.github.io/ErsteHilfe](https://mvs2-bot.github.io/ErsteHilfe/)

## Funktionen

- **Notfälle:** Herz, Schlaganfall, Lunge, Atemnot
- **Leitfäden:** Auto, Daheim, Herz-Lungen-Wiederbelebung mit Taktgeber (Ton an/aus), Spezialfälle wie Verbrennung, Verätzung, Unterkühlung, Krampfanfall, Kopf/Sonne und Knochenbruch
- **Hell/Dunkel-Modus:** gemeinsame Einstellung mit dem Dashboard (`overall-theme`), ohne eigene Wahl folgt die Seite dem Gerät
- **PWA:** installierbar (Icons für iPhone und Android) und offline nutzbar

## Aufbau

- `index.html`: die komplette App (HTML, CSS, JS)
- `sw.js`: Service Worker; bei neuen oder umbenannten Dateien die Cache-Version erhöhen
- `shared/ios-nav.js`: gemeinsame Navigation wie in den anderen Apps (Original im Repo `mvs2-bot.github.io`)
- `icon.svg`, `icons/`: App-Icon (Akzent Rot `#ff3b30`)
  - `favicon-32.png`, `icon-192.png`, `icon-512.png`: abgerundet, für Browser-Tab und Android
  - `apple-touch-icon.png` (180×180) und `icon-maskable-512.png`: randlos, iOS und Android runden selbst ab

Teil des Dashboards [mvs2-bot.github.io](https://mvs2-bot.github.io/).

> Hinweis: Diese Seite ersetzt keinen Erste-Hilfe-Kurs. Im Notfall immer zuerst **112** anrufen.
