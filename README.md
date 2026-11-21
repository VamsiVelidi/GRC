# GRC Knowledge Base

My personal wiki for **Governance, Risk and Compliance (GRC)**, written as I learn.

> **Learning in public.** These notes are written while I study, not after I've mastered the topic. Expect gaps, rough edges and corrections over time. Where something here conflicts with the official source, the official source wins.

---

## Why this repo exists

- To build a structured GRC knowledge base I can come back to and extend.
- To force myself to explain each concept in plain language. If I can't write it simply, I don't understand it yet.
- To keep a visible, dated record of what I've learned and when.

## Background

- Masters in Cybersecurity (La Trobe University)
- ~6 years in QA / test automation, moving into GRC and security
- ISTQB CTFL, AWS Certified Cloud Practitioner

I come at GRC from a testing background, so you'll see me lean on that: controls are like test cases, evidence is like test results, and an audit is a test run against a standard.

---

## How the repo is organised

Each framework gets its own folder. Inside each folder:

```
<framework>/
├── README.md        # Index for the framework: what it is, structure, progress
├── 00-overview.md   # The big picture: purpose, who uses it, how it's structured
├── 01-...md         # One file per major section, in learning order
└── ...
```

Every topic note follows the same pattern so the wiki stays consistent:

1. **What it is**: plain-language sentences
2. **Why it matters**: the risk or problem it addresses
3. **Key points**: the parts worth remembering
4. **Real-world example**: what it looks like inside an organisation
5. **Audit / evidence angle**: what an auditor would ask for to prove it's in place
6. **Links to other frameworks**: where it overlaps with other frameworks
7. **Sources**: official documents used

## How I work on this repo

- `main` holds reviewed notes.
- Each framework is drafted on its own branch (e.g. `nist-csf`) and merged into `main` through a pull request when a section is ready.
- Commit messages describe what I learned, e.g. `Add Govern function: GV.OC and GV.RM notes`.

---

## Disclaimer

These are personal study notes. They are not professional, legal or compliance advice, and they don't replace the official framework documents. Always check the primary source before relying on anything here.

## Connect

I also post short GRC concept breakdowns on LinkedIn: https://www.linkedin.com/in/vamsi-velidi/

Corrections and suggestions are welcome. Open an issue.
