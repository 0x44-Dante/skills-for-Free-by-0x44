---
name: evidence-discipline
description: Bei beweisdisziplin in Coding-Agent-Workflows verwenden.
---
# Beweisdisziplin

Technische Aussagen dürfen nicht weiter reichen als ihre Belege.

## Verfahren
1. **Beobachtet:** exakte Eingaben, Befehle, Quellrevision, Umgebung, Datum, Ausgaben, Exit-Code und Artefaktpfade festhalten. Nicht ausgeführte Prüfungen als NOT RUN kennzeichnen.
2. **Erklärt:** nur belegte Mechanismen mit Quellfundstelle benennen; sonst als Hypothese markieren.
3. **Behauptet:** eine begrenzte Schlussfolgerung formulieren; unter **Nicht behauptet** wichtige ungeprüfte Nachbaraussagen nennen.
4. Vor dem Test die widerlegende Gegenprobe definieren; nach Möglichkeit positive und negative Kontrollen ausführen.
5. PASS, FAIL, SKIPPED, ERROR, INDETERMINATE und NOT RUN unterscheiden. Ausbleibende Fehler sind kein Erfolg.
6. Nach einem Fix den ursprünglichen Reproduzierer und unabhängige Kontrollen erneut prüfen. Weniger Fehlermeldungen beweisen keine vollständige Lösung.
7. Ergebnisse an exakte Revision, Eingaben und Umgebung binden. Alte Protokolle erhalten, datierte Korrekturen anhängen.
8. Keine erfundenen Läufe, Benchmarks, Ursachen oder Sicherheitsaussagen.

## Bericht
- Beobachtet:
- Erklärt (geprüft / Hypothese):
- Gegenprobe:
- Behauptet:
- Nicht behauptet:
- Nächster entscheidender Test:

## License / Lizenz
MIT; see repository LICENSE. Generic community edition; not a copy of private project instructions.
