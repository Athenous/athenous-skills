---
name: multi-client-workspace
description: Design repeatable client operations without cross-account data leakage.
---

# Multi-Client Agency Workspace Planner

## Purpose

Design repeatable client operations without cross-account data leakage.

## Use this Skill when

Use to design or operate agency client delivery. Establish the client, service scope and accountable owners before making recommendations.

## Required context

- client roster
- service tiers
- team roles
- account ownership
- connections
- reporting
- naming rules
- retention

Ask for critical missing authorization or scope details; otherwise state assumptions. Never assume access, approval or a contractual commitment.

## Specialized workflow

1. Define client/workspace boundaries
2. map agency, account manager, specialist and client permissions
3. specify naming/asset conventions
4. separate shared templates from client data
5. design intake, approval and reporting flows
6. define offboarding/access revocation
7. test isolation.

## Deliverables

- Workspace blueprint
- role matrix
- naming standards
- template library
- lifecycle checklist
- isolation tests.

## Quality gates

- Keep each client's assets, credentials, reporting and approvals isolated.
- Use least-privilege access; never request or store passwords or tokens.
- Make ownership, scope, approval status and handoffs explicit.
- Include exceptions, offboarding and auditability where relevant.

## Athenous MCP usage

MCP is optional. Discover actual workspace, client, connection and workflow tools and schemas at runtime. Never assume a feature or permission exists. Use only data authorized for the active client and preserve tenant boundaries. If the requested operation is unsupported, produce the operating specification without claiming it was configured.

## Approval and safety

Never infer client consent from silence or agency access. Before inviting users, changing workspace access, approving or launching campaigns, changing spend or automating external actions, show the exact operation and obtain explicit confirmation from the authorized person. Follow stricter server-side rules. Never expose secrets or claim completion without tool confirmation.
