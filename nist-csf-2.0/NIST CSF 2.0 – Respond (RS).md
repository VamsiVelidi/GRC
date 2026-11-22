# NIST CSF 2.0 – Respond (RS)

**NIST definition:** Actions regarding a detected cybersecurity incident are taken.

Respond starts when Detect declares an incident (DE.AE-08) and ends when the recovery criteria are met (RS.MA-05) and Recover takes over.

## Categories and subcategories
Subcategory wording is paraphrased. Gaps in numbering are intentional: they mark CSF 1.1 items that were moved elsewhere in 2.0.

### RS.MA – Incident Management
| ID | Outcome |
|---|---|
| RS.MA-01 | The incident response plan is executed, in coordination with relevant third parties, once an incident is declared |
| RS.MA-02 | Incident reports are triaged and validated |
| RS.MA-03 | Incidents are categorized and prioritized |
| RS.MA-04 | Incidents are escalated or elevated as needed |
| RS.MA-05 | The criteria for initiating incident recovery are applied |

### RS.AN – Incident Analysis
| ID | Outcome |
|---|---|
| RS.AN-03 | Analysis establishes what took place during the incident and its root cause |
| RS.AN-06 | Investigation actions are recorded; record integrity and provenance are preserved |
| RS.AN-07 | Incident data and metadata are collected; integrity and provenance are preserved |
| RS.AN-08 | The incident's magnitude is estimated and validated |

### RS.CO – Incident Response Reporting and Communication
| ID | Outcome |
|---|---|
| RS.CO-02 | Internal and external stakeholders are notified of incidents |
| RS.CO-03 | Information is shared with designated internal and external stakeholders |

### RS.MI – Incident Mitigation
| ID | Outcome |
|---|---|
| RS.MI-01 | Incidents are contained |
| RS.MI-02 | Incidents are eradicated |

## RS.AN-08: how magnitude is validated
NIST doesn't set fixed parameters. Its implementation examples describe validating against **evidence**: review other potential targets for indicators of compromise and evidence of persistence, using manual review or automated tools.

Dimensions usually covered by an organization's severity matrix:
- **Breadth:** hosts, accounts, sites and business units affected
- **Depth:** privilege level reached, persistence
- **Data:** records, classification, personal information
- **Business impact:** critical services affected, downtime, cost
- **Duration:** dwell time before detection
- **External reach:** customers, third parties, regulatory thresholds

SP 800-61 Rev. 2 (now superseded) rated impact on three scales: functional impact, information impact and recoverability. Many severity matrices are still built on them.

The validated magnitude feeds prioritization (RS.MA-03), escalation (RS.MA-04), notification (RS.CO-02) and the recovery decision (RS.MA-05).

## What changed from CSF 1.1
- Response Planning (RS.RP) moved into the new, broader Incident Management category (RS.MA).
- Improvements (RS.IM) moved to Identify → Improvement (ID.IM). **Lessons learned is no longer part of Respond.**
- There is no "Prepare" step in Respond. Preparation sits in Govern, Identify and Protect (e.g. IR training under PR.AT).

## Dependencies on other Functions
- **Govern → Respond:** Govern decides who has authority to declare an incident, isolate production systems or approve major decisions. Without it, decisions stall waiting for approval.
- **Identify → Respond:** The asset inventory and business impact analysis drive prioritization (RS.MA-03). ID.IM takes in the lessons learned.
- **Protect → Respond:** IR training, tested backups and the IR plan as policy all come from Protect.
- **Detect → Respond:** The handoff happens at DE.AE-08.
- **Respond → Recover:** RS.MA-05 is the exit point. Without recovery criteria, teams may restore systems before eradication is complete and get reinfected.

## Audit angle
Common findings:
1. **IR plan never tested.** No tabletop or simulation in the last 12 months.
2. **No severity matrix (RS.MA-03),** or one that isn't applied consistently.
3. **Out-of-date escalation contacts (RS.MA-04).** The call tree lists staff who have left.
4. **Third parties missing from the plan (RS.MA-01).** MSPs, cloud providers, the cyber insurer and IR retainer aren't named.
5. **Evidence handling not defined (RS.AN-06/07).** No chain-of-custody procedure.
6. **Regulatory notification not mapped (RS.CO-02).** No documented path to applicable obligations, e.g. Australia's [Notifiable Data Breaches scheme](https://www.oaic.gov.au/privacy/notifiable-data-breaches).
7. **No root cause analysis (RS.AN-03).** Incidents closed as resolved with no cause recorded, then recurring.

Evidence to request:
- IR policy, plan and playbooks
- Severity matrix and RACI
- Tabletop reports with tracked actions
- A sample of incident tickets showing initial vs revised scope, with timestamped actions
- Regulatory notification register
- Forensic / chain-of-custody procedure
- IR retainer and cyber insurance contracts

## Worked example: ransomware
1. Incident declared, IR plan activated, insurer and IR retainer contacted (RS.MA-01).
2. Triage, then categorize as critical and escalate to executives (RS.MA-02 to -04).
3. Initial estimate of one file server. IOC sweep finds 14 hosts and two compromised service accounts (RS.AN-08).
4. Disk images and logs preserved with chain of custody (RS.AN-06/07).
5. Stakeholders and regulators notified as required (RS.CO-02/03).
6. Affected hosts isolated (RS.MI-01), ransomware and persistence removed, credentials reset (RS.MI-02).
7. Root cause found, e.g. an unpatched VPN appliance (RS.AN-03).
8. Recovery criteria met, so hand over to Recover for restore from backup (RS.MA-05).

## Sources
- [NIST CSF 2.0 (CSWP 29)](https://doi.org/10.6028/NIST.CSWP.29)
- [NIST CSF FAQs – changes from 1.1 to 2.0](https://www.nist.gov/faqs)
- [NIST SP 800-61 Rev. 3 (April 2025)](https://csrc.nist.gov/pubs/sp/800/61/r3/final)
