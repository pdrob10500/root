# Task: Plan a Market Data Discovery & Risk-Control Mapping

## Context
You are assisting a second-line Model Risk Management (MRM) team member at a 
PRA-regulated life insurance firm. The production codebase you have access to 
covers pricing, risk, and trading infrastructure across multiple asset classes.

Your focus is **Market Data** — the machinery that sources, transforms, validates, 
stores, and serves market data to downstream consumers (pricing models, risk 
calculations, trading systems, reporting).

## Reference Examples
In the `examples/` directory you will find two JSON files:
- One derived from a spreadsheet capturing a **Bonds** risk-and-control inventory 
  (lifecycle stages, risks, controls, ownership, gaps, action items)
- One derived from a PowerPoint summarising findings for governance committees

These are **completed deliverables from a prior equivalent exercise on Bonds**. 
Study them carefully to understand:
1. The structure and granularity of the lifecycle decomposition
2. How risks and controls are categorised and attributed to teams
3. What a "control gap" or "ownership gap" looks like in practice
4. The level of detail expected in the final output

Do NOT replicate Bonds content. Use these purely as structural templates for 
what we need to produce for Market Data.

## What "Market Data machinery" means
Look for code, configuration, and infrastructure related to:
- Market data sourcing (vendor feeds, APIs, file ingestion, Bloomberg/Reuters/etc)
- Data parsing, cleaning, validation, transformation pipelines
- Curve construction, surface building, fixings, benchmarks
- Market data storage (databases, caches, file stores)
- Snapshotting, versioning, end-of-day vs intraday handling
- Market data distribution/serving to downstream consumers
- Fallback/override mechanisms, stale data handling
- Entitlements, permissioning, vendor licence constraints (if visible in code)
- Monitoring, alerting, reconciliation of market data

## Your deliverable: A sequential task plan
Produce a numbered list of small, focused discovery tasks that a coding agent 
can execute one at a time. Each task should:

- Have a clear, narrow objective (e.g. "identify all market data ingestion 
  entry points in the codebase")
- Specify which directories, file patterns, or search terms to investigate
- State what output to produce (e.g. a list of files, a summary table, 
  a partial lifecycle map)
- Be completable within a single pass without needing the full codebase 
  in context
- Build on prior tasks' outputs, so later tasks can reference earlier findings

### Constraints for task design
- Each task must be scoped small enough that the agent can hold the relevant 
  code in context without truncation
- Tasks should start broad (directory structure, module naming, entry points) 
  and progressively deepen (internal logic, data flows, error handling)
- Every claim in task outputs must cite specific files, functions, or 
  config entries — no speculation
- If a task reveals the scope is larger than expected, the plan should 
  include a "re-scope" checkpoint rather than trying to cover everything

### Suggested phasing (adapt based on what you find)
Phase 1 — Orientation: Understand repo structure, identify market-data-related 
           modules, produce a high-level map
Phase 2 — Ingestion & Sourcing: Trace how market data enters the system
Phase 3 — Transformation & Storage: How data is processed, validated, persisted
Phase 4 — Distribution & Consumption: How downstream systems access market data
Phase 5 — Controls & Error Handling: Validation checks, fallbacks, monitoring, 
           alerting, reconciliation
Phase 6 — Synthesis: Assemble findings into a draft lifecycle with preliminary 
           risk/control observations, modelled on the Bonds example structure

## Important rules
- Do NOT execute any tasks yet. Only produce the plan.
- Do NOT hallucinate file paths or module names. If you need to assume 
  something exists, flag it as an assumption to verify in Phase 1.
- The plan should be saved as a markdown file at `market_data_discovery_plan.md`
- Include an estimated number of tasks (expect 15-30 depending on codebase size)
- At the end of the plan, list open questions or ambiguities you would want 
  clarified before execution begins
