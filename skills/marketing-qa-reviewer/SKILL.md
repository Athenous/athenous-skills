---
name: marketing-qa-reviewer
description: Review marketing assets and campaigns before release against a defined checklist.
---

# Marketing Quality Assurance Reviewer

## Purpose

Review marketing assets and campaigns before release against a defined checklist.

## Use this Skill when

Use for the agency operations or growth problem described here. Clarify whether the deliverable is a process, analysis, recommendation or client-facing artifact.

## Required context

- asset/campaign
- brief
- channel specs
- approved claims
- links/UTMs
- audience
- budget
- legal rules
- brand guide
- approval status

Ask only for critical missing inputs; state assumptions otherwise. Do not invent financial results, staffing commitments, approvals or process steps.

## Specialized workflow

1. Check objective/brief alignment
2. verify copy, offer, dates, price and claims
3. validate links, UTMs, landing page and conversion event
4. inspect format, targeting, exclusions and budget
5. review accessibility/mobile/brand
6. confirm approval and rollback
7. classify blockers and warnings.

## Deliverables

- Pass/fail checklist
- severity-ranked defects
- exact corrections
- retest evidence
- release recommendation.

## Quality gates

- Make recommendations executable by a named role with clear timing and acceptance criteria.
- Account for margin, workload, risk and client experience, not just volume or speed.
- Separate documented facts from assumptions and proposed policy.
- Include escalation, review and feedback loops where the process is recurring.



## Ready-to-use workflow

### Copy/paste prompt

```text
Use marketing-qa-reviewer for [team/client/business]. Desired result: [outcome]. Current process/context: [describe]. Scope and deadline: [details]. Systems/data available: [list or paste]. Constraints: [permissions, privacy, budget, tools]. Check: asset/campaign; brief; channel specs; approved claims; links/UTMs; audience; budget; legal rules; brand guide; approval status. Ask only one blocking clarification; otherwise document assumptions and provide the complete operational deliverables. Do not claim a workflow or change was deployed unless verified.
```

### Execution checklist

1. Confirm the requester, intended users, business outcome, scope, deadline and authority to act.
2. Map existing process, source data, systems, roles, dependencies and failure modes.
3. Apply the specialized workflow above. Make each recommendation operational with inputs, steps, owner and acceptance criteria.
4. Check privacy, client separation, least privilege, reversibility, exception handling and auditability.
5. Deliver a rollout/test plan and distinguish proposed design from changes actually made.

### Output contract

Lead with the recommended approach. Include:

- **Pass/fail checklist:** implementation-ready detail, owner and acceptance criteria.
- **severity-ranked defects:** implementation-ready detail, owner and acceptance criteria.
- **exact corrections:** implementation-ready detail, owner and acceptance criteria.
- **retest evidence:** implementation-ready detail, owner and acceptance criteria.
- **release recommendation.:** implementation-ready detail, owner and acceptance criteria.

Also include assumptions, risks, dependencies, open questions, rollout sequence and measurable acceptance criteria. Use **Not provided** for missing facts; never claim configuration or execution without tool confirmation.

### Example invocation

```text
Apply marketing-qa-reviewer to [team/process]. We need [outcome] by [date]. Current state: [details]. Systems and constraints: [details]. Produce a complete implementation-ready plan, including owners, edge cases, test cases and rollout checks.
```

### Quality check

- Make recommendations executable by a named role with clear timing and acceptance criteria.
- Account for margin, workload, risk and client experience, not just volume or speed.
- Separate documented facts from assumptions and proposed policy.
- Include escalation, review and feedback loops where the process is recurring.

## Athenous MCP usage

MCP is optional. Discover actual workspace, analytics, task, reporting and automation tools and exact schemas at runtime. Use only verified capabilities and authorized client data. Do not assume a workflow has been created or an operation performed. Preserve client isolation and disclose unsupported integrations.

## Approval and safety

Do not change access, client commitments, live campaigns, budgets or external communications without explicit approval from the authorized owner. Never expose credentials or client secrets. For QA, block release when a critical defect remains unresolved; do not claim a process or change is deployed unless a tool response confirms it.
