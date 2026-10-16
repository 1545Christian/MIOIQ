# Aktueller öffentlicher Status

Veröffentlichungsstand: **16. Oktober 2026**. Zusammenfassung der zuletzt verfügbaren Belege aus den Projektbereichen. Vollständige Runtime- und Produktabnahme erfordert weitere natürliche Nachweise.

English: [CURRENT_STATUS.md](CURRENT_STATUS.md)

> **Namenswechsel:** AlgoSphere heißt jetzt **MIOIQ**. Historische technische Bezeichner bleiben erhalten, wenn Kompatibilität oder Provenienz dies erfordern.

## Betriebs- und Sicherheitsgrenzen

- Research & Engineering: **aktiv**
- Paper-/Shadow-Research: **aktiv / fail-closed**
- Demo-Einladung und Registrierung: **zuvor im begrenzten Umfang nachgewiesen**
- Vollständige One-Session-Produktparität: **offen**
- Runtime-Abnahme: **teilweise / begrenzt**
- Vollständige aktuelle WebUI-Abnahme: **offen**
- Connected Demo/Testnet Execution E2E: **nicht bewiesen**
- Release / Distribution: **offen**
- Live-Trading: **deaktiviert**
- Echtgeld: **0**
- Automatische Promotion: **deaktiviert**

## Veränderungen seit dem 12. Oktober

Der aktuelle Master-Tracker wurde am 15. Oktober 2026 aktualisiert. Runtime-/Recovery-, Paper-V2-, Canonical-Learning- und Produktabnahmen bleiben in Prüfung. Multi-Market-/Multi-Asset-Planung ist spezifiziert, aber zurückgestellt. Weder kausaler Learning-Uplift noch ein neuer Challenger oder eine vollständige Release-Abnahme werden behauptet.

Siehe [Update vom 16. Oktober](updates/2026-10-16-public-status_DE.md).

## Frühere Oktober-Prüfung

- Ein fokussierter Startup-/Recovery-Preflight hat seinen geprüften Umfang bestanden. Vollständige Runtime-/Recovery-Abnahme steht weiter aus.
- Paper V2 sammelt Decisions; in der zuletzt geprüften No-Setup-Population fehlt weiterhin die neue kanonische Trade-→-Settlement-→-Learning-Kette. Es werden keine Trades erzwungen.
- Canonical Learning hat zusätzliche fokussierte Prüfungen und verknüpfte Settled-Outcome-Evidence. Ein kausaler Vorteil späterer vergleichbarer Entscheidungen nach Kosten ist nicht bewiesen.
- Die neueste begrenzte externe AI-Evidence enthält gültige NO_TRADE-Entscheidungen. Daraus folgt weder Profitabilität noch wirtschaftlicher Uplift.
- Unabhängiger Challenger-Proof, physischer Datenbank-Shrink, WebUI-Abnahme, Connected Demo und Release-Readiness bleiben offen.

Siehe [Update vom 16. Oktober](updates/2026-10-16-public-status_DE.md).

## Fachlich relevante Veränderungen

### Runtime und Execution-Kosten

Der aktuell geprüfte Execution-Cost-Contract ist in einem begrenzten Runtime-Pfad aktiv. Dort ist der ältere feste Kosten-Fallback nicht mehr aktiv.

Das ist **keine** vollständige Kostenwahrheit. Natürliche Forward-Kosten, gültige Labels und eine numerisch bewiesene Expected-Net-Entscheidungsgrenze fehlen weiterhin. Wo Kostenevidence unvollständig ist, bleibt das Verhalten fail-closed.

### WebUI — aktueller Zustand

Neue Browser-Gegenbelege zeigen, dass Positionszeilen während eines Refreshs vorübergehend wechseln und später wieder auftauchen können; im gleichen Bereich wurde Layout-Bewegung beobachtet.

Frühere Prüfungen von Filtern, Pagination und responsiver Ansicht gelten nur für ihren geprüften Umfang. Offen sind atomare Snapshot-/Refresh-Konsistenz, Erhalt von Filter-/Scroll-/Selektionszustand und abschließende Browser-Abnahme des tatsächlich ausgelieferten Builds.

### Decision → Outcome → Learning

Source- und Runtime-Evidence zeigt deutlicher, dass Learning-Informationen in spätere Decision-Kontexte gelangen können.

Nicht bewiesen ist der eigentliche wissenschaftliche Nutzen: ein abgeschlossenes Outcome derselben Identitätskette, das ein Learning-Update erzeugt und eine spätere vergleichbare Entscheidung nach Kosten messbar verbessert.

Allein die Nutzung von Learning-Kontext ist kein Nachweis kausaler Verbesserung.

### Externe AI-Analyse

Der aktuelle Analysepfad besitzt neuere Loaded-/Runtime-Evidence und einen erfolgreichen regulären Provider-Zyklus. Die dort beobachteten Decisions waren NO_TRADE.

Das belegt den Ablauf und ein gültiges Decision-Set, nicht Profitabilität, Trade-Generierung oder bessere Qualität. Outcome, Funnel, Learning und After-Cost-Wirkung bleiben offen.

### Storage und Datenbank

Die Datenbank ist nach früherer logischer Compaction weiter gewachsen. Read-only-Messungen belegen erneutes Wachstum und eine separate langsame Query-Grenze, aber noch nicht den verantwortlichen Writer oder die Ursache.

Physischer Shrink, verlustfreie Reorganisation und Query-Optimierung sind getrennte Aufgaben.

### Codebereinigung und Release

Begrenzte Source-Cleanup-Arbeiten gehen weiter. Nach späteren Source-Änderungen ist das Release-Manifest noch nicht auf dem erforderlichen Stand.

Daher gibt es weder einen globalen Source-Freeze noch Manifest-Parity-PASS oder Release-Abnahme. Codebereinigung ist kein Release-Nachweis.

## Research-Grenzen

Ein vollständig gematchter wirtschaftlicher Vergleich fehlt weiterhin. Die aktuellen A/B/C-Diagnosen beruhen noch nicht auf einer durchgehend identischen Population von Beobachtungen, Targets, Settlements und Kosten.

Daraus folgt weder ein Modell-Sieger noch eine Promotion- oder Profitabilitätsbehauptung.

## Weiterhin nicht bewiesen

- dauerhafter ML-Uplift
- Überlegenheit von V2 gegenüber V1
- kausaler wirtschaftlicher Nutzen des Learning-Loops
- Profitabilität der externen AI-Analyse
- vollständige Execution-Cost-Wahrheit
- vollständige aktuelle WebUI-Abnahme
- dauerhafter physischer DB-Shrink
- reproduzierbare Release-/Update-/Rollback-Abnahme
- Connected Demo/Testnet Execution E2E
- Live-Readiness

## Öffentlich / privat

MIOIQ veröffentlicht Projektrichtung, geprüfte Engineering-Fortschritte, Methodik und ausgewählte Evidence.

Nicht veröffentlicht werden private Strategielogik, exakte Schwellen, private Prompts, interne Owner-/Task-IDs, lokale Pfade, exakte Test-Fingerprints, private Schemas, Accountdaten, Credentials, Venue-Routing-Details oder Implementierungskombinationen, die die Rekonstruktion des privaten Systems erheblich erleichtern würden.

## Sicherheitsgrenze

**LIVE=false · REAL_CAPITAL=0 · automatische Promotion deaktiviert · Connected Demo/Testnet Execution E2E nicht bewiesen.**
