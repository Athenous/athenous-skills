---
name: meta-ads-optimizer
description: Diagnose Meta campaign delivery, structure, creative and conversion performance.
---

# Meta Ads Optimizer

## Purpose

Diagnose Meta campaign delivery, structure, creative and conversion performance.

## Use this Skill when

Use when evaluating paid media strategy or performance on the specified channel. Confirm campaign objective, conversion definition and reporting window first.

## Required context

- Ads Manager export/authorized data
- objective
- campaign hierarchy
- attribution window
- spend
- events
- creative
- audience
- landing page

If key data is absent, state what cannot be concluded and continue with a clearly labeled partial diagnosis. Never invent platform metrics or account structure.

## Specialized workflow

1. Validate dates, currency, attribution and event definitions
2. inspect delivery and learning
3. compare campaign/ad set/ad levels consistently
4. decompose CPM, CTR, CPC, frequency, CVR and CPA/ROAS
5. inspect creative fatigue and audience overlap where available
6. propose controlled tests.

## Deliverables

- Account diagnosis
- asset performance table
- funnel decomposition
- creative refresh brief
- prioritized actions
- proposed changes.

## Quality gates

- Keep campaign types, attribution windows, currencies and conversion definitions comparable.
- Separate platform-reported results from blended business outcomes and incrementality.
- Explain metric denominators and data coverage; don't infer causality from correlation.
- Prioritize changes by expected impact, confidence, risk and learning value.



## Ready-to-use workflow

### Copy/paste prompt

```text
Run meta-ads-optimizer for [agency/client/account]. Goal: [specific outcome]. Scope: [channels, assets, dates]. Context: [audience, offer, budget and constraints]. Inputs: [exports, creative, landing pages, audience details]. Verify: Ads Manager export/authorized data; objective; campaign hierarchy; attribution window; spend; events; creative; audience; landing page. State missing evidence, ask only one critical question if blocked, and return a complete prioritized plan. Do not apply changes without explicit approval.
```

### Execution checklist

1. Confirm the account/client, objective, campaign or asset scope, reporting window and authority.
2. Validate source data, attribution, event definitions, audience/creative scope and account boundaries.
3. Apply the channel-specific workflow above; compare like with like and explain metric definitions.
4. Rank actions by expected incremental impact, confidence, spend/risk and learning value. Identify what should not change.
5. Present proposed edits separately from analysis. Obtain explicit approval before any live change and verify the result afterward.

### Output contract

Begin with the key finding and recommended decision. Include:

- **Account diagnosis:** evidence-backed recommendation, implementation detail and owner.
- **asset performance table:** evidence-backed recommendation, implementation detail and owner.
- **funnel decomposition:** evidence-backed recommendation, implementation detail and owner.
- **creative refresh brief:** evidence-backed recommendation, implementation detail and owner.
- **prioritized actions:** evidence-backed recommendation, implementation detail and owner.
- **proposed changes.:** evidence-backed recommendation, implementation detail and owner.

Also include data coverage, metric definitions, assumptions, limitations, risks and validation plan. Mark unknowns **Not provided** and never invent account metrics or claim causality without evidence.

### Example invocation

```text
Use meta-ads-optimizer for [account/client] to improve [goal] over [period]. Review the supplied account data and assets. Return prioritized recommendations with rationale, expected impact range only where supportable, risks, and exact proposed changes for approval.
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
