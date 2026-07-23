# Product Vision ↔ Internal Strategy Alignment

- Artifact ID: ADV-MORNING-001-VIS-ALIGN-A001
- Artifact type: alignment-note (companion to the product vision; **does not modify it**)
- Job ID: ADV-MORNING-001
- Owner: Product
- Created: 2026-07-17
- Compares: [`product_vision.md`](product_vision.md) v0.11 (2026-07-16)
- Against: internal Notion + Google Drive strategy artifacts (see source register)
- Method: internal search across Notion and Google Drive for the **tax advisor platform** and **self-employed / SME (SE/SME)** work; full read of the most recent and most authoritative artifacts; manual diff against the vision.

> **Scope contract.** This note is additive. It records the internal information the
> product vision did not cite and explains where the two agree, where they diverge, and
> what must be reconciled. It changes nothing in `product_vision.md`. Every claim below is
> grounded in a dated internal source; where a source is older or lower-confidence, that is
> stated.

---

## Source register (internal artifacts consulted)

| ID | Artifact | Where | Date | Authority for | Confidence |
| --- | --- | --- | --- | --- | --- |
| INT-01 | 🌱 TA Platform Vision | Notion | 2026-07-07 | The canonical TA-platform vision: three-stage model, three levers, ARPU North Star, roadmap | high (most recent, most direct) |
| INT-02 | 🦾 TA Platform — H2 2026 Onsite Prep (Draft) | Notion | 2026-06-29 | Concrete 2026 delivery: DIFM mandate, TA Dashboard, handling time, white-label, dependencies | high |
| INT-03 | 🤖 TA Platform Agent Overview | Notion | 2026-04-01 | The named agent families and their capabilities | medium (Apr; agent set may have moved) |
| INT-04 | The Business Orchard Manifesto | Google Drive (markus@) | 2026-07 | Overarching business frame: SE → SME → TA, AI-first, ways of working | high |
| INT-05 | [DE Self Employed] Q2 QBR | Google Drive | 2026-07-13 | SE segment state, "2028 Vision", Business Backoffice, assistance demand | high (recent) |
| INT-06 | Overview: Launching a Self-Employed Product Line (DE) | Notion | 2025-10 | SE/SME segment definitions and sizing, TAM | medium (Oct 2025; refresh research noted as in-flight) |
| INT-07 | Company OKRs / 06 May 2026 Breakfast | Google Drive | 2026-05-06 | GBB (DIY/DIWM/DIFM) ladder, segment strategy, AI-native operating model | high |
| INT-08 | Self-Employed Strategy 2026 | Notion | 2025-10 | KU (Kleinunternehmer) monetization, SE strategy | medium (Oct 2025) |
| INT-09 | Who Checks the Tax Return? — Five-Plane Governance | Google Drive (Tobias) | 2026-06-15 | Governance model for the AI-first TA platform; Monitor harness proof | medium (position paper) |
| INT-10 | DATEV_Agent_PRD_Final / working-backwards | Google Drive | 2026-06-12 | DATEV agent system, harness build direction | medium |

---

## The internal strategy in brief (what the company has already defined)

**The business frame (INT-04, INT-07).** Taxfix is transforming from "a German, once-a-year,
DIY-first business" into a "subscription-first, year-round financial partner … AI-native
platform." The Business Orchard exists to **"fix finance for entrepreneurs."** The stated
sequence is **SE (heartland) → SME (graduation) → Tax Advisors**, and TAs are held in **two
roles at once**: partners/enablers ("a magic wand" that lets Taxfix reach every freelancer)
**and** customers in their own right (a TA practice is itself a self-employed business).

**The customer ladder (INT-07).** Good / Better / Best = **DIY** (self-service filing) →
**DIWM** (AI-driven expert support, "do it with me") → **DIFM** (personal tax accountant,
"do it for me"). The mission slide: "Serving every customer segment hyper-personalized
through one AI-native platform," with "growing unique value to tax accountants through
efficient AI tooling" as the TA lane.

**SE/SME segments and sizing (INT-06).** ~2.5M solo self-employed in DE, +460k new entrants/yr,
TAM ~€680M/yr; WTP ~€20–40/month for VAT-obliged filers:
- **SBO** ~1.2M (revenue ≤€25k prior / ≤€100k current) — acquisition, low WTP;
- **VAT-liable freelancers** ~800k (§18 EStG Katalogberufe, no trade tax, EÜR) — most attractive;
- **VAT-liable businesses w/o bookkeeping obligation** ~500k (§15 EStG Gewerbe, profit ≤€80k or revenue ≤€800k, trade tax) — attractive, trade-tax complexity;
- **VAT-liable businesses w/ bookkeeping obligation** ~300k (>€80k / >€800k, double bookkeeping) — higher complexity.

**The TA platform model (INT-01).** Net revenue ≈ **TA count × clients per TA × revenue per
client**, driven by three levers:
1. **Efficiency multiplier** — AI does routine work, TA reviews/signs. *Already built:* Tax Advisor Agent, Support Copilot, Document Review Agent. Grows clients/TA. "Not a differentiator on its own."
2. **Monetization multiplier** — AI surfaces who needs what advice from patterns Taxfix uniquely sees across clients (**AdvisorLens, ClientFit Scout**). Grows revenue/client.
3. **Marketplace lever** — onboard, train, quality-check, tier advisors so more can join. Grows TA count. This is what makes **white-label** sellable.

**Three stages (INT-01):** operational tool (one case at a time, *partially built in Monitor*)
→ **working machine** (runs the whole book, >90% automation) → **opportunity machine** (scans
the book for advisory/monetization patterns unprompted). Loop shorthand: **"Case → Prepare →
Trace → Seal."** North Star = **ARPU**. TA stays the gatekeeper — nothing goes direct to the
client yet.

**Concrete 2026 delivery (INT-02).** Ambition: **a Do-It-For-Me mandate runs end-to-end inside
the workspace by EOY 2026, and a tax advisor's handling time is measurably falling.** Proof
gate 1 = TA Dashboard live on Self-Employed DIFM; proof gate 2 = handling time instrumented and
falling. Targets: 331 direct clients, ~€37K exit MRR / ~€448K ARR. **White-label = €0 in H2 by
plan; first white-label Kanzleien Q1 2027.** Hard dependency: the **Self-Employed launch on
15 July 2026**. The DATEV roundtrip (manual first) is P0. Monitor owns the income-tax side and
the RPTAH handling-time metric — the TA platform must not duplicate it.

**The agent families (INT-03):** DataJanitor Pro (intake/normalisation), FristenGuard
(deadline/risk sentinel), OpsMaestro (practice orchestration), **AdvisorLens** (proactive
insight/advisory), **ClientFit Scout** (client qualification/tiering). Multi-market (DE, ES,
UK), deep legacy integration (DATEV, IRIS, A3). SKU bundles: Core Ops, Growth, Enterprise.

**Governance (INT-09).** The AI-first TA platform is framed around a five-plane runtime
governance model (reasoning / network / identity / endpoint / data) and six interruption
primitives — "govern actions, not thoughts" — proven on the Monitor harness.

---

## Where the vision and the internal strategy already agree

| Theme | Product vision (`product_vision.md`) | Internal strategy | Verdict |
| --- | --- | --- | --- |
| Agentic direction | "Codex for Tax Advisors" agentic workbench; workbench drives routine work | Three-stage "operational tool → working machine → opportunity machine" (INT-01); AI-native platform (INT-04, INT-07) | **Strong match** |
| First loop shape | `intervention → handled outcome` (start → plan → tool work → sourced result / blocker) | "Case → Prepare → Trace → Seal" (INT-01) | **Strong match** |
| First deep job | Bookkeeping-period preparation as the first executable job | EOY-2026 DIFM mandate on Self-Employed, DATEV roundtrip (INT-02) | **Strong match** |
| Human authority fence | Advisor keeps judgment + consequential actions; agents stop at gates | "TA stays the gatekeeper; nothing goes direct to the client yet" (INT-01) | **Strong match** |
| Advisory/monetization agents | Vision names AdvisorLens and ClientFit Scout in passing | Same two agents are the monetization multiplier (INT-01, INT-03) | **Match** (vision under-develops them — see Diff 2) |
| Rent-vs-own | "Rent the engine, own the vehicle"; own tax context, evidence, integrations | Agent primitives reusable across B2C/Ops/TA; own DATEV/IRIS/A3 integration (INT-03) | **Match** |
| Segment | German small/mid practices serving self-employed + SMEs | SE → SME → TA; DE SE/SME segments (INT-04, INT-06) | **Match on core; scope differs — see Diff 4** |

---

## The diff — where the vision and internal strategy diverge or leave gaps

Ordered by materiality. Each item states what the vision says, what internal sources say, and
a recommended reconciliation. **None of these are applied to the vision** — they are proposals.

### Diff 1 — North Star metric is inconsistent across all three sources ⚠️ material

- **Vision:** deliberately sets *no single* North Star; measures success as recovered Advisor time, accepted outcomes, low false-ready, coverage.
- **INT-01 (TA Platform Vision):** North Star = **ARPU** (revenue per client), explicitly to capture "turning *working* into *opportunity*."
- **INT-02 (H2 Onsite):** Opportunity Canvas North Star = **"Net Revenue per active Tax Advisor"**, and the *operating* proof metric = **handling time falling**.
- **Why it matters:** three different top metrics (recovered time vs ARPU vs net revenue/TA) will pull the roadmap in different directions. ARPU rewards the *monetization* lever; handling time rewards the *efficiency* lever; the vision's framing rewards *trust/coverage*.
- **Recommended reconciliation:** treat handling-time (efficiency) as the **month-1→month-9 operating proof**, ARPU/net-revenue-per-TA (monetization) as the **business North Star the opportunity machine unlocks**. The vision's "recovered time / accepted outcomes" are the *leading* trust indicators that gate both. State this hierarchy explicitly so the vision, INT-01, and INT-02 stop naming different top metrics.

### Diff 2 — The monetization lever + opportunity machine are underweighted in the vision ⚠️ material

- **Vision:** structured almost entirely around **organize + process** (efficiency, coverage, follow-through). Client-value detection appears as one capability late in the ladder ("assist, later delegate").
- **INT-01:** the **monetization multiplier is the differentiator** — "any competent AI tax tool ends up" at efficiency; the moat is AdvisorLens/ClientFit Scout surfacing advisory opportunities from cross-client patterns. Stage 3 (opportunity machine) is piloted **in parallel** with stage 2, not after it (GmbH segment, Q4 2026).
- **Why it matters:** the vision's paced ladder implicitly defers the exact capability the business calls the differentiator, and its "supervise by exception and advise" phase lands only at month 9.
- **Recommended reconciliation:** elevate an **opportunity-machine track** that runs in parallel from early in the vision's timeline (shadow first, per INT-01), mirroring the "we will not wait for stage 2 to mature before starting stage 3" stance. Keep it TA-gated.

### Diff 3 — Marketplace + white-label business model is absent from the vision ⚠️ material

- **Vision:** ends at "the Advisor Desk becomes the default operating model." No marketplace, no white-label, no external-TA commercialization.
- **INT-01 / INT-02:** the **marketplace** (register/qualify → train → quality-check → tier advisors) is a first-class lever, and **white-label** (external Kanzleien pay to run their own clients on the platform) is the commercial payoff — first white-label clients **Q1 2027**. INT-02 frames delivery as "two halves": tooling (leads in H2) + marketplace (prepared in H2, built Q1 2027).
- **Why it matters:** the vision's scope stops one layer short of how the platform actually makes money and scales TA count. A reader of only the vision would not know white-label exists.
- **Recommended reconciliation:** add a marketplace/white-label horizon *after* the month-9 default (maps naturally to the vision's "months 10–12 expand and harden"), noting it is the supply-side lever, not a change to the single-TA experience.

### Diff 4 — Segment framing and market scope are narrower/flatter in the vision

- **Vision:** "German small and mid-sized tax **practices** serving self-employed and SMEs" — the TA is the user, DE-only, one flat cohort.
- **Internal:** SE is the **heartland end-customer**, SME is graduation, and the TA is simultaneously a **channel** to reach SE/SME *and* a customer (INT-04). Segments are sized and tiered (INT-06: SBO 1.2M / VAT freelancers 800k / businesses 500k+300k). Agent docs are **multi-market (DE/ES/UK)** (INT-03).
- **Why it matters:** the vision treats "serving SE/SME" as background, but internally the TA platform's *reason to exist* is to serve SE/SME at scale through advisors. The month-9 rollout cohort (vision open question O006) should be chosen from INT-06's sized segments, not invented.
- **Recommended reconciliation:** anchor the vision's open "which Advisors / which jobs" (O006) to the concrete SE segments and the DIFM-on-SE beachhead (INT-02/INT-06); note DE-first with ES/UK as a later multi-market horizon.

### Diff 5 — Relative "months" vs the real calendar

- **Vision:** months 1–9 are relative, unanchored.
- **Internal (INT-01, INT-02):** hard dates — SE launch **15 Jul 2026**, DIFM mandate end-to-end **EOY 2026**, stage-2 pilot **Q3 2026** (70% automation), stage-1 proven **15 Oct 2026** (50+ paying clients), AdvisorLens GmbH pilot **Q4 2026**, marketplace starter pool **Q1 2027**, white-label + scale **2027**, "2028 Vision" (INT-05).
- **Recommended reconciliation:** add a one-row mapping of vision month 1 → real date so "month 9" resolves to a real quarter and the vision's gates line up with INT-01's roadmap milestones. (If month 1 ≈ the DIFM-on-SE workspace going live, month 9 ≈ ~Q1 2027, i.e. around white-label start.)

### Diff 6 — The named agent families are missing from the vision's orchestration story

- **Vision:** describes an "office manager + workers" multi-agent pattern generically.
- **INT-03:** the concrete agent set — DataJanitor Pro, FristenGuard, OpsMaestro, AdvisorLens, ClientFit Scout — with capabilities, dependencies, and SKU bundles (Core Ops / Growth / Enterprise).
- **Recommended reconciliation:** map the vision's phases to these agents (e.g. DataJanitor Pro + DATEV roundtrip = the month-1 bookkeeping wedge; FristenGuard = wait/deadline ownership; AdvisorLens/ClientFit Scout = the opportunity machine). Keeps the vision consistent with the already-designed agent portfolio.

### Diff 7 — "Seal" and the governance model: in or out?

- **Vision / repo `CLAUDE.md`:** PACS and formal Plan→Act→Check→**Seal** are removed from the PoC/MVP; "Seal is post-MVP"; "PACS or formal sealing as an MVP dependency" is listed as a **non-goal**.
- **INT-01:** the TA-platform loop is literally **"Case → Prepare → Trace → Seal"** — Seal is *in* the shorthand.
- **INT-09:** a five-plane runtime governance model is positioned as the platform's trust architecture.
- **Why it matters:** terminology clash — the business vision keeps "Seal" as the trust anchor while the current build deliberately defers it. This is a naming/sequencing question, not necessarily a contradiction (Seal-as-concept vs formal-PACS-Seal-as-MVP-dependency).
- **Recommended reconciliation:** clarify that "Trace → Seal" in INT-01 is the *durable evidence/audit* promise (which the vision does keep, as source-linked evidence + review packages), and that formal PACS sealing is the deferred *implementation*, not the deferred *promise*. Align vocabulary so "Seal" isn't read as both required and dropped.

### Diff 8 — Efficiency work already exists; the vision reads greenfield

- **Vision:** presents the agentic workbench as largely to-be-built, with today's PoC limited to `csv_reader`.
- **INT-01:** the **efficiency multiplier is already built** — Tax Advisor Agent, Support Copilot, Document Review Agent in Monitor; automation is being instrumented toward >90%. INT-02 targets 70% automation in Q3 2026.
- **Recommended reconciliation:** the vision's month-1 "trusted Desk + one real loop" should credit the existing Monitor efficiency agents as the starting substrate, not imply a cold start. (The repo PoC ≠ the production Monitor stack.)

### Diff 9 — DATEV integration: separate initiative vs working-machine feature ⚠️ material (product decision)

- **Scoping doc** (`docs/datev-agent-system-scoping.md`, 2026-07-08): frames the external DATEV Agent System PRD as "not a feature for this repo … its own initiative, own repo."
- **INT-01 / INT-02 / INT-03:** DATEV automation is a core **working-machine** lever — the DATEV roundtrip is P0, the roadmap names closing "DATEV CSV import and Bescheid upload," DataJanitor Pro emits DATEV-ready packages (SKR03/04), and Klardaten (DATEV automation) is the scale lever into 2027.
- **Product decision (2026-07-17):** DATEV integration is **one feature of the TA Platform and a major part of the automation process**; it sits inside the **working-machine** stage, not as an unrelated product.
- **Recommended reconciliation:** separate the *capability* (DATEV import/export + computer-use fallback = a working-machine feature of the platform) from the *legal/BD build track* (the 94-page PRD gated by DATEV AGB consent + GFR.ai/Klardaten deals, which may run as its own delivery track). The scoping doc's "separate repo" point is about legal/sequencing isolation and the harness PoC specifically (PoC ≠ production TA Platform), not about excluding DATEV from the platform's automation story.

---

## Open questions this alignment surfaces (for Product)

1. **North Star:** confirm the handling-time (operating) / ARPU (business) hierarchy in Diff 1, or pick one top metric across the vision, INT-01, and INT-02.
2. **Opportunity machine timing:** does the vision adopt INT-01's "pilot stage 3 in parallel, shadow-first" stance, or keep advisory at month 9?
3. **Marketplace/white-label:** should the vision explicitly carry the supply-side lever and the Q1-2027 white-label milestone, or stay single-TA-experience only by design?
4. **Rollout cohort (vision O006):** bind to which SE segment from INT-06 (VAT-liable freelancers ~800k is the "most attractive")?
5. **Calendar anchor:** what real date is vision "month 1" — the DIFM-on-SE workspace going live (post 15 Jul 2026)?
6. **"Seal" vocabulary:** reconcile INT-01's "Case → Prepare → Trace → Seal" with the repo's post-MVP-Seal decision.

---

## What was NOT changed

- `product_vision.md` — untouched.
- `sota_benchmark.md`, `sota_advisor_desk.md`, transcripts, the SOTA mockup — untouched.
- No internal source was edited; all were read-only.

This note is the only artifact added.
