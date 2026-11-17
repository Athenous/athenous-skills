---
name: retargeting-strategy
description: Design consent-aware retargeting journeys by intent and recency.
---

# Retargeting Strategy Planner

## Purpose

Design consent-aware retargeting journeys by intent and recency.

## Use this Skill when

Use for the paid campaign planning, creative or conversion task described here. Confirm the campaign goal and the decision owner.

## Required context

- consent/privacy rules
- eligible audience sizes
- site/app events
- CRM segments
- funnel stages
- exclusions
- frequency
- creative assets

State assumptions where inputs are incomplete. Never invent performance data, platform limits, approved claims or legal clearance.

## Specialized workflow

1. Define eligible first-party audiences and lawful consent basis
2. segment by intent and recency
3. exclude converters and unsuitable groups
4. set windows and frequency policy
5. sequence messages and offers
6. plan suppression and measurement
7. validate audience thresholds.

## Deliverables

- Audience map
- window/exclusion matrix
- message sequence
- creative brief
- measurement/privacy checklist.

## Quality gates

- Keep the audience, offer, creative and landing-page promise consistent.
- Verify claims, tracking, links, dates, currency and platform specifications.
- Separate estimates from observed data; state attribution and measurement caveats.
- Prioritize by impact, confidence, effort, risk and reversibility.



## Ready-to-use workflow

### Copy/paste prompt

```text
Run retargeting-strategy for [agency/client/account]. Goal: [specific outcome]. Scope: [channels, assets, dates]. Context: [audience, offer, budget and constraints]. Inputs: [exports, creative, landing pages, audience details]. Verify: consent/privacy rules; eligible audience sizes; site/app events; CRM segments; funnel stages; exclusions; frequency; creative assets. State missing evidence, ask only one critical question if blocked, and return a complete prioritized plan. Do not apply changes without explicit approval.
```

### Execution checklist

1. Confirm the account/client, objective, campaign or asset scope, reporting window and authority.
2. Validate source data, attribution, event definitions, audience/creative scope and account boundaries.
3. Apply the channel-specific workflow above; compare like with like and explain metric definitions.
4. Rank actions by expected incremental impact, confidence, spend/risk and learning value. Identify what should not change.
5. Present proposed edits separately from analysis. Obtain explicit approval before any live change and verify the result afterward.

### Output contract

Begin with the key finding and recommended decision. Include:

- **Audience map:** evidence-backed recommendation, implementation detail and owner.
- **window/exclusion matrix:** evidence-backed recommendation, implementation detail and owner.
- **message sequence:** evidence-backed recommendation, implementation detail and owner.
- **creative brief:** evidence-backed recommendation, implementation detail and owner.
- **measurement/privacy checklist.:** evidence-backed recommendation, implementation detail and owner.

Also include data coverage, metric definitions, assumptions, limitations, risks and validation plan. Mark unknowns **Not provided** and never invent account metrics or claim causality without evidence.

### Example invocation

```text
Use retargeting-strategy for [account/client] to improve [goal] over [period]. Review the supplied account data and assets. Return prioritized recommendations with rationale, expected impact range only where supportable, risks, and exact proposed changes for approval.
```

### Quality check

- Keep the audience, offer, creative and landing-page promise consistent.
- Verify claims, tracking, links, dates, currency and platform specifications.
- Separate estimates from observed data; state attribution and measurement caveats.
- Prioritize by impact, confidence, effort, risk and reversibility.

## Athenous MCP usage

MCP is optional. Discover exact available tools and schemas at runtime before reading or changing campaigns. Never invent campaign fields, platform integrations or write operations. Use only authorized client accounts and preserve workspace isolation. If the needed capability is unavailable, provide the plan and manual implementation steps.

## Approval and safety

Before publishing, launching, editing targeting or changing spend, show the exact settings and obtain explicit confirmation. Retargeting recommendations must respect consent, privacy law and platform policy; never advise bypassing consent or targeting sensitive traits. Do not claim an action succeeded without tool confirmation.
