# MIOIQ — public engineering documentation update (November 13, 2026)

Deutsch: [Deutsche Fassung](2026-11-13-public-status_DE.md)

This update expands the public summary of engineering work documented in release notes through v90.8.5.23 R3. It is a documentation update, not an announcement of a new application release or a new product-acceptance review.

## Engineering work documented in the release notes

- Research and Paper workflows are aligned through a shared, versioned execution contract with compatibility checks.
- Historical position and fill records receive stronger normalization and consistency checks before use in research.
- State changes have stronger recovery and rollback safeguards when an activation is interrupted.
- Paper, Shadow, Watch and reference workflows are more clearly separated and attributable.
- Paper and Watch metrics are derived from consistent snapshots, with open positions distinguished from realized results.
- Incomplete or inactive runtime states are surfaced as warnings; release artifacts receive stronger integrity checks before updates are applied.
- New research candidates remain separate from the active simulated workflow and are not automatically promoted.

## Scope and limits

These points summarize existing release documentation; they do not announce a new code change on November 13. They do not establish that every change is loaded or fully accepted in a running service, nor do they establish profitability or live readiness. No new application tests, provider requests, database changes or runtime operations were performed for this documentation update.

See the [engineering changelog](../CHANGELOG.md) · [current status](../CURRENT_STATUS.md) · [verification limits](../docs/verification/TEST_RESULTS.md).

Research and engineering only; no trading signals or investment advice.
