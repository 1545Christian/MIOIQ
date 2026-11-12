# MIOIQ Engineering Changelog

## Documented engineering updates — v90.8.5.17 to v90.8.5.23 R3

- Aligned research and paper workflows around a shared, versioned execution contract, with checks that reject incompatible artifacts.
- Improved consistency checks for historical position and fill records before they enter normalized research history.
- Rebuilt visible paper and watch metrics from a consistent data snapshot and made open positions distinct from realized results.
- Added recovery and rollback safeguards for interrupted state changes, with stricter validation before runtime changes are accepted.
- Improved separation and traceability across paper, shadow, watch and reference workflows.
- Made incomplete or inactive runtime state visible as a warning instead of presenting it as a successful integrity check.
- Strengthened release-package integrity checks before updates are applied.

These notes describe documented engineering changes. They do not claim that every runtime check has been completed, that live trading is enabled, or that profitability has been demonstrated.
