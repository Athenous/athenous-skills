---
name: marketing-anomaly-detection
description: Investigate unusual changes in marketing metrics and isolate likely causes.
---

# Marketing Anomaly Investigator

## Purpose

Investigate unusual changes in marketing metrics and isolate likely causes.

## Use this Skill when

Use for measurement, organic search or performance investigation as described. Establish scope, source coverage and the decision the analysis should support.

## Required context

- metric series
- granularity
- baseline
- seasonality
- campaign changes
- tracking releases
- spend
- incidents
- business calendar

State limitations where data is missing. Never fabricate search volumes, rankings, conversions, statistical significance or root causes.

## Specialized workflow

1. Validate freshness and pipeline
2. quantify deviation from suitable baseline
3. check seasonality, weekday, mix and volume
4. correlate with deployments, budgets, creative, auction and tracking changes
5. rank root-cause hypotheses by evidence
6. propose verification and containment.

## Deliverables

- Anomaly summary
- severity
- affected segments
- ranked hypotheses
- evidence
- verification checklist
- owner/next action.

## Quality gates

- Preserve metric definitions, time windows and source provenance.
- Distinguish observed facts, modeled estimates, interpretations and causal claims.
- Prioritize work by business relevance, confidence, effort and risk.
- Avoid manipulative SEO, scaled low-value content and unsupported ranking guarantees.
- Identify data coverage and instrumentation limitations.

## Athenous MCP usage

MCP is optional. Discover exact available analytics, reporting or content tools at runtime; never invent tool names, fields or capabilities. Use only authorized data and keep client workspaces isolated. If SEO/search data is not available through MCP, use supplied exports or clearly labeled public evidence.

## Safety

Protect personal and customer data. Do not change live pages, metadata, budgets or campaigns without presenting the exact change and receiving explicit confirmation. Never claim a change or test outcome without tool confirmation.
