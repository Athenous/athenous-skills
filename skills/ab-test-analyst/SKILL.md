---
name: ab-test-analyst
description: Design, analyze and communicate controlled marketing experiments.
---

# A/B Test Analyst

## Purpose

Design, analyze and communicate controlled marketing experiments.

## Use this Skill when

Use for measurement, organic search or performance investigation as described. Establish scope, source coverage and the decision the analysis should support.

## Required context

- hypothesis
- primary/guardrail metrics
- baseline
- traffic/sample
- allocation
- duration
- randomization unit
- experiment data

State limitations where data is missing. Never fabricate search volumes, rankings, conversions, statistical significance or root causes.

## Specialized workflow

1. Validate randomization and instrumentation
2. define estimand and eligible population
3. assess sample-size and power feasibility
4. pre-register metrics/stopping rules
5. analyze effect size and uncertainty
6. check guardrail harm and segment caveats
7. recommend ship, iterate or inconclusive.

## Deliverables

- Experiment protocol
- sample/time estimate
- results with justified intervals
- validity checks
- decision memo.

## Quality gates

- Preserve metric definitions, time windows and source provenance.
- Distinguish observed facts, modeled estimates, interpretations and causal claims.
- Prioritize work by business relevance, confidence, effort and risk.
- Avoid manipulative SEO, scaled low-value content and unsupported ranking guarantees.
- Identify data coverage and instrumentation limitations.



## Ready-to-use workflow

### Copy/paste starter prompt

```text
Act as a senior ab test analyst specialist. Design, analyze and communicate controlled marketing experiments.

Business/client: [name and context]
Goal or decision: [specific outcome]
Scope and period: [scope, dates, timezone if relevant]
Available inputs: [paste exports, URLs, documents or metrics]
Constraints: [budget, resources, brand, legal, platform or approval limits]

Use the available evidence first. Required context to check: hypothesis; primary/guardrail metrics; baseline; traffic/sample; allocation; duration; randomization unit; experiment data. If something important is missing, ask only the single most blocking question; otherwise state reasonable assumptions and continue. Produce every deliverable in this Skill's Output contract. Separate facts, calculations, assumptions and recommendations. Do not make live changes.
```

### Execution checklist

1. Confirm the business/client, objective, scope, reporting period and decision this work must support.
2. Inventory the supplied files, connected sources and missing fields. Validate dates, units, definitions and data coverage before drawing conclusions.
3. Apply the specialized workflow above in order. Show calculations and the evidence behind each material finding.
4. Rank recommendations by impact, confidence, effort, risk and dependencies. Distinguish quick wins from structural work.
5. Finish with owners, next steps and the evidence needed to validate outcomes. If the evidence is incomplete, provide a clearly labeled partial result rather than inventing facts.

### Output contract

Start with a concise executive answer, then include:

- **Experiment protocol:** include the decision-ready detail, evidence and next action.
- **sample/time estimate:** include the decision-ready detail, evidence and next action.
- **results with justified intervals:** include the decision-ready detail, evidence and next action.
- **validity checks:** include the decision-ready detail, evidence and next action.
- **decision memo.:** include the decision-ready detail, evidence and next action.

Also include: scope and period; sources/data coverage; assumptions and limitations; priority-ranked next actions; owner and suggested timing where known. Use tables when comparing multiple items. Mark unavailable values as **Not provided** rather than estimating them silently.

### Illustrative invocation

```text
Use ab-test-analyst for [business/client]. The goal is [measurable goal] over [period]. Here are the inputs: [paste data]. Return the complete decision-ready deliverables, identify any data gaps, and finish with the three highest-priority next actions.
```

### Final quality check

- Preserve metric definitions, time windows and source provenance.
- Distinguish observed facts, modeled estimates, interpretations and causal claims.
- Prioritize work by business relevance, confidence, effort and risk.
- Avoid manipulative SEO, scaled low-value content and unsupported ranking guarantees.
- Identify data coverage and instrumentation limitations.

## Athenous MCP usage

MCP is optional. Discover exact available analytics, reporting or content tools at runtime; never invent tool names, fields or capabilities. Use only authorized data and keep client workspaces isolated. If SEO/search data is not available through MCP, use supplied exports or clearly labeled public evidence.

## Safety

Protect personal and customer data. Do not change live pages, metadata, budgets or campaigns without presenting the exact change and receiving explicit confirmation. Never claim a change or test outcome without tool confirmation.
