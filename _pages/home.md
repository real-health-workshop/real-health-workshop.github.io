---
layout: default
title: "ReAL-Health 2027"
permalink: /
nav_order: 1
---

<!-- Logo & Title side by side -->
<div style="display:flex; align-items:center; justify-content:center; gap:1.5rem; margin:2rem 0; flex-wrap:wrap;">
  <img
    src="{{ '/assets/img/realhealth-logo.svg' | relative_url }}"
    alt="ReAL-Health 2027 Logo"
    style="width:120px; height:auto;"
  />
  <h1 style="margin:0; font-size:2.0rem; line-height:1.25;">
    ReAL-Health 2027: Reliability and Assurance for Language Technology in Health
  </h1>
</div>

<!-- Hero banner -->
<div style="text-align:center; margin-bottom:2.5rem; padding:2.5rem 1rem; border-radius:14px;
            background:linear-gradient(135deg,#0EA5A5 0%,#066B82 100%); color:#fff;">
  <div style="font-size:1.35rem; font-weight:600;">Proposed for NAACL 2027</div>
  <div style="font-size:1.05rem; margin-top:0.5rem;">June 1&ndash;5, 2027 &nbsp;&bull;&nbsp; San Francisco, USA &nbsp;&bull;&nbsp; Pending acceptance</div>
  <div style="font-size:0.95rem; margin-top:0.6rem; opacity:0.95;">Making clinical language technology reliable, auditable, private, and safe enough to deploy.</div>
</div>

## Welcome

Welcome to **ReAL-Health 2027: Reliability and Assurance for Language Technology in Health**, a one-day workshop proposed for **NAACL 2027**, the Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics.

Clinical language technology is already deployed at scale. Ambient scribes draft clinical notes, LLMs triage patient messages, summarize discharge records, draft prior-authorization letters, and increasingly act as multi-step agents over the electronic health record. But what makes a model accurate on a clinical QA benchmark is not what makes it safe at the bedside. Deployment demands properties our field treats as secondary: calibrated abstention, faithful grounding in the patient record, robustness to the messy multilingual language clinicians and patients actually produce, guarantees over protected health information (PHI), and evidence a regulator can audit.

ReAL-Health asks one question: **how do we build clinical language technology, increasingly agentic, that is reliable enough to deploy, and how do we produce the evidence that it is?** The workshop is organized around three thematic clusters, with multilinguality cutting across all three.

1. **Reliability and evaluation of clinical NLP.** Uncertainty, calibration, and selective prediction in clinical generation; hallucination and faithfulness in EHR-grounded summarization and report generation; clinician-in-the-loop and rubric-based evaluation beyond accuracy; negative results and failed deployments.

2. **Safety and assurance for clinical LLM agents.** Long-horizon evaluation of agents acting over the EHR; faithfulness of tool calls against FHIR resources; prompt injection via patient-supplied text and retrieved records; red-teaming methodology; escalation and human-handoff design; audit logs as assurance artifacts; assurance cases translating the EU AI Act, FDA SaMD guidance, and the NIST AI RMF into concrete NLP evaluation protocols.

3. **Privacy, fairness, and governance for clinical text.** De-identification and re-identification risk; PHI memorization and leakage from clinical LMs; federated training across hospital corpora; HIPAA/GDPR-aligned machine unlearning; disparate performance across patient populations.

**Multilingual and low-resource clinical NLP** cuts across all three rather than sitting beside them. Reliability established on English discharge summaries does not transfer to the languages in which most of the world receives care, and we explicitly solicit work on non-English clinical corpora, code-switched clinician&ndash;patient interaction, and interpretation in care settings.

We reserve program time for deployment experience reports from hospitals and industry, and for regulatory translation sessions, both of which are structurally excluded from paper-track-only venues.

### How we differ from neighbouring venues

ClinicalNLP and BioNLP center tasks, models, and resources for clinical and biomedical text. LOUHI centers health text analytics broadly. TrustNLP treats reliability, privacy, and fairness as general NLP properties. ReAL-Health occupies the gap between them: the **assurance evidence** for clinical language systems that have already left the lab, operationalized against HIPAA, GDPR, FDA SaMD, and the EU AI Act. Agentic health workshops have begun to appear, but are anchored in imaging and multimodal data or in general autonomy; none sits in a computational linguistics venue or centers the language-native failure modes of EHR agents.

<p align="center">
  <a href="https://real-health-workshop.github.io/">ReAL-Health 2027</a> &bull; A
  <a href="https://2027.naacl.org/">NAACL 2027</a> Workshop
</p>

**Workshop date:** June 2027, pending workshop acceptance (notification October 2, 2026)
**Location:** San Francisco, USA (NAACL 2027, hybrid)
**Format:** One day, approximately 7.5 hours, hybrid-ready
**Primary contacts:** sumon@case.edu, shibbir@txstate.edu

> **Note:** This site is under construction. Items marked **TBA** will be updated after the workshop notification on October 2, 2026, and as the program is finalized.

---

### Organizing Committee

<div style="display:flex; justify-content:center; align-items:flex-start; gap:1.5rem; flex-wrap:wrap; margin-bottom:3rem;">

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/islam.png' | relative_url }}"
         alt="Md Tauhidul Islam" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Md Tauhidul Islam</strong><br><em>Stanford University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/avanti.jpg' | relative_url }}"
         alt="Avanti Bhandarkar" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Avanti Bhandarkar</strong><br><em>Mayo Clinic, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/sumon.jpg' | relative_url }}"
         alt="Sumon Biswas" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Sumon Biswas</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/amit.jpg' | relative_url }}"
         alt="Amit Kumar Sikder" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Amit Kumar Sikder</strong><br><em>Iowa State University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/shahnewaz.jpg' | relative_url }}"
         alt="Shahnewaz Karim Sakib" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Shahnewaz Karim Sakib</strong><br><em>University of Tennessee at Chattanooga, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/anindya.jpg' | relative_url }}"
         alt="Anindya Bijoy Das" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Anindya Bijoy Das</strong><br><em>University of Akron, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/sahmed.jpg' | relative_url }}"
         alt="Shibbir Ahmed" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Shibbir Ahmed</strong><br><em>Texas State University, USA</em>
  </div>

</div>

Full bios are available on the [Organization page]({{ '/organization/' | relative_url }}).

---

### Invited Speakers

**Keynote speakers**

<div style="display:flex; justify-content:center; align-items:flex-start; gap:1.5rem; flex-wrap:wrap; margin-bottom:2rem;">

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/xiaofeng.jpg' | relative_url }}"
         alt="Xiaofeng Wang" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Xiaofeng Wang</strong><br><em>Cleveland Clinic, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/anant.jpg' | relative_url }}"
         alt="Anant Madabhushi" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Anant Madabhushi</strong><br><em>Georgia Tech &amp; Emory University, USA</em>
  </div>

<!-- NOT IN THE SUBMITTED NAACL 2027 PROPOSAL (which lists 9 confirmed speakers).
     Kept here so nothing is lost. If these three are genuinely confirmed, delete this
     comment wrapper to restore them, and update the speaker count in the proposal PDF. -->
<!--
  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/james.jpg' | relative_url }}"
         alt="James Zou" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. James Zou</strong><br><em>Stanford University, USA</em>
  </div>
-->

</div>

**Invited talks**

<div style="display:flex; justify-content:center; align-items:flex-start; gap:1.5rem; flex-wrap:wrap; margin-bottom:3rem;">

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/robert.jpg' | relative_url }}"
         alt="Robert Davis" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Robert Davis</strong><br><em>University of Tennessee Health Science Center, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/vipin.jpg' | relative_url }}"
         alt="Vipin Chaudhary" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Vipin Chaudhary</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/ritambhara.jpg' | relative_url }}"
         alt="Ritambhara Singh" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Ritambhara Singh</strong><br><em>Brown University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/satish.jpg' | relative_url }}"
         alt="Satish E. Viswanath" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Satish E. Viswanath</strong><br><em>Emory University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/farshid.jpg' | relative_url }}"
         alt="Farshid Alambeigi" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Farshid Alambeigi</strong><br><em>UT Austin, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/shuo.jpg' | relative_url }}"
         alt="Shuo Li" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Shuo Li</strong><br><em>CWRU &amp; Case Comprehensive Cancer Center, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/heidi.jpg' | relative_url }}"
         alt="Heidi Hanson" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Heidi Hanson</strong><br><em>Oak Ridge National Laboratory, USA</em>
  </div>

<!-- NOT IN THE SUBMITTED NAACL 2027 PROPOSAL (which lists 9 confirmed speakers).
     Kept here so nothing is lost. If these three are genuinely confirmed, delete this
     comment wrapper to restore them, and update the speaker count in the proposal PDF. -->
<!--
  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/lei.jpg' | relative_url }}"
         alt="Lei Xing" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Lei Xing</strong><br><em>Stanford University, USA</em>
  </div>
-->

<!-- NOT IN THE SUBMITTED NAACL 2027 PROPOSAL (which lists 9 confirmed speakers).
     Kept here so nothing is lost. If these three are genuinely confirmed, delete this
     comment wrapper to restore them, and update the speaker count in the proposal PDF. -->
<!--
  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/yanmin.jpg' | relative_url }}"
         alt="Yanmin Gong" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Yanmin Gong</strong><br><em>Texas A&amp;M University, USA</em>
  </div>
-->

</div>

Full speaker details on the [Speakers page]({{ '/speakers/' | relative_url }}).

---

## Participation

ReAL-Health welcomes original long and short papers, deployment experience reports, datasets, benchmarks, and position papers. Work in progress and negative results are explicitly in scope.

### Submission Types
- **Long papers** (8 pages plus unlimited references): novel research, methods, resources, or systems.
- **Short papers** (4 pages plus unlimited references): focused contributions, position papers, tool or benchmark previews.
- **Experience reports**: deployment lessons from hospitals, industry, or regulators, submitted as long or short papers.

- **Format:** ACL style files, anonymized for double-blind review.
- **Submission site:** OpenReview (link TBA).
- **Review process:** Double-blind, three program-committee reviews per submission, with a structured rubric that scores claim&ndash;evidence alignment for reliability assertions separately from novelty.
- **ARR:** ReAL-Health uses OpenReview as its own reviewing platform and does **not** accept ARR-committed submissions. All submissions go through the direct route above.

### Important Dates (NAACL 2027 timeline)

| Milestone | Date |
| --- | --- |
| Workshop acceptance notification (to organizers) | October 2, 2026 |
| First call for papers | October 26, 2026 |
| Second call for papers | November 23, 2026 |
| Third call for papers (optional) | January 4, 2027 |
| **Paper submission deadline** | **February 5, 2027** |
| Author notification | March 26, 2027 |
| Camera-ready due | April 16, 2027 |
| Proceedings due | May 7, 2027 |
| Pre-recorded video due | May 14, 2027 |
| Workshop | June 2027 (day TBA within NAACL 2027, June 1&ndash;5) |

> Accepted papers are **archival** and appear in the ACL Anthology. A **non-archival** option is available for presentation only, including Findings papers and work under review elsewhere, which matters for hospital and industry contributors who publish in clinical venues.

Full details on the [Call for Participation page]({{ '/call-for-papers/' | relative_url }}).

### Hybrid and Virtual Participation

NAACL 2027 is a hybrid conference, and ReAL-Health is designed to run fully virtually without loss. Every accepted paper supplies a pre-recorded video released before the workshop, so discussion is not gated on live attendance. Talks and the panel are live-streamed with a dedicated remote moderator whose only role is relaying chat questions into the room. Poster sessions run on a virtual platform with author slots duplicated across Americas-friendly and Europe/Asia-friendly time bands. Panel and discussion questions are collected in advance through a public form, so remote and in-person input carry equal weight.

### Shared Task

ReAL-Health 2027 will host a community shared task on the **safety of patient-facing clinical LLMs**, built on the publicly available HealthBench rubric, with a safety-evaluation track and a red-teaming track, plus **multilingual** and **multi-turn agentic** subtracks. Top systems present spotlight talks at the workshop, and **Best System** and **Best Student System** awards will be announced at closing. Participation does not require a paper submission.

Full task details, data, and timeline on the [Shared Task page]({{ '/shared-task/' | relative_url }}).

---

### Program

The one-day program spans roughly 7.5 hours, with more than half the time in discussion, posters, or panel rather than podium talks: two keynotes, two contributed sessions, two protected poster sessions, a cross-community panel, shared-task spotlights, and a facilitated open-problems discussion that produces a publicly posted memo. See the [Schedule page]({{ '/schedule/' | relative_url }}).

---

### Technical Program Committee Members

Our Program Committee spans clinical NLP, reliability and safety, clinical informatics, privacy and security, federated learning, and software engineering for AI. Members below have confirmed their participation in reviewing for ReAL-Health 2027. The committee is being expanded to 70+ members ahead of the first call for papers, with recruitment targeted at clinical NLP and at European, Asia-Pacific, and Global South institutions.

<div style="column-count: 2; column-gap: 2rem; margin-bottom: 3rem;">
  <ul style="padding-left: 1.2rem; margin: 0; line-height: 1.7;">
    <li><strong>Dr. Rahul Singh</strong>, <em>University of Rhode Island, USA</em></li>
    <li><strong>Dr. Dalal Alharthi</strong>, <em>The University of Arizona, USA</em></li>
    <li><strong>Dr. Praneeth Narayanamurthy</strong>, <em>Alcon, USA</em></li>
    <li><strong>Dr. Niloufar Alipour Talemi</strong>, <em>Clemson University, USA</em></li>
    <li><strong>Dr. Sayeed Shafayet Chowdhury</strong>, <em>Indiana University, USA</em></li>
    <li><strong>Dr. Ratna Kandala</strong>, <em>University of Kansas, USA</em></li>
    <li><strong>Dr. Mahmoud Nazzal</strong>, <em>Old Dominion University, USA</em></li>
    <li><strong>Dr. Farah Ferdaus</strong>, <em>Lamar University, USA</em></li>
    <li><strong>Dr. Akram Mohammed</strong>, <em>UT Health Science Center, USA</em></li>
    <li><strong>Dr. Aruna Jayasena</strong>, <em>UMass Amherst, USA</em></li>
    <li><strong>Dr. Filiz Bunyak Ersoy</strong>, <em>University of Missouri, USA</em></li>
    <li><strong>Dr. Zhonghao Liao</strong>, <em>Milwaukee School of Engineering, USA</em></li>
    <li><strong>Dr. Silpa Babu</strong>, <em>University of Iowa, USA</em></li>
    <li><strong>Dr. Amit Seal Ami</strong>, <em>University of South Florida, USA</em></li>
    <li><strong>Dr. Nigar Khasayeva</strong>, <em>Georgia State University, USA</em></li>
    <li><strong>Dr. Breno Dantas Cruz</strong>, <em>Tulane University, USA</em></li>
    <li><strong>Dr. An Wang</strong>, <em>Case Western Reserve University, USA</em></li>
    <li><strong>Dr. Erman Ayday</strong>, <em>Case Western Reserve University, USA</em></li>
    <li><strong>Dr. Nasik Muhammad Nafi</strong>, <em>Oak Ridge National Laboratory, USA</em></li>
    <li><strong>Dr. Emad Shihab</strong>, <em>Concordia University, Canada</em></li>
    <li><strong>Dr. Sayma Sultana</strong>, <em>Tulane University, USA</em></li>
    <li><strong>Dr. Gias Uddin</strong>, <em>York University, Canada</em></li>
    <li><strong>Dr. Kevin Xu</strong>, <em>Case Western Reserve University, USA</em></li>
    <li><strong>Dr. Jaydeb Sarker</strong>, <em>University of Nebraska at Omaha, USA</em></li>
    <li><strong>Dr. Abdullah Al Maruf</strong>, <em>California State University, USA</em></li>
    <li><strong>Dr. Yu Yin</strong>, <em>Case Western Reserve University, USA</em></li>
    <li><strong>Dr. Iftekhar Ahmed</strong>, <em>University of California, Irvine, USA</em></li>
    <li><strong>Dr. Sanmukh Kuppannagari</strong>, <em>Case Western Reserve University, USA</em></li>
    <li><strong>Dr. Masud Rahman</strong>, <em>Dalhousie University, Canada</em></li>
    <li><strong>Dr. Soumya Ray</strong>, <em>Case Western Reserve University, USA</em></li>
    <li><strong>Dr. Jing Ma</strong>, <em>Case Western Reserve University, USA</em></li>
    <li><strong>Yining She</strong>, <em>Carnegie Mellon University, USA</em></li>
    <li><strong>Dr. Shuai Xu</strong>, <em>Case Western Reserve University, USA</em></li>
    <li><strong>Dr. Feixiong Cheng</strong>, <em>Cleveland Clinic, USA</em></li>
    <li><strong>Dr. Dewan Fahim Noor</strong>, <em>Tuskegee University, USA</em></li>
    <li><strong>Dr. Chao Yan</strong>, <em>Vanderbilt University, USA</em></li>
    <li><strong>Dr. Yinghui Wu</strong>, <em>Case Western Reserve University, USA</em></li>
    <li><strong>Dr. Jing Li</strong>, <em>Case Western Reserve University, USA</em></li>
  </ul>
</div>

The full program committee is also listed on the [Organization page]({{ '/organization/' | relative_url }}).
