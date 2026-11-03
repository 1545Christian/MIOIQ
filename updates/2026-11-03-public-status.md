# MIOIQ — candidate validation, modeled costs and evidence preservation (November 3, 2026)

Deutsch: [Deutsche Fassung](2026-11-03-public-status_DE.md)

This bounded review follows the [November 2 update](2026-11-02-public-status.md). It reconciles selected current source paths and their callers/consumers with the public record. It is not a new application release, a full acceptance test or an economic evaluation.

## Newly documented source progress

- **Local candidate checks:** the reviewed Paper path distinguishes a proposed analysis candidate from an admitted decision. Local calculations and evidence checks can reject incomplete or unsupported candidates before publication and recheck eligibility at entry. Target payoff and statistical expected return remain different quantities.
- **Additional AI analysis:** the private implementation includes a Gemini analysis path. The current code checks scenario-based arithmetic against modeled costs and the executable entry basis. Scenario probabilities remain model estimates; internally consistent arithmetic does not establish calibrated probabilities or a profitable edge.
- **Costs and presentation:** scoped changes address cost attribution, funding direction, holding horizon and the separation of costs already represented in a quote from additional modeled charges. Trade presentation distinguishes Paper-model results from an actual account settlement. These findings do not establish complete natural cost evidence for every historical trade or full browser acceptance.
- **Storage:** current snapshot writers and readers support shared stored content with integrity checks. Scoped migration receipts report preservation of referenced original content. Logical reuse and internally reclaimable space are not proof that the database file has physically become smaller.
- **Recovery:** source work strengthens cooperative maintenance and state-preserving handoffs. Reported recovery checks concern specific protected states; they do not prove every service is currently loaded or all recovery paths accepted.
- **Public export:** the local documentation exporter now separates public fields from private working metadata and requires review bound to the exact proposed output. Automated checks supplement content review; this does not claim erasure of previously exposed historical material.

## What must remain qualified

Focused engineering receipts report regression and scoped integration checks. This documentation review did not independently rerun the private application suite, make provider requests, restart services, change the database or activate trading.

Some reviewed repairs are still awaiting completed runtime adoption or a complete new request-to-storage outcome. Earlier captured runtime evidence does not prove a later source change is loaded. Ongoing work must not be described as a completed product release.

A correct protection calculation does not guarantee a non-negative exit: an executable price can move beyond the protection level. Reaching a forecast target does not by itself establish a profitable complete plan. Full expected outcomes, natural costs, independent comparison and later learning benefit remain separate requirements.

## Access and evidence boundary

The application remains private; this documentation update introduces no public download or open demo. It grants no live execution, capital use, training or model promotion. No profitability or live-readiness claim follows.

Private code, strategies, parameters, prompts, model settings, budgets, account details, local paths, internal identifiers and exact private test fingerprints are excluded. Earlier dated updates retain their historical scope.

[Current status](../CURRENT_STATUS.md) · [Verification limits](../docs/verification/TEST_RESULTS.md) · [Open acceptance criteria](../docs/progress/ROADMAP.md)

Research and engineering only; no trading signals or investment advice.
