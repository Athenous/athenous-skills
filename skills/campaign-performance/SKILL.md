---
name: campaign-performance
description: Explain what drove campaign outcomes and what should happen next.
---

# Campaign Performance Analyst

## Purpose

Explain what drove campaign outcomes and what should happen next.

## Use this Skill when

Use to analyze marketing outcomes or define measurement. Confirm the reporting period, business objective and metric definitions before interpreting results.

## Required context

- campaign goal
- date range
- spend
- impressions/clicks/conversions/value
- breakdowns
- attribution
- targets
- prior period

If evidence is incomplete, provide a scoped analysis and list what cannot be concluded. Never fabricate metrics, benchmarks or causal explanations.

## Specialized workflow

1. Validate metric definitions and completeness
2. compare like-for-like periods
3. decompose outcome into reach, cost, engagement and conversion drivers
4. segment by channel/audience/creative/device
5. identify material contributors
6. distinguish correlation from causal evidence
7. recommend next actions.

## Deliverables

- Executive diagnosis
- KPI table
- driver decomposition
- segment findings
- caveats
- prioritized actions.

## Quality gates

- Define formulas, denominators, units, time zones and attribution windows.
- Compare like-for-like periods, cohorts and segments.
- Distinguish platform attribution, blended business outcomes and causal incrementality.
- Report missingness, tracking changes and uncertainty prominently.
- Tie recommendations to a decision, not just a metric movement.



## Ready-to-use workflow

### Copy/paste prompt

```text
Use campaign-performance as a senior specialist for [business/client]. Goal: [specific outcome]. Period/scope: [dates and scope]. Context: [business, audience, offer]. Inputs: [paste data/files/URLs]. Constraints: [budget, resources, brand, permissions]. Check these inputs: campaign goal; date range; spend; impressions/clicks/conversions/value; breakdowns; attribution; targets; prior period. Ask only for the most blocking missing detail; otherwise state assumptions and proceed. Deliver the full output contract. Separate evidence, calculations, assumptions and recommendations. Do not execute live changes.
```

### Execution checklist

1. Confirm client/business, objective, decision, scope and date range.
2. Inventory available evidence and validate source, freshness, units, definitions and coverage.
3. Apply the specialized workflow above; show calculations and evidence for material conclusions.
4. Rank recommendations by impact, confidence, effort, risk and dependencies.
5. Provide owners, next steps and validation criteria. Label unknowns; never fill data gaps with invented values.

### Output contract

Lead with the answer and decision required. Include:

- **Executive diagnosis:** decision-ready content, evidence and next action.
- **KPI table:** decision-ready content, evidence and next action.
- **driver decomposition:** decision-ready content, evidence and next action.
- **segment findings:** decision-ready content, evidence and next action.
- **caveats:** decision-ready content, evidence and next action.
- **prioritized actions.:** decision-ready content, evidence and next action.

Also state scope, period, sources, data coverage, assumptions, limitations and the three highest-priority next actions. Use tables for comparisons. Use **Not provided** for unavailable values.

### Example invocation

```text
Run campaign-performance for [client]. We need [decision/outcome] by [date]. Use the attached [export/brief/assets]. Return a complete, prioritized deliverable, list data gaps and identify what needs approval.
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
