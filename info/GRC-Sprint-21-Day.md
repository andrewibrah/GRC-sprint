# 21-Day GRC Sprint → First Role

**Time box:** 1–2 hrs/day. **Anchor framework:** NIST CSF + FTC Safeguards Rule (chosen deliberately — it doubles as AAND product work). **Output by Day 21:** 4 portfolio artifacts + a live application pipeline.

**Rule of the sprint:** every deliverable is built around a single fictional-but-realistic client — a mid-size franchised auto dealership group ("Meridian Auto Group," ~6 rooftops). Same client across all four artifacts so it reads as a real engagement, not disconnected samples.

---

## Week 1 — Learn the language, not the trivia

GRC is 80% vocabulary and document structure. You already have the technical depth; you need to speak compliance fluently so an interviewer can't tell you've never held the title.

**Day 1 — The GRC mental model (1 hr)**
- Internalize the policy hierarchy: *Policy → Standard → Procedure → Guideline*. Know the difference cold; it's a common screening question.
- Map the three pillars: Governance (who decides / accountability), Risk (what could hurt us / likelihood × impact), Compliance (what we're legally/contractually required to do).
- Deliverable: a 1-page note in your own words defining all three + the policy hierarchy. This is your study spine.

**Day 2 — Frameworks landscape (1–2 hrs)**
- Learn what each is *for* (not memorize controls): NIST CSF (voluntary, structure), NIST 800-53 (federal control catalog), ISO 27001 (certifiable ISMS), SOC 2 (attestation for SaaS/vendors), PCI DSS (card data), and the regulations: FTC Safeguards Rule, HIPAA, GDPR/CCPA.
- Deliverable: a comparison table — Framework | Mandatory? | Industry | What it proves. One row each.

**Day 3 — Read the actual FTC Safeguards Rule (1–2 hrs)**
- Read the rule itself (16 CFR Part 314). Focus on the 9 required elements of an information security program (qualified individual, risk assessment, access controls, encryption, MFA, monitoring/testing, training, oversight of service providers, incident response plan).
- Deliverable: bullet list of the 9 elements in plain English. This becomes the backbone of your portfolio.

**Day 4 — Risk assessment methodology (1–2 hrs)**
- Learn NIST 800-30 logic: identify assets → threats → vulnerabilities → likelihood → impact → risk rating → treatment (accept/mitigate/transfer/avoid).
- Learn the risk register format (Risk ID, description, likelihood, impact, inherent risk, control, residual risk, owner).
- Deliverable: an empty risk register template in Excel/Sheets. You'll fill it Week 2.

**Day 5 — Control mapping + evidence (1 hr)**
- Understand the auditor's world: a *control* satisfies a *requirement*, and *evidence* proves the control operates. This triad (requirement → control → evidence) is the entire job.
- Skim how GRC platforms automate this: Vanta, Drata, ServiceNow GRC, Archer, OneTrust. Know the names and what category each is. You don't need hands-on; you need to not look blank.
- Deliverable: 1-page glossary — control, evidence, gap, remediation, attestation, SoA, residual risk, risk appetite, third-party/vendor risk.

**Weekend (optional, 1–2 hrs total):** Start ISC2 Certified in Cybersecurity (CC) — it's free to study, exam is cheap, and it's a legitimate line on the resume that signals GRC-adjacent literacy. Don't let it block the portfolio.

---

## Week 2 — Build the artifact stack (this is what gets interviews)

All four artifacts target Meridian Auto Group against the FTC Safeguards Rule. Build them clean, branded, PDF-exported.

**Day 6–7 — Artifact 1: Risk Assessment (2 hrs ×2)**
- Fill the risk register with 12–15 realistic risks for a dealership (unencrypted customer PII in DMS, no MFA on F&I systems, third-party vendor sprawl, phishing exposure, missing backups, etc.).
- Score each, assign controls, residual risk, owner. Add a 1-page executive summary.

**Day 8–9 — Artifact 2: Information Security Policy (2 hrs ×2)**
- Write a real ISP: scope, roles/responsibilities (name the "Qualified Individual" required by the rule), access control, acceptable use, encryption, incident response reference, vendor management, review cadence.
- 6–10 pages. Use the policy hierarchy correctly. This proves you can write governance docs.

**Day 10 — Artifact 3: Compliance Checklist / Control Matrix (1–2 hrs)**
- Build a matrix: each of the 9 Safeguards Rule elements → mapped control(s) → status (Met / Partial / Gap) → remediation action → owner.
- This is the single most "real job" artifact you'll produce. It *is* the daily work of a GRC analyst.

**Day 11 — Artifact 4: Gap Assessment Report (1–2 hrs)**
- Tie it together: a short report stating Meridian's current compliance posture vs. the rule, prioritized gaps, and a remediation roadmap. Executive-readable.

**Day 12 — Package + publish (1–2 hrs)**
- Clean, consistent branding across all four. Export PDFs.
- Put them in a public GitHub repo *and* write one LinkedIn post: "I built a complete FTC Safeguards Rule compliance program for the franchised-dealership vertical — here's what most GRC programs miss in regulated retail." Link the repo. This post is itself a lead-gen tool for both jobs and AAND.

---

## Week 3 — Targeted pipeline (volume + asymmetry)

**Day 13 — Resume + LinkedIn rebuild (1–2 hrs)**
- Reframe your existing work in GRC language: the AI Prompt Firewall = "designed security controls and logging for an AI data-protection system"; pentests = "performed risk assessments and produced remediation reports." Lead the headline with "GRC | Risk & Compliance | Cybersecurity."
- Title in skills/headline must contain the exact phrases recruiters filter for: *GRC, Governance Risk Compliance, risk assessment, NIST, SOC 2, vendor risk*.

**Day 14 — Target list (1 hr)**
- Pull 30–40 roles: GRC Analyst, Compliance Analyst, IT Risk Analyst, Third-Party/Vendor Risk Analyst, IT Auditor, Security GRC Analyst. Mix remote + NYC metro (your geography is an asset — financial-services GRC density is highest there).
- Prioritize regulated industries: finance, healthcare, insurance, SaaS pursuing SOC 2. They hire GRC entry roles in volume.

**Day 15–19 — Apply + outreach (1–2 hrs/day)**
- 5–8 applications/day. Every application links the portfolio repo.
- The asymmetric channel: for 2–3 roles/day, skip the portal. Find the hiring manager or a GRC team member on LinkedIn and send a short message referencing your dealership compliance program. Most applicants don't do this; it's where you'll get traction.
- Track everything in a simple pipeline sheet (Company | Role | Channel | Date | Status | Contact).

**Day 20 — Interview prep (1–2 hrs)**
- Drill the 15 most common GRC screening questions out loud: policy vs. standard vs. procedure, how you'd run a risk assessment, walk me through a gap assessment, how do you handle a control with no evidence, what's residual risk, how do you prioritize remediation.
- For each, your answer references the Meridian work. You're never speaking hypothetically.

**Day 21 — Systemize (1 hr)**
- Build the repeatable application template + outreach template so you can run 30 min/day on autopilot going forward.
- Schedule weekly: 20 new applications + 5 direct outreaches until offer.

---

## What separates this from the generic roadmap

1. **One client, four artifacts** → reads as a real engagement, not homework.
2. **FTC Safeguards Rule + dealership vertical** → the work *is* AAND product validation. Nothing is throwaway.
3. **Direct outreach > portal spray** → where the asymmetry actually lives, since everyone else only applies through portals.
4. **Language reframe of existing work** → you're not entry-level pretending; you're an operator who's done the work under different labels.

## Calibrated expectations
- "Competition is almost zero" — false. GRC is the most-recommended entry path, so it's crowded. Your portfolio + vertical specificity is what cuts through.
- "$100K+ starting" — top of band. Plan for $65–95K first role; six figures comes fast with the title secured.
- 21 days gets you a pipeline and interviews, not necessarily a signed offer. Offer timeline is realistically 4–10 weeks from Day 1 depending on volume.
