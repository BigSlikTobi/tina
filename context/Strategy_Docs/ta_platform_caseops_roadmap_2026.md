# CaseOps Roadmap: to EOY 2026

- Status: Draft.
- Owner: Product (Tobias Latta).
- Updated: 2026-07-26
- Freshness: Current
- Confidence: Medium. 
- Parent: [TA Platform Strategy](./ta_platform_strategy.md)

## Scope

CaseOps is the backoffice and tooling workstream. It combines Expert Interaction, document state, GFR, DATEV, and Taxfix context into one workspace, so a case moves faster without being rebuilt by hand across systems.

This roadmap covers the horizon to EOY 2026 only. It does not cover TalentOps (growing the advisor network) or Network and Marketplace (the 200 to 1,000 scale-out). See those as separate documents.

## Milestones

| When | Milestone | Status | Source |
|---|---|---|---|
| Q3 2026 | TA Backoffice Dashboard live: client list, document status, filing progress, TA-to-client communication 
| Q3 2026 | DATEV Roundtrip, manual MVP: file import and Bescheid upload done by hand. Automation (Klardaten) 
| Q3 2026 | Handling-time measurement instrumented: start and stop events on each task in the TA workflow | Not started 
| Q3 2026 | Automation pilot clears about 70% of tasks. Opportunity-discovery scoping begins | Planned |
| Q4 2026 | AI agent design: DataJanitor Pro (intake) and FristenGuard (deadlines).| In discovery |
| Q4 2026 | AdvisorLens pilot live on one segment, shadow-mode first | Planned | 
| EOY 2026 | DIFM mandate runs end to end. The delivery plan states 331 clients. Handling time is falling | Planned, not yet observed | Strategy alignment |

## Dependencies

- GFR bookkeeping must stay automated upstream.
- DATEV or Klardaten API access for later automation.
- Expert Chat and interaction experience from Assisted Experiences, needed for the full mandate flow end to end.
- Data protection sign-off from Legal, required before TAs handle client data in the dashboard.

## Open items from strategy alignment‚

- Decision 4, Monitor as the B2C delivery system: Monitor's evolution into a B2C Tax Advisor Platform is a separate, Assisted-team-owned initiative also running in H2 2026. It is not part of this CaseOps build, but the two overlap in intent (both build tooling for TAs to do case work). 
- Broader CaseOps (pulling more from DATEV, adding SE/SME/B2C case types) is not scoped for 2026. The 2026 horizon stays SE-DIFM only.
