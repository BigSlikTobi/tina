# TA Platform Strategy

- Status: Proposed
- Decision owner: Product and business leadership
- Updated: 2026-07-26
- Freshness: Current
- Confidence: Medium
- Direct source: [Leadership input from 2026-07-26](./Raw/leadership_ta_platform_direction_2026-07-26.md)
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

### 3. Broader CaseOps

Pull more useful functionality from DATEV through approved integrations. Add more SE, SME, and B2C case types. Confirm Monitor's role in B2C delivery.

### 4. Network and marketplace

Grow from 200 to 1,000 qualified professionals.

Support employees, Tax Advisors, tax clerks, freelancers, and other allowed roles. Let several people work on one case inside a practice and, where allowed, across practices.

Professionals can work Taxfix's queue or bring their own clients. White-label practices run on the same platform.

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

1. What counts towards 200: registered, verified, contracted, qualified, activated, or first-paid-case professionals?
2. What are the dates for 200 and 1,000? How do they relate to the "1,000+ in Year 1" slide?
3. Do CaseOps and TalentOps run in parallel? Who owns each track?
4. Is Monitor the intended B2C delivery surface?
5. Which roles may perform, review, and own each type of work?
6. Can one case be split across practices? Under which mandate, liability, and data-access model?
7. How do contracts, pricing, and payouts work for Taxfix cases and own-client cases?
8. Is white-label needed before 200 or in the scale horizon towards 1,000?
