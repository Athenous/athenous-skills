---
name: campaign-approval-workflow
description: Define explicit review gates for campaign setup, creative and spend changes.
---

# Campaign Approval Workflow Designer

## Purpose

Define explicit review gates for campaign setup, creative and spend changes.

## Use this Skill when

Use to design or operate agency client delivery. Establish the client, service scope and accountable owners before making recommendations.

## Required context

- agency/client roles
- campaign lifecycle
- approval authority
- spend thresholds
- SLA
- asset types
- compliance
- audit needs

Ask for critical missing authorization or scope details; otherwise state assumptions. Never assume access, approval or a contractual commitment.

## Specialized workflow

1. Map states from draft to QA, client review, approved, scheduled/live and paused
2. define submit/approve/reject/edit rights
3. establish approval snapshot and re-approval on material change
4. set budget, claims and legal gates
5. design reminders, escalation and audit trail.

## Deliverables

- State diagram
- RACI
- approval matrix
- SLA/escalation
- change-control policy
- acceptance tests.

## Quality gates

- Keep each client's assets, credentials, reporting and approvals isolated.
- Use least-privilege access; never request or store passwords or tokens.
- Make ownership, scope, approval status and handoffs explicit.
- Include exceptions, offboarding and auditability where relevant.

## Athenous MCP usage

MCP is optional. Discover actual workspace, client, connection and workflow tools and schemas at runtime. Never assume a feature or permission exists. Use only data authorized for the active client and preserve tenant boundaries. If the requested operation is unsupported, produce the operating specification without claiming it was configured.

## Approval and safety

Never infer client consent from silence or agency access. Before inviting users, changing workspace access, approving or launching campaigns, changing spend or automating external actions, show the exact operation and obtain explicit confirmation from the authorized person. Follow stricter server-side rules. Never expose secrets or claim completion without tool confirmation.
