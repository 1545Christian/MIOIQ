# MIOIQ — öffentliches Engineering-Dokumentationsupdate (12. November 2026)

English: [English version](2026-11-12-public-status.md)

Dieses begrenzte Dokumentationsupdate fasst dokumentierte technische Änderungen aus den Releases v90.8.5.17 bis v90.8.5.23 R3 zusammen. Es ist kein neues Anwendungsrelease, keine vollständige Runtime-Prüfung und keine wirtschaftliche Bewertung.

## Neu zusammengefasste technische Hinweise

- Research-Auswertung und Paper-Abläufe nutzen einen gemeinsamen, versionierten Ausführungsvertrag mit Kompatibilitätsprüfungen.
- Historische Positions- und Fill-Datensätze werden vor der Normalisierung stärker auf Konsistenz geprüft.
- Paper- und Watch-Metriken werden aus konsistenten Snapshots abgeleitet; offene Positionen sind von realisierten Ergebnissen getrennt.
- Wiederherstellungs- und Rollback-Schutzmaßnahmen sichern unterbrochene Zustandsänderungen ab; Runtime-Updates werden strenger validiert.
- Paper-, Shadow-, Watch- und Referenzabläufe bleiben separat zuordenbar.
- Unvollständige oder inaktive Runtime-Zustände werden als Warnungen angezeigt.
- Release-Pakete erhalten vor dem Einspielen von Updates stärkere Integritätsprüfungen.

## Nachweis- und Geheimhaltungsgrenzen

Diese Punkte fassen die öffentlichen Release-Dokumente zusammen. Sie belegen nicht, dass jede Änderung in einem laufenden Dienst geladen oder vollständig abgenommen wurde. Profitabilität, Live-Bereitschaft oder eine aktuelle Runtime-Abnahme werden nicht behauptet. Private Strategien, Parameter, Zugangsdaten, Kontodetails, lokale Pfade, interne Kennungen und private Testfingerprints bleiben ausgeschlossen.

Siehe [Engineering-Changelog](../CHANGELOG_DE.md) · [aktueller Status](../CURRENT_STATUS_DE.md) · [Prüfgrenzen](../docs/verification/TEST_RESULTS_DE.md).

Nur Research und Engineering; keine Trading-Signale oder Anlageberatung.
