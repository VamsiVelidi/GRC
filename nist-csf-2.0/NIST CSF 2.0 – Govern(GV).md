# NIST CSF 2.0 – Govern (GV)

**NIST definition:** The organization's cybersecurity risk management strategy, expectations, and policy are established, communicated, and monitored.

Govern is new in CSF 2.0 doesn't secure anything directly. It decides who is accountable, how much risk is acceptable, what the rules are, and whether the programme is working. The other five Functions carry out what Govern sets.

In testing terms: Govern is the test strategy, the entry/exit criteria and the sign-off authority. Identify through Recover are the test execution. Without Govern, teams work hard against no agreed standard.

## Categories and subcategories
Wording below is NIST's Core text. Govern has **6 categories and 31 subcategories**, with no numbering gaps because the Function is new in 2.0.

The audit questions are practitioner interpretation, not NIST wording.

### GV.OC – Organizational Context
*The circumstances (mission, stakeholder expectations, dependencies, and legal, regulatory, and contractual requirements) surrounding the organization's cybersecurity risk management decisions are understood.*

| ID | Outcome | Audit question |
|---|---|---|
| GV.OC-01 | The organizational mission is understood and informs cybersecurity risk management | Can security priorities be traced back to the business strategy? |
| GV.OC-02 | Internal and external stakeholders are understood, and their needs and expectations regarding cybersecurity risk management are understood and considered | Is there a stakeholder list (board, regulators, customers, staff) with their expectations recorded? |
| GV.OC-03 | Legal, regulatory, and contractual requirements regarding cybersecurity, including privacy and civil liberties obligations, are understood and managed | Is there an obligations register with an owner and a review date for each item? |
| GV.OC-04 | Critical objectives, capabilities, and services that external stakeholders depend on or expect from the organization are understood and communicated | Are critical services identified, e.g. in a Business Impact Analysis (BIA)? |
| GV.OC-05 | Outcomes, capabilities, and services that the organization depends on are understood and communicated | Are upstream dependencies (cloud, key suppliers, utilities) documented? |

### GV.RM – Risk Management Strategy
*The organization's priorities, constraints, risk tolerance and appetite statements, and assumptions are established, communicated, and used to support operational risk decisions.*

| ID | Outcome | Audit question |
|---|---|---|
| GV.RM-01 | Risk management objectives are established and agreed to by organizational stakeholders | Are objectives documented and approved by the right forum? |
| GV.RM-02 | Risk appetite and risk tolerance statements are established, communicated, and maintained | Is the appetite board-approved, and are tolerances measurable (e.g. max downtime, patch timeframes)? |
| GV.RM-03 | Cybersecurity risk management activities and outcomes are included in enterprise risk management processes | Do cyber risks sit in the enterprise risk register on the same rating scale? |
| GV.RM-04 | Strategic direction that describes appropriate risk response options is established and communicated | Is it defined who can accept, mitigate, transfer or avoid a risk, and at what rating? |
| GV.RM-05 | Lines of communication across the organization are established for cybersecurity risks, including risks from suppliers and other third parties | Is there a defined escalation path for cyber and third-party risks? |
| GV.RM-06 | A standardized method for calculating, documenting, categorizing, and prioritizing cybersecurity risks is established and communicated | Is one risk methodology used consistently across teams? |
| GV.RM-07 | Strategic opportunities (i.e., positive risks) are characterized and are included in organizational cybersecurity risk discussions | Are opportunities (e.g. adopting AI or a new cloud service) assessed, not only threats? |

### GV.RR – Roles, Responsibilities, and Authorities
*Cybersecurity roles, responsibilities, and authorities to foster accountability, performance assessment, and continuous improvement are established and communicated.*

| ID | Outcome | Audit question |
|---|---|---|
| GV.RR-01 | Organizational leadership is responsible and accountable for cybersecurity risk and fosters a culture that is risk-aware, ethical, and continually improving | Do board or executive minutes show cyber risk being discussed and decided on? |
| GV.RR-02 | Roles, responsibilities, and authorities related to cybersecurity risk management are established, communicated, understood, and enforced | Is there a RACI, and does segregation of duties hold in practice? |
| GV.RR-03 | Adequate resources are allocated commensurate with the cybersecurity risk strategy, roles, responsibilities, and policies | Are budget and headcount linked to the strategy? |
| GV.RR-04 | Cybersecurity is included in human resources practices | Are screening, onboarding acknowledgement and offboarding access removal evidenced? |

### GV.PO – Policy
*Organizational cybersecurity policy is established, communicated, and enforced.*

| ID | Outcome | Audit question |
|---|---|---|
| GV.PO-01 | Policy for managing cybersecurity risks is established based on organizational context, cybersecurity strategy, and priorities and is communicated and enforced | Is the policy approved by senior management, version-controlled and acknowledged by staff? |
| GV.PO-02 | Policy for managing cybersecurity risks is reviewed, updated, communicated, and enforced to reflect changes in requirements, threats, technology, and organizational mission | Is there a review cycle (scheduled and event-triggered), and evidence of the last review? |

### GV.OV – Oversight
*Results of organization-wide cybersecurity risk management activities and performance are used to inform, improve, and adjust the risk management strategy.*

| ID | Outcome | Audit question |
|---|---|---|
| GV.OV-01 | Cybersecurity risk management strategy outcomes are reviewed to inform and adjust strategy and direction | Do management review minutes record decisions, not just updates? |
| GV.OV-02 | The cybersecurity risk management strategy is reviewed and adjusted to ensure coverage of organizational requirements and risks | Can strategy changes be traced to a review? |
| GV.OV-03 | Organizational cybersecurity risk management performance is evaluated and reviewed for adjustments needed | Are KPIs/KRIs and internal audit results reported and acted on? |

### GV.SC – Cybersecurity Supply Chain Risk Management
*Cyber supply chain risk management processes are identified, established, managed, monitored, and improved by organizational stakeholders.*

| ID | Outcome | Audit question |
|---|---|---|
| GV.SC-01 | A cybersecurity supply chain risk management program, strategy, objectives, policies, and processes are established and agreed to by organizational stakeholders | Is there an approved third-party risk management policy? |
| GV.SC-02 | Cybersecurity roles and responsibilities for suppliers, customers, and partners are established, communicated, and coordinated internally and externally | Is each supplier assigned an internal relationship owner? |
| GV.SC-03 | Cybersecurity supply chain risk management is integrated into cybersecurity and enterprise risk management, risk assessment, and improvement processes | Do supplier risks appear in the main risk register? |
| GV.SC-04 | Suppliers are known and prioritized by criticality | Is the supplier inventory complete and tiered by criticality? |
| GV.SC-05 | Requirements to address cybersecurity risks in supply chains are established, prioritized, and integrated into contracts and other types of agreements with suppliers and other relevant third parties | Do contracts include security clauses, breach notification and right to audit? |
| GV.SC-06 | Planning and due diligence are performed to reduce risks before entering into formal supplier or other third-party relationships | Is due diligence completed and signed off before the contract is signed? |
| GV.SC-07 | The risks posed by a supplier, their products and services, and other third parties are understood, recorded, prioritized, assessed, responded to, and monitored over the course of the relationship | Are critical suppliers reassessed periodically, not just at onboarding? |
| GV.SC-08 | Relevant suppliers and other third parties are included in incident planning, response, and recovery activities | Are key suppliers named in the IR plan and included in tabletops? |
| GV.SC-09 | Supply chain security practices are integrated into cybersecurity and enterprise risk management programs, and their performance is monitored throughout the technology product and service life cycle | Is supplier performance against security requirements monitored? |
| GV.SC-10 | Cybersecurity supply chain risk management plans include provisions for activities that occur after the conclusion of a partnership or service agreement | On exit, is access revoked and data returned or destroyed, with evidence? |

## What changed from CSF 1.1
- Govern is a **new Function**. In 1.1, governance outcomes were spread across Identify.
- Main sources: Business Environment (ID.BE) → GV.OC, Governance (ID.GV) → GV.PO / GV.RR / GV.OC-03, Risk Management Strategy (ID.RM) → GV.RM, Supply Chain Risk Management (ID.SC) → GV.SC.
- HR security (PR.IP-11 in 1.1) moved to GV.RR-04.
- **New ideas in 2.0:** an Oversight category (GV.OV) and positive risk / opportunities (GV.RM-07).
- Supply chain moved from one Identify category to a full Govern category with 10 subcategories, which shows how much weight NIST now puts on third-party risk.

## Dependencies on other Functions
- **Govern → Identify:** The risk method (GV.RM-06) is what ID.RA uses to rate risks. Supplier criticality (GV.SC-04) feeds the asset inventory (ID.AM).
- **Govern → Protect:** Policies (GV.PO) are implemented as Protect controls. HR practices (GV.RR-04) drive access removal (PR.AA) and training (PR.AT).
- **Govern → Detect:** Risk tolerance decides which alerts matter.
- **Govern → Respond:** Govern defines who has authority to declare an incident or isolate production systems (GV.RR-02). Key suppliers are part of incident response (GV.SC-08).
- **Govern → Recover:** Post-incident operating norms (RC.RP-04) are a risk decision made within the appetite Govern sets.
- **Identify → Govern:** Risk assessment results (ID.RA) and lessons learned (ID.IM) feed Oversight (GV.OV). This is the feedback loop.

## Audit angle
Common findings:
1. **Policy not approved at the right level (GV.PO-01).** Signed off by the IT manager instead of senior management or the board.
2. **Policy not reviewed (GV.PO-02).** Review dates passed, with no trigger-based reviews after major changes.
3. **Risk appetite not measurable (GV.RM-02).** "Low appetite for cyber risk" with no tolerances, so nothing can be tested against it.
4. **Cyber risk register separate from enterprise risk (GV.RM-03).** The board never sees cyber risk on the same scale as other risks.
5. **Risk acceptance without authority (GV.RM-04).** Risks accepted by IT staff, or acceptances with no expiry date.
6. **Incomplete supplier inventory (GV.SC-04).** Shadow SaaS is missing, and suppliers aren't tiered.
7. **Weak contracts (GV.SC-05).** No breach notification timeframe and no right to audit.
8. **No exit process (GV.SC-10).** Former suppliers keep access or data.
9. **Board reporting shows activity, not risk (GV.OV-03).** "10,000 phishing emails blocked" instead of risk against appetite.

Evidence to request:
- Information security policy with approval record and review history
- Board-approved risk appetite statement and tolerance metrics
- Enterprise risk register showing cyber risks
- Risk methodology and risk acceptance register (with approver and expiry)
- RACI, security role descriptions, and HR onboarding/offboarding records
- Board / risk committee minutes and reporting packs
- Obligations register (legal, regulatory, contractual)
- Supplier inventory with criticality tiers, due diligence records, sample contracts and exit records

## Worked example: an insurer onboarding a claims-processing SaaS provider
1. The provider will hold policyholder personal information, so privacy and regulatory obligations apply, e.g. the Privacy Act 1988 and APRA CPS 234 (GV.OC-03).
2. Claims processing is a critical service customers depend on (GV.OC-04), so the provider is tiered as critical (GV.SC-04).
3. Due diligence before signing: security questionnaire, SOC 2 Type II report, data location check (GV.SC-06).
4. The contract includes security requirements, a breach notification timeframe, right to audit and exit terms (GV.SC-05).
5. Remaining risk is rated using the standard method (GV.RM-06) and accepted by the business risk owner because it sits within appetite (GV.RM-02, GV.RM-04).
6. The provider is named in the IR plan and joins the annual tabletop (GV.SC-08).
7. Annual reassessment and performance monitoring (GV.SC-07, GV.SC-09), reported to the risk committee (GV.OV-03).
8. At contract end: access revoked, data returned, and a destruction certificate obtained (GV.SC-10).

## Links to other frameworks
Practitioner mapping. For official mappings, check NIST's Informative References for CSF 2.0.

| Govern category | ISO/IEC 27001:2022 | CISA domain |
|---|---|---|
| GV.OC | Clauses 4.1–4.3; A.5.31 (legal, statutory, regulatory and contractual requirements) | D2 Governance and Management of IT |
| GV.RM | Clauses 6.1–6.2, 8.2–8.3 (risk assessment and treatment) | D2 |
| GV.RR | Clauses 5.1, 5.3, 7.1; A.5.2–A.5.3; A.6.1–A.6.5 (people controls) | D2 |
| GV.PO | Clause 5.2; A.5.1 (policies for information security) | D2 |
| GV.OV | Clauses 9.1–9.3 (monitoring, internal audit, management review), 10 | D1 Information System Auditing Process, D2 |
| GV.SC | A.5.19–A.5.23 (supplier relationships, ICT supply chain, cloud services) | D2 |

Australian context: APRA CPS 234 makes the board ultimately responsible for information security (GV.RR-01), and CPS 230 covers material service providers (GV.SC).

## Sources
- [NIST CSF 2.0 (CSWP 29)](https://doi.org/10.6028/NIST.CSWP.29)
- [NIST CSF home](https://www.nist.gov/cyberframework)
- [NIST CSF FAQs – changes from 1.1 to 2.0](https://www.nist.gov/faqs)
- ISO/IEC 27001:2022, Information security management systems – Requirements
- [APRA Prudential Standard CPS 234](https://www.apra.gov.au/standards/cps-234)
