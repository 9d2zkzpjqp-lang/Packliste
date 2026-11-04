# Packfolio 1.6.0 – PDF-Druckfunktion

## Neu

- Die aktuelle Reise lässt sich über **Packliste → ⋯ → Packliste als PDF** als echte PDF-Datei herunterladen.
- Wahlweise **drei Spalten** (kompakt) oder **zwei Spalten** (mehr Platz für längere Namen).
- A4-Hochformat, Kategorien als eigene Abschnitte, automatische Seitenumbrüche und Fortsetzungsüberschriften.
- Alle Gegenstände der aktuellen Reise werden ausgegeben, einschließlich bereits abgehakter Gegenstände. Die PDF-Kästchen sind entsprechend markiert.
- Mengen werden als `(...x)` angegeben. Packfolio 1.5.7 kennt nur einen Abhakstatus pro Gegenstand, noch keinen gespeicherten Teilmengen-Fortschritt.
- Das PDF wird ohne externe Bibliotheken direkt im Browser erzeugt. Es werden keine Reisedaten an einen Server übertragen.

## GitHub-Installation

1. In Packfolio 1.5.7 vorher unter **Einstellungen & Daten** eine JSON-Sicherung exportieren.
2. Die ZIP-Datei entpacken.
3. `index.html` im eigenen Packfolio-Repository durch die neue Datei ersetzen; `README.md` optional ebenfalls hochladen.
4. GitHub Pages nach dem Veröffentlichen mit `?v=160` neu öffnen.

## Technische Hinweise

Die PDF-Erzeugung verwendet A4-PDF-Seiten mit standardisierten Helvetica-Schriften und eingebetteten Vektor-Kästchen. Sonderzeichen außerhalb der WinAnsi-Zeichenbelegung werden im PDF vereinfacht. Eine vollständige Schrift-Einbettung für beliebige Unicode-Zeichen wäre ein möglicher späterer Ausbau.

## Prüfstatus

- JavaScript-Syntax geprüft.
- PDF-Ausgabe für 2 und 3 Spalten mit 110 Testgegenständen erzeugt und mit `pdfinfo`/`pdftotext` überprüft.
- PDF visuell als gerenderte A4-Seite kontrolliert.
- **Noch nicht auf iPhone Safari getestet.** Bitte dort besonders das Öffnen/Sichern der PDF-Datei prüfen.
- Die vorhandenen Reisen und der JSON-Speicher werden für die PDF-Erzeugung nicht verändert.
