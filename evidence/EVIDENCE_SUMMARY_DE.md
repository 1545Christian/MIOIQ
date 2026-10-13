# Öffentliche Evidence-Übersicht und Register

English: [EVIDENCE_SUMMARY.md](EVIDENCE_SUMMARY.md)

<!-- HUMAN_TEXT_START -->

## Zweck

[REPORTS_PUBLIC_REGISTER.csv](REPORTS_PUBLIC_REGISTER.csv) ist eine bereinigte Bestandsaufnahme öffentlich registrierter Report-Artefakte. Sie enthält neutrale IDs, Kategorien, UTC-Daten, Status und gegebenenfalls Hashes, ohne private Dateinamen, Pfade oder Rohinhalte zu veröffentlichen.

## Kategorien

- **BUILD:** Build-Metadaten.
- **DELIVERY:** Delivery-/Release-Metadaten.
- **QA:** Prüfungs-/Audit-Metadaten.
- **TEST:** Test-Metadaten.
- **OTHER:** weitere registrierte Artefakte.
- **REGISTERED:** im bereinigten Inventar vorhanden; **kein** Test-PASS.
- **HASH_NOT_PUBLISHED:** ein Raw-Hash wird aus Privacy-/Fingerprint-Gründen nicht veröffentlicht.

## Grenzen von SHA-256

Ein SHA-256-Hash hilft, identische Dateien zu vergleichen. Er beweist weder Korrektheit noch erfolgreiche Tests, unabhängige Reproduzierbarkeit oder Eignung für Handelsentscheidungen.

## Verwendung

Neutrale ID, Kategorie, Datum und gegebenenfalls veröffentlichten Hash prüfen. Ein Registereintrag ist **kein** Zertifikat für fertige Features oder bestandene Tests.

<!-- HUMAN_TEXT_END -->

<!-- AUTO_VALUES_START -->
**Integrität des damaligen Exports: verifiziert.** Bereinigter Registerbestand: `4423`; veröffentlichte Hashes: `4422`; `HASH_NOT_PUBLISHED`: `1`.

| Kategorie | Anzahl |
|---|---:|
| BUILD | 17 |
| DELIVERY | 225 |
| QA | 313 |
| TEST | 82 |
| OTHER | 3786 |
| **Gesamt** | **4423** |

Die Anzahl ist weder die Anzahl bestandener Tests noch abgeschlossener Features oder nachgewiesener Verbesserungen.
<!-- AUTO_VALUES_END -->
