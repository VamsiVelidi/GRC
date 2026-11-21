# NIST Cybersecurity Framework (CSF) 2.0

Voluntary guidance from the US National Institute of Standards and Technology (NIST) for managing and reducing cybersecurity risk. It applies to organizations of any size, sector or country.

- **Current version:** CSF 2.0, published 26 February 2024 as [NIST CSWP 29](https://doi.org/10.6028/NIST.CSWP.29)
- **Previous versions:** 1.0 (2014), 1.1 (2018)
- **What it is not:** a certifiable standard or a control catalogue. CSF describes *outcomes*, not specific controls. For controls, map it to SP 800-53, ISO/IEC 27001 or CIS Controls through its Informative References.

## The three components

| Component | What it does |
|---|---|
| **Core** | The taxonomy of outcomes: 6 Functions → 22 Categories → 106 Subcategories |
| **Profiles** | A **Current Profile** (where you are) and a **Target Profile** (where you want to be). The gap between them becomes the action plan. **Community Profiles** are shared baselines for a sector or use case, e.g. SP 800-61r3 for incident response. |
| **Tiers** | How rigorous your risk governance and management are: Tier 1 Partial, Tier 2 Risk Informed, Tier 3 Repeatable, Tier 4 Adaptive. Tiers describe maturity of practice, not compliance. |

## The 6 Functions

| Function | NIST definition |
|---|---|
| **Govern (GV)** | The organization's cybersecurity risk management strategy, expectations, and policy are established, communicated, and monitored |
| **Identify (ID)** | The organization's current cybersecurity risks are understood |
| **Protect (PR)** | Safeguards to manage the organization's cybersecurity risks are used |
| **Detect (DE)** | Possible cybersecurity attacks and compromises are found and analyzed |
| **Respond (RS)** | Actions regarding a detected cybersecurity incident are taken |
| **Recover (RC)** | Assets and operations affected by a cybersecurity incident are restored |

Govern sits at the centre of the CSF wheel, because it shapes how the other five are carried out.

## The 22 Categories

| Function | ID | Category |
|---|---|---|
| Govern | GV.OC | Organizational Context |
| | GV.RM | Risk Management Strategy |
| | GV.RR | Roles, Responsibilities, and Authorities |
| | GV.PO | Policy |
| | GV.OV | Oversight |
| | GV.SC | Cybersecurity Supply Chain Risk Management |
| Identify | ID.AM | Asset Management |
| | ID.RA | Risk Assessment |
| | ID.IM | Improvement |
| Protect | PR.AA | Identity Management, Authentication, and Access Control |
| | PR.AT | Awareness and Training |
| | PR.DS | Data Security |
| | PR.PS | Platform Security |
| | PR.IR | Technology Infrastructure Resilience |
| Detect | DE.CM | Continuous Monitoring |
| | DE.AE | Adverse Event Analysis |
| Respond | RS.MA | Incident Management |
| | RS.AN | Incident Analysis |
| | RS.CO | Incident Response Reporting and Communication |
| | RS.MI | Incident Mitigation |
| Recover | RC.RP | Incident Recovery Plan Execution |
| | RC.CO | Incident Recovery Communication |

Subcategory numbers have gaps on purpose. A gap marks a CSF 1.1 item that was moved elsewhere in 2.0.

## Key changes from CSF 1.1

1. **New Govern Function.** Governance items formerly spread across Identify (ID.GV, ID.BE, ID.RM, ID.SC) now form their own Function.
2. **Broader scope.** It is no longer framed around US critical infrastructure. It now covers all organizations.
3. **Supply chain risk** gets its own Category (GV.SC).
4. **Improvement consolidated.** Lessons learned from Protect, Respond and Recover now sit in one place, ID.IM.
5. **Protect restructured.** It has new Categories PR.PS and PR.IR. PR.IP, PR.PT and PR.MA were split up and moved.
6. **Detect simplified.** DE.DP was split up across Govern, Identify and Detect.
7. **Respond restructured.** RS.RP became the broader RS.MA, and RS.IM moved to ID.IM.
8. **Core count.** It went from 5 Functions / 23 Categories / 108 Subcategories to 6 / 22 / 106.
9. **Online resources.** Implementation Examples, Quick-Start Guides and Informative References are published online so they can be updated more often than the Core.

## Notes in this folder

| # | Function | Note |
|---|---|---|
| 02 | Govern (GV) | Planned |
| 03 | Identify (ID) | Planned |
| 04 | Protect (PR) | Planned |
| | 05 | Detect (DE) | [Detect notes](nist-csf-2.0/NIST CSF 2.0 – Detect (DE)) | |
| 06 | Respond (RS) | [06-respond.md](06-respond.md) |
| 07 | Recover (RC) | Planned |
| 08 | CSF 2.0 vs ISO/IEC 27001 | Planned |

## Official sources
- [NIST CSF 2.0 (CSWP 29)](https://doi.org/10.6028/NIST.CSWP.29)
- [NIST CSF home](https://www.nist.gov/cyberframework)
- CSF 2.0 Reference Tool (linked from the NIST CSF home page): exact Core wording, exportable
- [NIST CSF FAQs – changes from 1.1 to 2.0](https://www.nist.gov/faqs)
