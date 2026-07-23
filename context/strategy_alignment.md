# Handover: Product Vision ↔ Internal Strategy Alignment (self-contained)

- Artifact ID: ADV-MORNING-001-VIS-ALIGN-HANDOVER-A001
- Type: self-contained handover (companion to [`product_vision.md`](product_vision.md); **does not modify it**)
- Job ID: ADV-MORNING-001
- Owner: Product
- Prepared: 2026-07-17
- Companion detail file (for readers WITH Notion/Drive access): [`product_vision_internal_alignment.md`](product_vision_internal_alignment.md)

---

## How to read this document

**You do not need Notion, Gmail, Google Drive, or any external tool to use this handover.**
Everything you need is inline below.

- [`product_vision.md`](product_vision.md) (v0.11, 2026-07-16) lives in this repo — you can read it directly.
- The **internal business-strategy content it must align with does NOT live in the repo**. It
  was captured from Notion and Google Drive on **2026-07-17** and is **embedded verbatim-enough
  below** (Section A) so you can reason about it without fetching anything.
- Source names/dates are given for **provenance only** — you are not expected to open them.
- Treat Section A as a **dated snapshot**, not a live source. Where a source is old or its
  numbers were flagged as under revision, that is stated. Do not present snapshot figures as
  current without re-confirmation.

---

## Section A — Internal strategy snapshot (embedded; captured 2026-07-17)

This is the internal context the product vision was not written against. Read it as "the
business strategy of record as of mid-July 2026."

### A1. The business frame

> Source: "The Business Orchard Manifesto" (Google Drive, July 2026) and Company OKRs / all-hands deck (2026-05-06).

- Taxfix is transforming from **"a German, once-a-year, DIY-first business"** into a
  **"subscription-first, year-round financial partner … an AI-native platform."**
- Mission framing: **"Fix finance for entrepreneurs."**
- Customer sequence: **Self-Employed (SE, the heartland) → SME (graduation) → Tax Advisors (TA).**
- **Tax Advisors play two roles at once:**
  1. **Enablers / channel** — "a magic wand": equipping TAs lets Taxfix reach every freelancer and small business indirectly.
  2. **Customers in their own right** — a TA practice is itself a self-employed business with books, compliance, and growth needs.
- Operating principles: bold bets over incremental; ship to learn (MVP → launch → feedback → PMF); AI-first is "how we think," not a buzzword; own outcomes not tasks.

### A2. The customer service ladder (GBB)

> Source: Company OKRs / all-hands deck (2026-05-06).

**Good / Better / Best** maps to three service depths:
- **DIY** — self-service tax filing ("file taxes yourself, fast & easy").
- **DIWM ("do it with me")** — AI-driven expert support ("file with guidance, when you need it").
- **DIFM ("do it for me")** — personal tax accountant ("stress-free, done by experts").

Company vision slide: **"Serving every customer segment hyper-personalized through one
AI-native platform,"** with **"growing unique value to tax accountants through efficient AI
tooling"** as the TA lane. Demand signals cited: **82% of SE users require some level of
assistance**; **60%+ want an all-in-one** (personal + business filing + tooling) solution.

### A3. SE/SME segments and sizing

> Source: "Overview: Launching a Self-Employed Product Line in the German Market" (Notion, **Oct 2025** — a refresh research effort was noted as in flight; treat sizes as indicative, not final).

- Total addressable: **~2.5M solo self-employed in Germany**, **+460k new entrants/year**, TAM **~€680M/year**; VAT-obliged filers' willingness to pay **~€20–40/month**.
- Segments:

| Segment | Definition | Approx. size | Notes |
| --- | --- | --- | --- |
| Small Business Owners (SBO) | revenue ≤€25k prior year / ≤€100k current | ~1.2M | Largest; low willingness to pay; files once/year |
| VAT-liable freelancers (§18 EStG, Katalogberufe) | all freelancers not classed as SBO; no trade tax; EÜR | ~800k | **"Most attractive segment"**; monthly/quarterly VAT; high WTP |
| VAT-liable businesses, no bookkeeping obligation (§15 EStG Gewerbe) | profit ≤€80k or revenue ≤€800k | ~500k | Trade-tax complexity; high WTP |
| VAT-liable businesses, with bookkeeping obligation | profit >€80k or revenue >€800k | ~300k | Double bookkeeping; higher complexity |

- The **beachhead** is Self-Employed DIFM (see A5).

### A4. The TA-platform model — levers and stages

> Source: "TA Platform Vision" (Notion, **2026-07-07** — most recent and most authoritative for the platform).

**Revenue identity:** `Net revenue ≈ (TA count) × (clients per TA) × (revenue per client)`.

**Three levers:**
1. **Efficiency multiplier** — AI does routine work, TA reviews/signs off. *Already built (in the Monitor product):* **Tax Advisor Agent, Support Copilot, Document Review Agent.** Grows clients/TA. Explicitly called **"not a differentiator on its own — any competent AI tax tool ends up here."**
2. **Monetization multiplier** — AI surfaces which client needs which advice, from patterns Taxfix uniquely sees across clients. Delivered by agents **AdvisorLens** and **ClientFit Scout.** Grows revenue/client. **This is the stated differentiator.**
3. **Marketplace lever** — onboard, train, quality-check, and tier advisors so more can join. Grows TA count. **This is what makes white-label sellable.**

**Three stages of the platform:**
1. **Operational tool** — automates one case at a time; TA approves each step. *Status: partially built in Monitor.*
2. **Working machine** — runs continuously across the whole book; TA sees only exceptions/approvals. Signal it's real: **automation rate >90%.** *Status: not yet built.* Its primary automation levers include the **DATEV integration** (import/export roundtrip, then Klardaten automation) — see Diff 9.
3. **Opportunity machine** — scans the book for advisory/monetization patterns and surfaces them unprompted; TA decides. *Status: named, not yet running.*

**Important sequencing note:** "We will not wait for stage 2 to fully mature before starting
stage 3. They are loosely coupled: stage 2 is coverage, stage 3 is insight. Pilot stage 3
narrow (one segment) **in parallel** with stage 2 scaling."

**Loop shorthand:** **"Case → Prepare → Trace → Seal."**

**North Star (per this doc):** **ARPU** (average net revenue per client), decomposed into
baseline ARPU + ARPU uplift from surfaced opportunities.

**The marketplace** is described as a *fourth thing, not a fourth stage*: register/qualify →
train (academy) → quality-check → tier advisors.

**Governance stance:** the TA stays the gatekeeper — **every AI recommendation stops at the
TA; nothing goes direct to the client yet.**

### A5. Concrete 2026 delivery plan

> Source: "TA Platform — H2 2026 Onsite Prep" (Notion, **2026-06-29**).

**Ambition:** *"By the end of 2026, a Do-It-For-Me mandate runs from start to finish inside our
workspace, and we can show a tax advisor's handling time falling."*

- **Proof gate 1 — workspace live:** TA Dashboard live on Self-Employed DIFM.
- **Proof gate 2 — advisor faster:** handling time instrumented **and falling.**
- Targets by EOY 2026: **331 direct clients**, **~€37K exit MRR / ~€448K ARR**.
- **White-label: €0 in H2 by plan; first white-label Kanzleien in Q1 2027.**
- **Two halves:** Side A = marketplace (supply side; **prepared, not built** in H2). Side B = tooling (workspace, DATEV roundtrip, agents; **leads in H2**).
- **Hard dependency:** the **Self-Employed launch on 15 July 2026** — no case volume, no proof.
- **DATEV roundtrip working (manually first) = P0.** A TA must finish a whole mandate end-to-end.
- **North Star (this doc's Opportunity Canvas):** **"Net Revenue per active Tax Advisor."**
- Coordination guardrail: the **Monitor** team owns the income-tax side and the handling-time metric (RPTAH); the TA platform must not duplicate/contradict it.

**Timeline anchors (real calendar):**

| When | Milestone |
| --- | --- |
| 15 Jul 2026 | Self-Employed launch (hard dependency) |
| Q3 2026 | Stage-2 pilot: automation clears ~70% of tasks; marketplace + stage-3 scoping |
| 15 Oct 2026 | Stage 1 proven: operational tool at 50+ paying clients |
| Q4 2026 | AdvisorLens pilot live on one segment (GmbH), shadow-mode first |
| EOY 2026 | DIFM mandate end-to-end; 331 clients; handling time falling |
| Q1 2027 | Marketplace starter pool; first white-label clients |
| 2027 | Stage 2 + 3 at scale; white-label broadly |
| 2028 | "2028 Vision" horizon (referenced in the SE QBR) |

### A6. The named agent families

> Source: "TA Platform Agent Overview" (Notion, **2026-04-01** — agent set may have evolved since).

Multi-market (DE, ES, UK); deep legacy-system integration (DATEV, IRIS, A3). Five families:

| Agent | Role | What it does (short) |
| --- | --- | --- |
| **DataJanitor Pro** | Intake & normalisation | Ingests chaotic multi-channel client data (email, chat, PDFs, bank feeds), maps to chart-of-accounts (SKR03/04), produces GL-ready, DATEV-importable work packages with confidence scores |
| **FristenGuard** | Deadline & risk sentinel | Unifies deadlines across DATEV/calendar/tax-office inboxes; flags risk, missing docs, capacity clashes; weekly risk brief |
| **OpsMaestro** | Practice orchestration | Learns/codifies workflows, monitors WIP and bottlenecks, simulates capacity, proposes process changes |
| **AdvisorLens** | Proactive insight & advisory | Scans client GL/history for optimisation + cross-sell opportunities, drafts recommendations and client-ready packages (the monetization multiplier) |
| **ClientFit Scout** | Client qualification & tiering | Scores leads for profitability/operational fit, filters "chaos clients," recommends engagement tier and pricing |

SKU bundles named: **Core Ops** (FristenGuard + DataJanitor Pro), **Growth** (ClientFit Scout
+ AdvisorLens), **Enterprise** (all five).

### A7. Governance model

> Source: "Who Checks the Tax Return? — Five-Plane Governance for Taxfix" (Google Drive, 2026-06-15; internal position paper).

The AI-first TA platform is framed around a **five-plane runtime governance model** (reasoning
/ network / identity / endpoint / data planes) with **six interruption primitives** (allow /
deny / allow-with-modification / deny-with-explanation / escalate / log-only) — principle:
**"govern actions, not thoughts."** Positioned as the trust architecture that lets AI
preparation be reviewed by governed agents rather than only humans. Built on the internal
**Monitor** harness, whose stated trajectory is: internal ops tool → AI-first TA platform.

---

## Section B — What the product vision says (summary, so this handover stands alone)

> Full text: [`product_vision.md`](product_vision.md). Summarized here for a reader who wants the diff without re-reading it.

- Anchor: **"Codex for Tax Advisors"** — an **agentic workbench** (not a copilot, not an autonomous practice manager).
- **Month 9** is the operating transformation target; months 10–12 expand/harden. Monthly, evidence-gated steps.
- Start = trusted SOTA "Advisor Desk" (a full-day command center) **plus** one agentic differentiator from day one: **`intervention → handled outcome`** (Desk ranks an item → Taxfix proposes an outcome → Advisor starts/edits → agent plans, uses tools, checks → returns a sourced result or a clear blocker → Advisor accepts/returns → Taxfix monitors).
- **First deep job: bookkeeping-period preparation.**
- Responsibilities split: **organize** (broad) / **process** (one deep job) / **decide** (human).
- **"Rent the engine, own the vehicle"** — use replaceable external models; own tax context, evidence, workflow, authority, evaluation, integration, recovery.
- **Human authority fence:** professional judgment + consequential external actions stay human; reversible internal work may earn bounded autonomy.
- Success measured by recovered Advisor time, coverage, no false-ready, accepted outcomes.

---

## Section C — Alignment (where the two already agree)

| Theme | Product vision | Internal strategy | Verdict |
| --- | --- | --- | --- |
| Agentic direction | "Codex for Tax Advisors" agentic workbench | operational tool → working machine → opportunity machine (A4) | Strong match |
| First loop shape | `intervention → handled outcome` | "Case → Prepare → Trace → Seal" (A4) | Strong match |
| First deep job | Bookkeeping-period preparation | EOY-2026 DIFM mandate on SE + DATEV roundtrip (A5) | Strong match |
| Human authority | Advisor keeps judgment + external actions | "TA stays gatekeeper; nothing goes direct to client" (A4) | Strong match |
| Advisory agents | Names AdvisorLens, ClientFit Scout | Same two = the monetization multiplier (A4, A6) | Match (vision under-develops them — Diff 2) |
| Rent vs own | Own tax context/evidence/integrations | Reusable agent primitives; own DATEV/IRIS/A3 (A6) | Match |
| Segment | German small/mid practices serving SE + SMEs | SE → SME → TA; DE SE/SME segments (A1, A3) | Core match; scope differs — Diff 4 |

---

## Section D — The diff (divergences and gaps; proposals only, nothing applied)

Ordered by materiality.

### Diff 1 — North Star metric is inconsistent across sources ⚠️ material
- Vision: no single North Star; recovered time / accepted outcomes / coverage / no false-ready.
- A4 (TA Platform Vision): North Star = **ARPU**.
- A5 (H2 Onsite): North Star = **"Net Revenue per active Tax Advisor"**; operating proof = **handling time falling**.
- **Reconcile:** handling-time = month-1→9 operating proof (efficiency); ARPU / net-revenue-per-TA = the business North Star the opportunity machine unlocks (monetization); the vision's trust metrics gate both. Name the hierarchy so three docs stop citing three different top metrics.

### Diff 2 — Monetization / opportunity machine is underweighted in the vision ⚠️ material
- Vision: built around organize + process (efficiency/coverage); client-value detection arrives late ("assist, later delegate").
- Internal (A4): monetization is **the differentiator**; efficiency is table stakes; stage 3 pilots **in parallel** with stage 2 (GmbH, Q4 2026, shadow-first).
- **Reconcile:** add a parallel opportunity-machine track early in the vision timeline (shadow first, TA-gated), matching "don't wait for stage 2."

### Diff 3 — Marketplace + white-label are absent from the vision ⚠️ material
- Vision: ends at "Advisor Desk becomes the default operating model." No marketplace, no white-label.
- Internal (A4, A5): marketplace (register/qualify → train → QA → tier) is a first-class lever; **white-label** (external Kanzleien pay to run their own clients) is the commercial payoff, first clients **Q1 2027**.
- **Reconcile:** add a marketplace/white-label horizon after the month-9 default (fits the vision's "months 10–12 expand and harden") as the supply-side lever.

### Diff 4 — Segment framing is narrower/flatter in the vision
- Vision: "German small/mid tax practices serving SE + SMEs" — TA is the user, DE-only, one flat cohort.
- Internal (A1, A3, A6): SE is the heartland end-customer, SME graduation, TA = channel **and** customer; segments are sized/tiered; agents are multi-market (DE/ES/UK).
- **Reconcile:** bind the vision's open "which Advisors / which jobs" (its question O006) to a concrete SE segment (VAT-liable freelancers ~800k = "most attractive") and the DIFM-on-SE beachhead; DE-first, ES/UK later.

### Diff 5 — Relative "months" vs the real calendar
- Vision: months 1–9 unanchored.
- Internal (A5): hard dates (15 Jul 2026 SE launch → EOY 2026 DIFM mandate → Q1 2027 white-label → 2028 vision).
- **Reconcile:** anchor vision "month 1" to a real date. If month 1 ≈ DIFM-on-SE workspace going live (~post 15 Jul 2026), month 9 ≈ ~Q1 2027 (≈ white-label start).

### Diff 6 — Named agent families missing from the vision's orchestration story
- Vision: generic "office manager + workers."
- Internal (A6): concrete set — DataJanitor Pro, FristenGuard, OpsMaestro, AdvisorLens, ClientFit Scout + SKU bundles.
- **Reconcile:** map vision phases to these agents (DataJanitor Pro + DATEV roundtrip = month-1 bookkeeping wedge; FristenGuard = wait/deadline ownership; AdvisorLens/ClientFit Scout = opportunity machine).

### Diff 7 — "Seal" / governance vocabulary clash
- Repo `CLAUDE.md` + vision: PACS and formal **Seal** removed from PoC/MVP; "Seal is post-MVP"; formal sealing listed as a non-goal.
- Internal (A4): platform loop is literally **"Case → Prepare → Trace → Seal"**; (A7) a five-plane governance model is central.
- **Reconcile:** clarify "Trace → Seal" = the durable evidence/audit *promise* (which the vision keeps as source-linked evidence + review packages); formal PACS sealing = the deferred *implementation*. Align vocabulary so "Seal" isn't read as both required and dropped.

### Diff 8 — Efficiency layer already exists; the vision reads greenfield
- Vision: workbench largely to-be-built; repo PoC limited to `csv_reader`.
- Internal (A4, A5): efficiency agents already built in Monitor (Tax Advisor Agent, Support Copilot, Document Review Agent); Q3 2026 targets ~70% automation.
- **Reconcile:** credit the existing Monitor efficiency agents as the month-1 substrate (repo PoC ≠ production Monitor stack).

### Diff 9 — DATEV integration: separate initiative, or a working-machine feature? ⚠️ material (product decision)
- **Scoping doc** (`docs/datev-agent-system-scoping.md`, 2026-07-08): frames the external DATEV Agent System PRD as "not a feature for this repo … its own initiative, own repo," distinct from the harness.
- **Internal strategy (A4, A5, A6):** DATEV automation is a **core automation lever of the working machine** — the H2 plan makes the DATEV roundtrip **P0**, the roadmap names closing "the two biggest manual steps: **DATEV CSV import and Bescheid upload**," **DataJanitor Pro** emits DATEV-ready packages (SKR03/04), and **Klardaten** (DATEV automation) is the scale lever into 2027.
- **Product decision (2026-07-17):** DATEV integration is **one feature of the TA Platform and a major part of the automation process** — it belongs inside the **working-machine** stage, not as an unrelated product.
- **Reconcile:** distinguish (a) the *capability* — DATEV import/export + eventual computer-use fallback — which is a working-machine feature of the platform, from (b) the *legal/BD build track* — the 94-page DATEV Agent System PRD gated by DATEV AGB consent + GFR.ai/Klardaten commercial deals — which may still run as its own delivery track. The scoping doc's "separate repo" point is about legal/sequencing isolation **and about the harness PoC specifically** (PoC ≠ production TA Platform); it is not a reason to exclude DATEV from the platform's automation story.

---

## Section E — Open questions for Product

1. **North Star:** adopt the handling-time (operating) / ARPU (business) hierarchy in Diff 1, or pick one top metric across all docs?
2. **Opportunity machine timing:** adopt the "pilot in parallel, shadow-first" stance (A4), or keep advisory at month 9?
3. **Marketplace/white-label:** carry it in the vision, or keep the vision single-TA-experience by design?
4. **Rollout cohort:** bind the vision's month-9 cohort to which SE segment (A3)?
5. **Calendar anchor:** what real date is vision "month 1"?
6. **"Seal" vocabulary:** reconcile A4's "Case → Prepare → Trace → Seal" with the repo's post-MVP-Seal decision.

---

## Section F — Provenance, freshness, and what was NOT changed

- **Snapshot date:** 2026-07-17. Section A is a captured copy, not live.
- **Freshness flags:** A3 segment sizing is from **Oct 2025** with a refresh noted as in flight — re-confirm before relying on the numbers. A6 agent set is from **Apr 2026** and may have evolved.
- **Provenance:** all Section A content came from internal Notion pages and Google Drive files listed by name at each subsection; a reader without access cannot verify them and should treat them as reported, not independently confirmed.
- **Not changed:** `product_vision.md`, `sota_benchmark.md`, `sota_advisor_desk.md`, the transcripts, and the SOTA mockup are untouched. No internal source was edited (all read-only). The only artifacts added are this handover and its companion detail file.
