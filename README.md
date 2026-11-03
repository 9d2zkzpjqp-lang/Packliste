# Packfolio 1.5.6 – Qualitätsüberarbeitung

Eine persönliche Packlisten-App für iPhone, iPad und Mac (GitHub Pages).

## Installation

Die `index.html` im Repository-Root ersetzen. GitHub Pages muss diesen Branch veröffentlichen. Danach die Seite neu öffnen, ggf. mit `?v=156`. **Vorher die bestehende Packfolio-Datensicherung als JSON exportieren.**

## Änderungen

- Versionsanzeige in den Einstellungen auf **1.5.6** korrigiert.
- Die neun persönlichen Vorlagen bleiben erhalten; 21 ausdrücklich abgewählte **exakte Bezeichnungen** werden aus künftigen Vorlagen entfernt.
- Vereinbarte Bezeichnungen und Kategorien einschließlich **Schule & Klassenfahrt** und **Sportstützen (2)** ergänzt.
- `Sonnencreme & Lippen` wird in zwei Gegenstände aufgeteilt; `Klassenliste + Stempel` bleibt ein gemeinsamer Eintrag.
- Die Vorschläge lassen sich durch erneutes Antippen wieder entfernen. Auch bereits vorhandene Flip-Flops können so wieder abgewählt werden.
- Die bisherige automatische Bestandsmigration beim Start wird nicht mehr ausgeführt: bestehende Reisen, Häkchen und Mengen werden durch das Update nicht automatisch geändert.

## Hinweise

- **Bestehende Reisen werden nicht automatisch umgeschrieben.** Deshalb können dort noch alte Kategorien wie „Nachprüfung“ oder historische Bezeichnungen stehen. Die neuen Kategorien gelten für neue Reisen.
- „Entfernen“ meint die abgewählte **Bezeichnung in neuen Vorlagen/Vorschlägen**, nicht die Löschung alter Reisen oder sämtlicher ähnlicher Gegenstände.
- Daten bleiben browserlokal gespeichert. Ein JSON-Export ist vor jeder Aktualisierung wichtig.
- Die Tests auf iPhone Safari müssen nach dem Hochladen noch manuell durchgeführt werden.

## Kurztest

1. Neue Reise mit „Wochenendtrip“ erstellen.
2. Prüfen, ob die Versionsanzeige 1.5.6 lautet.
3. In „Passende Ergänzungen“ Flip-Flops hinzufügen und durch erneutes Antippen entfernen.
4. Eine Schulreise erstellen und Kategorie „Schule & Klassenfahrt“ prüfen.
5. Bestehende Reise mit Häkchen und Mengen kontrollieren; JSON-Export testen.
