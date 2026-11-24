# NIST CSF 2.0 – Detect (DE)

**NIST definition:** Possible cybersecurity attacks and compromises are found and analyzed.

Detect sits between Protect and Respond. It assumes protective controls will sometimes fail, and finds out when they have.

## Categories and subcategories
Subcategory wording is paraphrased. Gaps in numbering are intentional: they mark CSF 1.1 items that were moved elsewhere in 2.0.

### DE.CM – Continuous Monitoring
| ID | Outcome |
|---|---|
| DE.CM-01 | Networks and network services are monitored |
| DE.CM-02 | The physical environment is monitored |
| DE.CM-03 | Personnel activity and technology usage are monitored |
| DE.CM-06 | External service provider activities and services are monitored |
| DE.CM-09 | Hardware, software, runtime environments and their data are monitored |

### DE.AE – Adverse Event Analysis
| ID | Outcome |
|---|---|
| DE.AE-02 | Potentially adverse events are analyzed to better understand associated activities |
| DE.AE-03 | Information is correlated from multiple sources |
| DE.AE-04 | The estimated impact and scope of adverse events are understood |
| DE.AE-06 | Information on adverse events is provided to authorized staff and tools |
| DE.AE-07 | Cyber threat intelligence and other context are integrated into the analysis |
| DE.AE-08 | Incidents are declared when adverse events meet the defined incident criteria |

**DE.AE-08 is the handoff point.** Once an incident is declared, the work moves to Respond.

## What changed from CSF 1.1
- 1.1 had three categories: Anomalies and Events (DE.AE), Security Continuous Monitoring (DE.CM), Detection Processes (DE.DP).
- In 2.0, DE.DP was split up and its subcategories moved to Govern, Identify and Detect. Process items such as roles and continuous improvement now sit in Govern and in Identify → Improvement (ID.IM).

## Dependencies on other Functions
- **Identify → Detect:** You can't monitor assets you don't know you have. A weak asset inventory (ID.AM) means gaps in monitoring.
- **Govern → Detect:** Govern sets ownership and risk tolerance, which decide which alerts matter.
- **Protect → Detect:** Detection checks whether protective controls are working.
- **Detect → Respond:** The handoff happens at DE.AE-08. Without written incident criteria, the declaration becomes a judgement call.

## Audit angle
Common findings:
1. **Logs collected but never reviewed.** Retention settings exist, but there's no evidence of triage.
2. **Monitoring doesn't cover the asset inventory.** Systems sending logs don't match the asset register, with cloud and shadow IT usually missing.
3. **Third parties not monitored (DE.CM-06).** SaaS and MSP activity isn't visible.
4. **No defined incident criteria (DE.AE-08).**
5. **No correlation (DE.AE-03).** Tools alert in isolation and nobody joins them up.

Evidence to request:
- Logging and monitoring standard
- SIEM use-case register
- Alert triage SLAs and a sample of closed alerts
- Incident classification matrix
- Evidence that threat intelligence feeds are actually used
- A sample of closed false positives with triage notes. This proves that reviews operate routinely and not only during the adversaries. 

## Sources
- [NIST CSF 2.0 (CSWP 29)](https://doi.org/10.6028/NIST.CSWP.29)
- [NIST CSF FAQs – changes from 1.1 to 2.0](https://www.nist.gov/faqs)
