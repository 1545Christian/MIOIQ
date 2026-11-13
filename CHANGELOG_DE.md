# MIOIQ Engineering-Changelog

## Dokumentierte technische Updates — v90.8.5.17 bis v90.8.5.23 R3

- Research- und Paper-Abläufe wurden über einen gemeinsamen, versionierten Ausführungsvertrag abgestimmt; Prüfungen erkennen inkompatible Artefakte.
- Historische Positions- und Fill-Datensätze werden vor ihrer Verwendung im Research stärker normalisiert und auf Konsistenz geprüft.
- Unterbrochene Zustandsänderungen sind besser durch Wiederherstellungs- und Rollback-Schutz abgesichert.
- Paper-, Shadow-, Watch- und Referenzabläufe sind klarer getrennt und zuordenbar.
- Paper- und Watch-Metriken beruhen auf konsistenten Snapshots; offene Positionen sind von realisierten Ergebnissen getrennt.
- Unvollständige oder inaktive Runtime-Zustände werden als Warnungen statt als erfolgreiche Integritätsprüfungen angezeigt.
- Release-Artefakte erhalten vor dem Einspielen von Updates stärkere Integritätsprüfungen.
- Neue Research-Kandidaten bleiben vom aktiven simulierten Ablauf getrennt und werden nicht automatisch übernommen.

Diese Einträge fassen dokumentierte technische Arbeiten zusammen. Sie belegen weder, dass alle Änderungen in einem laufenden Dienst geladen oder vollständig abgenommen sind, noch Profitabilität oder Live-Bereitschaft.
