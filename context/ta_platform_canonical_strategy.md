# TA Platform Strategy

- Status: Proposed
- Decision owner: Product and business leadership
- Updated: 2026-07-26
- Freshness: Current
- Confidence: Medium
- Direct source: [Leadership input from 2026-07-26](./Raw/leadership_ta_platform_direction_2026-07-26.md)
- Cross-check: [Decisions cross-checked against Notion](./ta_platform_decisions_notion_crosscheck.md)
- Revisit trigger: Strategy approval, target definition, or legal operating model changes

## Strategy

Taxfix builds the operating system and marketplace for tax professionals.

Qualified professionals can join the network, work Taxfix cases or bring their own clients, and complete tax work with shared tools, context, and controls.

The professional workspace offers a Codex experience for Tax Advisors.

## Product model

| Layer | What it does |
|---|---|
| Client frontends | Taxfix-branded and white-label client experiences |
| Practice tools | Professional workspace, documents, communication, planning, review, deadlines, and evidence |
| Tax modules | Income tax, VAT, BWA, annual accounts, and B2C/B2B advice |
| Marketplace | Routes cases and tasks by qualification, permission, capacity, and responsibility |
| Talent foundation | Registration, verification, qualifications, training, contracts, practice membership, and payouts |

The layers depend on each other.

The workbench without TalentOps and the marketplace becomes an internal tool. The marketplace without the workbench becomes a staffing marketplace with weak delivery control.

## Work experience

The workspace offers a Codex experience for tax work.

It shows:

- The client and case context.
- What changed.
- What is missing or blocked.
- Where the source lives.
- Who owns the next action.
- What the platform can prepare.
- What needs professional judgment or review.
- What happened, with an evidence-linked history.

The workspace can plan and prepare approved work. The accountable professional keeps judgment and consequential external actions.

## Roadmap

### 1. CaseOps backoffice

Build a backoffice that can be used in live SE/SME operations.

Combine Expert Interaction, document state, GFR, DATEV, and Taxfix context. Show ownership, blockers, freshness, source, and next action.

The focus is better information flow and faster case progression. We do not build another bookkeeping engine.

Roadmap to EOY 2026: [ta_platform_caseops_roadmap_2026.md](./ta_platform_caseops_roadmap_2026.md).

### 2. TalentOps

Build the path from 7 manually managed Tax Advisors to 200:

- Registration and identity verification.
- Qualification profile.
- Training and approvals.
- Contracts and practice membership.
- Availability and work preferences.
- Payout setup.
- Self-service support.
- First suitable case.

Proposed sequencing:

CaseOps and TalentOps run in parallel.

Roadmap to EOY 2026: [ta_platform_talentops_roadmap_2026.md](./ta_platform_talentops_roadmap_2026.md).

### 3. Broader CaseOps

Pull more useful functionality from DATEV through approved integrations. Add more SE, SME, and B2C case types. Confirm Monitor's role in B2C delivery.

### 4. Network and marketplace

Grow from 200 to 1,000 qualified professionals.

Support employees, Tax Advisors, tax clerks, freelancers, and other allowed roles. Let several people work on one case inside a practice and, where allowed, across practices.

Professionals can work Taxfix's queue or bring their own clients. White-label practices run on the same platform.

Roadmap to EOY 2026: [ta_platform_network_marketplace_roadmap_2026.md](./ta_platform_network_marketplace_roadmap_2026.md). Nothing in this phase is scoped for 2026.

## Shared foundation

CaseOps and TalentOps need one shared model for:

- People, organisations, and practice membership.
- Qualifications, roles, and permissions.
- Clients, cases, workstreams, and tasks.
- Assignment, review, and accountability.
- Evidence, source history, and audit.
- Contracts and payouts.
- Tenant and data-access boundaries.

Architect for multi-person work. Build only what the first real workflows need.

## First proofs

CaseOps:

One real SE/SME case moves through Expert Interaction, documents, GFR, and the controlled DATEV handoff without the case context being rebuilt manually across systems.

TalentOps:

One new Tax Advisor registers, becomes verified and qualified, completes the required training and contract steps, receives suitable work, completes a first case, and becomes payout-ready.

## Proposed success measures

Platform:

- Quality-approved tax work completed through the platform.
- Share of Taxfix's eligible queue completed by the network.
- Net revenue per active Tax Advisor.
- Active white-label practices and own-client work.

Supply:

- Verified and qualified professionals.
- Professionals activated through a first paid case.
- Time from registration to first paid case.
- 30-day and 90-day active-professional retention.

Work:

- Time to assign suitable work.
- Case and task cycle time.
- Time spent searching for information.
- Review, rework, reassignment, and failure rates.
- Payout accuracy and latency.

Guardrails:

- No false-ready work.
- No work outside qualification or permission.
- No missing accountable reviewer.
- No untraceable material action.
- No cross-client or cross-practice data leak.
- No duplicate consequential action during recovery.

## Decisions needed

Each item below carries a status from the Notion cross-check. Still open means no Notion source answers it. Details and sources are in [ta_platform_decisions_notion_crosscheck.md](./ta_platform_decisions_notion_crosscheck.md).

1. **TA-count definition.** Which milestone counts as one of the 200 TAs: registered, verified, contracted, qualified, activated, or first paid case? **Still open.** No stage taxonomy exists in Notion.
2. **Target dates for 200 and 1,000.** When do we reach 200 TAs and when do we reach 1,000, and does either date match the "1,000+ in Year 1" slide? **Answered, and it contradicts the slide.** Internal plans put 100 to 300 TAs live by EOY 2026 and 1,000 by EOY 2027, with white-label starting Q1 2027. Nothing in Notion supports "1,000+ in Year 1." Confirm with leadership what "Year 1" means.
3. **CaseOps and TalentOps sequencing and ownership.** Do CaseOps and TalentOps run on the same timeline, and who owns each track? **Partially answered.** CaseOps items are in delivery for Q3 2026. TalentOps (the Marketplace MVP: register, qualify, train, quality-check) is in discovery for Q4 2026, one quarter behind. Product owner is Tobias Latta. No named owner exists for TalentOps beyond that.
4. **Monitor as the B2C delivery system.** Is Monitor the system Tax Advisors will use to deliver B2C cases? **Answered: yes.** Two active H2 2026 initiatives name Monitor directly as the B2C Tax Advisor Platform.
5. **Role permissions for tax work.** Which roles are allowed to prepare, review, and hold liability for each type of tax work? **Partially answered.** A two-tier split exists: TA owner (Berufsträger) carries liability, does QA, and gives final approval; TA staff (Sachbearbeiter) prepares cases, with a four-eyes check before filing. Nothing defines where freelancers or Minijobber roles fit.
6. **Cross-practice case handling.** Can one case be handled by more than one practice, and under what mandate, liability, and data-access rules? **Answered: not today.** Each case binds to a single providerID at assignment. There is currently no way to even reassign a case to a different advisor through Monitor, let alone split it across practices.
7. **Contract, pricing, and payout model.** How do contracts, pricing, and payouts work for a case Taxfix assigns to a TA versus a client the TA brings themselves? **Answered as a live risk.** Monitor does not yet reflect the process in the updated T&Cs and TA contracts, a flagged legal and operational risk. Payment timing for routed cases is still being decided. Payout mechanics for a TA's own, white-label clients don't exist yet. Advisor-facing billing is scoped for 2027.
8. **White-label timing.** Does white-label need to launch before 200 TAs are reached, or only later while scaling toward 1,000? **Answered: no, not before 200.** White-label starts Q1 2027, alongside the climb toward 1,000.
