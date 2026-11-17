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

## Athenous MCP usage

MCP is optional. Discover exact available tools and schemas at runtime before reading or changing campaigns. Never invent campaign fields, platform integrations or write operations. Use only authorized client accounts and preserve workspace isolation. If the needed capability is unavailable, provide the plan and manual implementation steps.

## Approval and safety

Before publishing, launching, editing targeting or changing spend, show the exact settings and obtain explicit confirmation. Retargeting recommendations must respect consent, privacy law and platform policy; never advise bypassing consent or targeting sensitive traits. Do not claim an action succeeded without tool confirmation.
