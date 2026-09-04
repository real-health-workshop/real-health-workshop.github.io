---
layout: page
title: "Call for Participation"
permalink: /call-for-papers/
nav: true
nav_order: 3
nav_title: "CFP"
---

# Call for Participation

**ReAL-Health 2027: Reliability and Assurance for Language Technology in Health**, a one-day workshop proposed for **NAACL 2027** (San Francisco, June 1&ndash;5, 2027), invites contributions that advance the engineering of reliable, auditable, private, and safe clinical language technology. We emphasize actionable techniques, evidence (tests, metrics, logs, audit trails, regulatory alignment), and open artifacts (benchmarks, evaluation protocols, red-teaming playbooks). The workshop deliberately bridges research and deployment, and welcomes work in progress and negative results alongside completed results.

> **Status.** This call is provisional pending workshop acceptance. Notification is expected **October 2, 2026**, after which the OpenReview site and final dates go live here.

---

## Topics of Interest

We welcome submissions across three clusters, with multilinguality cutting across all of them.

**1. Reliability and evaluation of clinical NLP**
- Uncertainty quantification, calibration, and selective prediction in clinical generation
- Hallucination and faithfulness in EHR-grounded summarization and report generation
- Clinical grounding, provenance, and attribution to the patient record
- Evaluation beyond accuracy: clinician-in-the-loop protocols, rubric-based scoring, refusal behavior, distribution shift
- Negative results, failed deployments, and reproducibility in clinical NLP

**2. Safety and assurance for clinical LLM agents**
- Long-horizon evaluation of agents acting over the electronic health record
- Faithfulness of tool calls against FHIR resources and structured clinical data
- Prompt injection through patient-supplied text and retrieved records
- Red-teaming methodology and threat models for EHR-integrated agents
- Escalation, human handoff, and oversight design for agentic clinical workflows
- Audit logs as assurance artifacts
- Assurance cases translating the EU AI Act, FDA SaMD guidance, and the NIST AI RMF into concrete NLP evaluation protocols

**3. Privacy, fairness, and governance for clinical text**
- De-identification and re-identification risk
- PHI memorization and leakage from clinical language models
- Federated and privacy-preserving training across hospital corpora
- Machine unlearning aligned with HIPAA and GDPR right-to-be-forgotten
- Measurement of disparate performance across patient populations

**Cross-cutting: multilingual and low-resource clinical NLP**
- Non-English clinical corpora and clinical NLP beyond well-resourced health systems
- Code-switched clinician&ndash;patient interaction; interpretation in care settings
- Whether and how reliability evidence transfers across languages and care settings
- Open datasets, toolkits, benchmarks, and shared infrastructure
- Deployment experience reports from hospitals, industry, and regulators

---

## Submission

- **Types.** Long papers (8 pages plus unlimited references) and short papers (4 pages plus unlimited references). Deployment experience reports are welcome in either format.
- **Format.** ACL style files, anonymized for double-blind review. Templates will be linked with the OpenReview site.
- **Submission site.** OpenReview (link TBA).
- **ARR.** ReAL-Health uses **OpenReview as its own reviewing platform and does not accept ARR-committed submissions.** For a first-edition workshop whose audience includes clinicians, informaticians, and regulatory researchers largely outside the ARR ecosystem, a single direct submission route is simpler for authors and lets us apply a rubric tailored to assurance claims.
- **Review.** Double-blind, at least three program-committee reviews per submission, structured rubric that scores claim&ndash;evidence alignment for reliability assertions separately from novelty.
- **Archival status.** Accepted papers are **archival** and appear in the ACL Anthology. Authors may instead choose a **non-archival** presentation-only option, which covers Findings papers and work under review elsewhere.
- **Hybrid participation.** NAACL 2027 is a hybrid conference. Every accepted paper supplies a pre-recorded video, and remote presentation is fully supported. See the [Schedule page]({{ '/schedule/' | relative_url }}) for details.

---

## Ethics and Responsible Research

Submissions are reviewed for adherence to the [ACL Code of Ethics](https://www.aclweb.org/portal/content/acl-code-ethics), and authors working with clinical data should state IRB or data-use status. No real protected health information may be included in submissions or shared-task entries. Work on red-teaming and adversarial methods should discuss responsible release; the workshop applies a posted responsible-release policy to shared-task artifacts.

All participants are expected to be aware of and abide by the [ACL anti-harassment policy](https://www.aclweb.org/adminwiki/index.php?title=Anti-Harassment_Policy).

---

## Diversity and Inclusion

We explicitly invite clinicians, deployment practitioners, and researchers from low-resource settings, and we put experience reports and negative results in scope, which lowers the barrier for contributors without large compute budgets. A mentoring program pairs first-time submitters from under-represented groups with program-committee members for pre-submission feedback, opening with the second call for papers. All shared-task artifacts are released under permissive licences so that groups without proprietary data access can build on them.

---

## Shared Task

Beyond paper submissions, the workshop hosts a **community shared task on the safety of patient-facing clinical LLMs**, built on HealthBench, with safety-evaluation and red-teaming tracks plus multilingual and multi-turn agentic subtracks. Top systems present spotlight talks. Participation does not require a paper. See the [Shared Task page]({{ '/shared-task/' | relative_url }}) for task description, tracks, evaluation protocol, and timeline.

---

## Important Dates (NAACL 2027)

| Milestone | Date |
| --- | --- |
| Workshop acceptance (to organizers) | October 2, 2026 |
| First call for papers | October 26, 2026 |
| Second call for papers | November 23, 2026 |
| Third call for papers (optional) | January 4, 2027 |
| **Paper submission deadline** | **February 5, 2027** |
| Author notification | March 26, 2027 |
| Camera-ready due | April 16, 2027 |
| Proceedings due | May 7, 2027 |
| Pre-recorded video due | May 14, 2027 |
| Workshop | June 2027 (day TBA within June 1&ndash;5) |

---

## Conflict of Interest

Organizers do not submit or present, do not review submissions from their own institutions, and do not handle work by current or recent students and postdocs. The shared-task lead is recused from systems with co-authors at her institution, with a designated program-committee deputy handling those independently. The COI workflow is documented in the OpenReview configuration.

---

### Contact

For questions about **ReAL-Health 2027**, please reach any of the organizers.

- **Dr. Md Tauhidul Islam** &middot; Stanford University &middot; [tauhid@stanford.edu](mailto:tauhid@stanford.edu)
- **Dr. Avanti Bhandarkar** &middot; Mayo Clinic &middot; [bhandarkar.avanti@mayo.edu](mailto:bhandarkar.avanti@mayo.edu)
- **Dr. Sumon Biswas** &middot; Case Western Reserve University &middot; [sumon@case.edu](mailto:sumon@case.edu)
- **Dr. Amit Kumar Sikder** &middot; Iowa State University &middot; [aksikder@iastate.edu](mailto:aksikder@iastate.edu)
- **Dr. Shahnewaz Karim Sakib** &middot; University of Tennessee at Chattanooga &middot; [shahnewazkarim-sakib@utc.edu](mailto:shahnewazkarim-sakib@utc.edu)
- **Dr. Anindya Bijoy Das** &middot; University of Akron &middot; [adas@uakron.edu](mailto:adas@uakron.edu)
- **Dr. Shibbir Ahmed** &middot; Texas State University &middot; [shibbir@txstate.edu](mailto:shibbir@txstate.edu)
