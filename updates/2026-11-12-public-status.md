# MIOIQ — public engineering documentation update (November 12, 2026)

Deutsch: [Deutsche Fassung](2026-11-12-public-status_DE.md)

This bounded documentation update consolidates documented engineering changes from releases v90.8.5.17 through v90.8.5.23 R3. It is not a new application release, a full runtime review or an economic evaluation.

## Newly consolidated engineering notes

- Research evaluation and Paper workflows use a shared, versioned execution contract with compatibility checks.
- Historical position and fill records receive stronger consistency checks before normalization.
- Paper and Watch metrics are derived from consistent snapshots, with open positions distinguished from realized outcomes.
- Recovery and rollback safeguards protect interrupted state changes; runtime updates receive stricter validation.
- Paper, Shadow, Watch and reference workflows are kept separately attributable.
- Incomplete or inactive runtime states are surfaced as warnings.
- Release packages receive stronger integrity checks before updates are applied.

## Evidence and privacy limits

These points summarize the public release documentation; they do not establish that every change is loaded or fully accepted in a running service. No profitability, live readiness or current runtime acceptance is claimed. Private strategies, parameters, credentials, account details, local paths, internal identifiers and private test fingerprints are excluded.

See the [engineering changelog](../CHANGELOG.md) · [current status](../CURRENT_STATUS.md) · [verification limits](../docs/verification/TEST_RESULTS.md).

Research and engineering only; no trading signals or investment advice.
