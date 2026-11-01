# MIOIQ FAQ

Deutsch: [FAQ_DE.md](FAQ_DE.md)

A short, plain-language answer to the questions that come up most often around the project.

## What is MIOIQ?

MIOIQ is an independent AI × Quant research and engineering project for market analysis, starting with crypto and including selected equity- and commodity-linked derivatives in research. This does not establish general instrument coverage or execution permission.

The project explores how market context, rules, machine learning, OpenAI-assisted analysis, canonical memory and Paper/Shadow execution can be combined in a way that is measurable and auditable.

The long-term direction is a configurable research and trading-analysis system that can work across a broad market universe, compare strategies and models, learn from outcomes and improve through evidence-gated revalidation.

It is not presented as a finished trading product.

More detail: [Project Direction](project/PROJECT_DIRECTION.md).

## Is there an MIOIQ download here?

No public application download is currently offered from this repository.

This GitHub repository is the public documentation and evidence layer. It also contains small verification tools for the public export, but not the private trading/runtime application.

See [Public Repository Scope](project/PUBLIC_REPOSITORY_SCOPE.md).

## Is MIOIQ live trading with real money?

No.

The reviewed current configuration disables live execution, real-capital use and training. This is a configuration finding, not an independent account audit or observation of every running process. No new model promotion or release readiness is claimed.

Paper and Shadow paths are used for research and validation.

## Is this a signal service?

No.

The public repository and Telegram channel document research and development progress. They are not a trading-signal service and do not provide investment advice.

## Is the full source code public?

No.

Private application source code, credentials, account configuration, market databases, trained model bundles and proprietary strategy parameters are not published here.

## Is MIOIQ intended to become autonomous?

Increasingly autonomous in research and validation, yes — but not uncontrolled.

The intended loop is:

new evidence → evaluation → learning delta → revalidation → lifecycle decision

The goal is to automate more market analysis, strategy research, ML training and evidence-based adaptation over time while keeping promotion, execution permissions and any future real-capital use explicitly governed.

## Is the system limited to the instruments shown in current reports?

No.

Those instruments are working populations. The long-term direction is a configurable market universe, limited by data quality, compute, liquidity, exchange support and validation quality rather than by a hard-coded small list.

## Does the machine learning already beat the rule-based system?

Not proven.

The historical single-market pilot described in the [September 21 update](../updates/2026-09-21-public-status.md) completed technically but did not beat the preserved Rule baseline and was not promoted. That result is not a new or fully matched current model evaluation.

That negative result is intentionally kept visible.

## What is CURRENT vs CONTEXT_V2?

CURRENT is the control path.

CONTEXT_V2 is a Shadow research variant that can use market-state context and Canonical Learning Delta evidence when evaluating strategy candidates.

The two are kept separate so they can be compared without silently mixing evidence.

## Is CONTEXT_V2 better?

Not proven yet.

There is not enough natural, comparable settled evidence to make that claim.

## What does “Canonical Memory” mean here?

It is the project’s common evidence layer for connecting decisions, trades, outcomes and learning.

The goal is to preserve enough identity and provenance to answer questions such as:

- Which decision produced this trade?
- What market state and strategy were involved?
- What happened after entry?
- What did the system learn from the outcome?
- Did that evidence change later selection?

## What role does OpenAI have?

OpenAI is used as an independent analysis layer inside the AI-only research path.

The model authors the analysis; the application still checks facts, costs, risks and permissions. Those checks can block execution. A model response alone is not execution authorization and does not replace local validation.

OpenAI decision quality and profitability are still not proven.

## Why are failed or negative results published?

Because a research system is not useful if it only preserves good-looking results.

FAILED_OOS, insufficient evidence, degraded ML results and unresolved limitations are part of the project record.

## What is the Demo / Packaging / Release track?

It is a separate workstream for turning selected parts of MIOIQ into a controlled demo/client experience. The reviewed invite/registration path has passed for its scoped flow, but one-session product acceptance and connected Demo end-to-end proof remain open.

Demo does not mean Live.

Release readiness requires separate acceptance of demo isolation, approved model packages, Demo/Testnet execution, installation/update/rollback, credential protection and release integrity. Existing implementation in these areas does not replace acceptance.

## Can I contribute?

Feedback, reproducible bug reports, research questions, relevant papers/methods and documentation corrections are welcome.

Please read [CONTRIBUTING.md](../CONTRIBUTING.md) before opening an issue.

## Where should I start?

- [README](../README.md)
- [Project Direction](project/PROJECT_DIRECTION.md)
- [Current Status](../CURRENT_STATUS.md)
- [Latest Update](../updates/2026-11-01-public-status.md)
- [Roadmap](progress/ROADMAP.md)
- [Evidence Summary](../evidence/EVIDENCE_SUMMARY.md)
