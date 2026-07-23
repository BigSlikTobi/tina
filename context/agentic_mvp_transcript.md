# 💬 Agentic MVP (transcript)

- Artifact ID: ADV-MORNING-001-MVP-T001
- Version: 1.2
- Updated: 2026-07-21
- Lens artifact: agentic_mvp.md

This is a sanitized record of the Agentic MVP conversation. The full transcript is preserved in the repository at `docs/product/wow/ADV-MORNING-001/agentic_mvp_agent_transcript.md`.

## Key turns

### T-001 — User

> Ok we now have the SOTA and the Product Vision. the next step would be wow-agentic-mvp. let's kick it off

### T-005 — User — Kano-first reframing

> I think the Kano Matrix is a good starting point. we should define the must haves, the performance accelerators and the delighter for the first platform shot. I also think we should go into the codex UI direction but not completely deal into it.

### T-009 — User — SOTA parity challenge

> ok, I think we need to at least meet the sota on features, right?

### T-011 — User — daily-home-base correction

> the discussion point is: why should a german tax advisor use our app over the market solution? They need to do all their work and the "extra" we giving them. we cannot "just" support one feature and leave them hanging on the rest, right?

### T-013 — User — platform scope confirmation

> yeah, now we are talking, this is what I see as starting point

### T-016 — User — greenfield boundary correction

> one important correction! Don't take the current build (or any current build) as foundation! We only check the wow context and will build the MVP from scratch. things like "no pdf-reader" are wrong statements because nothing is build yet!

### Key decisions confirmed by user

- D001: First shot is a SOTA-complete daily Advisor workbench plus one deep agentic bookkeeping workflow.
- D006: AI may draft client messages in the later iteration. Only the Advisor can click Send. An AI command never sends.
- D007: MVP ends with Advisor accept or return plus a recorded human-operated downstream handoff.
- D008: First evaluation mode is synthetic replay.
- D009: Agent owns bounded L2 preparation until review, blocker, cancellation, or human stop.
- D010: Opportunity Radar runs after supported preparation. Shows at most one strong overdue-receivables signal. Never changes readiness.
- D012: One Taxfix AI front door leads the mission. DataJanitor Pro, FristenGuard, and AdvisorLens work behind it.
- D015: Hold the product gate and narrow the next work to the exact proof contract.
- D017: This is a greenfield MVP. Current code, features, tests, and limits do not define product scope.
- D018: MVP workbench connects to DATEV, task lists, and Taxfix systems at the control layer.
- D019: Advisor-client chat and the AI-assisted client-message loop are outside the MVP.
- D020: Primary MVP user is an internal Taxfix Advisor. A Tax Expert supports preparation.
- D021: Reuse the existing gate systems. Metrics owns G001 and G002. GTM owns recruitment and rollout gates.
- D022: Open matters are grouped by when they are needed. A later real-data question does not reopen confirmed MVP scope.
