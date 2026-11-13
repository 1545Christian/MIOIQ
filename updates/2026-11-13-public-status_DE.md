# MIOIQ — öffentliches Engineering-Dokumentationsupdate (13. November 2026)

English: [English version](2026-11-13-public-status.md)

Dieses Update erweitert die öffentliche Zusammenfassung der in den Release-Notizen bis v90.8.5.23 R3 dokumentierten technischen Arbeiten. Es ist ein Dokumentationsupdate, keine Ankündigung eines neuen Anwendungsreleases und keine neue Produktabnahme.

## In den Release-Notizen dokumentierte Arbeiten

- Research- und Paper-Abläufe sind über einen gemeinsamen, versionierten Ausführungsvertrag mit Kompatibilitätsprüfungen abgestimmt.
- Historische Positions- und Fill-Datensätze werden vor ihrer Verwendung im Research stärker normalisiert und auf Konsistenz geprüft.
- Zustandsänderungen sind bei unterbrochenen Aktivierungen besser durch Wiederherstellungs- und Rollback-Schutz abgesichert.
- Paper-, Shadow-, Watch- und Referenzabläufe sind klarer getrennt und zuordenbar.
- Paper- und Watch-Metriken beruhen auf konsistenten Snapshots; offene Positionen sind von realisierten Ergebnissen getrennt.
- Unvollständige oder inaktive Runtime-Zustände werden als Warnungen angezeigt; Release-Artefakte erhalten vor Updates stärkere Integritätsprüfungen.
- Neue Research-Kandidaten bleiben vom aktiven simulierten Ablauf getrennt und werden nicht automatisch übernommen.

## Umfang und Grenzen

Diese Punkte fassen bestehende Release-Dokumentation zusammen; sie melden keine neue Codeänderung am 13. November. Sie belegen weder, dass alle Änderungen in einem laufenden Dienst geladen oder vollständig abgenommen sind, noch Profitabilität oder Live-Bereitschaft. Für dieses Dokumentationsupdate wurden keine neuen Anwendungstests, Provideranfragen, Datenbankänderungen oder Runtime-Aktionen ausgeführt.

Siehe [Engineering-Changelog](../CHANGELOG_DE.md) · [aktueller Status](../CURRENT_STATUS_DE.md) · [Prüfgrenzen](../docs/verification/TEST_RESULTS_DE.md).

Nur Research und Engineering; keine Trading-Signale oder Anlageberatung.
