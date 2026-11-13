# MIOIQ

**Evidence-Driven Quant Intelligence**  
**AI • Quant Research • Trading Systems**

MIOIQ ist ein unabhängiges Research- und Engineering-Projekt rund um AI-gestützte Quant-Research, Market Intelligence, evidenzbasiertes Learning und kontrollierte Research-to-Execution-Workflows.

English: [README.md](README.md)<br>
Aktueller Status: [CURRENT_STATUS_DE.md](CURRENT_STATUS_DE.md)<br>
Neuestes dokumentiertes Engineering-Update: [13. November 2026](updates/2026-11-13-public-status_DE.md) · [English](updates/2026-11-13-public-status.md)<br>
Engineering-Changelog: [Deutsch](CHANGELOG_DE.md) · [English](CHANGELOG.md)<br>
Telegram: https://t.me/+BXzjABr9iQpjMTgy<br>
Unterstützen: [GitHub Sponsors](https://github.com/sponsors/1545Christian) · [Ko-fi](https://ko-fi.com/mioiq)<br>
Neu hier? [Hier anfangen](docs/START_HERE_DE.md) · [Architektur](docs/project/ARCHITECTURE_OVERVIEW_DE.md) · [Dokumentationsübersicht](docs/README_DE.md)

> **Hinweis zur Umbenennung:** AlgoSphere heißt jetzt **MIOIQ**. Es ist dasselbe fortlaufende Projekt mit derselben Research-Historie und Evidence-Basis. Historische Dateien und Screenshots können den früheren Namen weiterhin tragen, wenn das für Provenienz notwendig ist.

> **Hinweis zum öffentlichen Repository:** Dieses Repository dokumentiert das Projekt und ausgewählte Evidence. Es ist kein Download der privaten MIOIQ-Trading-Anwendung.

## Was du hier mitnehmen kannst

Wenn du mit KI entwickelst oder quantitative Forschung beurteilen möchtest, kannst du MIOIQ als dokumentierte Fallstudie nutzen:

- Sieh nach, wie Entwicklungsaussagen anhand von Belegen geprüft und abgeschlossene Prüfungen von offenen Fragen getrennt werden.
- Erfahre, warum simulierte Ergebnisse, Handelskosten und negative Befunde bei der Beurteilung von Research-Aussagen wichtig sind.
- Verfolge praktische Erfahrungen aus der KI-gestützten Softwareentwicklung, ohne Zugang zur privaten Anwendung zu benötigen.

Beginne mit dem [Einstieg](docs/START_HERE_DE.md) und vergleiche das [neueste dokumentierte Engineering-Update](updates/2026-11-13-public-status_DE.md) mit den [aktuellen Grenzen](CURRENT_STATUS_DE.md). Die öffentliche Dokumentation ist kostenlos lesbar. Auf [Ko-fi](https://ko-fi.com/mioiq) kannst du kürzere Research-Updates verfolgen und die Entwicklung, Tests und verständlichere Dokumentation freiwillig unterstützen.

Die Anwendung bleibt privat; einen öffentlichen Download oder eine offene Demo gibt es nicht. Die Inhalte belegen keinen profitablen Trading-Vorteil und bieten keine Trading-Signale.

## Überblick

MIOIQ verbindet quantitative Marktanalyse, Market-State- und Regime-Research, Rule- und ML-Validierung, evidence-verknüpfte Decision → Outcome → Learning-Workflows, externe AI-gestützte Analyse, Paper-/Shadow-Ausführung, Lifecycle-Governance und spätere Demo-/Packaging-/Release-Arbeit.

Im Mittelpunkt stehen Reproduzierbarkeit, kausale Auswertung, klare Lineage und der Erhalt positiver wie negativer Evidence.

## Wohin sich MIOIQ entwickeln soll

MIOIQ wird zu einem konfigurierbaren quantitativen Research- und Trading-Analyse-System entwickelt, das ein breites Marktuniversum untersuchen soll, ausgehend von Krypto und mit ausgewählten aktien- und rohstoffbezogenen Derivaten im Research. Konfiguration oder Datenverfügbarkeit beweisen dabei keine vollständige Handelsberechtigung oder Abnahme.

Das Ziel ist nicht, ein Modell oder eine Strategie auf jeden Markt zu zwingen. Das System soll anhand messbarer Evidence lernen:

- welche Klassen von Ansätzen unter unterschiedlichen Marktbedingungen funktionieren
- wann eine Rule-Strategie stärker ist als ML
- wann ein Modell revalidiert werden sollte
- wann eine Strategie im Research bleiben muss
- und wann **NO_TRADE** die bessere Entscheidung ist

Research, Validierung und Evidence-Handling sollen stärker automatisiert werden, während Promotion, Execution-Berechtigungen und jede spätere Echtgeld-Nutzung ausdrücklich geregelt bleiben.

Exakte private Strategielogik, Modellinternas und Execution-Regeln werden bewusst nicht veröffentlicht.

## Research-Lifecycle

HYPOTHESIS → QUICK → ROBUST_OOS → CHALLENGER → PAPER → CHAMPION

Ein neueres Modell wird nicht allein deshalb aktiv, weil es neuer ist. Promotion soll von reproduzierbarer Evidence und kontrolliertem Vergleich abhängen.

## Neu dokumentierte technische Updates

Öffentliche Release-Notizen bis v90.8.5.23 R3 beschreiben:

- einen gemeinsamen, versionierten Vertrag zur Abstimmung von Research-Auswertung und Paper-Ausführung;
- stärkere Konsistenzprüfungen für normalisierte historische Positions- und Fill-Datensätze;
- Wiederherstellungs- und Rollback-Schutz bei unterbrochenen Zustandsänderungen;
- klarere Trennung und Zuordnung von Paper-, Shadow-, Watch- und Referenzabläufen;
- konsistente Paper-/Watch-Metrik-Snapshots, die offene von realisierten Ergebnissen trennen;
- sichtbare Warnungen bei unvollständigem oder inaktivem Runtime-Status und stärkere Integritätsprüfungen für Release-Artefakte;
- einen getrennten Research-Kandidatenpfad ohne automatische Übernahme.

Das ist eine Zusammenfassung der Release-Dokumentation und keine neue Quellen- oder Runtime-Abnahme. Profitabilität und Live-Bereitschaft werden dadurch nicht belegt.

## Aktuell geprüfter Stand

| Bereich | Aktueller Stand |
|---|---|
| Research & Engineering | Aktiv; fokussierte Korrekturen an Research-Eingaben geprüft |
| Paper / Shadow | Quellenpfade vorhanden; aktuelle Gesamtabnahme offen |
| Paper-V2-/Learning-Pfad | Learning-Consumer vorhanden; kausaler wirtschaftlicher Uplift nicht bewiesen |
| Evidence-/Learning-Pfad | Verknüpfung weiter verbessert; natürliche wirtschaftliche Wirkung bleibt offen |
| Historische Performance-Reconciliation | Historische Interpretation reconciled; kein aktueller Profit-Claim |
| Externe AI-Analyse | Aktueller Request-/Validierungs-Code geprüft; wirtschaftlicher Nutzen unbewiesen |
| Demo Invite + Registrierung | Begrenzter Pfad früher nachgewiesen |
| One-Session-Produkt-Parität | **Offen** |
| Vollständige aktuelle WebUI-Abnahme | **Offen** |
| Research Storage | Keine neue physische Größenprüfung; Shrink bleibt offen |
| Multi-Venue-Kostenwahrheit | Aktueller Vertrag weiter; vollständige natürliche Kostentruth offen |
| Öffentliche Anwendung / offene Demo | **Nicht verfügbar; Anwendung bleibt privat** |
| Demo / Testnet Execution E2E | **Nicht bewiesen** |
| Release / Distribution | **Offen** |
| Live-Trading | In aktueller Konfiguration deaktiviert |
| Echtgeldnutzung | In aktueller Konfiguration deaktiviert |
| Training | In aktueller Konfiguration deaktiviert |
| Automatische Promotion | Keine neue Promotion behauptet |

Details: [CURRENT_STATUS_DE.md](CURRENT_STATUS_DE.md).

## Evidence und Transparenz

MIOIQ veröffentlicht ausgewählte geprüfte Projektstände, Research-Zusammenfassungen, Verifikationsergebnisse, Evidence, Entwicklungshistorie und bekannte Grenzen.

Negative Ergebnisse bleiben sichtbar. Technischer Abschluss ist kein Beweis für Modellqualität, Profitabilität oder Live-Readiness.

## MIOIQ unterstützen

Wenn du die unabhängige Research- und Engineering-Arbeit unterstützen möchtest, kannst du das freiwillig über [GitHub Sponsors](https://github.com/sponsors/1545Christian) oder [Ko-fi](https://ko-fi.com/mioiq) tun. Beiträge helfen, Entwicklungszeit, Testinfrastruktur und öffentliche Dokumentation zu finanzieren. Unterstützung ist keine Investition und bietet weder Eigentum noch Rückzahlung, finanzielle Erträge, Trading-Signale, Anlageberatung oder garantierte Ergebnisse. Die MIOIQ-Anwendung bleibt privat; dieses Repository veröffentlicht Dokumentation und ausgewählte Evidence.

## Öffentlich / privat

Dieses Repository ist die **öffentliche Dokumentations- und Evidence-Schicht** von MIOIQ.

Nicht enthalten sind privater Anwendungscode, Zugangsdaten, Kontokonfiguration, private Marktdatenbanken, private Model Bundles, proprietäre Strategieparameter, exakte Schwellen, Feature-/Label-Definitionen, Scoring-Logik, private Prompts, Execution-Formeln, Venue-Routing oder andere rekonstruktionssensitive Implementierungsdetails.

Eine öffentliche MIOIQ-Anwendung wird derzeit nicht über dieses Repository zum Download angeboten.

Siehe [Umfang des öffentlichen Repositorys](docs/project/PUBLIC_REPOSITORY_SCOPE_DE.md) und [Lizenzierung](docs/legal/LICENSING_DE.md).

## Dokumentation

- [Hier anfangen](docs/START_HERE_DE.md)
- [Architektur](docs/project/ARCHITECTURE_OVERVIEW_DE.md)
- [Projektrichtung](docs/project/PROJECT_DIRECTION_DE.md)
- [Aktueller Status](CURRENT_STATUS_DE.md)
- [Engineering-Changelog](CHANGELOG_DE.md)
- [Update vom 12. November](updates/2026-11-12-public-status_DE.md)
- [Update vom 3. November](updates/2026-11-03-public-status_DE.md)
- [Roadmap](docs/progress/ROADMAP_DE.md)
- [Dokumentierte Arbeiten](docs/progress/COMPLETED_WORK_DE.md)
- [FAQ](docs/FAQ_DE.md)
- [Glossar](docs/GLOSSARY_DE.md)
- [Verifikation](docs/verification/TEST_RESULTS_DE.md)

## Öffentliche Updates

Kürzere Entwicklungs- und Research-Updates erscheinen auf Telegram:

https://t.me/+BXzjABr9iQpjMTgy

## Disclaimer

MIOIQ ist ein Research- und Engineering-Projekt. Nichts in diesem Repository ist Finanz- oder Anlageberatung. Krypto- und Derivatehandel sind mit erheblichen Risiken verbunden. Historische, simulierte oder Paper-Ergebnisse garantieren keine zukünftigen Ergebnisse.
