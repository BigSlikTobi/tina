# 🔗 Strategy alignment: vision ↔ internal strategy

# Strategy Alignment: Product Vision ↔ Internal Strategy
- Artifact ID: ADV-MORNING-001-VIS-ALIGN-HANDOVER-A001
- Type: self-contained handover (companion to product_vision.md; does not modify it)
- Job ID: ADV-MORNING-001
- Owner: Product
- Prepared: 2026-07-17

## How to read this document

Everything you need is inline below. You do not need Notion, Gmail, or Google Drive to use this handover.

- The internal business-strategy content does NOT live in the repo. It was captured from Notion and Google Drive on 2026-07-17 and is embedded verbatim-enough below so you can reason about it without fetching anything.
- Treat Section A as a **dated snapshot**, not a live source.
- This alignment intentionally excludes the TA Platform Vision model. It is not treated as an aligned Product Vision or as a prerequisite for the product direction below.

## Section A: Internal strategy snapshot (captured 2026-07-17)

### A1. The business frame

Source: "The Business Orchard Manifesto" (Google Drive, July 2026) and Company OKRs / all-hands deck (2026-05-06).

- Taxfix is transforming from "a German, once-a-year, DIY-first business" into a "subscription-first, year-round financial partner … an AI-native platform."
- Mission framing: **"Fix finance for entrepreneurs."**
- Customer sequence: **Self-Employed (SE, the heartland) → SME (graduation) → Tax Advisors (TA).**
- **Tax Advisors play two roles at once:** (1) Enablers / channel, a "magic wand"; (2) Customers in their own right, since a TA practice is itself a self-employed business.
- Operating principles: bold bets over incremental; ship to learn; AI-first is "how we think," not a buzzword; own outcomes not tasks.

### A2. The customer service ladder (GBB)

Source: Company OKRs / all-hands deck (2026-05-06).

**Good / Better / Best** maps to three service depths: **DIY** (self-service filing) → **DIWM** (AI-driven expert support) → **DIFM** (personal tax accountant). Demand signals cited: **82% of SE users require some level of assistance**; **60%+ want an all-in-one** solution.

### A3. SE/SME segments and sizing

Source: "Overview: Launching a Self-Employed Product Line" (Notion, **Oct 2025**. A refresh research effort was noted as in-flight; treat sizes as indicative).

- Total addressable: ~2.5M solo self-employed in Germany, TAM ~€680M/year; WTP ~€20–40/month.
- Segments: SBO ~1.2M (low WTP); **VAT-liable freelancers ~800k (most attractive)**; VAT-liable businesses without bookkeeping obligation ~500k; VAT-liable businesses with bookkeeping obligation ~300k.

### A4. Concrete 2026 delivery plan

Source: "TA Platform: H2 2026 Onsite Prep" (Notion, **2026-06-29**).

**Ambition:** "By the end of 2026, a Do-It-For-Me mandate runs from start to finish inside our workspace, and we can show a tax advisor's handling time falling."

| When | Milestone |
|---|---|
| 15 Jul 2026 | Self-Employed launch (hard dependency) |
| Q3 2026 | Automation pilot clears ~70% of tasks; opportunity discovery scoping begins |
| 15 Oct 2026 | Operational workspace proven at 50+ paying clients |
| Q4 2026 | AdvisorLens pilot live on one segment (GmbH), shadow-mode first |
| EOY 2026 | DIFM mandate end-to-end; 331 clients; handling time falling |
| Q1 2027 | First white-label Kanzleien |
| 2027 | Automation and proactive advisory at scale; white-label broadly |

**Hard dependency:** the Self-Employed launch on 15 July 2026. **DATEV roundtrip working (manually first) = P0.** Operating proof: **handling time falling**. Commercial metric: **Net Revenue per active Tax Advisor.**

### A5. The named agent families

Source: "TA Platform Agent Overview" (Notion, **2026-04-01**).

| Agent | Role | Short description |
|---|---|---|
| DataJanitor Pro | Intake & normalisation | Ingests multi-channel client data, maps to chart-of-accounts (SKR03/04), produces DATEV-importable work packages with confidence scores |
| FristenGuard | Deadline & risk sentinel | Unifies deadlines across DATEV/calendar/tax-office inboxes; flags risk, missing docs, capacity clashes |
| OpsMaestro | Practice orchestration | Learns/codifies workflows, monitors WIP and bottlenecks, simulates capacity |
| AdvisorLens | Proactive insight & advisory | Scans client GL/history for optimisation + cross-sell opportunities |
| ClientFit Scout | Client qualification & tiering | Scores leads for profitability/fit, recommends engagement tier and pricing |

SKU bundles: Core Ops (FristenGuard + DataJanitor Pro), Growth (ClientFit Scout + AdvisorLens), Enterprise (all five).

## Section B: What the product vision says (summary)
- Anchor: **"Codex for Tax Advisors"**, an agentic workbench.
- Month 9 is the operating transformation target.
- First deep job: bookkeeping-period preparation.
- Responsibilities split: organize (broad) / process (one deep job) / decide (human).
- Human authority fence: professional judgment + consequential external actions stay human.

## Section C: Alignment (where the two already agree)

| Theme | Product vision | Internal strategy | Verdict |
|---|---|---|---|
| Agentic direction | "Codex for Tax Advisors" agentic workbench | AI-native platform and named agent families for TA work | Strong match |
| First deep job | Bookkeeping-period preparation | EOY-2026 DIFM mandate on SE + DATEV roundtrip | Strong match |
| Human authority | Advisor keeps judgment + external actions | Personal tax accountant remains the delivery layer for DIFM | Strong match |
| Operating proof | Recovered advisor time, accepted outcomes, low false-ready, coverage | Handling time falling inside an end-to-end mandate | Strong match |
| Advisory agents | Names AdvisorLens, ClientFit Scout | Same two agent families, with a Q4 shadow-mode pilot for AdvisorLens | Match; vision under-develops them |
| Commercial horizon | Practice workbench first | White-label Kanzleien from Q1 2027 | Compatible sequencing |

## Section D: Key divergences and reconciliation decisions

**Diff 1: Metrics need a clear hierarchy (material):**
- Vision: measures recovered advisor time, accepted outcomes, low false-ready, and coverage.
- Internal delivery plan: operating proof is handling time falling; commercial metric is **Net Revenue per active Tax Advisor**.
- **Reconciliation (D021):** Handling time is the Month-1 to Month-9 operating proof. Net revenue per active TA is the business outcome. Recovered time, accepted outcomes, low false-ready, and coverage are the leading trust indicators that gate both.

**Diff 2: Proactive advisory is underweighted in the vision (material):**
- Vision: structured primarily around organize + process. Advisory agents appear late.
- Internal delivery plan: AdvisorLens has a Q4 shadow-mode pilot on one segment; the agent portfolio also includes ClientFit Scout.
- **Reconciliation (D020):** Run an advisor-gated, shadow-first Opportunity Radar in parallel from Month 1, using the evidence-backed opportunity-card format described in the vision. It informs advisor judgment and does not become a prerequisite for the core workflow.

**Diff 3: White-label is outside the near-term product vision:**
- Internal delivery plan: first white-label Kanzleien are planned for Q1 2027.
- Vision: focuses on proving the practice workbench and operating transformation first.
- **Reconciliation (D017 roadmap):** Place marketplace and white-label on the post-transformation horizon. The vision correctly defers them until the internal workflow is proven.

**Diff 4: Scope of "customers" (minor):**
- Vision: "German small and mid-sized tax practices."
- Internal: SE → SME → TA as a customer sequence; TAs play both partner and customer roles.
- **Reconciliation:** The vision's scope is correct for the first shot. Multi-market and marketplace expansion are later.

**Diff 5: Monitor substrate acknowledgement:**
- Internal: the TA platform is being built on the Monitor harness; efficiency agents are already built.
- Vision: reads as greenfield.
- **Reconciliation (D025):** Named agent families are future targets; Monitor substrate is operating context, not a current platform claim.

**Diff 6: PACS / Seal language:**
- Vision: PACS and formal sealing are not MVP scope.
- Internal delivery plan: requires a manual DATEV roundtrip and end-to-end mandate proof.
- **Reconciliation (D024):** Trace is the present evidence-and-review promise. Seal is a later trust-hardening stage.

## Source register (internal artifacts consulted)

| ID | Artifact | Where | Date | Confidence |
|---|---|---|---|---|
| INT-02 | TA Platform: H2 2026 Onsite Prep | Notion | 2026-06-29 | high |
| INT-03 | TA Platform Agent Overview | Notion | 2026-04-01 | medium |
| INT-04 | The Business Orchard Manifesto | Google Drive | 2026-07 | high |
| INT-05 | DE Self Employed Q2 QBR | Google Drive | 2026-07-13 | high |
| INT-06 | Overview: Launching a Self-Employed Product Line | Notion | 2025-10 | medium |
| INT-07 | Company OKRs / 06 May 2026 Breakfast | Google Drive | 2026-05-06 | high |
