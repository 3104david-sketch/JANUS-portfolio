# JANUS NDX-1 | Explainable Market Intelligence Dashboard

> **Portfolio case study · Documentation-only · Original source remains private**

JANUS is a decision-support dashboard that combines Nasdaq/QQQ-related signals into transparent market-regime assessments. It focuses on explainable analysis, data freshness, and an auditable record of predictions.

## The problem
Market dashboards can mislead when data inputs differ in quality or conclusions are presented without evidence and uncertainty.

## My contribution
Product direction, workflow and dashboard design, and iterative AI-assisted application development. AI coding assistance was used; this is not a claim that every line was manually written.

## Workflow
1. Collect market inputs through modular data-provider adapters.
2. Label each input as live, delayed, fallback, or mock.
3. Compute six signals and a bullish, neutral, or defensive regime score.
4. Present evidence, confidence context, scenarios, and invalidation conditions.
5. Record qualifying daily snapshots and evaluate outcomes by programmed criteria.

## Architecture and stack
Next.js · React · TypeScript · SQLite · Recharts · Tailwind CSS · Vitest.

Source adapters feed signal calculations and a scoring engine. The dashboard displays the result and its underlying evidence; a SQLite recordkeeper preserves dated assessments.

## Relevance to AI marketing
This work demonstrates data aggregation, analytic storytelling, provenance, and explainable dashboards—skills transferable to marketing intelligence, growth analytics, and business reporting.

## Status and limitations
The private source README describes a v1.2 dashboard with live-data adapters, explicit fallback labeling, and a daily recordkeeper. This public case study does not independently verify deployment or prediction performance.

- Not a trading bot or investment advice.
- The breadth indicator is a labeled proxy.
- Mock and fallback data are not real historical performance.
- No independently verified live performance record is provided here.

## Text-only walkthrough
Read [WORKFLOW.md](WORKFLOW.md) for an explanatory walkthrough and [PROJECT_FACTS.json](PROJECT_FACTS.json) for structured metadata. No screenshots, recordings, interactive demo, or source code are included.

## Privacy and scope
This is a **documentation-only showcase**. The original source, deployments, credentials, and Git history remain private. See [SECURITY.md](SECURITY.md).

## Author
**Benjamin Jackson** — [GitHub](https://github.com/3104david-sketch) · AI-assisted application development and growth-oriented analytics.
