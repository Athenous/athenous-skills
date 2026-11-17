---
name: marketing-workflow-automation
description: Specify reliable automations with triggers, safeguards and recovery.
---

# Marketing Workflow Automation Designer

## Purpose

Specify reliable automations with triggers, safeguards and recovery.

## Use this Skill when

Use to design or operate agency client delivery. Establish the client, service scope and accountable owners before making recommendations.

## Required context

- process
- systems
- triggers
- fields
- frequency
- owners
- permissions
- failure impact
- exceptions

Ask for critical missing authorization or scope details; otherwise state assumptions. Never assume access, approval or a contractual commitment.

## Specialized workflow

1. Map current process and handoffs
2. define trigger and idempotency key
3. specify preconditions, transformations and outputs
4. design retries, deduplication, rate limits and dead-letter handling
5. classify risk and approval gates
6. define observability, rollback and manual fallback
7. test edge cases.

## Deliverables

- Automation specification
- sequence/decision flow
- field mapping
- permissions
- retry/failure policy
- monitoring
- test cases.

## Quality gates

- Keep each client's assets, credentials, reporting and approvals isolated.
- Use least-privilege access; never request or store passwords or tokens.
- Make ownership, scope, approval status and handoffs explicit.
- Include exceptions, offboarding and auditability where relevant.



## Ready-to-use workflow

### Copy/paste prompt

```text
Use marketing-workflow-automation for [team/client/business]. Desired result: [outcome]. Current process/context: [describe]. Scope and deadline: [details]. Systems/data available: [list or paste]. Constraints: [permissions, privacy, budget, tools]. Check: process; systems; triggers; fields; frequency; owners; permissions; failure impact; exceptions. Ask only one blocking clarification; otherwise document assumptions and provide the complete operational deliverables. Do not claim a workflow or change was deployed unless verified.
```

### Execution checklist

1. Confirm the requester, intended users, business outcome, scope, deadline and authority to act.
2. Map existing process, source data, systems, roles, dependencies and failure modes.
3. Apply the specialized workflow above. Make each recommendation operational with inputs, steps, owner and acceptance criteria.
4. Check privacy, client separation, least privilege, reversibility, exception handling and auditability.
5. Deliver a rollout/test plan and distinguish proposed design from changes actually made.

### Output contract

Lead with the recommended approach. Include:

- **Automation specification:** implementation-ready detail, owner and acceptance criteria.
- **sequence/decision flow:** implementation-ready detail, owner and acceptance criteria.
- **field mapping:** implementation-ready detail, owner and acceptance criteria.
- **permissions:** implementation-ready detail, owner and acceptance criteria.
- **retry/failure policy:** implementation-ready detail, owner and acceptance criteria.
- **monitoring:** implementation-ready detail, owner and acceptance criteria.
- **test cases.:** implementation-ready detail, owner and acceptance criteria.

Also include assumptions, risks, dependencies, open questions, rollout sequence and measurable acceptance criteria. Use **Not provided** for missing facts; never claim configuration or execution without tool confirmation.

### Example invocation

```text
Apply marketing-workflow-automation to [team/process]. We need [outcome] by [date]. Current state: [details]. Systems and constraints: [details]. Produce a complete implementation-ready plan, including owners, edge cases, test cases and rollout checks.
```

### Quality check

- Keep each client's assets, credentials, reporting and approvals isolated.
- Use least-privilege access; never request or store passwords or tokens.
- Make ownership, scope, approval status and handoffs explicit.
- Include exceptions, offboarding and auditability where relevant.

## Athenous MCP usage

MCP is optional. Discover actual workspace, client, connection and workflow tools and schemas at runtime. Never assume a feature or permission exists. Use only data authorized for the active client and preserve tenant boundaries. If the requested operation is unsupported, produce the operating specification without claiming it was configured.

## Approval and safety

Never infer client consent from silence or agency access. Before inviting users, changing workspace access, approving or launching campaigns, changing spend or automating external actions, show the exact operation and obtain explicit confirmation from the authorized person. Follow stricter server-side rules. Never expose secrets or claim completion without tool confirmation.
