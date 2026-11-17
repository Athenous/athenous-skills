---
name: conversion-rate-analysis
description: Find conversion friction and quantify funnel improvement opportunities.
---

# Conversion Rate Analyst

## Purpose

Find conversion friction and quantify funnel improvement opportunities.

## Use this Skill when

Use to analyze marketing outcomes or define measurement. Confirm the reporting period, business objective and metric definitions before interpreting results.

## Required context

- event definitions
- sessions/users
- stage counts
- device/source/segment
- period
- tracking
- page/form samples

If evidence is incomplete, provide a scoped analysis and list what cannot be concluded. Never fabricate metrics, benchmarks or causal explanations.

## Specialized workflow

1. Validate event uniqueness and denominators
2. calculate stage conversion and drop-off
3. segment by source/device/cohort
4. inspect journey friction
5. distinguish traffic quality from UX
6. quantify opportunity from observed volume
7. prioritize tests and instrumentation fixes.

## Deliverables

- Funnel table
- segment diagnosis
- opportunity range
- friction hypotheses
- experiment backlog.

## Quality gates

- Define formulas, denominators, units, time zones and attribution windows.
- Compare like-for-like periods, cohorts and segments.
- Distinguish platform attribution, blended business outcomes and causal incrementality.
- Report missingness, tracking changes and uncertainty prominently.
- Tie recommendations to a decision, not just a metric movement.



## Ready-to-use workflow

### Copy/paste prompt

```text
Apply conversion-rate-analysis to [business/client]. Desired outcome: [goal]. Audience: [who will use the result]. Period/scope: [dates]. Context and constraints: [brief]. Evidence: [paste exports, URLs, examples]. Check: event definitions; sessions/users; stage counts; device/source/segment; period; tracking; page/form samples. Ask only one blocking question if necessary; otherwise state assumptions and complete the deliverables. Cite source data where possible and do not invent results.
```

### Execution checklist

1. Confirm the audience, business objective, scope and decision this work should enable.
2. Review supplied evidence; check source, freshness, coverage, definitions and constraints.
3. Execute the specialized workflow above in sequence and show the reasoning behind material choices.
4. Rank outputs by business value, confidence, effort and risk; identify trade-offs and dependencies.
5. Provide a practical handoff: owner, next step, timing and validation measure. Clearly label assumptions and unknowns.

### Output contract

Start with a concise recommendation, followed by:

- **Funnel table:** include a usable artifact, rationale and next action.
- **segment diagnosis:** include a usable artifact, rationale and next action.
- **opportunity range:** include a usable artifact, rationale and next action.
- **friction hypotheses:** include a usable artifact, rationale and next action.
- **experiment backlog.:** include a usable artifact, rationale and next action.

Include scope, sources, assumptions, limitations and next steps. Use structured tables where they improve actionability. Mark missing information **Not provided**; do not fabricate metrics, customer statements or outcomes.

### Example invocation

```text
Use conversion-rate-analysis for [client/project]. The audience is [audience], and the objective is [objective]. Use these materials: [inputs]. Produce the full deliverables in a format I can hand to my team/client, with priorities and open questions.
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
