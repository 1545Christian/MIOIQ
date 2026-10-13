# Sicherheit und Veröffentlichungsgrenzen

English: [SECURITY.md](SECURITY.md)

## Öffentlich und privat

MIOIQ veröffentlicht ausgewählte Dokumentation, Evidence und kleine Verifikationswerkzeuge — nicht den privaten Anwendungs-/Runtime-Code, Zugangsdaten, API-Keys, Wallet-/Exchange-Kontodaten, private Datenbanken und Logs, Modell-Bundles, Strategieparameter, exakte Schwellen, Scoring-Logik, Execution-Regeln oder interne Infrastruktur.

## Öffentliche Prüfungen

Das Repository enthält `tools/verify_public_export.py`.

- **Repository-Checks:** prüfen öffentliche Dateigrenzen, gängige Secret-/Privacy-Muster, interne Markdown-Links, Sprachverweise und Struktur.
- **Staged-Export-Checks:** prüfen zusätzlich SHA-256-Manifest und exakte Bytes eines konkreten Exportstands.

Das historische Manifest `evidence/EXPORT_CONTENTS.md` ist kein dauerhafter Hash-Lock für alle späteren Änderungen. Automatisierte Prüfungen können Risiken reduzieren, aber menschliche Prüfung nicht ersetzen.

## Verantwortungsvoller Umgang mit Sicherheitsproblemen

Keine Tokens, privaten Schlüssel, Accountdaten, Strategie-/Modelldetails oder ausnutzbaren Schwachstellen öffentlich posten.

Für normale Dokumentations-/Tooling-Probleme die GitHub-Issue-Formulare nutzen. Für vertrauliche Sicherheitsmeldungen GitHub Private Vulnerability Reporting verwenden, **sofern** es für das Repository aktiviert ist. Falls nicht, keine sensiblen Details öffentlich veröffentlichen.

## Trading- und Kontosicherheit

Die öffentlichen Dateien benötigen keine Exchange-Credentials oder ein Echtgeldkonto. Ein künftiger Demo-/Client-Release braucht eigene Berechtigungs-, Credential- und Release-Integritätsgrenzen.
