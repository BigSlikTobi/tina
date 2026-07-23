# 💬 Metrics and gates (transcript)

- Artifact ID: ADV-MORNING-001-MET-T001
- Version: 1.1
- Updated: 2026-07-19

This is a sanitized record of visible collaboration. The full transcript is preserved in the repository at `docs/product/wow/ADV-MORNING-001/metrics_agent_transcript.md`.

## Key turns

### T-001 — User — 2026-07-19

> you are right, let's define the wow-metrics first. what do we need to measure to define if the product is successfull or not and what metrics do we need to learn from them

### T-005 — User — plain-language request

> please explain this again in easy words with examples a non expert person understands

### T-007 — User — scorecard confirmation

> awesome! I confirm that we need a separate bookkeeping-period and Advisor-day scorecard.
> Final gate is product that is true but the Domain, the Advisors and the responsible positions have veto rights.
> We leave numeric thresholds open until we define the exact case rubric and collect the five-day Advisor baseline

## Key decisions confirmed by user

- D001: Use separate bookkeeping-period and Advisor-day scorecards. Do not combine into one weighted score.
- D002: Product owns the final gate. Domain, Advisors, and responsible control owners have veto rights in their areas.
- D003: Keep numeric thresholds open until the exact case rubric is defined and the five-day Advisor baseline is collected.
- D004: A correction is material when it changes readiness, reconciliation, a missing-evidence request, the Advisor decision, or the manual DATEV handoff.
- D005: Use two immediate lifecycle gates: discovery to build, then build to synthetic replay.
- D006: Build the Advisor-day baseline from named internal SE-DIFM Advisors across five normal full workdays.
- D007: The first baseline replay case is one German VAT-liable SE-DIFM freelancer or digital consultant, one calendar month, low document volume, and realistic synthetic structured inputs.
- D008: A package is acceptable only for the correct client and month, with every required input present or visibly missing, supported evidence reconciled, every material claim source-linked, conflicts and unknowns visible, unsupported evidence blocked, and human accept or return available.
- D009: The first manual downstream handoff must not depend on GFR availability or a GFR connection. Define a vendor-neutral, versioned, human-operated handoff contract.
- D010: Build and test the PDF reader in parallel. Keep its exact version and hash inactive for bookkeeping runs until its separate extraction, evidence-linking, safe-disposition, cost, and approval proof passes.
- D011: Use a vendor-neutral manual handoff. Taxfix creates a versioned package with structured bookkeeping data, reconciliation summary, unresolved items, and source list.
- D012: Use a versioned gold case pack containing the fake client and month, input manifest, expected matches and unmatched items, missing inputs, conflicts, expected claims and evidence links, correct readiness result, and expected handoff outcome.
- D013: Product owns the final gate. Domain owns accounting rules and gold answers. Advisor representatives own usefulness and acceptance truth. Engineering owns runtime and measurement events. Actual names are required before G001 can pass.
- D014: Replay must cover every required happy, exception, recovery, authority, scope, and malicious-input scenario.
- D015: Separate the metric system into four early success KPIs, later business KPIs, non-negotiable guardrails, and learning metrics.
