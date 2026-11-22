# NIST CSF 2.0: Recover (RC)

Recover is the sixth function of NIST CSF 2.0. It covers restoring assets and operations affected by a cybersecurity incident. The aim is to bring normal operations back on time and limit the incident's effects.

Source: [NIST CSWP 29, The NIST Cybersecurity Framework (CSF) 2.0](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf)

## Categories

Recover has 2 categories.

### RC.RP: Incident Recovery Plan Execution

The technical and operational work. 6 subcategories:

| ID | Outcome | Audit question |
|---|---|---|
| RC.RP-01 | The recovery portion of the incident response plan is executed once the incident response process starts it. | Is there a defined handoff from Respond to Recover, and who has authority to trigger it? |
| RC.RP-02 | Recovery actions are selected, scoped, prioritized and performed. | Is prioritization tied to the Business Impact Analysis (BIA), or is it ad hoc? |
| RC.RP-03 | The integrity of backups and other restoration assets is verified before they are used. | Are backups tested regularly and protected from the same compromise? |
| RC.RP-04 | Critical mission functions and cybersecurity risk management are considered to set post-incident operating norms. | Does recovery follow business criticality and risk appetite? |
| RC.RP-05 | The integrity of restored assets is verified, services are restored and normal operating status is confirmed. | Is there evidence of validation, not just "systems are up"? |
| RC.RP-06 | The end of recovery is declared against criteria, and incident documentation is completed. | Are the exit criteria written down? |

### RC.CO: Incident Recovery Communication

Recovery activities are coordinated with internal and external parties. 2 subcategories:

| ID | Outcome |
|---|---|
| RC.CO-03 | Recovery progress is communicated to designated stakeholders. |
| RC.CO-04 | Public updates use approved methods and messaging. |

## How Recover connects to other functions

- **Respond → Recover:** Respond's incident response process initiates recovery (RC.RP-01).
- **Govern → Recover:** Govern sets the cyber risk management context that informs post-incident operating norms (RC.RP-04).

## Example: ransomware attack

**Respond**
- The team activates the incident response plan, notifies stakeholders and works out which systems are affected and how badly.
- Infected systems are isolated (containment) and the ransomware is removed (eradication).
- Root cause analysis finds how the attacker got in so the gap can be closed.

**Recover**
- Backups are integrity-checked before use (RC.RP-03).
- Business-critical systems are restored first, validated and returned to normal operation (RC.RP-02, RC.RP-05).
- Stakeholders are told when systems are back online (RC.CO-03).
- Recovery is declared complete against written exit criteria, and documentation is finished (RC.RP-06).

## Notes

- Backups sit in Protect (data backup and resilience). Recover covers executing restoration and verifying it.
- Recover does not mean "restore to the old state." RC.RP-04 sets the post-incident operating norms, which are a risk decision.
- The audit questions are practitioner interpretation, not NIST wording.
