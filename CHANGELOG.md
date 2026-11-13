# MIOIQ Engineering Changelog

## Documented engineering updates — v90.8.5.17 to v90.8.5.23 R3

- Research and Paper workflows were aligned around a shared, versioned execution contract, with checks for incompatible artifacts.
- Historical position and fill records received stronger normalization and consistency checks before use in research.
- Interrupted state changes gained stronger recovery and rollback safeguards.
- Paper, Shadow, Watch and reference workflows are more clearly separated and attributable.
- Paper and Watch metrics are built from consistent snapshots, with open positions distinct from realized results.
- Incomplete or inactive runtime states are surfaced as warnings rather than successful integrity checks.
- Release artifacts receive stronger integrity checks before updates are applied.
- New research candidates remain separate from active simulated workflows and are not automatically promoted.

These notes summarize documented engineering work. They do not establish that every change is loaded or fully accepted in a running service, or that profitability or live readiness has been demonstrated.
