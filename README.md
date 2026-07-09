# osc-runs

Statisches Lauftagebuch fuer GitHub Pages.

## GitHub Pages

Die App liegt als `index.html` im Hauptordner. GitHub Pages kann dieses Repository direkt aus dem Branch `main` und dem Ordner `/` veroeffentlichen.

Oeffentliche URL nach Aktivierung:

```text
https://oschwamm.github.io/osc-runs/
```

## Laufdaten aktualisieren

Die Laufdaten sind bewusst direkt in der HTML-Datei gespeichert. So bleibt das Tool ohne Server, Datenbank oder Login nutzbar.

1. Seite oeffnen.
2. Lauf hinzufuegen, bearbeiten oder loeschen.
3. `Als HTML speichern` klicken.
4. Die heruntergeladene `index.html` im Repository ersetzen.
5. Aenderung committen und pushen.

Optional kann mit `JSON Backup` zusaetzlich eine Sicherung der Laufdaten exportiert werden.
