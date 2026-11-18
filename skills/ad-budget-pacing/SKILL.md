---
name: ad-budget-pacing
description: Detect under/over-pacing and propose controlled budget corrections.
---

# Ad Budget Pacing Analyst

## Purpose

Detect under/over-pacing and propose controlled budget corrections.

## Use this Skill when

Use for the paid campaign planning, creative or conversion task described here. Confirm the campaign goal and the decision owner.

## Required context

- approved budget
- spend-to-date
- elapsed days
- campaign delivery
- flight
- timezone
- commitments
- performance guardrails

State assumptions where inputs are incomplete. Never invent performance data, platform limits, approved claims or legal clearance.

## Specialized workflow

1. Normalize period and timezone
2. calculate expected spend using plan shape
3. compare actual versus plan
4. distinguish delivery limits from intentional underspend
5. forecast period-end spend
6. model catch-up required
7. inspect performance before reallocation
8. define approval thresholds.

## Deliverables

- Pacing table
- variance/forecast
- cause hypotheses
- options and risks
- exact proposed changes
- alert thresholds.

## Quality gates

- Keep the audience, offer, creative and landing-page promise consistent.
- Verify claims, tracking, links, dates, currency and platform specifications.
- Separate estimates from observed data; state attribution and measurement caveats.
- Prioritize by impact, confidence, effort, risk and reversibility.



## Ready-to-use workflow

### Copy/paste starter prompt

```text
Act as a senior ad budget pacing specialist. Detect under/over-pacing and propose controlled budget corrections.

Business/client: [name and context]
Goal or decision: [specific outcome]
Scope and period: [scope, dates, timezone if relevant]
Available inputs: [paste exports, URLs, documents or metrics]
Constraints: [budget, resources, brand, legal, platform or approval limits]

Use the available evidence first. Required context to check: approved budget; spend-to-date; elapsed days; campaign delivery; flight; timezone; commitments; performance guardrails. If something important is missing, ask only the single most blocking question; otherwise state reasonable assumptions and continue. Produce every deliverable in this Skill's Output contract. Separate facts, calculations, assumptions and recommendations. Do not make live changes.
```

### Execution checklist

1. Confirm the business/client, objective, scope, reporting period and decision this work must support.
2. Inventory the supplied files, connected sources and missing fields. Validate dates, units, definitions and data coverage before drawing conclusions.
3. Apply the specialized workflow above in order. Show calculations and the evidence behind each material finding.
4. Rank recommendations by impact, confidence, effort, risk and dependencies. Distinguish quick wins from structural work.
5. Finish with owners, next steps and the evidence needed to validate outcomes. If the evidence is incomplete, provide a clearly labeled partial result rather than inventing facts.

### Output contract

Start with a concise executive answer, then include:

- **Pacing table:** include the decision-ready detail, evidence and next action.
- **variance/forecast:** include the decision-ready detail, evidence and next action.
- **cause hypotheses:** include the decision-ready detail, evidence and next action.
- **options and risks:** include the decision-ready detail, evidence and next action.
- **exact proposed changes:** include the decision-ready detail, evidence and next action.
- **alert thresholds.:** include the decision-ready detail, evidence and next action.

Also include: scope and period; sources/data coverage; assumptions and limitations; priority-ranked next actions; owner and suggested timing where known. Use tables when comparing multiple items. Mark unavailable values as **Not provided** rather than estimating them silently.

### Illustrative invocation

```text
Use ad-budget-pacing for [business/client]. The goal is [measurable goal] over [period]. Here are the inputs: [paste data]. Return the complete decision-ready deliverables, identify any data gaps, and finish with the three highest-priority next actions.
```

### Final quality check

- Keep the audience, offer, creative and landing-page promise consistent.
- Verify claims, tracking, links, dates, currency and platform specifications.
- Separate estimates from observed data; state attribution and measurement caveats.
- Prioritize by impact, confidence, effort, risk and reversibility.

## Athenous MCP usage

MCP is optional. Discover exact available tools and schemas at runtime before reading or changing campaigns. Never invent campaign fields, platform integrations or write operations. Use only authorized client accounts and preserve workspace isolation. If the needed capability is unavailable, provide the plan and manual implementation steps.

## Approval and safety

Before publishing, launching, editing targeting or changing spend, show the exact settings and obtain explicit confirmation. Retargeting recommendations must respect consent, privacy law and platform policy; never advise bypassing consent or targeting sensitive traits. Do not claim an action succeeded without tool confirmation.
