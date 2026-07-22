# CalTracker - Kalorien Tracker für iPhone

Eine Progressive Web App (PWA) zum Tracken von Kalorien und Nährwerten.

## Features
- 📊 Lebensmittel aus Excel importieren (DMacros)
- 🔍 Lebensmittel filtern
- 📝 Nährwerte tracken (Menge in Gramm)
- 🧾 Summe aller getrackten Einträge
- 💾 Export als Excel (DMacros.xlsx)
- 📱 Optimiert für iPhone (Smartphone-Ansicht)
- 🌐 Offline-fähig (kein Internet nötig)

## Installation für iPhone
1. Repository auf GitHub hochladen
2. Auf dem iPhone die GitHub-Seite öffnen
3. Im Safari Browser: **Teilen** → **Zum Home-Bildschirm**
4. Die App erscheint als eigenes Icon auf dem Home-Bildschirm

## Verwendung
1. Excel-Datei importieren (Spalten: ID, Food, Energie, Fat, SFA, Carb, Sugar, Fiber, Protein)
2. Lebensmittel in Liste auswählen
3. **Track** klicken und Menge in Gramm eingeben
4. Eintrag erscheint in der Tracking-Liste
5. Summe wird automatisch berechnet

## Dateien
- `index.html` - Hauptanwendung
- `xlsx.full.min.js` - SheetJS Library (Excel Import/Export)

## Offline-Nutzung
Die App funktioniert komplett ohne Internet, da alle Bibliotheken lokal eingebunden sind.