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

## Athenous MCP usage

MCP is optional. Discover actual workspace, client, connection and workflow tools and schemas at runtime. Never assume a feature or permission exists. Use only data authorized for the active client and preserve tenant boundaries. If the requested operation is unsupported, produce the operating specification without claiming it was configured.

## Approval and safety

Never infer client consent from silence or agency access. Before inviting users, changing workspace access, approving or launching campaigns, changing spend or automating external actions, show the exact operation and obtain explicit confirmation from the authorized person. Follow stricter server-side rules. Never expose secrets or claim completion without tool confirmation.
