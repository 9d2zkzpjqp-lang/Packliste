# Packfolio 1.7.9

Eigenständige Packlisten-App für Safari, bereitgestellt über GitHub Pages.

## Installation

`index.html` und die Dokumentationsdateien in das GitHub-Repository kopieren. Vor dem Austausch über **Einstellungen & Daten** eine JSON-Sicherung exportieren. Die Reise- und Lexikondaten liegen lokal im Browser und werden beim Dateiaustausch normalerweise nicht überschrieben.

## Änderungen in 1.7.6

- Deckende, einheitliche Hintergründe für fixierte Kategorieüberschriften.
- Reisezeitraum: Übernachtungen aus Beginn und Ende berechnet, Enddatum-Auswahl nach Beginn angestoßen.
- Gemeinsamer Gegenstandsauswahldialog für globale Suche und einzelne Kategorien.
- Mehrfachauswahl durch wiederholtes Antippen; hinzugefügte Einträge werden markiert.
- Unbekannte Suchbegriffe können als neue Lexikoneinträge angelegt werden.
- Dialogpositionierung bei eingeblendeter iOS-Tastatur über Visual Viewport.
- Kleine Korrekturen gegen horizontales Überlaufen im Reiseformular.

## Hinweise

- Automatisches Öffnen des iOS-Datumsauswahlfensters hängt von Safari ab; das Enddatum ist in jedem Fall direkt auswählbar.
- Bei neuen Gegenständen aus der globalen Suche wird die Kategorie zunächst über einen einfachen Eingabedialog abgefragt.
- Inhaltliche Dubletten im Lexikon werden bewusst nicht automatisch zusammengeführt.
- Änderungen an der Reise- und Packlistenlogik bitte auf einem Testeintrag prüfen.


## Version 1.7.6
- Ein einziges Schließen-Symbol im Gegenstand-Auswahldialog.
- Neue Gegenstände erhalten eine grafische Kategorieauswahl mit Farben und Illustrationen statt eines iOS-Texteingabefensters.
- Zurück zur Suche ohne Verlust des Suchbegriffs.

## Version 1.7.9
- Im Lexikon kann ein Gegenstand nach Sicherheitsabfrage endgültig gelöscht werden.
- Bestehende Packlisten bleiben mit Mengen und Packstatus erhalten.
- Gelöschte Standardgegenstände bleiben auch nach einem Neustart aus dem Lexikon ausgeblendet.
- JSON-Backups enthalten die Löschmarkierungen.
