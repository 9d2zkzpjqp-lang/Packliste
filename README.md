# Packfolio V1.3 – Änderungen

**Die neue Version verwendet denselben LocalStorage-Schlüssel wie V1.2.** Beim Aktualisieren **derselben Website im selben Browser** bleiben die gespeicherten Reisen erhalten. Das Öffnen einer lokalen HTML-Datei kann hingegen einen anderen Speicherbereich verwenden. Daher vor dem Umstieg eine JSON-Sicherung exportieren und bei Bedarf importieren.

- Reisen können jetzt direkt auf der Startseite mit ✕ gelöscht werden (Sicherheitsabfrage).
- Einzelne Gegenstände können per ✕ entfernt werden, ohne die Menge oder andere Gegenstände zu verändern.
- Der Fortschritt wird immer aus den **aktuell vorhandenen** Gegenständen errechnet: nach Entfernen von 5 bei 40 ursprünglichen und Packen der verbleibenden 35: **35/35 – 100 %**.
- Über „Was habe ich vergessen?“ können nach der Reise einzelne oder mehrere Gegenstände erfasst werden. Sie bleiben im JSON-Backup, sind auch im Lexikon suchbar und werden bei **neuen** Reisen als wählbare Vorschläge angezeigt. Diese Einträge beeinflussen nicht die Packfortschrittsanzeige. Sie lassen sich aus dem Reise-Rückblick wieder entfernen.
- Die bisherigen Bedienkonventionen bleiben: Kategorien, Check rechts, Menge in der Mitte, Hinzufügen unten, zuletzt verwendet und kombinierbare Vorlagen.
- Rückreise-/Abreise-Checkliste ist als **späterer Ausbau** vorgesehen und in V1.3 noch nicht eingebaut.
- Eigene Mikrofontaste und Fotoimport handschriftlicher Listen bleiben vorerst zurückgestellt.

## Dateien
- `index.html`: zum Deployment auf GitHub Pages
- `Packfolio_V1_3.html`: zum direkten Öffnen und lokalen Ausprobieren (separat geliefert)

## Speichern
Die Web-App speichert derzeit lokal im Browser; JSON-Sicherungen über Einstellungen → Daten exportieren erstellen. Die V1.3 speichert neue Daten im vorhandenen Zustand `state.forgotten` und `trip.forgotten`.
