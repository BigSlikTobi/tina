# Current SOTA Benchmark: Advisor Desk — first bookkeeping wedge and later working machine

- Artifact ID: ADV-MORNING-001-SOTA-A001
- Artifact type: current-sota-benchmark
- Version: 1.2
- Artifact completeness: complete
- Job ID: ADV-MORNING-001
- Canonical lifecycle stage: discovery
- Capability mode: mixed
- Requested transition: none
- Gate decision: not-decided
- Decision consequence: Open
- Owner: Product
- Updated date: 2026-07-17
- Canonical brief: Open
- Input artifacts: TAX-PLATFORM-CONTEXT-A001 v0.1 ([../../tax-advisor-platform-context.md](../../tax-advisor-platform-context.md)), used only for authority, evidence, data, and safety boundaries—not as SOTA evidence
- Transcript link: [sota_benchmark_agent_transcript.md](sota_benchmark_agent_transcript.md)
- v1.2 alignment (2026-07-17): the first product wedge and the later whole-book SOTA are now explicitly separate. DATEV authority, data custody, controlled handoff, opportunity detection, and vendor-dependency limits are recorded in D013–D016 and H013–H015.
- v1.1 review addendum (2026-07-17): retained below as limited vendor and integration evidence (E041–E053). It does not prove product support, authority, reliability, or commercial value.
- Reader-facing synthesis: [sota_advisor_desk.md](sota_advisor_desk.md)

## Current framing — confirmed 2026-07-17

This benchmark has two horizons. They must not be blended into one promise.

| Horizon | Product boundary | Success condition |
| --- | --- | --- |
| First wedge | `SE-DIFM bookkeeping mandate → evidence-linked, review-ready package → controlled DATEV handoff` | The Advisor can accept or return a prepared bookkeeping period with sources, blockers, unknowns, and a controlled next handoff. |
| Later SOTA | A whole-book working machine across the Advisor's practice | The Advisor can return throughout the day to current, source-linked, human-gated work across systems without rebuilding context. |

The first wedge keeps bounded, human-gated, evidence-linked preparation. It does not claim a completed whole-practice command center. The later horizon remains useful market SOTA, but it is not first-wedge scope or proof.

## Evidence and decision register

| ID | Type | Status | Claim or decision | Source/link | Date | Owner | Confidence |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-SOTA-E007 | fact | active | In representative STAX 2024 survey data, German solo practices used an average 6.9 of 16 surveyed digital tools and professional companies 10.7. DMS use was 44.8% versus 79.5%, client-software interfaces 37.6% versus 75.0%, and CRM only 5.0% versus 11.8%. Reported blockers include organizational effort, lack of time, poor usability, incompatible systems, and weak client connectivity. | [BStBK / IfD Allensbach, STAX 2024](https://www.bstbk.de/downloads/bstbk/recht-und-berufsrecht/fachinfos/02_Sonderauswertungen_Digitalisierung_Fachkraeftemangel_STAX2024.pdf) | 2026-07-15 | BStBK / IfD Allensbach | high |
| ADV-MORNING-001-SOTA-E008 | fact | active | Official role definitions show specialists prepare bookkeeping, business figures, annual accounts, tax returns, assessment checks, advisory work, and digital data flows; the Advisor remains responsible for higher judgment and representation. | [BStBK education and professional roles](https://www.bstbk.de/de/berufsbild-steuerberater/aus-und-fortbildung); [Advisor role](https://www.bstbk.de/de/berufsbild-steuerberater/der-steuerberater) | 2026-07-15 | BStBK | high |
| ADV-MORNING-001-SOTA-E009 | fact | active | The official beSt workflow provides a concrete daily handoff: staff can draft and prepare messages, while the Advisor reviews the drafts at day end and personally releases selected messages; dispatch and receipt are recorded. | [BStBK Steuerberaterplattform and beSt](https://www.bstbk.de/de/themen/steuerberaterplattform) | 2026-07-15 | BStBK | high |
| ADV-MORNING-001-SOTA-E010 | fact | active | DATEV commercial documentation describes Post, Fristen und Bescheide recording inbound from paper, phone, fax, and email; creating and monitoring deadlines from notices; linking DMS documents; and supporting states, alerts, tasks, handoffs, and four-eyes workflow. | [DATEV program overview](https://wissensplattform.apps.datev.de/help/document/9250343); [DATEV product stack](https://wissensplattform.apps.datev.de/help/document/9217659) | 2026-07-15 | DATEV | medium |
| ADV-MORNING-001-SOTA-E011 | fact | active | VAT pre-filings and wage-tax filings create monthly or quarterly day-ten cycles, while annual returns create a separate yearly deadline cycle. | [UStG §18](https://www.gesetze-im-internet.de/ustg_1980/__18.html); [EStG §41a](https://www.gesetze-im-internet.de/estg/__41a.html); [AO §149](https://www.gesetze-im-internet.de/ao_1977/__149.html) | 2026-07-15 | German Federal Ministry of Justice / Federal Office of Justice | high |
| ADV-MORNING-001-SOTA-E012 | fact | active | Current practitioner reports describe late client questions, incomplete or late inputs, manual email filing, software outages, and intake spread across portals, scans, encrypted PDFs, USB sticks, and phone photos. | [DATEV Community practitioner thread](https://www.datev-community.de/t5/Freie-Themen/Womit-verbringt-ihr-in-der-Steuerberatung-unn%C3%B6tig-viel-Zeit/td-p/488499) | 2026-07-15 | DATEV Community contributors | low |
| ADV-MORNING-001-SOTA-H002 | hypothesis | active | The typical Advisor has no single trusted full-day command center today; orientation is reconstructed across multiple specialist tools, channels, and human handoffs. | ADV-MORNING-001-SOTA-E007 through E012 | 2026-07-15 | Product | medium |
| ADV-MORNING-001-SOTA-E013 | fact | active | DATEV commercial documentation describes Arbeitsplatz centrally aggregating tasks from integrated DATEV applications with filters, grouping, sorting, reminders, rights, reassignment, and source links. | [DATEV task documentation](https://wissensplattform.apps.datev.de/help/document/9216659) | 2026-07-15 | DATEV | medium |
| ADV-MORNING-001-SOTA-E014 | fact | active | DATEV commercial documentation describes Eigenorganisation comfort modeling client orders with tax year, order type, sub-orders, deadlines, status, staffing, capacity, checklists, notes, cost, fees, billing, and plan-versus-actual control. | [DATEV order overview](https://wissensplattform.apps.datev.de/help/document/9257861) | 2026-07-15 | DATEV | medium |
| ADV-MORNING-001-SOTA-E015 | fact | active | DATEV commercial documentation describes ProCheck adding client/order checklists, recorded steps, visible status, reassignment, responsibility, linked aids, filtering, and archiving. | [DATEV ProCheck setup guide](https://wissensplattform.apps.datev.de/help/document/0904161) | 2026-07-15 | DATEV | medium |
| ADV-MORNING-001-SOTA-E016 | fact | active | An independent 2019 Bundeskartellamt report placed DATEV above 60% market share and reported that users perceived it as the only complete provider at that time. | [Bundeskartellamt case report B7-25/17](https://www.bundeskartellamt.de/SharedDocs/Entscheidung/DE/Fallberichte/Missbrauchsaufsicht/2019/B7-25-17.pdf?__blob=publicationFile&v=4) | 2026-07-15 | Bundeskartellamt | medium |
| ADV-MORNING-001-SOTA-E017 | fact | active | The current DATEV Kanzleimanagement cloud offers a useful order board, but DATEV still describes bundling tasks, documents, deadlines, and responsibilities into the order as future scope. | [DATEV cloud transition page](https://www.datev.de/web/de/steuerberatung/themen-im-fokus/umstieg-cloud-vorbereiten/kanzleimanagement); [DATEV Kanzleimanagement training](https://www.datev.de/content/dam/markenassets/themen-und-produktgruppen/service/pdf/Schulungsunterlage_DATEV_Kanzleimanagement.pdf) | 2026-07-15 | DATEV | medium |
| ADV-MORNING-001-SOTA-E018 | fact | active | milia.io markets as commercially available a German practice-wide view across matters, tasks, deadlines, owners, status, next steps, approvals, and activity history. This is availability evidence, not independent quality proof. | [milia Kanzleisteuerung](https://milia.io/kanzleisteuerung); [Vorgangsmanagement](https://milia.io/feature/vorgangsmanagement) | 2026-07-15 | milia | medium |
| ADV-MORNING-001-SOTA-E019 | fact | active | milia's product documentation describes time- or event-triggered deterministic workflows, client requests, reminders, approval steps, logged human approvals, and chronological matter history. | [milia workflow automation](https://milia.io/workflow-automatisierung); [Approvals](https://milia.io/feature/freigaben); [Activity history](https://milia.io/feature/aktivitatsverlauf) | 2026-07-15 | milia | medium |
| ADV-MORNING-001-SOTA-E020 | fact | active | milia's assistive AI for DATEV open-item analysis, request drafting, document analysis, and contextual chat is marketed as live, while multi-step AI agents are explicitly marked `Bald verfügbar`. | [milia.AI](https://milia.io/milia-ai) | 2026-07-15 | milia | medium |
| ADV-MORNING-001-SOTA-E021 | fact | active | The milia Taxy.io Answers add-on returns German tax answers with named sources and links to licensed full text; accuracy and “no hallucinations” claims are not independently proven. | [Taxy.io Answers](https://milia.io/feature/taxy-io-answers) | 2026-07-15 | milia | medium |
| ADV-MORNING-001-SOTA-E022 | fact | active | Karbon Kai describes the closest agentic command-center behavior: a briefing across unread email, client requests, blocked, due, and overdue work; live firm-data questions; prioritization; agent invocation; and approve, edit, or reject controls. Kai and agentic workflows remain limited or early access. | [Karbon Kai](https://karbonhq.com/feature/kai/); [Karbon AI Agents](https://karbonhq.com/feature/agents/) | 2026-07-15 | Karbon | low |
| ADV-MORNING-001-SOTA-E023 | fact | active | Karbon's broadly available AI is currently assistive: client, work, and email summaries, drafting, quick replies, and smart assignment suggestions. | [Karbon March 2026 release notes](https://karbonhq.com/release-notes/mar-31-2026/) | 2026-07-15 | Karbon | high |
| ADV-MORNING-001-SOTA-E024 | fact | active | Karbon's current integration catalog lists global accounting and US tax tools but no DATEV integration. | [Karbon integrations](https://karbonhq.com/integrations/) | 2026-07-15 | Karbon | medium |
| ADV-MORNING-001-SOTA-H003 | hypothesis | active | The most honest frontier is two-part: milia as the feasible German operating floor and Karbon Kai as the adjacent agentic behavior ceiling. No single product currently proves both. | ADV-MORNING-001-SOTA-E018 through E024 | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-E025 | fact | active | STAX 2024 reports that 59.1% of vacancies in solo practices and 29.1% in professional practice companies remained unfilled. | [BStBK / IfD Allensbach, STAX 2024](https://www.bstbk.de/downloads/bstbk/recht-und-berufsrecht/fachinfos/02_Sonderauswertungen_Digitalisierung_Fachkraeftemangel_STAX2024.pdf) | 2026-07-15 | BStBK / IfD Allensbach | high |
| ADV-MORNING-001-SOTA-E026 | fact | active | German domestic businesses have had to be able to receive structured e-invoices since 1 January 2025, with staged transition rules for issuing them through 2026 and 2027. | [BMF e-invoice FAQ](https://www.bundesfinanzministerium.de/Content/DE/FAQ/e-rechnung.html) | 2026-07-15 | Bundesministerium der Finanzen | high |
| ADV-MORNING-001-SOTA-E027 | fact | active | STAX 2024 reports chatbot use by 12.2% of solo practices and 27.4% of professional practice companies, with a further 25.3% and 36.7% planning adoption. This measures broad chatbot adoption, not proven tax automation. | [BStBK / IfD Allensbach, STAX 2024](https://www.bstbk.de/downloads/bstbk/recht-und-berufsrecht/fachinfos/02_Sonderauswertungen_Digitalisierung_Fachkraeftemangel_STAX2024.pdf) | 2026-07-15 | BStBK / IfD Allensbach | high |
| ADV-MORNING-001-SOTA-E028 | fact | active | STAX respondents identified structured client-data analysis for additional services as an opportunity: 26.4% in solo practices and 41.1% in professional practice companies. | [BStBK / IfD Allensbach, STAX 2024](https://www.bstbk.de/downloads/bstbk/recht-und-berufsrecht/fachinfos/02_Sonderauswertungen_Digitalisierung_Fachkraeftemangel_STAX2024.pdf) | 2026-07-15 | BStBK / IfD Allensbach | high |
| ADV-MORNING-001-SOTA-H004 | hypothesis | active | Structured e-invoicing moves bookkeeping toward continuous machine-readable intake, making ongoing exception and advisory workflows more valuable than periodic document collection alone. | ADV-MORNING-001-SOTA-E026 | 2026-07-15 | Product | medium |
| ADV-MORNING-001-SOTA-H005 | hypothesis | active | Proposed SOTA synthesis to test: maintain live practice state → detect changes and exceptions → explain and rank interventions → prepare a sourced decision packet → let the Advisor decide → execute only bounded work → monitor and learn from explicit corrections. The reviewed products prove components, not this integrated loop. | ADV-MORNING-001-SOTA-E007 through E040 | 2026-07-15 | Product | medium |
| ADV-MORNING-001-SOTA-H006 | hypothesis | active | Product-archetype hypothesis to test: an Advisor operating and decision layer across systems of record may create more value than another static dashboard, isolated AI chat, embedded copilot, or full-suite replacement. Buyer demand, integration feasibility, adoption cost, and ROI are unproven. | ADV-MORNING-001-SOTA-E007 through E040 | 2026-07-15 | Product | medium |
| ADV-MORNING-001-SOTA-E029 | fact | active | Taxy.io commercially provides German source-grounded tax Q&A; TaxFeed and BFH Updates add regulatory and case-law summaries with full-source links. Matching changes to affected clients is a vendor claim, not independently demonstrated performance. | [Taxy.io Answers](https://www.taxy.io/answers); [TaxFeed](https://www.taxy.io/tax-feed); [BFH Updates](https://www.taxy.io/bfh-updates) | 2026-07-15 | Taxy.io | medium |
| ADV-MORNING-001-SOTA-E030 | fact | active | Intuit Accountant Suite documents a customizable work hub with tasks, alerts, workflows, portfolio views, client KPIs, anomaly/root-cause views, and source links. It is US-focused and some advanced close capabilities have limited availability. | [Intuit Accountant Suite](https://quickbooks.intuit.com/accountants/intuit-accountant-suite/); [Getting started](https://quickbooks.intuit.com/learn-support/en-us/help-article/intuit-account-management/getting-started-intuit-accountant-suite/L7UmR2gtO_US_en_US) | 2026-07-15 | Intuit | medium |
| ADV-MORNING-001-SOTA-E031 | fact | active | CoCounsel Tax documents cited tax research, file interrogation, inconsistency and review-area detection, scenario comparison with assumptions and contrary considerations, and cited memo/client-deliverable preparation. It is not a German daily practice command center. | [Thomson Reuters CoCounsel Tax](https://tax.thomsonreuters.com/en/products/cocounsel-tax) | 2026-07-15 | Thomson Reuters | medium |
| ADV-MORNING-001-SOTA-E032 | fact | active | BStBK registry data show average Advisor age rising from 53.6 to 53.7 between 1 January 2025 and 1 January 2026, the 70+ share rising from 13.4% to 13.7%, and registered apprentices falling 1.3% from 17,301 to 17,081. | [BStBK Berufsstatistik 2024](https://www.bstbk.de/downloads/bstbk/ebooks/Berufsstatistik-2024.pdf); [2025](https://www.bstbk.de/downloads/bstbk/presse-und-kommunikation/berufsstatistiken/BStBK_Berufsstatistik_2025.pdf) | 2026-07-15 | BStBK | high |
| ADV-MORNING-001-SOTA-E033 | fact | active | In the same registry data, the employed-Advisor share rose from 33.6% to 34.1%, exclusively self-employed practice owners fell from 25,528 to 25,079, and recognized professional practice companies rose 3.8% from 14,670 to 15,232. This does not prove revenue concentration or M&A consolidation. | [BStBK Berufsstatistik 2024](https://www.bstbk.de/downloads/bstbk/ebooks/Berufsstatistik-2024.pdf); [2025](https://www.bstbk.de/downloads/bstbk/presse-und-kommunikation/berufsstatistiken/BStBK_Berufsstatistik_2025.pdf) | 2026-07-15 | BStBK | high |
| ADV-MORNING-001-SOTA-E034 | fact | active | Active and passive beSt use has been mandatory since 1 January 2023; BStBK reported about 90% of 109,688 inboxes activated by 7 May 2026 and documents staff-draft/Advisor-release operation. | [BStBK Steuerberaterplattform and beSt](https://www.bstbk.de/de/themen/steuerberaterplattform) | 2026-07-15 | BStBK | high |
| ADV-MORNING-001-SOTA-E035 | fact | active | STAX reports average profession satisfaction falling from 4.2/5 in 2018 to 3.8/5 in 2024; employed and freelance Advisors rated work-life balance 3.4/5, with 20.5% selecting the bottom two ratings. | [BStBK / IfD Allensbach, STAX 2024](https://www.bstbk.de/downloads/bstbk/recht-und-berufsrecht/fachinfos/02_Sonderauswertungen_Digitalisierung_Fachkraeftemangel_STAX2024.pdf) | 2026-07-15 | BStBK / IfD Allensbach | high |
| ADV-MORNING-001-SOTA-E036 | fact | active | BStBK's March 2026 AI guidance says AI can support preparation, extraction, research, and checks, but output may be false or incomplete; the Advisor retains responsibility. It requires professional secrecy, approved tools, documented use, monitoring, and careful hosting/data controls. | [BStBK AI FAQ](https://www.bstbk.de/downloads/bstbk/digitalisierung/BStBK_FAQ-KI_end.pdf) | 2026-07-15 | BStBK | high |
| ADV-MORNING-001-SOTA-E037 | fact | active | STAX found a positive association between digital maturity and revenue/profit development after controlling for several practice factors. This is self-reported association, not causal proof. | [BStBK / IfD Allensbach, STAX 2024](https://www.bstbk.de/downloads/bstbk/recht-und-berufsrecht/fachinfos/02_Sonderauswertungen_Digitalisierung_Fachkraeftemangel_STAX2024.pdf) | 2026-07-15 | BStBK / IfD Allensbach | medium |
| ADV-MORNING-001-SOTA-E038 | fact | active | About 25.5% of both practice cohorts named weak client connectivity as a digitalization blocker; current practitioner reports also describe mixed intake and missing or late input. | [BStBK / IfD Allensbach, STAX 2024](https://www.bstbk.de/downloads/bstbk/recht-und-berufsrecht/fachinfos/02_Sonderauswertungen_Digitalisierung_Fachkraeftemangel_STAX2024.pdf); [DATEV Community](https://www.datev-community.de/t5/Freie-Themen/Womit-verbringt-ihr-in-der-Steuerberatung-unn%C3%B6tig-viel-Zeit/td-p/488499) | 2026-07-15 | BStBK / practitioners | medium |
| ADV-MORNING-001-SOTA-E039 | fact | active | Under the BMF transition, practices must handle structured e-invoices alongside paper, PDFs, and hybrid formats; a plain PDF is not an e-invoice, and the original structured component must be retained for eight years. | [BMF e-invoice FAQ](https://www.bundesfinanzministerium.de/Content/DE/FAQ/e-rechnung.html) | 2026-07-15 | Bundesministerium der Finanzen | high |
| ADV-MORNING-001-SOTA-E040 | fact | active | Karbon's commercial documentation presents a global daily-work spine around Triage, My Week, recurring work, task automation, client requests, reminders, shared context, summaries, drafting, and assignment suggestions; its integration catalog lists no DATEV integration. | [Karbon](https://karbonhq.com/); [automation guide](https://karbonhq.com/resources/how-karbon-uses-automation-to-save-you-hours-each-week); [integrations](https://karbonhq.com/integrations/) | 2026-07-15 | Karbon | medium |
| ADV-MORNING-001-SOTA-H007 | hypothesis | active | Among the reviewed products, milia is the closest modern German whole-day reference, DATEV remains the deepest German execution/control comparator, Karbon core is the strongest reviewed global daily-work reference, and Karbon Kai is an early-access interaction ceiling. This is a public-evidence scan, not a product-quality verdict. | ADV-MORNING-001-SOTA-E013 through E040 | 2026-07-15 | Product | medium |
| ADV-MORNING-001-SOTA-H008 | hypothesis | superseded | Historical composite whole-book SOTA standard. Superseded in scope by H015: it remains a later-horizon reference, not the first-wedge product claim. | ADV-MORNING-001-SOTA-E007 through E040 | 2026-07-16 | Product | medium |
| ADV-MORNING-001-SOTA-H001 | hypothesis | superseded | Initial proposal: bound the job as morning triage ending when the Advisor enters the highest-priority item. Superseded by ADV-MORNING-001-SOTA-D001. | Working session | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-O001 | open question | superseded | Which Advisor cohort and geography should set the benchmark? Resolved by ADV-MORNING-001-SOTA-D002. | Working session | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-O002 | open question | superseded | What observation window will be used for direct as-is workflow evidence? Resolved by ADV-MORNING-001-SOTA-D003. | Working session | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-O003 | open question | superseded | Which conventional product or process is the strongest same-job comparator? Resolved by ADV-MORNING-001-SOTA-D010. | Working session | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-O004 | open question | superseded | Which AI-native system is the strongest credible frontier reference? Resolved by ADV-MORNING-001-SOTA-D011. | Working session | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-O005 | open question | superseded | What testable behavior defines conventional parity for the full-day command center? Resolved by ADV-MORNING-001-SOTA-D012. | Working session | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-O006 | open question | active | What will direct five-day observation reveal about work frequency, interruptions, priority rules, waits, overrides, return triggers, and the feeling of being in control? | External research gap | 2026-07-15 | Product | low |
| ADV-MORNING-001-SOTA-O007 | open question | active | What external German professional-secrecy, DSGVO, AI-provider, liability, documentation, and delegation rules must shape the SOTA safety bar? | Research gap | 2026-07-15 | Legal / Privacy / Product | low |
| ADV-MORNING-001-SOTA-O008 | open question | active | Which product archetype wins after testing DATEV/API access, sync latency, duplicate state, source ownership, onboarding, migration, configuration, trust, and failure recovery? | Research and prototype gap | 2026-07-15 | Product / Engineering | low |
| ADV-MORNING-001-SOTA-O009 | open question | active | Will target firms buy and adopt the proposed operating layer, and does it improve orientation time, missed-work rate, review quality, Advisor judgment time, staff leverage, client response time, and economics? | Discovery gap | 2026-07-15 | Product / Commercial | low |
| ADV-MORNING-001-SOTA-O010 | open question | superseded | Should reliable bounded action under visible Advisor control set the current SOTA bar, rather than broad autonomy across client communication, filing, payment, or professional judgment? Resolved by ADV-MORNING-001-SOTA-D008. | Working session | 2026-07-16 | Product | high |
| ADV-MORNING-001-SOTA-D001 | decision | superseded | Historical full-workday command-center scope. Superseded by D013, which keeps this as the later horizon and names a narrower first wedge. | User confirmation | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-D002 | decision | active | Benchmark German small and mid-sized tax practices serving self-employed people and SMEs. | User confirmation | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-D003 | decision | active | Target observation is the entire workday across five normal workdays. Narrow only if research shows the boundary is too broad, and record that change. | User confirmation | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-D004 | decision | active | Define SOTA from a blank-sheet market perspective. Market change, real Advisor work, and the best available products set the bar. The current Taxfix build and current internal product definition do not. | User correction | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-D005 | decision | superseded | Historical single-horizon market-standard definition. Superseded by D013: retain the market standard as later SOTA while testing a narrow first wedge first. | User direction | 2026-07-16 | Product | high |
| ADV-MORNING-001-SOTA-D006 | decision | superseded | Historical treatment of client-value detection as a core market-standard capability. Superseded by D015: it is a separate TA-gated shadow frontier, not a market fact or first-wedge acceptance condition. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-SOTA-D007 | decision | superseded | Historical single-product category. Superseded by D013: a cross-system daily home base remains later SOTA, not the first-wedge promise. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-SOTA-D008 | decision | active | Set reliable bounded action under visible Advisor control as the current SOTA bar. The product may perform real internal work inside clear permissions and stop points; the Advisor retains professional judgment and control over external or consequential actions. Broad autonomy is not required. | User confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-SOTA-D009 | decision | active | Finish the SOTA definition before choosing the next product lens. No decision has been made on whether Agentic MVP, product vision, or another lens should follow. | User direction | 2026-07-16 | Product | high |
| ADV-MORNING-001-SOTA-D010 | decision | active | Use the mature DATEV desktop stack as the strongest conventional same-job comparator. The benchmark includes DATEV Arbeitsplatz, Eigenorganisation comfort, Aufgaben, Post, Fristen und Bescheide, DMS, and ProCheck. The newer cloud product alone does not set the current bar. | User wrap-up confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-SOTA-D011 | decision | active | Use a two-part frontier. milia plus Taxy.io is the feasible German floor. Karbon core, Kai, and AI Agents are the adjacent behavior ceiling. No single reviewed product proves both German fit and the complete agentic behavior. | User wrap-up confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-SOTA-D012 | decision | active | Define parity as matching German work coverage, source fidelity, ownership, rights, handovers, checks, and safe progress. Do not define parity as copying DATEV screens or every feature. AI is not required for parity. | User wrap-up confirmation | 2026-07-16 | Product | high |
| ADV-MORNING-001-SOTA-D013 | decision | active | Use two horizons. First wedge: `SE-DIFM bookkeeping mandate → evidence-linked, review-ready package → controlled DATEV handoff`. Later SOTA: a whole-book working machine across the practice. Do not use the later horizon to inflate the first-wedge claim. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-SOTA-D014 | decision | active | DATEV remains authoritative for DATEV-owned production data. Taxfix owns its own case, task, run, evidence, review, and handoff records. Start with a manual, human-controlled DATEV handoff. Any later read or write needs a sanctioned API or connector, named authority, tenant approval, source mapping, minimum data path, reconciliation, and human gates. | User confirmation; ADV-MORNING-001-SOTA-E043 through E045 | 2026-07-17 | Product | high |
| ADV-MORNING-001-SOTA-D015 | decision | active | Treat opportunity detection as a separate TA-gated shadow frontier. It may surface an evidence-backed candidate need with confidence and unknowns; the Advisor decides whether to save, dismiss, or start a client conversation. It is not conventional parity, a market fact, automatic outreach, or automatic selling. | User confirmation | 2026-07-17 | Product | high |
| ADV-MORNING-001-SOTA-D016 | decision | active | Treat GFR.ai, Klardaten, and similar products as limited vendor-dependency signals only. They do not prove product support, permitted access, data custody, reliability, integration availability, or customer value for Taxfix. | User confirmation; ADV-MORNING-001-SOTA-E041 through E046 | 2026-07-17 | Product | high |
| ADV-MORNING-001-SOTA-H013 | hypothesis | active | A narrow manual handoff can validate the review-ready bookkeeping package before a live DATEV integration is attempted. This must be tested with the correct mandate, acceptance rubric, and handoff outcome. | ADV-MORNING-001-SOTA-D013 through D014 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-SOTA-H014 | hypothesis | active | A TA-gated shadow opportunity signal can be useful only if Advisors judge its evidence, relevance, and uncertainty as acceptable. It must earn promotion from shadow use through observed precision and Advisor decisions. | ADV-MORNING-001-SOTA-D015 | 2026-07-17 | Product | low |
| ADV-MORNING-001-SOTA-H015 | hypothesis | active | The whole-book working machine remains a later composite hypothesis: current practice state, explained priority, source-linked decisions, bounded progress, and interruption recovery may belong together, but no reviewed product proves the combination in the German market. | ADV-MORNING-001-SOTA-E007 through E040; D013 | 2026-07-17 | Product | medium |
| ADV-MORNING-001-SOTA-O014 | open question | active | What exact manual DATEV handoff action is allowed first, who performs it, and how is success or failure reconciled back to the mandate? | ADV-MORNING-001-SOTA-D014 | 2026-07-17 | Product / Advisor / Engineering | low |
| ADV-MORNING-001-SOTA-O015 | open question | active | What evidence, confidence, false-positive limit, and Advisor decision rate are required before a TA-gated opportunity signal can leave shadow use? | ADV-MORNING-001-SOTA-D015 | 2026-07-17 | Product / Advisor | low |
| ADV-MORNING-001-SOTA-E002 | fact | active | Project constraint only: the Advisor owns professional judgment, client relationships, handover acceptance or return, and opportunity decisions. This does not define the market SOTA. | [Platform context](../../tax-advisor-platform-context.md) | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-E001 | fact | superseded | Internal Today-view direction. Excluded from the market SOTA bar by ADV-MORNING-001-SOTA-D004. | Internal product direction | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-E003 | fact | superseded | Internal IA direction. Excluded from the market SOTA bar by ADV-MORNING-001-SOTA-D004. | Internal product direction | 2026-07-15 | Product | high |
| ADV-MORNING-001-SOTA-E004 | fact | superseded | Current local UI behavior. Excluded from the market SOTA bar by ADV-MORNING-001-SOTA-D004. | Local implementation | 2026-07-15 | Engineering | high |
| ADV-MORNING-001-SOTA-E005 | fact | superseded | Current local projection behavior. Excluded from the market SOTA bar by ADV-MORNING-001-SOTA-D004. | Local implementation | 2026-07-15 | Engineering | high |
| ADV-MORNING-001-SOTA-E006 | fact | superseded | Current local state-display behavior. Excluded from the market SOTA bar by ADV-MORNING-001-SOTA-D004. | Local implementation | 2026-07-15 | Engineering | high |

## Conversation decisions

- Confirmed two-horizon boundary: The first wedge is `SE-DIFM bookkeeping mandate → evidence-linked, review-ready package → controlled DATEV handoff`. The whole-book working machine is later SOTA. Do not represent the latter as first-wedge scope.
- Confirmed cohort and geography: German small and mid-sized tax practices serving self-employed people and SMEs.
- Confirmed observation window: Entire workday across five normal workdays. The boundary may be narrowed if evidence shows it is too broad.
- Confirmed benchmark perspective: Blank-sheet market SOTA. Internal product direction and implementation are out of scope as benchmark evidence.
- Confirmed product-definition boundary: The later whole-book market standard remains a useful reference. The first wedge proves one bounded mandate before it claims that standard.
- Confirmed client-value boundary: Opportunity detection is a separate TA-gated shadow frontier. It never sends, sells, or converts automatically.
- Confirmed product category: A cross-system daily home base is later SOTA. The first wedge starts with the bookkeeping mandate and a controlled DATEV handoff.
- Confirmed action bar: Real bounded work inside visible permissions and stop points. Broad autonomy is not required; the Advisor retains professional and external authority.
- Confirmed DATEV boundary: DATEV remains authoritative for DATEV-owned production data; Taxfix owns its own workflow and review records. Start manual. Move to a sanctioned API or connector only after authority, custody, and control checks pass.
- Confirmed vendor boundary: GFR.ai and Klardaten are limited vendor-dependency signals, not Taxfix product proof.
- Confirmed session boundary: Finish the SOTA definition first. The sequence after SOTA remains undecided.
- Confirmed conventional comparator: Mature DATEV desktop stack under ADV-MORNING-001-SOTA-D010.
- Confirmed AI-native frontier: milia plus Taxy.io as the feasible German floor; Karbon as the adjacent behavior ceiling under ADV-MORNING-001-SOTA-D011.
- Confirmed parity bar: German work coverage and control, not screen or feature copying, under ADV-MORNING-001-SOTA-D012.
- Matters explicitly delegated to the agent: none.

## Provisional market readback

- The market has moved from simple digitization toward scarce-capacity orchestration: more tools, more structured data, more mandatory digital channels, more AI use, and continued deadline waves—but uneven integration and client readiness.
- Advisor value is moving toward review, judgment, supervision, client decisions, and proactive advice. Evidence does not prove that compliance work or production pressure has disappeared.
- Among products reviewed, DATEV sets the German execution/control depth, milia is the closest modern German whole-day reference, Karbon core sets the strongest reviewed global daily-work pattern, Taxy.io and CoCounsel show grounded knowledge/preparation patterns, Intuit shows portfolio anomaly/advisory patterns, and Karbon Kai describes an early-access agentic ceiling.
- No reviewed product proves the full combination with German tax depth, broad availability, independent outcome evidence, and safe whole-day agents.
- The leading later-horizon hypothesis is an Advisor operating and decision layer. It must still beat incumbent extension, embedded copilot, and replacement-suite alternatives on real workflow outcomes, integration feasibility, adoption, and ROI.
- The immediate proof point is smaller: one SE-DIFM bookkeeping mandate, a review-ready package, and a controlled DATEV handoff. That does not prove a whole-book working machine.

## Research coverage

- Research mechanisms used: browser research; supplied project constraints
- Search boundary and date: German and relevant global market change, Advisor workflow, conventional-product, modern-platform, and AI-frontier evidence current to 2026-07-15.
- Research limitations or blockers: No direct five-day observation of real Advisors has been supplied. External research can bound the market and product SOTA, but it cannot substitute for that baseline.

### Evidence and maturity vocabulary

- `independent evidence`: regulator, law, representative study, or independently hosted observation;
- `official process evidence`: professional-body or public-authority workflow;
- `commercial-doc`: vendor documentation presents the capability as currently sold or available;
- `GA-release`: official help or release note confirms broad availability;
- `limited`: beta, open beta, limited rollout, or early access;
- `roadmap`: coming soon or future scope;
- `vendor-claim`: performance, adoption, compliance, or outcome assertion without independent proof;
- `hypothesis`: synthesis or product implication that still needs observation or testing.

Availability is not performance proof. Features available in separate products do not prove that their combination is feasible, adoptable, or safe in one German platform.

| Source ID | Publisher | URL | Access date | Supported claim | Evidence quality | Claim status |
| --- | --- | --- | --- | --- | --- | --- |
| DE-ASIS-001 | BStBK / IfD Allensbach | [STAX 2024 special analysis](https://www.bstbk.de/downloads/bstbk/recht-und-berufsrecht/fachinfos/02_Sonderauswertungen_Digitalisierung_Fachkraeftemangel_STAX2024.pdf) | 2026-07-15 | Practice size, tool adoption, digital blockers, staffing pressure, and data-analysis opportunity | Representative weighted survey; 5,815 respondents; self-report rather than observation | independent evidence |
| DE-ASIS-002 | BStBK | [The Tax Advisor](https://www.bstbk.de/de/berufsbild-steuerberater/der-steuerberater) | 2026-07-15 | Official Advisor responsibility | Primary professional-body source | official process evidence |
| DE-ASIS-003 | BStBK | [Education and professional roles](https://www.bstbk.de/de/berufsbild-steuerberater/aus-und-fortbildung) | 2026-07-15 | Specialist preparation and handoff roles | Primary professional-body source | official process evidence |
| DE-ASIS-004 | BStBK | [Steuerberaterplattform and beSt](https://www.bstbk.de/de/themen/steuerberaterplattform) | 2026-07-15 | Mandatory channel and concrete staff-to-Advisor release workflow | Primary official process evidence | official process evidence |
| DE-ASIS-005 | DATEV | [Post, Fristen und Bescheide overview](https://wissensplattform.apps.datev.de/help/document/9250343) | 2026-07-15 | Multi-channel inbound, notice, deadline, state, alert, DMS, and four-eyes workflow | Current official product documentation | commercial-doc |
| DE-ASIS-006 | DATEV | [Post, Fristen und Bescheide product stack](https://wissensplattform.apps.datev.de/help/document/9217659) | 2026-07-15 | Tasks and handoffs created from inbound, outbound, notices, and deadlines | Current official product documentation | commercial-doc |
| DE-ASIS-007 | Federal Ministry of Justice / Federal Office of Justice | [UStG §18](https://www.gesetze-im-internet.de/ustg_1980/__18.html), [EStG §41a](https://www.gesetze-im-internet.de/estg/__41a.html), [AO §149](https://www.gesetze-im-internet.de/ao_1977/__149.html) | 2026-07-15 | Recurring monthly, quarterly, and annual deadline waves | Primary law | independent evidence |
| DE-ASIS-008 | WMS | [A day in the life of a tax advisor](https://www.wms-stb.de/artikel/ein-tag-im-leben-eines-steuerberaters/) | 2026-07-15 | One partner's day spans client, team, process, IT, and succession-advice meetings | First-person account from one mid-sized practice | limited |
| DE-ASIS-009 | DATEV Community contributors | [Practitioner thread on avoidable time](https://www.datev-community.de/t5/Freie-Themen/Womit-verbringt-ihr-in-der-Steuerberatung-unn%C3%B6tig-viel-Zeit/td-p/488499) | 2026-07-15 | Missing inputs, channel fragmentation, interruptions, and software failure reports | Current qualitative signal; not representative | limited |
| CONV-001 | Bundeskartellamt | [Case report B7-25/17](https://www.bundeskartellamt.de/SharedDocs/Entscheidung/DE/Fallberichte/Missbrauchsaufsicht/2019/B7-25-17.pdf?__blob=publicationFile&v=4) | 2026-07-15 | DATEV market maturity and historical completeness | Independent primary authority; dated 2019 | independent evidence |
| CONV-002 | DATEV | [Working with tasks in DATEV](https://wissensplattform.apps.datev.de/help/document/9216659) | 2026-07-15 | Central task aggregation, filters, groups, sorting, reminders, Outlook, and rights | Current operating documentation | commercial-doc |
| CONV-003 | DATEV | [Order overview](https://wissensplattform.apps.datev.de/help/document/9257861) | 2026-07-15 | Client-order planning and control across deadlines, staff, capacity, status, checklists, economics, and billing | Current operating documentation | commercial-doc |
| CONV-004 | DATEV | [ProCheck setup guide](https://wissensplattform.apps.datev.de/help/document/0904161) | 2026-07-15 | Process checklist, responsibility, handoff, status, and archive behavior | Current operating documentation | commercial-doc |
| CONV-005 | DATEV | [Eigenorganisation comfort](https://www.datev.de/web/de/shop/produkt-details/eigenorganisation-comfort-61400) | 2026-07-15 | Early-warning, daily order overview, economics, and implementation claims | Vendor marketing and customer quote | vendor-claim |
| CONV-006 | DATEV | [Kanzleimanagement cloud transition](https://www.datev.de/web/de/steuerberatung/themen-im-fokus/umstieg-cloud-vorbereiten/kanzleimanagement) | 2026-07-15 | Tasks, documents, deadlines, and responsibilities remain future bundled scope | Vendor roadmap wording | roadmap |
| CONV-007 | Wolters Kluwer | [ADDISON Kanzleiorganisation](https://www.wolterskluwer.com/de-de/solutions/addison-komplettloesung-steuerberater/addison-kanzleiorganisation) | 2026-07-15 | Closest broad-suite alternative: client activities, process planning, task lists, open items, billing | Vendor summary | vendor-claim |
| CONV-008 | Agenda | [Agenda Office-Management](https://www.agenda-software.de/steuerberater/software/office-management.php) | 2026-07-15 | Lean challenger: status, assignment, deadlines, substitutes, checklists, DMS, profitability | Vendor summary | vendor-claim |
| FRONT-001 | milia | [Kanzleisteuerung](https://milia.io/kanzleisteuerung) | 2026-07-15 | Real-time firm view across matters, tasks, deadlines, owners, status, approvals, and history | Concrete vendor documentation; no independent outcome proof | commercial-doc |
| FRONT-002 | milia | [Vorgangsmanagement](https://milia.io/feature/vorgangsmanagement) | 2026-07-15 | Matter list with status, open tasks, owner, next step, priority sorting, and filters | Concrete vendor feature documentation | commercial-doc |
| FRONT-003 | milia | [milia.AI](https://milia.io/milia-ai) | 2026-07-15 | Assistive AI marketed as available; multi-step agents are `Bald verfügbar` | Strong for stated feature status; weak for accuracy claims | commercial-doc / roadmap |
| FRONT-004 | milia | [Workflow automation](https://milia.io/workflow-automatisierung) | 2026-07-15 | Triggered workflows create tasks, deadlines, reminders, requests, and approvals | Detailed vendor workflow documentation | commercial-doc |
| FRONT-005 | milia | [Activity history](https://milia.io/feature/aktivitatsverlauf), [Approvals](https://milia.io/feature/freigaben) | 2026-07-15 | Chronological matter history and logged human approval | Direct vendor feature documentation | commercial-doc |
| FRONT-006 | milia | [Taxy.io Answers](https://milia.io/feature/taxy-io-answers) | 2026-07-15 | German source-linked tax research integration | Vendor integration evidence; accuracy claim unproven | commercial-doc / vendor-claim |
| FRONT-007 | Karbon | [Kai](https://karbonhq.com/feature/kai/) | 2026-07-15 | Briefing, live firm questions, prioritization, summaries, agent invocation, and human controls | Detailed vendor claim; limited early access | limited / vendor-claim |
| FRONT-008 | Karbon | [AI Agents](https://karbonhq.com/feature/agents/) | 2026-07-15 | Continuous monitoring, bottleneck detection, process following, auditability, and human gates | Vendor claim; early access | limited / vendor-claim |
| FRONT-009 | Karbon | [March 2026 release notes](https://karbonhq.com/release-notes/mar-31-2026/) | 2026-07-15 | GA assistive summaries, drafting, quick replies, and smart suggestions | Official availability evidence | GA-release |
| FRONT-010 | Karbon | [Integrations](https://karbonhq.com/integrations/) | 2026-07-15 | No DATEV integration listed | Current official integration catalog | commercial-doc |
| FRONT-011 | Intuit | [Intuit Accountant Suite](https://quickbooks.intuit.com/accountants/intuit-accountant-suite/) | 2026-07-15 | Adjacent US portfolio dashboard, anomaly detection, tasks, and cross-client insights | Vendor evidence; wrong tax system and mixed maturity | commercial-doc / limited |
| MARKET-001 | Bundesministerium der Finanzen | [FAQ zur obligatorischen E-Rechnung](https://www.bundesfinanzministerium.de/Content/DE/FAQ/e-rechnung.html) | 2026-07-15 | Mandatory ability to receive structured domestic B2B e-invoices from 2025 and staged issuing transition | Primary official guidance | regulatory fact |
| MARKET-002 | BStBK | [Berufsstatistik 2024](https://www.bstbk.de/downloads/bstbk/ebooks/Berufsstatistik-2024.pdf) | 2026-07-15 | Advisor age, employment, ownership, apprentice, and company-form baseline at 1 January 2025 | Administrative registry census | independent evidence |
| MARKET-003 | BStBK | [Berufsstatistik 2025](https://www.bstbk.de/downloads/bstbk/presse-und-kommunikation/berufsstatistiken/BStBK_Berufsstatistik_2025.pdf) | 2026-07-15 | One-year movement in Advisor demographics and practice structure at 1 January 2026 | Administrative registry census | independent evidence |
| MARKET-004 | BStBK | [FAQ zum Einsatz generativer KI](https://www.bstbk.de/downloads/bstbk/digitalisierung/BStBK_FAQ-KI_end.pdf) | 2026-07-15 | Human responsibility, hallucination risk, professional secrecy, approved-tool use, documentation, monitoring, and hosting/data guidance | Professional-body guidance; not outcome evidence | official process evidence |
| FRONT-012 | Taxy.io | [TaxFeed](https://www.taxy.io/tax-feed), [BFH Updates](https://www.taxy.io/bfh-updates), [Answers](https://www.taxy.io/answers) | 2026-07-15 | German source-grounded research and regulatory/case-law update patterns | Primary vendor evidence; client matching and outcome quality unproven | commercial-doc / vendor-claim |
| FRONT-013 | Intuit | [Accountant Suite help](https://quickbooks.intuit.com/learn-support/en-us/help-article/intuit-account-management/getting-started-intuit-accountant-suite/L7UmR2gtO_US_en_US) | 2026-07-15 | Work hub, tasks, alerts, workflows, navigation, and portfolio tracking | Primary product/help evidence; US fit | commercial-doc |
| FRONT-014 | Thomson Reuters | [CoCounsel Tax](https://tax.thomsonreuters.com/en/products/cocounsel-tax) | 2026-07-15 | Cited research, file review, inconsistency detection, scenarios, and cited deliverables | Primary vendor evidence; performance claims unverified; US content | commercial-doc / vendor-claim |
| FRONT-015 | Karbon | [Core platform](https://karbonhq.com/), [automation guide](https://karbonhq.com/resources/how-karbon-uses-automation-to-save-you-hours-each-week) | 2026-07-15 | Triage, My Week, recurring work, automation, requests, reminders, and shared daily-work context | Primary commercial documentation; no independent same-job outcome proof | commercial-doc |
| LOCAL-004 | Taxfix Harness Product | [Platform context](../../tax-advisor-platform-context.md) | 2026-07-15 | Later project authority, evidence, data, and safety constraints | Primary internal contract | project-constraint, not SOTA evidence |

## Market changes shaping the SOTA

| Market shift | Evidence | What it changes in the Advisor's daily process | Confidence |
| --- | --- | --- | --- |
| Scarce professional capacity | 59.1% of solo-practice vacancies and 29.1% in professional practice companies remained unfilled | The platform must remove coordination and preparation load, protect Advisor judgment time, and make delegation safer. Adding another inbox is failure. | high |
| Aging profession and thinner training pipeline | Average Advisor age and the 70+ share rose while apprentice numbers fell between the 2024 and 2025 registry snapshots | Reusable practice knowledge, clear delegation, review context, and continuity cannot depend on one partner's memory. | high for fact; medium for implication |
| More employed Advisors and professional practice companies | Employed-Advisor share and recognized practice companies rose while exclusively self-employed owners fell | The daily platform must handle teams, role boundaries, handoffs, supervision, and multiple approval levels—not only a solo owner's to-do list. | high for fact; medium for implication |
| More tools, uneven integration | Practices report using many digital tools, while DMS, client interfaces, and CRM adoption differ sharply by practice size; incompatibility and organizational effort remain blockers | SOTA must join work across systems and work for less-digitized firms. It cannot depend on every client and practice having a perfect stack. | high |
| Continuous structured data | Domestic B2B e-invoice receipt became mandatory in 2025, with issuing transitions through 2026/27 | The operating model shifts from waiting for document batches toward monitoring data flow, exceptions, missing evidence, and changing client state. | high for rule; medium for workflow implication |
| Hybrid evidence will persist during transition | Plain PDFs do not qualify as e-invoices, the structured component must be retained, and transitional paper/PDF/hybrid intake remains | SOTA needs format-aware intake, readable views, source preservation, visible failures, and a safe way to work when client digitization is incomplete. | high |
| Mandatory professional digital channels | beSt has been mandatory since 2023 and supports staff preparation followed by Advisor release | The daily process needs trusted identity, inbound/outbound state, deadlines, explicit send authority, and end-of-day control—not merely internal tasks. | high |
| AI adoption is real but shallow | Chatbots are already used or planned by a material share of practices, especially larger ones | As adoption grows, generic chat alone is a weak differentiation hypothesis. Context, workflow state, sources, bounded action, human control, and measured correction need validation as the stronger bar. | high for adoption; medium for implication |
| AI governance is now a product gate | BStBK warns that AI output can be false or incomplete and requires retained Advisor responsibility, professional secrecy, approved tools, documentation, and monitoring | Grounding, review state, data-path clarity, and human responsibility are part of the market bar, not optional enterprise polish. | high for guidance |
| Value may extend toward judgment and advice | Practices identify structured client-data analysis as an opportunity for additional services; specialist staff already prepare much routine compliance work | The first wedge should produce review-ready decisions. Evidence-backed client needs belong to a separate TA-gated shadow frontier, not a claimed market outcome. | medium-high |
| Compliance work arrives in recurring waves | Monthly, quarterly, and annual legal deadlines coexist with notices, client questions, and internal review | SOTA must continuously rebalance scheduled work and exceptions instead of serving a static morning list. | high |
| Work pressure is visible | Profession satisfaction and work-life-balance ratings have declined | The product should be judged on reduced re-orientation, fewer missed loops, and more protected judgment time—not engagement or screen time. | high for fact; medium for implication |
| Client-side connectivity remains uneven | Roughly one quarter of both cohorts named weak client connectivity as a blocker, while practitioners report mixed channels and late input | The process must represent waiting-on-client work and channel/source state instead of assuming clean portal adoption. | medium-high |

## Observed as-is workflow — desk-research reconstruction

This is the **later whole-book horizon**. It describes the market job the working machine may eventually cover. It is not the first-wedge job contract.

- Cohort and sample size: German small and mid-sized tax practices serving self-employed people and SMEs; no real Advisor sample supplied yet.
- Observation window: Target is the entire workday across five normal workdays; no direct observation completed yet.
- Direct evidence available: Representative German self-report data, official role and process definitions, primary law, current market-product operating documentation, and limited practitioner reports. No direct five-day observation exists.
- Jurisdiction and regime: Germany. Later horizon: cross-client recurring bookkeeping and business-tax work. First wedge: one named SE-DIFM bookkeeping mandate and period; tax year and bookkeeping period remain visible per item.
- Eligible cohort: Licensed Advisors in small and mid-sized practices serving self-employed people and SMEs, plus their supervised preparation handoffs.
- Explicit cohort exclusions: DACH-wide comparison, large-enterprise tax departments, and individual-income-tax-only practices.
- Actor and trigger: The Advisor opens or returns to the desk after starting the day, finishing work, receiving an interruption, or expecting changed state.
- Desired outcome: Later horizon: maintain control across commitments, changes, waits, reviews, client work, and professional decisions throughout the day. First wedge: deliver an evidence-linked, review-ready bookkeeping package and controlled DATEV handoff.
- Accepted end state: Confirmed within the outcome-and-control parity bar under ADV-MORNING-001-SOTA-D012: every material item is visible and current; each urgent item is handled, intentionally delegated or deferred with owner and timing, or visibly blocked with reason; no critical item is silently absent.
- Material correction: Confirmed within ADV-MORNING-001-SOTA-D012: a correction that changes whether an item must be shown, its priority tier, deadline or consequence, owner, blocker, required Advisor decision, or source support.
- False-ready definition: Confirmed within ADV-MORNING-001-SOTA-D012: the desk states or implies that work is clear, safe, or complete while a material deadline, review, unresolved conflict, missing input, unsupported capability, stale state, or required Advisor decision is absent or misclassified.
- Valid blocked outcomes: Waiting on client, authority, internal preparation/review, or a required system/data connection. Every block needs a reason, owner, source, and next check.
- External safety boundary: BStBK guidance keeps professional responsibility with the Advisor and requires secrecy, approved tools, documentation, monitoring, and data-path care. The complete German legal and privacy bar remains ADV-MORNING-001-SOTA-O007.

| Step | Role | Tool | Input/artifact | Output | Hands-on time | Waiting | Failure or rework risk |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1. Orient and repeatedly re-orient | Advisor | Calendar, deadline/task lists, inboxes, DMS, specialist tax software | New inbound, deadlines, follow-ups, meetings, prepared work | Working priority order | Unknown | Unknown | No direct evidence that one surface holds the complete current state |
| 2. Receive and triage inbound | Staff and Advisor | Paper, phone, fax, email, beSt, ELSTER, portals | Messages, documents, notices, questions | Filed input, task, deadline, reply, or handoff | Unknown | Unknown | Channel spread, manual filing, missed context, duplicate work |
| 3. Prepare recurring work | Tax specialists | Bookkeeping, payroll, return, DMS, and client-collaboration software | Client data and documents | Bookkeeping, business figures, returns, accounts, assessment checks | Unknown | Client input and authority response | Missing, late, or incompatible input; staffing constraints |
| 4. Review and apply judgment | Advisor | Specialist work products, source documents, research, task records | Prepared work and exceptions | Approval, correction, advice, representation, or return | Unknown | Internal review queue | Weak handover, hidden evidence gap, professional rework |
| 5. Advise clients and lead the practice | Advisor | Meetings, phone, email, analysis, team coordination | Client questions, business figures, risks, team issues | Advice, decisions, assignments, follow-ups | Unknown | Client and colleague response | Scheduled work competes with urgent exceptions |
| 6. Handle exceptions and missing input | Staff and Advisor | Inboxes, tasks, deadlines, client requests | Notice deviation, deadline risk, missing evidence, urgent question | Resolution, escalation, request, deferment, or visible block | Unknown | Client, authority, or reviewer | Interruptions, unclear owner, repeated chase work |
| 7. Close control loops | Staff and Advisor | beSt and process controls | Prepared messages and decisions | Advisor release, dispatch, receipt, recorded state | Unknown | Transmission/receipt | Items can remain hidden across separate queues |

- What works today: Mature specialist workflows exist for tasks, deadlines, notices, documents, staff preparation, Advisor review, and recorded dispatch. Role boundaries and four-eyes controls are real strengths.
- Main pain, delay, risk, and handoff failures: Evidence shows split tools and channels, missing input, incompatible systems, manual filing, staffing pressure, and interruptions. It suggests—but does not directly observe—that Advisors must repeatedly join task, deadline, message, document, client, team, and risk signals themselves.
- Missing baseline evidence: The requested five-day observation does not exist in the sources found. Time per work type, daily interruptions, channel switches, actual priority order, wait duration, small-versus-mid practice differences, Advisor versus staff screen use, opportunity frequency, and what “in control” means at different times remain unknown.

### Workflow variation the benchmark must cover

| Variation | Why one generic “Advisor day” is insufficient | Required observation |
| --- | --- | --- |
| Role | Solo owner, employed Advisor, partner, and team lead have different books, authority, and supervision load | Tag every event by role, decision authority, preparer, and reviewer |
| Practice size and digital maturity | Small and mid-sized firms differ sharply in tool adoption, interfaces, staffing, and client connectivity | Sample both cohorts and record actual systems and workarounds |
| Day mode | Morning orientation, client meetings, focused review blocks, urgent notices, staff escalations, and end-of-day release create different needs | Capture return trigger, current intent, interruption source, and time to resume |
| Seasonality | Monthly VAT/payroll, quarterly waves, annual returns, Jahresabschluss work, and one-off legal changes create different load shapes | Repeat research in at least one normal and one peak period |
| Client readiness | Some clients provide structured digital data; others send late, incomplete, or mixed-format evidence | Record channel, format, completeness, wait owner, chase count, and resolution |
| Work type | Compliance production, review, advice, practice leadership, and client relationship work use different context and success criteria | Tag job type, desired outcome, source evidence, and accepted end state |

Desk research cannot determine the final information order. The five-day study must do that.

## Proposed synthesis of a state-of-the-art daily Advisor process

This is the **later whole-book working-machine horizon**. The reviewed market evidence supports testing a repeating control loop. It does not prove that this full loop is already adopted or delivered by one product:

```text
sync state → detect change → orient and rank → prepare → decide → act → monitor → return
```

| Stage | Advisor outcome | Proposed platform role | 2026 evidence and maturity |
| --- | --- | --- | --- |
| 1. Maintain current practice state | The Advisor does not reconstruct reality from memory | Join current client, engagement, task, deadline, message, document, filing, review, team, and regulatory state while keeping source ownership and timestamps | Components are commercially documented in DATEV, milia, and Karbon. Complete cross-system state and DATEV/API feasibility are unproven. |
| 2. Detect material change | New work reaches the right human | Detect deltas, missing input, deadline risk, notice deviations, blockers, stale work, review needs, capacity conflicts, and evidence-backed advisory triggers | Rules and workflow triggers are commercially documented. Broad AI detection quality and affected-client matching lack independent proof. |
| 3. Re-orient on every return | The Advisor understands what changed and what it means | Give a change-since-last-visit brief, scheduled commitments, waiting work, and the few interventions that may need judgment | Partial support is documented. Karbon's richer continuous briefing is limited/early access and non-German. |
| 4. Rank transparently | The Advisor can trust or correct the order | Rank by visible factors such as legal deadline, client harm, financial consequence, readiness, wait duration, dependency, confidence, and capacity; show why; allow override | Filtering and rule-based priority are commercially documented. Reliable whole-day AI reprioritization is unproven. |
| 5. Prepare a decision packet | Judgment starts with context, not hunting | Assemble client context, impact, evidence and sources, prior actions, unknowns, conflicting signals, recommended next step, and safe alternatives | Grounded research, summaries, document analysis, and workflow context exist in separate products. The integrated packet is a hypothesis. |
| 6. Decide and direct | The Advisor keeps professional authority | Accept, correct, return, delegate, defer, dismiss, or decide whether a real client need warrants follow-up; capture the reason and required next step | Approval and workflow controls are commercially documented. BStBK guidance keeps professional responsibility with the Advisor. |
| 7. Execute bounded work | Decisions become progress without losing control | Update internal state, assign work, start deterministic workflows, prepare drafts or missing-document requests, and stop at named gates before external or consequential action | Deterministic workflows and drafts are commercially documented. Broad multi-step agents remain limited, early access, or roadmap. |
| 8. Monitor, close, and learn | The Advisor can leave and return without losing the thread | Track waits, replies, results, retries, deadlines, receipts, corrections, and outcomes; learn only from explicit accepted corrections; surface the next changed state | Durable histories are commercially documented. Safe policy learning from Advisor behavior is not proven. |

### Outcomes that must prove the synthesis

| Outcome | What to measure against the current workflow |
| --- | --- |
| Fast orientation and recovery | Time to identify the next material intervention after opening or returning; time to resume after interruption |
| Complete coverage | Material items omitted, stale, duplicated, or misclassified; false-clear rate |
| Decision readiness | Source-hunting time, unknowns found after opening work, and material corrections during review |
| Better flow | Context switches and screens opened per resolved intervention; time from signal to owned next action |
| Safer delegation | Handover returns, reassignment, ambiguous ownership, and work waiting without a named unblocker |
| Better client flow | Wait time for client input, repeated chase work, response turnaround, and missed service commitments |
| More Advisor-value time | Share of time spent on judgment, advice, review, and client decisions instead of coordination and status reconstruction |
| Trust and control | Advisor overrides, reason for override, acceptance/return rate, ignored alerts, and recovery after wrong or stale state |
| Practice economics | Throughput, WIP, staff leverage, review cost, billing delay, profitability signal, and adoption/configuration effort |

No numeric target is locked yet. The five-day baseline must set it.

### Product-archetype hypothesis to validate

This is the **later whole-book horizon**, not the first-wedge architecture decision.

The leading later-horizon hypothesis is an **Advisor operating and decision layer**. This is not established market fact. It must beat three credible alternatives on adoption, integration, trust, and ROI.

| Archetype | Why it could win | Main risk | Current assessment |
| --- | --- | --- | --- |
| Extend the German incumbent | Native data, identity, production links, and lower duplicate-state risk | Dependence on incumbent roadmap and module boundaries | Strong conventional path; difficult for a new product to control |
| Embed a copilot inside one existing tool | Low switching cost and fast access to local context | Narrow context reproduces fragmentation and cannot govern the whole day | Useful capability, weak full-job answer |
| Add an orchestration and decision layer across systems | Can join changes, decisions, evidence, waits, and bounded action without replacing production systems | API access, source ownership, latency, duplicate state, failure recovery, and onboarding may kill it | Leading hypothesis; requires integration prototype and buyer proof |
| Replace the practice suite | One coherent model and interaction | Migration, training, workflow variance, trust, and German tax breadth create extreme adoption cost | Do not assume this wins without strong buyer evidence |

The orchestration-layer hypothesis is that it should:

- sit across the firm's systems of record while leaving source ownership explicit;
- keep a live cross-client model of work, evidence, deadlines, people, waits, decisions, and client needs;
- make every return valuable by explaining what changed and what needs judgment now;
- prepare source-linked decision packets rather than generic summaries;
- turn Advisor decisions into bounded, traceable workflow progress;
- preserve human authority and documented approval where professional responsibility or external effect requires it;
- learn from explicit corrections and outcomes, not silently infer policy from clicks.

The current evidence suggests that a KPI dashboard or isolated tax chat would cover too little of the job. It does not yet prove that a cross-system orchestration layer is technically feasible or commercially superior.

## Later whole-book working-machine SOTA

This section defines a **later market-standard horizon**, not the first Taxfix product. It states the problems a whole-book Advisor Desk must eventually solve, the general capabilities it must provide, and the proof required to succeed. It does not choose a UI, architecture, roadmap, feature sequence, or autonomy level.

No reviewed product meets the complete standard. The definition is a composite of the strongest documented German operating capabilities, global daily-work patterns, grounded tax-work preparation, and the credible agentic frontier. It is a later-horizon hypothesis under ADV-MORNING-001-SOTA-H015 until direct workflow, integration, adoption, and outcome evidence validate it.

### Product definition in one sentence

The later SOTA Advisor Desk is the Advisor's **operating and decision layer**: it maintains a current view of the practice across existing systems, detects what materially changed, explains what needs judgment and why, prepares the decision, turns the Advisor's choice into bounded progress, and preserves the thread until the work is closed.

The standard is outcome-based. AI is optional for each capability. A reliable rule, workflow, or integration is better than an impressive agent that misses work or hides uncertainty.

### First wedge before the working machine

The first product has a smaller, testable contract:

```text
SE-DIFM bookkeeping mandate → reconcile available evidence and blockers → review-ready package → Advisor accept or return → controlled DATEV handoff
```

- The package links every material claim to evidence and names missing input, conflicts, unknowns, and unsupported capability.
- The Advisor accepts or returns it. Human judgment stays with the Advisor.
- The first DATEV handoff is manual and controlled. Taxfix does not silently change DATEV-owned production data.
- Opportunity signals, if shown, stay in a TA-gated shadow lane and do not affect the package's readiness decision.
- A sanctioned DATEV API or connector is later work, not an assumed first-wedge dependency.

### DATEV authority, data custody, and handoff route

| Concern | Rule |
| --- | --- |
| System of record | DATEV remains authoritative for DATEV-owned production data and the effect of any DATEV action. Taxfix remains authoritative only for its own case, task, run, evidence, review, and handoff records. |
| Source and custody | Every package item shows its source, timestamp, and owner. Taxfix uses only the minimum data approved for the named mandate and does not treat a vendor connector or copied data as a new source of truth. |
| First handoff | A named human reviews the package and performs or approves the DATEV handoff. The handoff result is recorded with its source and status. |
| Later integration | Read or write may move to a sanctioned DATEV API or connector only after named authority, tenant approval, source mapping, data-path/custody review, error handling, reconciliation, and human gates are proven. |
| Not allowed by this SOTA | Unapproved credentials, unsanctioned screen-driving, silent DATEV writes, or a connector treated as proof of permission or reliability. |

The exact first DATEV action remains open: document transfer, export, posting proposal, or another controlled handoff. Do not silently choose it.

### Problems the product must solve

| Problem | Required user outcome |
| --- | --- |
| The Advisor reconstructs practice state from tools, inboxes, people, and memory | One current view shows material work, its source, owner, state, deadline, wait, and last change |
| Important changes hide inside separate queues | New deadlines, messages, documents, notice deviations, blockers, stale work, review needs, capacity conflicts, and regulatory changes become visible interventions |
| Every return to the desk starts with re-orientation | The Advisor sees what changed since the last visit, today's fixed commitments, what is waiting, and what needs attention now |
| Priority lives in the Advisor's head | The product proposes an order, shows the factors behind it, and lets the Advisor correct it without losing the original reasoning |
| Review starts with source hunting | Each intervention arrives with client context, impact, evidence, history, unknowns, conflicts, options, and the required decision |
| Decisions create more coordination work | The Advisor can accept, correct, return, delegate, defer, dismiss, or request follow-up and create an owned next action from the same context |
| Waiting work and interruptions lose their thread | Client waits, internal waits, authority waits, retries, replies, receipts, and next checks stay visible until closure |
| Delegation creates weak handovers and hidden supervision load | People and agents receive bounded work with clear authority, evidence, escalation, review, and ownership |
| Potential client needs are easy to miss | Later, a TA-gated shadow lane may surface evidence-backed candidate needs for Advisor judgment. It must not claim a market-proven match or change first-wedge readiness. |
| New software adds another silo and a long migration | The Desk works across the firm's systems of record, preserves source ownership, and creates value before the whole practice is transformed |

### Required capability families

| Capability | Minimum market-standard behavior | 2026 maturity |
| --- | --- | --- |
| 1. Federated practice state | Join client, engagement, work, task, deadline, message, document, filing, review, team, capacity, and relevant economic state. Keep the owning source, timestamp, and sync health visible. | Components are mature. Reliable cross-system German integration is unproven. |
| 2. Change and exception engine | Convert source events into current interventions. Detect deltas, missing input, deadline risk, conflicts, stale state, review needs, notice deviations, waiting breaches, and capacity collisions. | Rules and triggers are mature. Broad cross-signal quality is unproven. |
| 3. Return brief | On opening and every return, explain what changed, what is fixed today, what moved, what is blocked, and where the Advisor's judgment has the highest consequence. | Partial commercial support exists. Rich continuous briefing is still frontier behavior. |
| 4. Transparent priority | Rank by visible factors such as legal deadline, client harm, financial consequence, readiness, dependency, wait duration, confidence, and capacity. Support filters, manual override, and an explanation of the order. | Filters and rule-based priority are mature. Reliable whole-day AI ranking is unproven. |
| 5. Decision packets | Assemble the work product, client context, impact, sources, prior actions, unknowns, conflicts, recommendation, safe alternatives, and exact decision needed. | The pieces exist in separate products. The integrated packet remains a hypothesis. |
| 6. Decision and bounded-action controls | Let the Advisor accept, correct, return, delegate, defer, dismiss, or initiate a controlled next step. Prepare drafts and deterministic workflows. Stop at named gates before professional or external effects. | Human-controlled workflows are mature. Broad multi-system agent execution is not. |
| 7. Client and wait orchestration | Link inbound, requests, documents, reminders, response state, promises, and follow-ups to the correct client and work. Show who or what is holding progress. | Requests, reminders, and histories are available. Clean multi-channel joining remains uneven. |
| 8. Monitoring, recovery, and closure | Track results, replies, receipts, retries, changed sources, corrections, reopened work, and overdue next checks. Resume after interruption without rebuilding context. | Durable histories are mature. Continuous re-ranking and safe policy learning are unproven. |
| 9. Team and agent supervision | Show ownership, workload, readiness, handovers, escalations, review load, capability limits, and authority boundaries across people and agents. | Conventional role and capacity controls exist. Agent supervision maturity varies. |
| 10. Grounded tax and regulatory intelligence | Answer tax questions with sources, surface relevant legal or case-law changes, and identify potentially affected work or clients without presenting a match as certain. | Source-linked German research exists. Affected-client matching lacks independent proof. |
| 11. TA-gated opportunity shadow frontier | Separately surface an observed candidate need, its evidence, client impact, confidence, and unknowns. The Advisor may save, dismiss, or start a conversation. It does not auto-sell, auto-contact, or set first-wedge readiness. | This is a product hypothesis, not conventional parity or a market fact. |
| 12. Trust, authority, and recovery | Make sources, unknowns, conflicts, permissions, review state, action history, sync failure, and safe fallback visible. Never present stale, incomplete, or unsupported work as clear. | Rights, approvals, and histories are mature. Complete AI, privacy, and liability proof remains open. |

### Required interaction shape

This is not a screen design. It is the minimum behavior the product surface must support.

| Product mode | What the Advisor must be able to do |
| --- | --- |
| Return brief | Regain control in minutes after opening or an interruption |
| Ranked intervention stream | See the small set of current items that need attention, why they matter, and what can wait |
| Decision workspace | Review the complete packet, inspect sources and unknowns, make the decision, and start the next action without context hunting |
| Durable client and work context | Move from an intervention into the client's relationship, obligations, communication, evidence, active work, decisions, and history |
| Practice control | Search or ask across live practice state; inspect work, waits, people, agents, capacity, integrations, and policy; correct ownership or priority when needed |

A separate dashboard, inbox, task list, chat, and automation console do not satisfy this shape if the Advisor must mentally join them.

### Market-entry bar, winning bar, and proof bar

| Bar | A product must show |
| --- | --- |
| First-wedge acceptance bar | One named SE-DIFM bookkeeping mandate and period; evidence-linked reconciliation; visible blockers, unknowns, conflicts, and unsupported capability; Advisor accept/return; controlled manual DATEV handoff; no silent DATEV change |
| Later market-entry parity | German tax-practice depth; tasks, deadlines, clients, documents, notices, requests, roles, rights, process steps, source links, deterministic workflows, approvals, histories, and credible DATEV or equivalent system fit |
| Later SOTA winning behavior | Change-since-last-visit briefing; complete and current cross-client interventions; explained priority; source-linked decision packets; bounded action; wait monitoring; interruption recovery; grounded regulatory signals. TA-gated opportunity detection remains a separate shadow frontier. |
| Market-success proof | Fast onboarding; reliable sync and source ownership; low false-clear and missed-item rates; shorter orientation and source-hunting time; fewer context switches; more Advisor judgment time; safer delegation; better client response; repeat daily use; and economic value above configuration and support cost |

No numeric threshold is invented here. The five-day baseline and later pilot must set it.

### What does not qualify as a SOTA Advisor Desk

- A KPI dashboard that shows problems but cannot move them forward.
- A larger task list or inbox that still makes the Advisor reconstruct context.
- A generic chatbot without current practice state, sources, authority, and durable workflow.
- AI summaries that hide missing input, conflicting evidence, or stale state.
- An automation builder that shifts process design and exception handling back to the Advisor.
- A replacement suite that requires a full migration before delivering daily value.
- Autonomous client messages, filings, payments, legal judgment, or selling presented as progress.
- A product measured mainly by logins, clicks, messages, or model usage instead of accepted outcomes and recovered Advisor time.

### Honest maturity boundary

The first wedge can be useful today with evidence-linked preparation, explicit readiness, Advisor accept/return, and controlled manual DATEV handoff. It does not need broad federated state, autonomous agents, or live DATEV write access.

The main later-horizon bets are complete change briefs, whole-day explained ranking, integrated decision packets, continuous cross-system monitoring, and bounded agents that survive retries and interruptions. They must still be validated before anyone claims they work reliably or drive market success. TA-gated opportunity signals are a separate shadow bet under H014.

## Best-in-class market map

This map benchmarks the **later whole-book horizon**. It does not make any listed product a first-wedge dependency or prove controlled DATEV handoff.

Among the products reviewed, none covers the whole Advisor day with German tax depth, independent outcome proof, and broadly available agentic behavior. The benchmark therefore uses strongest reviewed components plus an explicitly immature agentic ceiling.

| Market role | Strongest reviewed reference | Documented bar | Important limit |
| --- | --- | --- | --- |
| German tax and practice system backbone | DATEV Arbeitsplatz + Eigenorganisation comfort + Aufgaben + Post/Fristen/Bescheide + DMS + ProCheck | Domain depth, client/order structure, source links, deadlines, roles, checklists, four-eyes control, economics, and integration into German tax production | Broad but list- and module-led; no public proof of a single Advisor decision layer |
| German cross-mandate workflow and collaboration | milia.io | Matters combining tasks, deadlines, owners, next steps, messages, documents, approvals, workflows, and activity history with DATEV fit | AI agents are roadmap; independent outcome proof is thin |
| Global daily-work coordination and interruption recovery | Karbon core | Triage, My Week, recurring work, automation, client requests, reminders, shared context, summaries, and assignment support | No listed DATEV integration; global accounting fit does not prove German tax fit |
| German grounded tax knowledge and change signal | Taxy.io Answers, TaxFeed, and BFH Updates | Named German sources, full-text links, and a pattern for turning regulatory change into affected-client work | Client matching and quality claims are not independently proven; not a command center alone |
| Portfolio anomaly and advisory insight | Intuit Accountant Suite | Cross-client work hub, alerts, workflow, KPIs, anomalies, root-cause views, and source links | US market and data model; some advanced behavior has limited availability |
| Evidence-backed tax work preparation | Thomson Reuters CoCounsel Tax | Cited research, document interrogation, inconsistency detection, scenarios, and cited deliverables | Not German and not the full daily practice operating layer |
| Agentic command behavior ceiling | Karbon Kai + AI Agents | Briefing across changed work, natural-language firm queries, prioritization, continuous monitoring claims, and approve/edit/reject gates | Limited or early access, no DATEV/German grounding, no independent full-job proof |

The scan suggests whitespace at the combination of German domain depth, a current cross-client operating model, grounded decision preparation, transparent prioritization, and bounded action under Advisor control. Buyer demand and integration feasibility remain open.

### Public-evidence fit scan

This score compares the reviewed **whole-practice platforms**, not specialist research tools. `0` means no relevant public evidence found, `1` partial or adjacent evidence, and `2` strong public documentation for the criterion. It scores documented fit, not usability, reliability, adoption, ROI, or product quality.

| Platform | German domain fit | Full-day job coverage | Cross-client state | Workflow and human control | Intelligence and preparation | Evidence maturity | Total / 12 |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| milia.io | 2 | 2 | 2 | 2 | 1 | 1 | 10 |
| Mature DATEV stack | 2 | 2 | 1 | 2 | 0 | 2 | 9 |
| Karbon core + Kai | 0 | 2 | 2 | 2 | 1 | 1 | 8 |
| Intuit Accountant Suite | 0 | 2 | 2 | 1 | 2 | 1 | 8 |
| ADDISON | 2 | 2 | 1 | 1 | 0 | 1 | 7 |
| Agenda / Simba | 2 | 1 | 1 | 1 | 0 | 1 | 6 |

The score makes milia the closest **documented modern German reference**, not the proven best product. DATEV remains the harder parity bar for German execution depth and control. Karbon supplies the strongest reviewed daily-work pattern but lacks German grounding.

## Strongest conventional alternative

- Horizon: later whole-book working machine. This comparator does not expand the first-wedge contract.
- Product or process: Confirmed under ADV-MORNING-001-SOTA-D010: the mature DATEV desktop stack centered on DATEV Arbeitsplatz, Eigenorganisation comfort, DATEV Aufgaben, Post, Fristen und Bescheide, DATEV DMS, and DATEV ProCheck. Do not use the newer DATEV Kanzleimanagement cloud product alone as the current bar.
- Why it is the relevant comparator: It is the deepest documented German same-cohort stack and covers the real control objects: tasks, client orders, deadlines, inbound, notices, documents, processes, staffing, capacity, rights, and economics. Independent but dated market evidence supports its maturity.
- Demonstrated behavior versus vendor claim: Current commercial documentation describes central task aggregation, structured orders, linked source items, filters, reminders, deadlines, rights, handoffs, checklists, archived process steps, and four-eyes controls. Early detection of idle time, cost overruns, and contribution-margin changes is a vendor claim, not independently proven performance.
- Strengths to preserve: Broad job coverage; client/year/order structure; deep tax-tool links; explicit dates, status, owners, capacity, and economics; source links; configurable rights; reassignment; checklists; four-eyes control; recorded completion.
- Weaknesses or gaps: The public material reviewed did not establish one cross-module, Advisor-specific decision layer, an explained “needs my judgment now” order, or one packet combining readiness, blockers, unknowns, evidence, and the required decision. This is an evidence gap, not proof that private or newly released capability is absent.
- Maturity and availability: Current commercial documentation plus dated 2019 independent market evidence support a mature installed position. They do not prove 2026 user outcomes. Setup and practice-specific implementation effort appear material from vendor material and need field validation.
- Alternatives considered: ADDISON is the closest broad-suite rival but public proof is shallower. Agenda is a strong lean challenger for smaller practices. Simba provides broad features but no proven ranked command view. The newer DATEV cloud board is promising but incomplete for this job.

## Strongest credible AI-native or agentic frontier

- Horizon: later whole-book working machine. These references do not prove first-wedge product support, authority, or a DATEV integration route.
- Product, process, or research system: Confirmed under ADV-MORNING-001-SOTA-D011: a clearly labeled two-part frontier. **milia.io + Taxy.io Answers** is the feasible German same-job floor. **Karbon Kai + AI Agents** is the adjacent agentic behavior ceiling. No single product currently proves both.
- Why it is credible and relevant: milia commercially documents a German/DATEV cross-mandate operating spine, controlled workflows, approvals, history, and source-linked tax research. Karbon describes the closest reviewed all-day re-orientation and agent-control behavior, but lacks German/DATEV fit and remains early access.
- Demonstrated behavior versus vendor claim: milia's practice view, workflows, activity history, approvals, and assistive AI are marketed as commercial features; its multi-step agents are roadmap. Karbon's summaries and drafting are GA; Kai's full briefing, prioritization, and agent behaviors are early-access vendor claims.
- Agentic loop, if present: Karbon claims continuous monitoring → detect bottleneck or change → prepare or invoke work → human approve, edit, or reject → record activity. Treat this as an early-access interaction hypothesis, not broad production proof. milia commercially documents deterministic triggered workflows plus AI assistance; its multi-step agent loop is roadmap.
- Differentiating behavior: Explain what changed since the last visit; synthesize live firm state; rank work by consequence; prepare source-linked decision packets; follow processes; act only inside explicit gates; let the Advisor edit, reject, defer, or redirect; keep an activity record.
- New risks and human-control needs: Ranking opacity, automation bias, hidden omissions, stale state, weak evidence, confidentiality breaches, unsafe client messages, and authority confusion. Priority reasons, source links, unknowns, approved data paths, human gates, documentation, monitoring, and recovery require validation against BStBK guidance and the open legal/privacy review.
- Feasible now as separate building blocks: Cross-client work views; filters and rule-based priority; deterministic workflows; drafting, summarizing, document analysis, source-linked German research; approval controls; roles; and history are commercially documented across separate products. Their reliable integration into one German product is unproven.
- Unproven, unavailable, unsafe, or irrelevant: Reliable AI reprioritization across an entire day; combined tax/client/urgency/value/capacity ranking; complete evidence and unknown packets; end-to-end agent execution across DATEV; autonomous client communication, filing, payment, signing, or sales; generic chat as the main desk.
- Alternatives considered: Taxy.io alone is research, not a command center. Intuit Accountant Suite is a strong US adjacent pattern but wrong tax system. CoCounsel Tax is US research and deliverable preparation. DATEV alone is the conventional spine, not the AI-native frontier. Karbon alone is too early and non-German.

## Comparison

| Dimension | As-is | Conventional alternative | AI-native frontier | Evidence IDs | Confidence |
| --- | --- | --- | --- | --- | --- |
| Job coverage | Mature specialist workflows, but the daily loop is spread across tools, channels, and handoffs | Broad coverage across tasks, orders, deadlines, inbound, documents, processes, people, capacity, rights, and economics | milia covers the German operational spine; Karbon describes broader briefing and agent behavior | ADV-MORNING-001-SOTA-E007 through E024 | medium |
| Outcome quality | No five-day baseline | No independent same-job outcome evidence found | No independent full-job outcome evidence; vendor and early-access claims dominate | ADV-MORNING-001-SOTA-D003, E016, E018 through E024 | low |
| Traceability | Strong inside specialist systems; cross-lifecycle strength is unobserved | Linked source objects, process steps, checklists, status, and archives | milia commercially documents matter history and approvals; full agent auditability is an early-access Karbon claim | ADV-MORNING-001-SOTA-E009, E010, E013 through E015, E019, E022 | medium |
| Exception handling | Deadlines, alerts, notices, tasks, and four-eyes checks exist, but cross-channel exceptions still require human joining | Filters, reminders, deadline alerts, status, reassignment, and four-eyes workflows | Live operational filters and workflows in milia; claimed continuous detection and prioritization in Karbon | ADV-MORNING-001-SOTA-E009, E010, E013 through E015, E018, E019, E022 | medium |
| Human authority and control | BStBK role and AI guidance keep professional responsibility with the Advisor | Fine-grained task rights, responsibility, handoff, and four-eyes control | milia commercially documents approvals; Karbon claims approve/edit/reject gates around early-access agent output | ADV-MORNING-001-SOTA-E008, E009, E013, E015, E019, E022, E036 | medium-high |
| Integration and effort | Work spans many tools and intake channels with uneven connectivity | Deep DATEV application integration with material configuration and onboarding effort | milia has German/DATEV fit; Karbon lacks listed DATEV integration | ADV-MORNING-001-SOTA-E007, E010, E012 through E015, E018, E020, E024 | medium |
| Safety and failure recovery | Official workflows use Advisor release; BStBK requires responsibility, secrecy, approved tools, documentation, and monitoring | Alerts, reassignment, source links, recorded steps, and four-eyes checks | Commercial approval/history patterns exist; autonomous prioritization and action safety are unproven | ADV-MORNING-001-SOTA-E009, E010, E013, E015, E019, E022, E036 | medium-high |
| Maturity and feasibility | Mature professional process with no direct five-day digital-workflow baseline | Mature installed suite; market proof is dated; user-outcome proof missing | milia operating spine is commercial; its agents are roadmap; Karbon Kai/agents are early access | ADV-MORNING-001-SOTA-E007 through E012, E016, E018 through E024 | medium |

## Parity and differentiation bars

The table below is for the **later whole-book horizon**. First-wedge acceptance is D013–D014: a review-ready package, Advisor accept/return, and controlled DATEV handoff. It is not feature parity with DATEV.

| Dimension | Conventional parity bar | Frontier opportunity | Evidence IDs | How a future solution could prove it |
| --- | --- | --- | --- | --- |
| Re-orientation throughout the day | From one entry point, find current tasks and client orders using status, owner, date, client, work type, filters, grouping, and sorting | Explain what changed since the last visit and why it matters | ADV-MORNING-001-SOTA-E013, E014, D012 | Timed first-action and return-to-desk study with real Advisors |
| Work coverage | Cover live tasks, orders, deadlines, inbound, notices, linked documents, process steps, staffing, and relevant economics without losing the source-module detail | Fold these signals into one current, role-specific intervention set | ADV-MORNING-001-SOTA-E010, E013 through E015, D012 | Coverage replay against known work items plus five-day shadow comparison |
| Priority and exception control | Support explicit dates, statuses, reminders, alerts, filters, reassignment, and four-eyes control | Evidence-linked, role-aware ranking with visible reasons and safe Advisor override | ADV-MORNING-001-SOTA-E010, E013, E015, D012 | Compare system order with Advisor order; measure misses and overrides |
| Actionability | Open the linked source, assign or reassign work, update status, and progress a controlled process | Resolve, delegate, defer, accept, or return from the same decision packet | ADV-MORNING-001-SOTA-E013 through E015 | Task completion, context-switch count, and stale-state checks |
| Trust and control | Preserve source links, rights, responsibilities, process records, and four-eyes checks | Show evidence, unknowns, authority, and safe fallback next to the decision | ADV-MORNING-001-SOTA-E002, E010, E013, E015 | False-clear, missed-item, unauthorized-action, and recovery tests |
| Agent assistance | No conventional agent bar; preserve deterministic workflows and human control | Prepare a decision packet, draft bounded work, and wait at the named human gate | ADV-MORNING-001-SOTA-E019 through E023 | Replay and shadow tests for omission, correction, approval, rejection, retry, and audit history |

- Strengths that must not be lost: German tax-job coverage, source links, dates, status, ownership, rights, reassignment, checklists, four-eyes control, documented work history, and retained professional responsibility.
- Product shapes not supported as the full answer by current evidence: a feature-for-feature DATEV replacement, a KPI-only dashboard, isolated tax chat, or autonomous external action. These remain hypotheses until buyer, workflow, and safety research closes.
- Frontier ideas requiring later validation: Personalized consequence-based ranking, change-since-last-visit brief, agent-prepared decision packets, continuous bottleneck detection, batching similar judgments, and a provable “desk clear” state.

## Validation and contradictions

| Check | Result | Evidence or link |
| --- | --- | --- |
| Same job and cohort compared | pass with limitations | ADV-MORNING-001-SOTA-D002, D010, D011, and D013. Direct five-day target-cohort observation is still missing. |
| Facts separated from claims | pass with limitations | The register and maturity vocabulary separate independent evidence, official process evidence, commercial documentation, limited access, roadmap, vendor claims, and hypotheses; product quality remains largely unobserved |
| Primary sources preferred | pass | BStBK, German law, Bundeskartellamt, current operating documentation, release notes, and explicit product-status pages were preferred; community and case-study evidence is marked limited |
| Parity bar is testable | pass with limitations | ADV-MORNING-001-SOTA-D012 and the parity table above. Baseline values and targets still require direct observation. |
| Current build excluded from SOTA bar | pass | ADV-MORNING-001-SOTA-D004; E001 and E003–E006 are superseded tombstones only |
| Later SOTA separated from the first product | pass | ADV-MORNING-001-SOTA-D013 and H015; the working-machine standard is a later horizon, not a UI or roadmap commitment |
| Historical client-value-core claim retired | pass | ADV-MORNING-001-SOTA-D006 superseded by D015 |
| Historical single-home-base claim retired | pass | ADV-MORNING-001-SOTA-D007 superseded by D013 |
| Bounded-action market bar confirmed | pass | ADV-MORNING-001-SOTA-D008; ADV-MORNING-001-SOTA-O010 superseded |
| First wedge separated from later whole-book SOTA | pass | ADV-MORNING-001-SOTA-D013; D001, D005, and D007 are superseded historical single-horizon decisions |
| DATEV authority, custody, and phased handoff made explicit | pass with limitations | ADV-MORNING-001-SOTA-D014; exact handoff action and sanctioned interface remain open |
| Opportunity detection kept separate and TA-gated | pass | ADV-MORNING-001-SOTA-D015 and H014; it is not parity or a market fact |
| GFR.ai and Klardaten limited to dependency signals | pass | ADV-MORNING-001-SOTA-D016; E041–E042 remain vendor evidence only |
| Product archetype, integrated loop, and later working-machine standard proven | open | H005, H006, H015, O008, and O009 require workflow, integration, adoption, buyer, and ROI evidence |
| Direct target-cohort workflow observed | open | ADV-MORNING-001-SOTA-O006 |

- Contradictions found: The initial morning-triage boundary was too narrow. The later full-day command-center framing was then too broad as a first-product claim. D013 resolves this with two horizons. The initial internal-build lens is superseded by the blank-sheet market lens. DATEV's mature desktop stack is the later conventional bar; its newer cloud command layer still describes key objects as future scope. milia has German fit but marks multi-step agents as roadmap; Karbon has the closest reviewed agentic concept but lacks German/DATEV fit and broad availability.
- Remaining open questions: ADV-MORNING-001-SOTA-O006 through ADV-MORNING-001-SOTA-O009 and O014 through O016. O003 through O005 and O010 through O013 are superseded or resolved.

## Project constraints applied after the market benchmark

The Tax Advisor Platform overlay still applies to any future Taxfix product: tenant boundaries, source-linked outputs, untrusted uploaded evidence until human acceptance, visible blocked states, and no automatic client outreach, filing, payment, sale, or other irreversible action.

Those are project constraints. They do not prove the market SOTA, select the product archetype, or validate the proposed operating loop.

## Limited DATEV and vendor-dependency note — 2026-07-17

This is not a first-wedge product comparison or proof of an integration route. E041–E053 are retained for traceability. GFR.ai and Klardaten are vendor-dependency signals only under D016. DATEV access, authority, data custody, handoff, and actual connector behavior remain Taxfix-specific open work under D014 and O014–O016.

### Retained integration and vendor evidence

| ID | Type | Status | Claim | Source | Quality |
| --- | --- | --- | --- | --- | --- |
| ADV-MORNING-001-SOTA-E041 | fact | superseded | Historical vendor claim: GFR.ai markets preparatory bookkeeping, accountant approval, and DATEV export. Superseded as active product evidence by D016: it is a limited vendor-dependency signal, not proof of Taxfix support, authority, custody, reliability, or outcome. | [gfr.ai](https://gfr.ai/); [NorthData](https://www.northdata.com/GFR+Software+GmbH,+Berlin/Amtsgericht+Charlottenburg+(Berlin)+HRB+252724+B) | vendor-claim + official-process |
| ADV-MORNING-001-SOTA-E042 | fact | superseded | Historical vendor claim: Klardaten markets a DATEVconnect Gateway and related services. Superseded as active product evidence by D016: it is a limited vendor-dependency signal, not proof of Taxfix support, authority, custody, reliability, or outcome. | [klardaten.com](https://klardaten.com/en/products/datevconnect-gateway); [tax&bytes](https://www.taxandbytes.de/360/klardaten-geht-mit-ki-gestuetzter-datev-api-an-den-start) | vendor-claim + secondary |
| ADV-MORNING-001-SOTA-E043 | fact | active | DATEV AGB ("Besondere Bedingungen für Software und DATEV-Cloud-Lösungen", Fassung 01.01.2025) clause **2.6**: products may be operated only by natural persons; automated access or interface connection for automated data exchange is permitted **only after prior consent by DATEV**. | [DATEV AGB 2025 (PDF)](https://www.datev.de/content/dam/markenassets/unternehmenskommunikation/agb/AGB%202025.pdf) | primary |
| ADV-MORNING-001-SOTA-E044 | fact | active | DATEV API auth is OAuth2/OIDC anchored to a human DATEV login; the live discovery doc advertises only interactive response types and **no `client_credentials` grant** → no anonymous service account; production access is partner-gated behind certification + interface-agreement review (reported ~4–12 weeks). | [login.datev.de OIDC config](https://login.datev.de/openid/.well-known/openid-configuration); [Apideck](https://www.apideck.com/blog/datev-api-integration-guide) | primary + vendor-claim |
| ADV-MORNING-001-SOTA-E045 | fact | active | Two non-interchangeable DATEV integration surfaces: (a) **cloud REST APIs** — `accounting:documents` (push receipts to Belege online) + four Rechnungswesen webservices (bidirectional posting/journal export), SaaS-friendly, consent-anchored; (b) **on-prem DATEVconnect** — powerful read/write but requires local DATEV install, which is exactly what Klardaten brokers to the cloud. | [DATEV Developer Portal](https://developer.datev.de/en/product-detail/accounting-documents/2.0/overview); [initOS](https://www.initos.com/blog/datev-datenuebertragung-mit-einem-erp-system/) | official-process + secondary |
| ADV-MORNING-001-SOTA-E046 | fact | superseded | Historical technical interpretation of DATEV authentication constraints. Superseded by D014: Taxfix will not assume unattended access; the exact sanctioned route remains open and must be approved before use. | [DATEV SmartLogin](https://www.datev.de/web/de/shop/produkt-details/datev-smartlogin-60101); [DATEV-Benutzer](https://www.datev.de/web/de/berufsgruppenuebergreifend/mydatev/cloud-sicherheit/anmeldeverfahren-bei-datev/datev-benutzer) | official-process |
| ADV-MORNING-001-SOTA-E047 | fact | active | German e-invoicing: **receive** structured B2B e-invoices mandatory since **1 Jan 2025** (no threshold/exemption); **issue** staged — from 1 Jan 2027 for issuers with prior-year turnover > €800k, from 1 Jan 2028 for all domestic B2B; a plain PDF is **not** a valid e-invoice; only XRechnung and ZUGFeRD ≥ 2.0.1 qualify (not MINIMUM/BASIC-WL). | [BMF e-invoice FAQ](https://www.bundesfinanzministerium.de/Content/DE/FAQ/e-rechnung.html) | official-process |
| ADV-MORNING-001-SOTA-E048 | fact | active | GoBD (BMF Schreiben 14 Jul 2025): the structured **XML** part of an e-invoice must be archived unchangeably and remain machine-evaluable for the retention period (no format-conversion deletion). Retention for invoices/booking receipts shortened **10 → 8 years** (BEG IV, eff. 2025), but **reversed for financial-sector firms** — retention defaults must be segment-aware. | [BMF GoBD 2025 (PDF)](https://www.bundesfinanzministerium.de/Content/DE/Downloads/BMF_Schreiben/Weitere_Steuerthemen/Abgabenordnung/2025-07-14-GoBD-2-aenderung.pdf); [Haufe](https://www.haufe.de/finance/buchfuehrung-kontierung/buerokratieentlastungsgesetz-aufbewahrungspflichten-verkuerzt_186_634670.html) | official-process + secondary |
| ADV-MORNING-001-SOTA-E049 | fact | active | DATEV's own KI-Automatisierungsservice Rechnungen ran across 100,000+ Buchführungen at ~7,000 firms, generating **7.5M+ booking suggestions/month** (milestone Aug 2025), but strictly as a **suggestion engine where the human decides** — not autonomous filing. | [DATEV press, 17 Sep 2025](https://www.datev.de/web/de/berufsgruppenuebergreifend/presse/presseinformationen/meldungen-2025/ki-reduziert-manuellen-aufwand-beim-buchen) | vendor-claim |
| ADV-MORNING-001-SOTA-E050 | fact | active | DATEV Copilot (GA in MyDATEV **May 2026**) is text/document-only (draft/translate/summarize up to 1,000 pages), **cannot analyze structured accounting data**, and keeps professional judgment with the human. | [DATEV Copilot page](https://www.datev.de/web/de/berufsgruppenuebergreifend/nachrichten/themen-im-fokus/ki-intelligent-nutzen/datev-copilot-das-kann-der-ki-assistent-heute) | vendor-claim |
| ADV-MORNING-001-SOTA-E051 | fact | active | milia.AI claims AI trained on DATEV formats analyzing DATEV reports/Jahresabschlüsse/BWAs under strict human-in-the-loop ("no AI content sent to clients without approval"); fully autonomous end-to-end agents are labelled "coming soon" — not shipped. Extends prior E020 with a dated 2026 read. | [milia.io/milia-ai](https://milia.io/milia-ai) | vendor-claim |
| ADV-MORNING-001-SOTA-E052 | fact | active | Karbon launched "Kai" (AI coworker) **3 Jun 2026, early access** — assistive/flagging, human oversight retained (flag-not-file). Karbon "State of AI in Accounting 2026" (n≈600): **98% of firms use AI**, ~21h/month saved, but only **21% have an AI policy**. Extends prior E022–E023. | [Karbon Kai (GlobeNewswire)](https://www.globenewswire.com/news-release/2026/06/03/3306285/0/en/Karbon-Launches-Kai-the-AI-Coworker-That-Knows-Your-Firm.html); [State of AI 2026](https://karbonhq.com/resources/state-of-ai-accounting-2026/) | vendor-claim |
| ADV-MORNING-001-SOTA-E053 | fact | superseded | Historical adjacent computer-use evidence. Superseded as a decision input by D014: first-wedge DATEV handoff is manual and controlled; any later interface requires a sanctioned route. | [OSWorld leaderboard](https://leaderboard.steel.dev/leaderboards/osworld/) | community |

### Historical hypotheses

| ID | Type | Status | Claim | Basis |
| --- | --- | --- | --- | --- |
| ADV-MORNING-001-SOTA-H009 | hypothesis | superseded | Historical claim that DATEV access is the single binding automation constraint. Superseded by D014: authority, custody, approved route, reconciliation, and human control are joint gates. | E043–E046 |
| ADV-MORNING-001-SOTA-H010 | hypothesis | superseded | Historical broad-market convergence claim. Superseded by D008 and D013: retain bounded human-gated work as a product rule without claiming market convergence. | E049–E052 |
| ADV-MORNING-001-SOTA-H011 | hypothesis | superseded | Historical differentiation claim. Superseded by D014 and D016: neither a vendor connector nor a model proves the required authority, custody, reliability, or outcome. | E049–E052 |
| ADV-MORNING-001-SOTA-H012 | hypothesis | superseded | Historical category-timing claim. Superseded as irrelevant to the first-wedge decision. | E041–E046, E051–E052 |

### Integration open questions

| ID | Type | Status | Question | Basis |
| --- | --- | --- | --- | --- |
| ADV-MORNING-001-SOTA-O011 | open question | superseded | Historical question about an automated DATEV route. Superseded by O016 because the first decision is now the exact controlled handoff after manual validation. | E043–E045 |
| ADV-MORNING-001-SOTA-O012 | open question | superseded | Historical question about named vendors' consent. Superseded as a first-wedge prerequisite by D016: Taxfix does not infer its own authority from a vendor's claimed route. | E042–E043 |
| ADV-MORNING-001-SOTA-O013 | open question | superseded | Historical request for vendor efficacy and unrelated connector review. Superseded as non-decisive for the first-wedge scope; independent reliability evidence remains generally absent. | E041, E049–E052 |
| ADV-MORNING-001-SOTA-O016 | open question | active | Which sanctioned DATEV route, if any, can satisfy D014 for the chosen first handoff after manual validation? | E043–E045; D014 |

### Current interpretation

- D008 still holds: bounded, human-gated work is the relevant product rule.
- D014 now controls the DATEV route: manual first; sanctioned API or connector only after explicit authority, custody, source, reconciliation, and human-control checks.
- GFR.ai and Klardaten do not move into the product frontier. They remain limited vendor-dependency signals under D016.

## Decision and handoff

- Confirmed active decisions: ADV-MORNING-001-SOTA-D002 through D004, D008 through D016. D001, D005 through D007 are superseded historical single-horizon decisions.
- Assumptions and hypotheses: H015 is the later operating-loop and working-machine hypothesis. H013 is the first-wedge manual-handoff hypothesis; H014 is the TA-gated opportunity-shadow hypothesis. None proves a product outcome.
- Blockers to market proof: Direct five-day observation, external legal/privacy analysis, the exact DATEV handoff action, sanctioned interface feasibility, buyer demand, adoption cost, and ROI evidence are absent. These do not block completion of the benchmark document.
- Recommended implication for later work: Prove the first wedge with a manual, controlled DATEV handoff before treating live integration or the working-machine archetype as proven.
- Inputs for later work: This completed benchmark, [reader-facing synthesis](sota_advisor_desk.md), transcript, primary market sources, and any supplied Advisor workflow evidence. Do not use the current Advisor Desk build or IA as the product bar.
- Output links: [this artifact](sota_benchmark.md) | [reader-facing synthesis](sota_advisor_desk.md) | [transcript](sota_benchmark_agent_transcript.md) | canonical brief Open
- Recommended next conversation: No next product lens is selected. If the SOTA work continues, gather the missing workflow and feasibility evidence.
