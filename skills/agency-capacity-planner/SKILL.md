---
name: agency-capacity-planner
description: Forecast team capacity and protect delivery margins across clients.
---

# Agency Capacity Planner

## Purpose

Forecast team capacity and protect delivery margins across clients.

## Use this Skill when

Use for the agency operations or growth problem described here. Clarify whether the deliverable is a process, analysis, recommendation or client-facing artifact.

## Required context

- team roles
- available hours
- leave
- retainers
- task estimates
- utilization
- deadlines
- skills
- margin targets

Ask only for critical missing inputs; state assumptions otherwise. Do not invent financial results, staffing commitments, approvals or process steps.

## Specialized workflow

1. Normalize productive capacity and non-client overhead
2. estimate workload by role and week
3. compare demand to capacity
4. identify bottlenecks and single points of failure
5. model hiring, freelance, scope and sequencing options
6. protect QA and contingency time
7. flag margin risk.

## Deliverables

- Capacity forecast
- utilization by role
- overload map
- staffing/scoping scenarios
- hiring triggers
- weekly review.

## Quality gates

- Make recommendations executable by a named role with clear timing and acceptance criteria.
- Account for margin, workload, risk and client experience, not just volume or speed.
- Separate documented facts from assumptions and proposed policy.
- Include escalation, review and feedback loops where the process is recurring.



## Ready-to-use workflow

### Copy/paste starter prompt

```text
Act as a senior agency capacity planner specialist. Forecast team capacity and protect delivery margins across clients.

Business/client: [name and context]
Goal or decision: [specific outcome]
Scope and period: [scope, dates, timezone if relevant]
Available inputs: [paste exports, URLs, documents or metrics]
Constraints: [budget, resources, brand, legal, platform or approval limits]

Use the available evidence first. Required context to check: team roles; available hours; leave; retainers; task estimates; utilization; deadlines; skills; margin targets. If something important is missing, ask only the single most blocking question; otherwise state reasonable assumptions and continue. Produce every deliverable in this Skill's Output contract. Separate facts, calculations, assumptions and recommendations. Do not make live changes.
```

### Execution checklist

1. Confirm the business/client, objective, scope, reporting period and decision this work must support.
2. Inventory the supplied files, connected sources and missing fields. Validate dates, units, definitions and data coverage before drawing conclusions.
3. Apply the specialized workflow above in order. Show calculations and the evidence behind each material finding.
4. Rank recommendations by impact, confidence, effort, risk and dependencies. Distinguish quick wins from structural work.
5. Finish with owners, next steps and the evidence needed to validate outcomes. If the evidence is incomplete, provide a clearly labeled partial result rather than inventing facts.

### Output contract

Start with a concise executive answer, then include:

- **Capacity forecast:** include the decision-ready detail, evidence and next action.
- **utilization by role:** include the decision-ready detail, evidence and next action.
- **overload map:** include the decision-ready detail, evidence and next action.
- **staffing/scoping scenarios:** include the decision-ready detail, evidence and next action.
- **hiring triggers:** include the decision-ready detail, evidence and next action.
- **weekly review.:** include the decision-ready detail, evidence and next action.

Also include: scope and period; sources/data coverage; assumptions and limitations; priority-ranked next actions; owner and suggested timing where known. Use tables when comparing multiple items. Mark unavailable values as **Not provided** rather than estimating them silently.

### Illustrative invocation

```text
Use agency-capacity-planner for [business/client]. The goal is [measurable goal] over [period]. Here are the inputs: [paste data]. Return the complete decision-ready deliverables, identify any data gaps, and finish with the three highest-priority next actions.
```

### Final quality check

- Make recommendations executable by a named role with clear timing and acceptance criteria.
- Account for margin, workload, risk and client experience, not just volume or speed.
- Separate documented facts from assumptions and proposed policy.
- Include escalation, review and feedback loops where the process is recurring.

## Athenous MCP usage

MCP is optional. Discover actual workspace, analytics, task, reporting and automation tools and exact schemas at runtime. Use only verified capabilities and authorized client data. Do not assume a workflow has been created or an operation performed. Preserve client isolation and disclose unsupported integrations.

## Approval and safety

Do not change access, client commitments, live campaigns, budgets or external communications without explicit approval from the authorized owner. Never expose credentials or client secrets. For QA, block release when a critical defect remains unresolved; do not claim a process or change is deployed unless a tool response confirms it.
