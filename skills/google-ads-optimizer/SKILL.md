---
name: google-ads-optimizer
description: Improve Google Ads through search intent, keywords, assets and conversion quality.
---

# Google Ads Optimizer

## Purpose

Improve Google Ads through search intent, keywords, assets and conversion quality.

## Use this Skill when

Use when evaluating paid media strategy or performance on the specified channel. Confirm campaign objective, conversion definition and reporting window first.

## Required context

- Google Ads exports
- campaign type
- search terms
- keywords/match types
- conversion actions
- budgets
- landing pages
- geo/device

If key data is absent, state what cannot be concluded and continue with a clearly labeled partial diagnosis. Never invent platform metrics or account structure.

## Specialized workflow

1. Verify conversion actions and values
2. separate Search, Shopping, Performance Max and other types
3. analyze query intent, match coverage and negatives
4. review ad/asset relevance
5. inspect impression share and budget limits
6. prioritize fixes by marginal value.

## Deliverables

- Campaign-type audit
- search-term actions
- keyword/negative recommendations
- asset and landing fixes
- measurement gaps.

## Quality gates

- Keep campaign types, attribution windows, currencies and conversion definitions comparable.
- Separate platform-reported results from blended business outcomes and incrementality.
- Explain metric denominators and data coverage; don't infer causality from correlation.
- Prioritize changes by expected impact, confidence, risk and learning value.



## Ready-to-use workflow

### Copy/paste prompt

```text
Run google-ads-optimizer for [business/client]. Objective: [measurable goal]. Audience/market: [segment and geography]. Time horizon: [period]. Budget/resources: [constraints]. Inputs: [data, links, exports]. Check for: Google Ads exports; campaign type; search terms; keywords/match types; conversion actions; budgets; landing pages; geo/device. If one critical input is missing, ask one focused question; otherwise state assumptions and proceed. Return all deliverables, ranked priorities and measurement plan.
```

### Execution checklist

1. Translate the requested outcome into a measurable decision and confirm the time horizon.
2. Check the required context and inventory evidence, sources, freshness and data gaps.
3. Apply the specialized workflow above. Show formulas, assumptions and decision criteria for any model or score.
4. Compare options and prioritize by expected impact, confidence, effort, risk and dependencies.
5. Convert the recommendation into owners, milestones, next actions and a measurement/review cadence.

### Output contract

Lead with the recommended decision and why. Then provide:

- **Campaign-type audit:** specific, evidence-based recommendation or artifact.
- **search-term actions:** specific, evidence-based recommendation or artifact.
- **keyword/negative recommendations:** specific, evidence-based recommendation or artifact.
- **asset and landing fixes:** specific, evidence-based recommendation or artifact.
- **measurement gaps.:** specific, evidence-based recommendation or artifact.

Include scope, time horizon, source/data coverage, assumptions, risks, alternatives rejected and validation criteria. Use **Not provided** for unknowns; distinguish forecast from actual results.

### Example invocation

```text
I need google-ads-optimizer for [business] to achieve [goal] within [timeframe] using [budget/resources]. Here is the available context: [paste]. Produce a prioritized, implementable plan with milestones, KPIs, owners and assumptions.
```

### Quality check

- Keep campaign types, attribution windows, currencies and conversion definitions comparable.
- Separate platform-reported results from blended business outcomes and incrementality.
- Explain metric denominators and data coverage; don't infer causality from correlation.
- Prioritize changes by expected impact, confidence, risk and learning value.

## Athenous MCP usage

MCP is optional. If connected, discover actual account, campaign, reporting and editing tools plus exact schemas at runtime. Use only authorized accounts and verified fields. Never assume a platform integration, breakdown or mutation capability exists. If unavailable, analyze supplied exports and disclose limitations. Keep client workspaces isolated.

## Approval and safety

Analysis and recommendations do not authorize live changes. Before editing campaigns, audiences, creatives, bids or budgets, show the exact proposed change, account and expected impact/risk, then obtain explicit confirmation. Never apply changes automatically or claim success without tool confirmation. Follow server-side permissions and audit requirements.
