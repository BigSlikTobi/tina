# 🔍 Agentic MVP (source audit)

- Audit target: agentic_mvp.md (ADV-MORNING-001-MVP-A001, v1.0, 2026-07-18)
- Audit date: 2026-07-19
- Method: every active claim/decision cross-checked against the MVP's own cited repo sources and the live internal strategy in Notion + Google Drive (fetched 2026-07-19).

**Verdict in one line: All F1-F5 findings are closed. F1 resolved by D016, F2 and F4/F5 acknowledged as deliberate choices, F3 invalidated (PoC is not a source constraint for the MVP build). Only eight low-severity documentation-hygiene items (L1-L8) remain open.**

## Findings, ranked

| # | Finding | Type | Severity | Status |
|---|---|---|---|---|
| F1 | "SOTA daily Advisor workbench" is a co-equal must-have, contradicting the MVP's own SOTA benchmark (D013) which puts the whole-book desk in the later horizon | Inconsistency (vs cited source) | High | **Resolved — D016 (2026-07-19)** |
| F2 | Cohort qualifiers "low-document-volume" and "digital consultants" are product-directed, not backed by the sized SE research | Unbacked / provenance-thin | Medium | **Acknowledged — accepted product assumption** |
| F3 | The csv_reader-only capability floor makes the headline "reconcile transactions and invoices" value depend on synthetic CSV invoices | Realism gap | Medium | **Invalidated — finding relied on the PoC's current state** |
| F4 | The MVP carries no North Star, and omits even the one MVP-altitude, replay-evaluable north-star its own cited manifesto defines | Gap (partly deferred) | Low-Medium | **Acknowledged — deliberate hold, gated on O004** |
| F5 | DataJanitor Pro is re-scoped to "reconciles the period" (not in its internal definition); the agent team silently blends two different internal agent taxonomies | Inconsistency (vs cited source) | Low-Medium | **Acknowledged — deliberate scope choice** |

## F1 — Resolved by D016 (2026-07-19)

The MVP's D016 has been added: "The MVP explicitly supersedes SOTA benchmark D013's two-horizon framing. The SOTA-complete daily Advisor workbench is a must-have of the first shot, not a later-horizon addition. A product that launches below SOTA parity at the control layer forces the Advisor to keep the market solution for most of their day — the product fails the must-have bar. One deep agentic mission runs inside that workbench, not alongside a stripped shell."

## F2 — Acknowledged (2026-07-19)

The "low-document-volume / digital consultants" qualifiers are accepted product assumptions. The risk — that the cohort turns out to have more documents than expected — is known and will drive product adaptation as evidence arrives.

## F3 — Invalidated (2026-07-19)

This finding used the PoC harness's current csv_reader-only implementation as a constraint on the MVP. The PoC is not a source for the MVP build — the MVP will be built with the capabilities it requires, including document reading beyond CSV.

## F4 — Acknowledged (2026-07-19)

The blanket metrics deferral is a deliberate hold, gated on O004. The manifesto's period-level north-star ("% eligible periods reaching advisor-ready within target time, no material correction") is the MVP's replay success metric direction.

## F5 — Acknowledged (2026-07-19)

The re-scope and blended taxonomy are deliberate product choices for the first shot. The existing footnote — "Named agents are target product roles. They are not claims that the current harness already supports every role" — covers the divergence from internal definitions.

## Low-severity items (L1-L8)

Eight low-severity documentation-hygiene items remain open:
- **L1:** Undefined, inconsistently-named handoff role ("Operator" vs "Operations" vs implied "Administrator").
- **L2:** A declared blocked state (needs_human_review) has no test scenario.
- **L3:** Resume step missing from the effect/retry/recovery contract.
- **L4:** Kano Radar proof under-lists the Radar contract field requirements.
- **L5:** Two team agents (Support Copilot, Document Review Agent) aren't placed in D012 architecture.
- **L6:** Column-semantics anomaly in the Communicate row of the agent loop.
- **L7:** Radar contract drops the "from the allowed catalog" governance anchor.
- **L8:** Light Codex nav not reconciled with the manifesto's out-of-first-state-scope statement on navigation consolidation.

The full audit is preserved in the repository at `docs/product/wow/ADV-MORNING-001/agentic_mvp_source_audit.md`.
