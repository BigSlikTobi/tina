# Codex for Tax Advisors — Agentic MVP context

In 2017, a team at Google published a paper with a four-word title: "Attention Is All You Need."

They weren't being modest. They were right. You don't need recurrence. You don't need convolution. You just need to know where to look.

Tax advisors have known this for a long time.

Every morning, a Steuerberater opens the same case. The client is there. The evidence is there. The deadline is there. Most of it is buried across five different tools, an inbox, a spreadsheet, and their own memory. Before they can do anything useful, they have to rebuild the picture.

That's not a talent problem. That's a context problem.

We're building the Codex for Tax Advisors because we believe the same thing that team believed in 2017. The answer isn't more tools. It's not a smarter model on its own. It's the right context, in one place, honest about what it knows and what it doesn't.

**Context is all you need.**

The agent works inside that context. The advisor owns it. Every claim links to a source. Every gap is visible. Every decision stays with the human who's accountable for it.

> Context is the foundation. Controlled execution creates the outcome.

---

## What's in this folder

This folder holds the complete discovery context for the first Tax Advisor Platform shot. Read it before building anything. It tells you what was decided, why, and what's still open.

### The product

| File | What it is |
| --- | --- |
| `manifesto.md` | The Agentic Tax Practice manifesto — the ground rules for the whole platform |
| `product_vision.md` | The Agentic Product Roadmap v0.14 — the Codex north star and nine-month path |
| `sota_to_vision.md` | How we moved from market SOTA to the Codex vision |
| `agentic_mvp.md` | The MVP artifact v1.3 — scope, Kano matrix, agent team, open questions |
| `build_decision.md` | The Phase-1 build decision record — what we build, why, and the ten decisions with rationale |

### The research

| File | What it is |
| --- | --- |
| `sota_benchmark.md` | The full SOTA benchmark v1.2 — evidence register, market decisions, two-horizon framing |
| `sota_synthesis.md` | The reader-facing market synthesis — what the market looks like in plain words |
| `strategy_alignment.md` | How the product vision aligns with internal Notion/Drive strategy (self-contained) |
| `strategy_alignment_detail.md` | The full diff — every divergence and reconciliation between vision and internal strategy |

### The stress tests

| File | What it is |
| --- | --- |
| `war_game.md` | The war game v2.1 — 32 re-adjudicated scenarios, 10-front attack, kill-shot verdicts |
| `war_game_thought_process.md` | How we reached the war game decision in plain words |
| `agentic_mvp_source_audit.md` | Two-pass audit of every MVP claim against live internal strategy (all F1–F5 resolved) |

### The measurement and go-to-market

| File | What it is |
| --- | --- |
| `metrics.md` | The metrics contract v1.1 — four KPIs, two gates, hard guardrails, 30-formula catalog |
| `metrics_thought_process.md` | How we reached the measurement contract |
| `metrics_dashboard_mock.md` | The teaching mock — what a healthy synthetic replay could look like |
| `gtm.md` | The go-to-market scenario v1.0 — seven stages, evidence-to-claim register |
| `gtm_thought_process.md` | How we reached the GTM scenario |

### The path and the backlog

| File | What it is |
| --- | --- |
| `sota_to_vision_thought_process.md` | The 13 turning points from SOTA analysis to Codex vision |
| `agentic_mvp_thought_process.md` | How we narrowed a big idea into a provable first slice |
| `todo_before_mvp.md` | The open checklist — 11 items that must close before Gate G001 approves build |

---

## The decision in one sentence

Build the daily home base for a German Tax Advisor: a vendor-agnostic, governed control-and-review surface, synthetic replay first, AI prepares, human decides.

## What's still open before building

Five things close Gate G001:

1. Five-day Advisor observation (which systems, what time, what gets missed).
2. The connected-source contract (DATEV, task list, Taxfix — ownership, freshness, effects).
3. The first bookkeeping case (the exact Buchungsprofil, schema, rubric, gold pack).
4. The downstream handoff (Untervollmacht A-1, ELSTER reconciliation).
5. The named gate owners (sponsor confirmed; Security/CISO still open).

Three things are real prerequisites but belong at later gates, not the build gate: reviewer failover for the single Steuerberater, filing authority, and named security owner with provider agreements.

See `todo_before_mvp.md` for the full checklist and `build_decision.md` for the complete gate picture.
