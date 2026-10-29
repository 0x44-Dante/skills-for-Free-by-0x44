---
name: change-validation
description: Bei änderungsverifikation in Coding-Agent-Workflows verwenden.
---
# Änderungsverifikation

Ein grüner Test ist nur nützlich, wenn er einen realistischen Fehler erkennen kann.

1. Projektregeln, `git status`, Branch und laufende Tests prüfen. Parallele Arbeit schützen.
2. Kleinste Änderung, Invariante, Akzeptanzkriterien und Gegenbeispiel festhalten.
3. Echte Produktpfade mit **Muss-bestehen-**, **Muss-fehlschlagen-** und ggf. **Unbekannt-/Fehlerfall** prüfen.
4. In einer wegwerfbaren Arbeitskopie einen plausiblen Fehler absichtlich einführen. Prüfen, ob der passende Test reagiert. Keine Mutationsprobe auf Produktivdaten.
5. Zuerst gezielte Tests, danach geeignete Regressionen auf einer unveränderten Revision. Exit-Status und PASS/FAIL/SKIPPED-Zahlen sichern.
6. Ursprünglichen Fehler und unabhängige Fälle erneut prüfen. Leeres Fehlerlog nicht als Erfolg werten.
7. Diff, Dokumentation, Geheimnisse und generierte Dateien prüfen. Exakte Pfade stagen und kleine nachvollziehbare Commits erstellen. Keine pauschalen Bereinigungen, destruktiven Resets oder Force-Pushes ohne ausdrückliche Freigabe.
8. Nicht ausführbare Tests als NOT RUN dokumentieren, nicht als bestanden.

## Abschluss
- Änderung und Revision:
- Positiv- / Negativprüfungen:
- Regression:
- Übersprungen / nicht ausgeführt:
- Offene Unsicherheiten:

## License / Lizenz
MIT; see repository LICENSE. Generic community edition; not a copy of private project instructions.
