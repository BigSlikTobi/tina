# Source Audit: `agentic_mvp.md` — inconsistencies, unbacked claims, and gaps

- Audit target: [`agentic_mvp.md`](agentic_mvp.md) — "Agentic MVP: The first Tax Advisor platform shot" (ADV-MORNING-001-MVP-A001, v1.0, 2026-07-18)
- Audit date: 2026-07-19
- Method: each active claim/decision cross-checked against (a) the MVP's own cited repo sources and (b) the **live** internal strategy in Notion + Google Drive (fetched 2026-07-19), not only the repo's 2026-07-17 snapshot.
- Verdict in one line: **All F1–F5 findings are closed: F1 resolved by D016, F2 and F4/F5 acknowledged as deliberate choices, F3 invalidated (PoC is not a source constraint for the MVP build). Only eight low-severity documentation-hygiene items (L1–L8) remain open.**

---

## How to read this audit

The MVP is a **discovery-stage** artifact (gate = hold, "stay in discovery and narrow the proof contract"). It *deliberately* defers metrics, calendar dates, real data, and most of the business model. A fair audit must separate:

- **Genuine inconsistency** — the MVP contradicts a source it cites, or contradicts itself.
- **Unbacked / provenance-thin** — asserted as fact but not supported by the sized internal research.
- **Realism gap** — internally consistent for synthetic replay, but soft-pedals a real-world viability problem.
- **Legitimately deferred** — absent, but explicitly and reasonably scoped out (these are *not* findings; they are listed at the end so the reader doesn't over-react to them).

Every finding below states the strongest counter-argument, because several plausible-looking findings do not survive one (an adversarial verification pass refuted five candidate findings outright — see Methodology).

---

## Findings, ranked

| # | Finding | Type | Severity | Status |
| --- | --- | --- | --- | --- |
| F1 | "SOTA daily Advisor workbench" is a co-equal **must-have**, contradicting the MVP's own SOTA benchmark (D013) which puts the whole-book desk in the *later* horizon, and the manifesto's depth-before-breadth refusals | Inconsistency (vs cited source) | **High** | **Resolved — D016 (2026-07-19)** |
| F2 | Cohort qualifiers "low-document-volume" and "digital consultants" are product-directed, not backed by the sized SE research the strategy actually contains | Unbacked / provenance-thin | **Medium** | **Acknowledged — accepted product assumption; risk is known and will drive adaptation** |
| F3 | The `csv_reader`-only capability floor makes the headline "reconcile transactions and invoices" value depend on synthetic CSV invoices; real freelancer invoices are PDFs → `needs_capability` | Realism gap | **Medium** | **Invalidated — finding relied on the PoC's current state, which is not a constraint on the MVP build** |
| F4 | The MVP carries **no** North Star, and omits even the one MVP-altitude, replay-evaluable north-star its own cited manifesto defines | Gap (partly deferred) | **Low–Medium** | **Acknowledged — deliberate hold, gated on O004** |
| F5 | DataJanitor Pro is re-scoped to "reconciles the period" (not in its internal definition); the agent team silently blends two different internal agent taxonomies | Inconsistency (vs cited source) | **Low–Medium** | **Acknowledged — deliberate scope choice, covered by the "target roles" footnote** |
| — | Minor notes (decision count, vocabulary drift, GFR/Bescheid omission, marketplace not in the MVP's own deferral list) | Housekeeping | Low | Open |

---

## F1 — "SOTA daily workbench" as a must-have contradicts the MVP's own SOTA benchmark  ·  ~~High~~ **Resolved — D016 added 2026-07-19**

**What the MVP says.** D001: *"The first shot is a SOTA-complete daily Advisor workbench plus one deep agentic bookkeeping workflow."* Kano **must-have #1**: *"SOTA daily Advisor workbench — All important clients, deadlines, tasks, waits, blockers, reviews, owners, sources, and next actions stay visible … Without this, the Advisor still needs the market solution to run the day."*

**What the cited sources say.**
- **SOTA benchmark** (SOTA-A001, an MVP input artifact), decision **D013**, active, 2026-07-17: *"Use two horizons. First wedge: `SE-DIFM bookkeeping mandate → evidence-linked, review-ready package → controlled DATEV handoff`. Later SOTA: a whole-book working machine across the practice. **Do not use the later horizon to inflate the first-wedge claim.**"* And: *"A cross-system daily home base is later SOTA. The first wedge starts with the bookkeeping mandate and a controlled DATEV handoff."* The full-workday command-center scope (SOTA-D001) is explicitly **superseded**.
- **Manifesto** (cited for four E-rows): principle 9 *"Depth before breadth. One real end-to-end workstream beats twenty shallow modules";* and "What we refuse" includes *"A second maintained 'SOTA app' beside the agentic product"* and *"Generic platform work before one real workflow works."*
- **Platform context** (cited): *"Individual income-tax filing is not the first MVP wedge"* — i.e., the first wedge is deliberately narrow.

**Why it matters.** The SOTA benchmark's central 2026-07-17 decision was to **shrink** the first wedge to the bookkeeping mandate and push the whole-book daily command center into "later SOTA," precisely so the first-wedge claim isn't inflated. The MVP re-promotes that daily command center to a co-equal **must-have #1** of the first shot — the exact move D013 warns against. Because "must-have" sets build scope, this materially widens the MVP beyond what its own benchmark confirmed.

**Root cause — an unreconciled conflict between two cited inputs.** The MVP's *other* primary input, the product vision, *does* re-introduce the SOTA desk (vision start = "trusted SOTA Advisor Desk (a full-day command center) **plus** one agentic differentiator"). So the MVP inherited a genuine conflict between its inputs — SOTA benchmark (narrow, bookkeeping-only) vs product vision (SOTA desk + agentic job) — and silently sided with the broader one without reconciling the narrower.

**Strongest counter-argument (why it's not fatal).** The MVP tries to bound the breadth: the Alignment table says *"Breadth stays at the control layer. Deep execution stays with bookkeeping,"* and must-have #1's proof is only *"a synthetic book shows no hidden work."* So it's "broad visibility, one deep execution," not twenty deep modules. Still, D013 puts even the *control-layer* cross-system home base in the later horizon, so a co-equal must-have remains in tension with the cited benchmark.

**Resolution (2026-07-19).** Option (b) was chosen. D016 has been added to the MVP's evidence and decision register: *"The MVP explicitly supersedes SOTA benchmark D013's two-horizon framing. The SOTA-complete daily Advisor workbench is a must-have of the first shot, not a later-horizon addition. A product that launches below SOTA parity at the control layer forces the Advisor to keep the market solution for most of their day. One deep agentic mission runs inside that workbench, not alongside a stripped shell."* The decision traces to the original discovery conversation (T-013: *"yeah, now we are talking, this is what I see as starting point"*) and is now explicit rather than implied. The contradiction is closed.

---

## F2 — Cohort qualifiers "low-document-volume" and "digital consultants" are not backed by the sized research  ·  **Medium**

**What the MVP says.** E002 (fact, active, confidence *"high for intended scope"*): *"The first intended cohort is German, low-document-volume, VAT-liable freelancers and digital consultants in SE-DIFM,"* sourced to `product_vision.md#current-user-truth`.

**What the sources actually support.**
- The product vision's cohort row (VIS-E027) sources the same claim to the **DATEV ecosystem review** — explicitly a *"provenance only, not web-verifiable"* internal snapshot — and VIS-D019 records it as a **"User confirmation."** The vision itself flags: *"Missing user evidence: We do not yet have verified eligible case volume, direct observation … or proof that this cohort will trust the flow."*
- The **sized** SE research (Notion, "Launching a Self-Employed Product Line," Oct 2025) supports **"VAT-liable freelancers ~800k = most attractive segment,"** TAM ~€680M/yr, WTP ~€20–40/mo — but says **nothing** about "low-document-volume" or "digital consultants." The MVP does not cite these numbers at all.

**Why it matters.** The two operative qualifiers that actually define the beachhead — "low-document-volume" and "digital consultants" — are product-directed choices, not market evidence. They are presented as an active *fact* rather than an assumption. The MVP's own "Assumptions" line half-acknowledges this (*"The proposed first cohort remains the right replay cohort until the exact contract is confirmed"*), but E002's "fact / high" framing overstates the grounding.

**Strongest counter-argument.** E002 honestly qualifies confidence as *"high for intended scope"* (not "high, validated"), and the cohort is internally consistent with the sibling vision. So this is a provenance-*depth* issue (the citation chain bottoms out in user direction), not a fabrication.

**Note the coupling to F3:** "low-document-volume" is load-bearing — it's what keeps the `csv_reader`-only happy path viable — yet it is exactly the unvalidated qualifier.

**Recommendation.** Re-label "low-document-volume / digital consultants" as a **hypothesis** to validate (tie to open question O004), and cite the ~800k "most attractive segment" sizing as the evidence that *does* exist for the broader VAT-liable-freelancer cohort.

**Acknowledged (2026-07-19).** This is an accepted product assumption. The risk — that the cohort turns out to have more documents than expected — is known and will drive product adaptation as evidence arrives. No change required.

---

## F3 — `csv_reader`-only floor vs an invoice-reconciliation value proposition  ·  **Medium**

**What the MVP says.** Headline value (Kano must-have "One deep bookkeeping mission"; DataJanitor Pro; agent loop "Prepare"): *"reconcile transactions, invoices, and open items."* Capability allowlist: *"Active approved `csv_reader` and `csv_read`"* only; *"Unsupported PDF, Word, image, and sheet parsing must stop visibly."*

**The tension.** Reconciliation needs invoice data. Real self-employed invoices are overwhelmingly **PDF/image**, which under the MVP's own rules stop at `needs_capability` — there is no active `pdf_reader` (the platform context and CLAUDE.md confirm `pdf_reader` is detected-but-not-implemented). So the headline "reconcile invoices" only works when invoices arrive as **synthetic CSV/text** fixtures.

**Why it's (barely) internally consistent.** The manifesto resolves it: *"Use versioned synthetic CSV and text fixtures for the first happy path,"* and the MVP lists "Broad binary document support" as a *later* accelerator and includes an "Unsupported capability" required scenario. So for **replay**, it holds.

**Why it's still a finding.** The first *genuinely useful* real case almost certainly needs a `pdf_reader` that is explicitly not built. The MVP presents invoice reconciliation as a core must-have without foregrounding that, absent PDF support, the supported happy path is CSV-only — a real-world viability gap softened by the (unvalidated, per F2) "low-document-volume" cohort choice.

**Recommendation.** State plainly that the MVP happy path is CSV/text-only and that real-invoice reconciliation is gated on a future validated `pdf_reader`; make "how many target invoices are non-CSV" an explicit part of the O004 input contract.

**Invalidated (2026-07-19).** This finding used the PoC harness's current `csv_reader`-only implementation as a constraint on the MVP. The PoC is not a source for the MVP build — the MVP will be built with the capabilities it requires, including document reading beyond CSV. The finding does not apply to the MVP artifact.

---

## F4 — No North Star, and the one in-scope north-star from its own manifesto is dropped  ·  **Low–Medium**

**What the MVP says.** No North Star metric anywhere; the only KPI-framed hypothesis (H004, "Time to trusted review … is a KPI, not a feature") is **superseded**; *"Recommended next conversation: Define the metrics and learning plan after Product and Domain close O004."*

**What the sources say.**
- Sibling **product vision** D021 (2026-07-17, one day before the MVP): *"Net Revenue per active Tax Advisor is the business North Star; ARPU is a diagnostic; falling handling time is operating proof."*
- Live **Notion TA Platform Vision** (2026-07-07): North Star = **ARPU**; **H2 Initiative List**: handling-time baseline **16.64 min**.
- The **manifesto** the MVP cites defines its *own* proposed north-star: *"Percentage of eligible bookkeeping periods that reach an evidence-complete, advisor-ready state within the target time and without a material correction,"* plus a long measures catalog.

**Why it's mostly deferral, not defect (the honest downgrade).** An adversarial verification pass **refuted** the strong version of this finding, correctly: the MVP *explicitly* defers metrics (not silently), the deferral is gated on the active O004 (which names the material-correction rule and observation window any north-star needs), and the manifesto itself says *"Baselines and numeric thresholds must be set before a real pilot. We do not invent them from a desk."* The business/book-level metrics (handling time, Net Rev/TA) genuinely can't be evaluated on one synthetic period, and the quality-gate layer *is* carried (no-false-ready, evidence-links, the Kano proof column's "hands-on minutes"/"time to first work").

**What survives.** Two low-severity edges: (1) the MVP doesn't even *name* the North Star hierarchy its sibling vision settled a day earlier, as a forward pointer; and (2) the manifesto's north-star is **period-level and evaluable in synthetic replay** — it *is* at MVP altitude — yet the MVP defers *all* metrics wholesale rather than adopting that one. The blanket deferral slightly over-corrects.

**Recommendation.** Carry the manifesto's period-level north-star ("% eligible periods reaching advisor-ready within target time, no material correction") as the MVP's replay success metric now, and add a one-line forward pointer to the vision's Net-Rev-per-TA / ARPU hierarchy for post-replay.

**Acknowledged (2026-07-19).** The blanket metrics deferral is a deliberate hold. It remains gated on O004. No change to the MVP artifact; the deferral is already explicit in the document.

---

## F5 — DataJanitor Pro re-scoped; two agent taxonomies silently blended  ·  **Low–Medium**

**What the MVP says.** Agent team: *"DataJanitor Pro — Inventories supported data, normalizes it, **reconciles the period**, and exposes gaps."* Team also lists Tax Advisor Agent, FristenGuard, AdvisorLens, Support Copilot, Document Review Agent.

**What the sources say.**
- Live **Notion TA Platform Agent Overview** (2026-04-01) defines **DataJanitor Pro** as *Intake & Normalisation* — client-data guidance, multi-channel ingestion, chart-of-accounts (SKR03/04) normalisation, ambiguity resolution, and GL-ready **DATEV-importable work packages with confidence scores**. **Reconciliation (bank↔invoice matching / open items) is not among its listed capabilities.**
- **Tax Advisor Agent, Support Copilot, Document Review Agent** are not in the Agent Overview's five families — they are the **efficiency-multiplier** agents named in the *TA Platform Vision* ("built today … not a differentiator on its own"). **DataJanitor Pro, FristenGuard, AdvisorLens** are three of the five Agent-Overview **families**. The MVP's team blends both sets without noting they come from different source taxonomies.

**Why it matters (mildly).** "Reconciles the period" quietly extends DataJanitor Pro beyond its defined intake/normalise role; a reader mapping the MVP back to the strategy will mis-attribute the reconciliation capability.

**Strongest counter-argument (why it's minor).** The MVP explicitly hedges: *"Named agents are target product roles. They are not claims that the current harness already supports every role."* And it is admirably **honest where it narrows** — it deliberately shrinks FristenGuard to *"Taxfix deadlines … No claim of live DATEV, calendar, inbox, or tax-office coverage"* (vs. its cross-system internal remit) and AdvisorLens to *"one evidence-backed opportunity card … Never contacts or sells,"* and it correctly defers OpsMaestro + ClientFit Scout to "later accelerators." So the agent section is largely well-grounded; the DataJanitor "reconcile" re-scope is the one substantive drift.

**Recommendation.** Either move "reconcile the period" to the Tax Advisor Agent / a bookkeeping worker, or add a line that the MVP extends DataJanitor Pro's role to include period reconciliation for the first wedge.

**Acknowledged (2026-07-19).** The re-scope and blended taxonomy are deliberate product choices for the first shot. The existing footnote — *"Named agents are target product roles. They are not claims that the current harness already supports every role"* — covers the divergence from internal definitions. No change to the MVP artifact.

---

## Minor notes (Low)

- **Decision count.** D002 says *"Taxfix client flow and agentic bookkeeping preparation are performance accelerators"* (two), while the Kano table lists **three** (adds in-app communication, via D004). Not a contradiction — D004 supplements D002 — but no single decision enumerates all three; a reader can miscount.
- **Workstream vocabulary drift.** The manifesto's workstream tabs are Overview / Work / Trace / **Outcome**; the MVP's "Light Codex UI" uses Today / Clients / **Mission** / Plan / Work / Trace / **Review** / Conversation / Return Brief. Harmless drift ("Mission" vs "Workstream/Case," "Review" vs "Outcome"), but worth aligning.
- **DATEV specificity omitted.** The vision (VIS-E028/D023) commits to a concrete mechanism — *"manual GFR CSV to DATEV import and manual Bescheid upload back to the workspace."* The MVP abstracts this to "manual DATEV handoff" and never names **GFR** or the **Bescheid upload** leg. The DATEV boundary itself (no platform write, simulated in replay) is well-aligned; only the mechanism detail is thinner than the vision.
- **Marketplace/white-label not in the MVP's own deferral list.** The "Later accelerators, not MVP scope" table lists DATEV, OpsMaestro, ClientFit Scout, broad binary support — but not the **marketplace** or **white-label** (a first-class internal lever; white-label = the Q1-2027 commercial payoff). It's legitimately out of an MVP (the manifesto scopes out "a broad agent marketplace"), but the MVP doesn't restate that deferral where a reader would look for it.

---

## Second sweep — additional low-severity findings (L1–L8)

A second, leaner audit pass (24 agents, 0 errors, sources pre-loaded) swept specifically for the *low-severity* issues the first pass could have missed — register bookkeeping, cross-table contradictions, undefined terms, contract mismatches. It found **no new issue above low severity**, which corroborates the main verdict. It did surface eight verified low-severity items, all **documentation-hygiene** rather than product/governance defects; each is confirmed against exact line numbers. (The undefined-role item L1 was independently rediscovered by 5 of the 6 lenses — the single most robust of the low-severity findings.)

| ID | Finding | Where | Fix |
| --- | --- | --- | --- |
| **L1** | **Undefined, inconsistently-named handoff role.** The DATEV-handoff human gate/owner is *"Advisor / **Operator**"* in the agent loop but *"Advisor / **Operations**"* in the effect table and scenarios (and `operator` inside the idempotency key) — a role absent from the platform-context roles table (Client, Tax Expert, Advisor, Administrator, Agent). | Agent loop L306; effect L319; scenarios L361 | Define the role or rename to **Administrator**; use one spelling. Advisor (the actual decision authority) is correctly named in every cell, so severity is low. |
| **L2** | **A declared blocked state has no test.** `needs_human_review` is one of seven "valid blocked states" (L266), but no Required-scenarios row has it as an expected state (closest is "Human rejection" → "returned or reopened"). | L266 vs L353–364 | Mark it intermediate (and say what it resolves to) or add a scenario row; else a fixture set can't exercise it. |
| **L3** | **`Resume` missing from the effect/retry/recovery contract.** The loop has a Resume step and an acceptance criterion says *"retry and resume do not duplicate actions"* (L373), but the effect table's seven rows include no Resume (or Radar) row — so the resume event has no defined idempotency key. | Loop L303 + L373 vs effect L311–319 | Add a Resume row (or state that it decomposes into Evidence-read + Claims-and-package). |
| **L4** | **Kano Radar proof under-lists the Radar contract.** The Kano "MVP proof" cell names 5 fields; the Radar contract requires 7 — *"Observed need"* and *"suggested allowed service"* are missing, and *"Advisor choice"* (Kano) vs *"Advisor decision"* (contract) drift. | Kano L147 vs Radar contract L207 | Point the acceptance bar at the contract's field list; a test anchored only on the Kano cell under-verifies. |
| **L5** | **Two team agents aren't placed in the architecture.** The agent-team table declares six agents, but D012 names only three "behind the front door," and the agent-loop attributes no step to **Support Copilot** or **Document Review Agent**. | Agent team L163–170; D012 L85; loop L297–307 | Distinct from F5 (placement, not scope): enumerate all six in D012 or state D012 lists only the primary visible specialists. |
| **L6** | **Column-semantics anomaly.** The agent-loop "Communicate" row puts a *human* action (*"Advisor checks recipient and text"*) in the **Check** column, which every other row uses for an automated system check. | Loop, Communicate row L302 | Move to the Human-gate column; harmless given D006 + the safe-loop section. |
| **L7** | **Radar contract drops a governance anchor.** *"suggested allowed service"* (L207) omits the *"from the allowed catalog"* qualifier that the platform context **and** the agent-loop Radar "Observe" column (L307) both carry — leaving "allowed" undefined in the output schema. | Radar contract L207 vs loop L307 | Restore "from the allowed catalog" so the constraint is traceable where a builder reads the schema. |
| **L8** | **Light Codex nav not reconciled with the manifesto.** The Light Codex lists a flat, consolidated 9-area surface without noting the manifesto puts *"top-level navigation consolidation"* out of first-state scope and requires keeping the Advisor/Expert desk split. *(Partial:* softened by *"this is not a final visual design"* and the manifesto's own *open question* on nav.) | Light Codex L212–228 vs manifesto out-of-scope + dual-desk | Add one line that the consolidated nav is a later IA direction, not first-state scope. |

**Related note (folded into F5, not a separate finding):** FristenGuard is scoped to the *inverse* of its canonical definition — the MVP's hard limit *"No claim of live DATEV, calendar, inbox, or tax-office coverage"* negates the exact four cross-system capabilities that define the Notion FristenGuard. This is **honestly disclosed** (the hard-limit column + the "named agents are target roles" footnote), so it is a transparent narrowing, not a hidden mismatch — same class as F5.

---

## What is well-aligned (so the audit is balanced)

These were checked and found **consistent** with internal strategy — do not "fix" them:

- **DATEV boundary** — manual handoff, no platform write, simulated in replay (D007) aligns with vision D023 and the internal "manual DATEV roundtrip first = P0." Appropriate to simulate for a synthetic MVP.
- **Opportunity Radar as a narrow, single-signal, shadow-adjacent, Advisor-gated "delighter"** — this is *more* aligned with the live Notion stance ("pilot stage 3 narrow, on one segment, in parallel," "shadow mode first," "no build commitment yet") than the parent vision was. The Kano "delighter" label is an *expectation* axis, not a strategic demotion; the Alignment table openly ties Radar to the "shadow-first opportunity machine." (A candidate "monetization demoted" finding was **refuted** on this basis.) The only soft note: the strategically-central monetization lever appears at minimal weight in shot #1 — defensible, but worth a conscious decision.
- **Overdue-receivables first signal** — grounded: the manifesto's pilot-data list names "overdue receivables"; AdvisorLens's internal remit includes "flag cashflow pressure signals in SMEs."
- **Human-authority model** — Advisor owns Send / judgment / acceptance, Tax Expert supervises exceptions — grounded in the manifesto first-state, the platform-context roles table, and Notion's "TA stays the gatekeeper; nothing goes direct to the client."
- **PACS / formal Seal as a non-goal** — consistent across manifesto, platform context, and context-architecture (all post-MVP). The only residual is a vocabulary gap vs. the live Notion loop "Case → Prepare → Trace → **Seal**," already reconciled by the vision's D024 ("Trace is the present evidence-and-review promise").
- **No calendar dates claimed as live** — principled, not a gap: matches vision D022 ("Month 1 begins only after verified SE-DIFM workspace availability … No calendar date is claimed as live") and E030 ("a planned calendar launch is not proof").
- **Citation anchors** E003 (SOTA "first wedge before the working machine"), E008 (SOTA "parity and differentiation bars"), E010 (context-architecture "Context is the foundation") all resolve to real, supporting sections.

## Legitimately deferred (absent by design — not findings)

Marketplace, white-label, SKU bundles, the three-stage / three-lever business-model framing, the revenue identity, TA-as-channel-and-customer duality, multi-market (DE/ES/UK), OpsMaestro + ClientFit Scout, numeric baselines/thresholds, and real-client data. Each is explicitly scoped out by the manifesto's "Out of scope," the platform context, or the MVP's own "later accelerators" / gate-hold posture.

---

## Methodology, provenance, and limitations

- **Sources cross-checked.** Repo: the MVP and every doc it cites (manifesto, platform context, product vision, SOTA benchmark, context architecture) plus the vision↔strategy alignment handover, the DATEV ecosystem review, and the DATEV scoping doc. Live: Notion "TA Platform Vision" (2026-07-07), "TA Platform Agent Overview" (2026-04-01), "Strategy Rundown V0.3" (2026-06-27), "H2 2026 Onsite Prep" + "H2 Initiative List" (2026-06-29) and the SE product-line sizing — fetched **2026-07-19** (not only the repo's 2026-07-17 snapshot).
- **Adversarial verification.** Candidate findings were run through an independent refutation pass. In the main pass, **five** candidate findings (a "North Star is missing" defect, a "superseded-H004" internal inconsistency, and three "opportunity machine demoted / un-instrumented / arbitrary-signal" findings) were **refuted** as legitimate, acknowledged deferrals and are deliberately *not* reported as defects — their residue is folded into F4 and the "well-aligned" section. This is why the report is short: the MVP survives most challenges.
- **Two audit runs.** Run 1 (the main pass) hit infrastructure timeouts on 7 of 9 automated auditors (heavy live-fetch loads on a 1M-context model idled the streams); those seven dimensions were completed **manually** against the same live sources. Findings F1, F2, F3, F5 and the minor notes come from that manual pass; F4 and the refuted-candidate calibration come from the two automated clusters that completed. Run 2 (the low-severity sweep) fixed the timeout by pre-loading the internal sources inline and running on a faster model with capped live fetches; it completed cleanly (**24 agents, 0 errors**), producing the L1–L8 items after de-duplication (18 raw candidates → 16 verified-surviving → 8 distinct; two candidates were refuted/subsumed by F4 and F5). It surfaced **no new finding above low severity**.
- **Confidence.** High for every reported finding — each cites verbatim source text with line numbers, independently re-checked in the verification pass. The earlier "additional low-severity findings may exist" caveat is now largely closed by Run 2; residual risk is limited to items requiring live-source *nuance* not captured in the pre-loaded pack.
- **Freshness flags.** SE segment sizing is from Oct 2025 (a refresh was noted in flight — treat ~800k / TAM as indicative). The Agent Overview is from Apr 2026 and may have evolved. Live-source content is a dated snapshot, not a contract.
