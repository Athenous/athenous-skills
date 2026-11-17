---
name: roas-roi-analysis
description: Evaluate advertising return using revenue, margin and cost consistently.
---

# ROAS and ROI Analyst

## Purpose

Evaluate advertising return using revenue, margin and cost consistently.

## Use this Skill when

Use to analyze marketing outcomes or define measurement. Confirm the reporting period, business objective and metric definitions before interpreting results.

## Required context

- spend
- attributed revenue
- gross margin
- fees
- agency/production costs
- refunds
- attribution window
- incrementality evidence
- currency

If evidence is incomplete, provide a scoped analysis and list what cannot be concluded. Never fabricate metrics, benchmarks or causal explanations.

## Specialized workflow

1. Reconcile periods and currency
2. calculate platform and blended ROAS
3. calculate contribution after variable costs
4. calculate ROI with explicit cost scope
5. derive break-even ROAS from margin
6. sensitivity-test attribution and incrementality
7. state decision implications.

## Deliverables

- Formula sheet
- ROAS/ROI comparison
- break-even threshold
- scenarios
- data gaps
- scale/hold/reduce recommendation.

## Quality gates

- Define formulas, denominators, units, time zones and attribution windows.
- Compare like-for-like periods, cohorts and segments.
- Distinguish platform attribution, blended business outcomes and causal incrementality.
- Report missingness, tracking changes and uncertainty prominently.
- Tie recommendations to a decision, not just a metric movement.



## Ready-to-use workflow

### Copy/paste prompt

```text
Apply roas-roi-analysis to [website/brand/client]. Objective: [business outcome]. Audience/market: [details]. Period/scope: [dates and channels]. Inputs: [analytics, exports, URLs, content]. Constraints: [brand, legal, budget]. Check: spend; attributed revenue; gross margin; fees; agency/production costs; refunds; attribution window; incrementality evidence; currency. Validate evidence and definitions; ask one critical question only if needed. Return complete deliverables with transparent assumptions and actionable priorities.
```

### Execution checklist

1. Confirm site/brand/client, target audience, objective, scope, date range and desired decision.
2. Inventory sources and validate freshness, coverage, definitions, language/market and any sampling limitations.
3. Apply the specialized workflow above. Support claims with supplied data or linked evidence; separate fact from inference.
4. Prioritize actions by business relevance, confidence, effort and risk; state dependencies and what to test next.
5. Deliver implementation-ready recommendations or copy, plus measurement and review criteria.

### Output contract

Lead with the most important conclusion. Include:

- **Formula sheet:** concrete finding or asset, evidence and next action.
- **ROAS/ROI comparison:** concrete finding or asset, evidence and next action.
- **break-even threshold:** concrete finding or asset, evidence and next action.
- **scenarios:** concrete finding or asset, evidence and next action.
- **data gaps:** concrete finding or asset, evidence and next action.
- **scale/hold/reduce recommendation.:** concrete finding or asset, evidence and next action.

Also state scope, source links/data coverage, assumptions, limitations, and a prioritized next-step list. Do not invent search volume, rankings, sentiment, reach, revenue or performance. Mark unknowns **Not provided**.

### Example invocation

```text
Run roas-roi-analysis for [brand/site] targeting [audience/market]. Goal: [goal]. Analyze [provided sources/data] for [period]. Return the full deliverables, evidence behind each finding, quick wins, longer-term actions and KPIs.
```

### Quality check

- Define formulas, denominators, units, time zones and attribution windows.
- Compare like-for-like periods, cohorts and segments.
- Distinguish platform attribution, blended business outcomes and causal incrementality.
- Report missingness, tracking changes and uncertainty prominently.
- Tie recommendations to a decision, not just a metric movement.

## Athenous MCP usage

MCP is optional. If connected, discover actual reporting and analytics tools and exact schemas at runtime. Use only authorized workspaces and verified data fields; never assume metrics or integrations exist. Keep client data isolated. If a data source is unavailable, use supplied exports and disclose the gap.

## Safety

Use aggregate data where possible and protect personal information. Do not expose customer-level records unnecessarily. Analysis does not authorize budget or campaign edits; obtain explicit confirmation before consequential writes and never claim success without tool confirmation.
