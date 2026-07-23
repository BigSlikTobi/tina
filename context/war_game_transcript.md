# 💬 War game (transcript)

- Artifact ID: ADV-MORNING-001-WAR-T001
- Version: 2.1
- Updated: 2026-07-21
- War-game artifact link: war_game.md

This is a sanitized record of visible collaboration across the two war-game runs. It excludes hidden reasoning, system or developer prompts, secrets, raw tool output, environment dumps, personal data, and unrelated turns.

The full transcript is preserved in the repository at `docs/product/wow/ADV-MORNING-001/war_game_agent_transcript.md`.

## v1.0 run — key turns (2026-07-21)

### T-006 — User — scope and authority correction

> please explain in easy non technical words and short sentences what you mean with full day workbench and why we are not execution it? the SOTA doc is only an analysis af AsIs and should not steer the MVP

### T-011 — User — full delegation

> so run all challenges

### T-016 — User — greenfield boundary correction

> one improtant correction! Don't take the current build (or any current build)as foundation! We only check the wow context and will build the MVP from scratch. things like "no pdf-reader" are wrong statements because nothing is build yet!

## v2.0 rerun — key turns (2026-07-21)

### T-023 — User — rerun request

> before we do this please do a 360 degrees war game using the wow-war-game skill one more time with the notion and company background we now have. Then create one final agentic_mvp_decision.md with the MVP we want to build, the open questions, the War Game result and the decisions we took. Everything ready to build the first phase of our product. Failing is ok! we just want to be sure we can comunicate why we took a decisions.

## v2.1 corrections — key turns (2026-07-21)

### T-028 — User — three corrections

> I see that we still introduce the current POV build (open router models) this is not part of the plan, we only work on the docs inside of docs/product/wow/ADV-Morning-001. I see references to opencode but this is not part of the decision matrix, is this clear? I also want to challenge the greenfield brownfied statement. Eventhoug GFR or FinAPI are mentioned, we will build vendor agonstic and implement with APIs and a clear architecture. So this is not a MVP kill shot to me.

### T-029 — Agent — corrections accepted

> Understood, and agreed on all three. First: the current PoC build — the `taxfix_harness` codebase and its model-provider config (OpenRouter) — is out of the decision matrix; judging the MVP by the prototype repeats the current-build mistake v1.0 already ruled out. I'm retracting the "illegal LLM egress" finding (F023) and removing every reference to the current code. Second: the greenfield-vs-brownfield framing is a false choice — the MVP is vendor-agnostic, built against clean APIs, and naming GFR/FinAPI/DATEV in strategy is not lock-in, so that is not a kill shot; I'm superseding F021 and F027.

## v1.0 decision council decisions

- D003: MVP owns scope — full-day workbench plus deep bookkeeping job.
- D004: Greenfield only. Current build excluded.
- D005: Run all design attacks; missing proof stays unknown, contradictions stay failed.
- D006: Documents are evidence, never instructions.
- D007 (superseded): hold → narrow (corrected to D009).

## v2.1 final decisions

- D009: Gate stays hold → narrow.
- D013: Current PoC build is OUT of the decision matrix.
- D014: MVP is vendor-agnostic, built against clean API abstractions.
