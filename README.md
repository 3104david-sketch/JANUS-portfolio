# JANUS | Evidence-Based Market Intelligence Dashboard

## Overview
JANUS NDX-1 is a market-intelligence and scenario-analysis dashboard that organizes several Nasdaq/QQQ market indicators into an explainable regime assessment. It was built to make complex information easier to interpret, with explicit attention to the reliability and freshness of data.

**Portfolio focus:** AI-assisted software development, data visualization, analytical storytelling, and decision-support design. This is not a marketing campaign platform, trading bot, or investment recommendation.

## What the project demonstrates
- **Data aggregation:** A modular provider architecture draws on market signals such as QQQ trends, volatility, semiconductor relative strength, yields, and dollar strength.
- **Transparent analysis:** Summarizes a market environment as bullish, neutral, or defensive, with an explanation of drivers and conditions that could invalidate the assessment.
- **Scenario communication:** Presents conditional scenarios and model-estimated probabilities to help users understand uncertainty.
- **Data provenance:** Labels live, delayed, fallback, and mock inputs rather than treating them as equivalent.
- **Auditability:** Designed to preserve daily snapshots and score outcomes with rule-based criteria.
- **Product design:** An accessible dashboard presents complex calculations as readable insights.

## Technical stack
- Next.js, React, TypeScript
- Data-provider adapters and a modular scoring pipeline
- SQLite for recorded snapshots
- Recharts for data visualization
- Vitest for automated tests
- AI-assisted development tools used in implementation

## High-level architecture
```text
Market-data providers
        |
        v
Input validation + source/freshness labeling
        |
        v
Signal calculations and regime scoring
        |
        v
Confidence, explanation and scenarios
        |
        v
Dashboard + dated record of assessments
```

## Development status
The private project README documents an NDX-1 dashboard, a mock/demo mode, a data-provider layer with per-series fallbacks, and daily recordkeeping behavior. These are **project-documented features**, not independently verified performance claims.

An underlying breadth signal is identified in the project documentation as a *proxy*, not a fully connected live feed. Mock or fallback data should never be presented as a real market record.

## Why it belongs in an AI marketing portfolio
JANUS shows transferable capabilities relevant to marketing analytics and AI-powered growth operations: combining disparate data sources, communicating uncertainty, translating signals into decisions, and designing dashboards for business users.

## Demonstrations
See [DEMO.md](DEMO.md) for the showcase plan. Any future screenshots should be reviewed to ensure they contain no credentials, private operational information, or misleading performance statistics.

## Security and scope
This public repository is a **documentation-only portfolio showcase**. It does not contain the original JANUS source code, secrets, deployment settings, private history, or a deployable copy of the system. The source project remains private. See [SECURITY.md](SECURITY.md).

## Author
Benjamin Jackson — product direction and AI-assisted application development.
