---
layout: page
title: "Shared Task"
permalink: /shared-task/
nav: true
nav_order: 4
nav_title: "Shared Task"
---

# Shared Task: Safety of Patient-Facing Clinical LLMs

> **Note:** This shared task becomes active upon workshop acceptance. Notification is expected **October 2, 2026**. The task description, data selection, and timeline below describe the planned task and will be confirmed at that point.

## Overview

ReAL-Health 2027 will host a community shared task on the **safety of patient-facing clinical large language models**, the deployment setting moving fastest from research into practice and where failures are most visible to patients and clinicians. The task is designed to be approachable, reproducible, and aligned with how clinical language technology is actually evaluated in practice.

The task is built on **HealthBench**, the publicly released benchmark of realistic patient-facing health conversations annotated by physicians with rubrics covering safety, factuality, completeness, refusal behavior, and communication quality. Building on an existing high-quality benchmark, rather than constructing a new dataset, lets the task focus on methods development and evaluation rigor within the workshop timeline.

## Tracks

Participation in any combination of tracks is welcome.

**Track 1: Safety evaluation.** Teams submit either a fine-tuned or prompted language model, or a separate guardrail or classifier that takes a model output and predicts whether it satisfies the HealthBench safety rubric. The guardrail sub-track is of particular interest, since deployable guardrails for patient-facing systems remain underexplored.

**Track 2: Red-teaming.** Teams submit adversarial prompts that elicit safety failures from a public reference model on HealthBench's safety dimensions. The best red-team set is released as a community artifact, with credit to contributing teams.

### Subtracks

**Multilingual subtrack.** A subset of prompts is extended beyond English. Reliability evidence established on English-language interactions does not automatically transfer to the languages in which most of the world receives care, and this subtrack makes that gap measurable.

**Multi-turn agentic subtrack.** Rather than scoring a single response, this subtrack evaluates safety across a multi-turn interaction in which the system may call tools or retrieve from a simulated record. It targets failure modes specific to agentic clinical deployments: unsafe escalation, unfaithful tool use, and injection through retrieved content.

## Evaluation

Submissions are scored against the HealthBench physician-written rubrics, reported per rubric dimension (safety, factuality, refusal, communication). Track 1 submissions are scored on rubric performance; Track 2 submissions on the rubric-failure rate they elicit, with manual organizer review for spurious or out-of-scope prompts. A reproducible evaluation harness and starter notebook are released at task launch. Teams submit a model checkpoint or handle, a callable API, or a classifier function, alongside a system description paper.

## Ethics and Risk Management

All shared-task data are **fully synthetic or publicly licensed**. No real protected health information is used or accepted, and submissions containing PHI are rejected. The red-teaming track releases prompts but withholds any completions that constitute directly actionable clinical harm, under a posted responsible-release policy reviewed by the organizers before publication. Participants agree to that policy at registration. Dual-use considerations are handled in line with the ACL Code of Ethics.

## Timeline (planned)

| Milestone | Date |
| --- | --- |
| Workshop acceptance | October 2, 2026 |
| Task announced, page and starter code live | October 26, 2026 (with the first call) |
| Data and baselines released | December 2026 |
| Evaluation phase | February 8 to March 1, 2027 |
| System description papers due | March 8, 2027 |
| Notification | March 26, 2027 (with the main track) |
| Camera-ready | April 16, 2027 |
| Results announced at workshop | June 2027 |

We estimate 25 to 40 participating teams.

## Artifacts

The following are released publicly at the workshop, under permissive licences: the top-performing guardrail models, the community red-team prompt set, and the evaluation harness.

## Recognition

Top systems in each track present **10-minute spotlight talks** during a dedicated shared-task session. **Best System** and **Best Student System** awards are announced at closing. System description papers appear in the workshop proceedings.

Participation does not require a paper submission to the main track. Teams may submit both a shared-task entry and a paper; the two review processes are independent.

## Organizers

The shared task is led by **Dr. Avanti Bhandarkar** (Mayo Clinic). For questions before launch, please contact the [workshop organizers]({{ '/contact/' | relative_url }}).
