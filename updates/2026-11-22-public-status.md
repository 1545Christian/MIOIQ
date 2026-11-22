# MIOIQ — Public Engineering Update (November 22, 2026)

Deutsch: [Deutsche Version](2026-11-22-public-status_DE.md)

This update summarizes engineering areas visible in the source code at a high level. It avoids private implementation details.

## Areas visible in the code

- Installation and update paths include checks for configuration migration and feature parity.
- Research candidates use distinct lifecycle states and evidence tracking; historical candidates can be marked as superseded.
- Virtual paper observation is modeled separately from live trading.
- WebUI read views use bounded snapshots and integrity checks to identify incomplete or inconsistent data.
- Research and evaluation tools cover additional causal, cost-aware candidate comparisons.

## Limits

These are source-code observations, not claims about a running or loaded runtime. They do not establish complete end-to-end acceptance, profitability, or live readiness. Private strategy details, specific parameters, local paths, and non-public data are not disclosed.

Research and engineering only; no trading signals or investment advice.
