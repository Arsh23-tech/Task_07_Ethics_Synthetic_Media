# Task 07 — The Ethics of Synthetic Representation

> **Research project disclosure:** This repository contains analysis and governance work about synthetic media. The project does not create or distribute any new synthetic media for Task 7. The analysis is grounded in the synthetic audio/video experiment completed in Task 6.

## Project Overview

Task 7 examines the ethical and organizational implications of synthetic representation by starting from a hands-on experiment completed in Task 6 and reasoning outward from that experience.

In Task 6, I used ElevenLabs to generate synthetic narration from a verified analytical narrative developed in Task 5 and used HeyGen to create a synthetic talking-avatar video using my own photograph. The experiment demonstrated how accessible synthetic-media generation has become while also exposing limitations involving pronunciation, head movement, positioning, lip synchronization, watermarking, export restrictions, and detectability.

Task 7 moves from **building the capability to governing its use**.

The project has two phases:

- **Phase A — Ethical Analysis:** Examines synthetic representation through the truth, consent, context, and scale axes and evaluates the mitigation landscape.
- **Phase B — Governance Policy:** Develops a practical synthetic-media policy for a University Communications Office and stress-tests where that policy could fail.

The assignment requires the analysis to remain grounded in the Task 6 experience rather than relying primarily on examples from the news or existing deepfake incidents.

---

# Organizational Context

## University Communications Office

The policy is written for a University Communications Office responsible for public-facing and internal communications such as:

- university websites;
- social media;
- marketing and recruitment;
- admissions communications;
- alumni and donor communications;
- training and educational materials;
- events and presentations;
- public relations; and
- digital communications.

This setting was selected because a university has legitimate reasons to use synthetic media for education, accessibility, translation, training, and creative communication, while also handling sensitive identities, institutional authority, public trust, and high-impact communications.

The policy is intentionally operational so that the same control framework can be adapted to corporate communications, marketing, HR, executive communications, training, and customer-facing functions.

---

# Connection to Task 6

Task 6 provided the practical foundation for this project.

The Task 6 experiment demonstrated:

- ElevenLabs could create natural-sounding narration with very little effort.
- The first ElevenLabs generation mispronounced my surname, leading to a second generation after removing it from the script.
- HeyGen could generate a talking avatar from my own photograph.
- HeyGen provided customization choices for the presentation.
- The resulting video remained visibly synthetic because of limitations in head movement, positioning, and other facial-motion cues.
- The free tier introduced practical restrictions, including a watermark and inability to download the final MP4.
- The generated audio received a **98% AI-generated classification** from the detector used in Task 6.
- The original audio/video artifacts did not contain an explicit spoken or on-screen AI disclosure.

These observations became the evidence base for the ethical analysis in Phase A.

## Task 6 Repository

The Task 7 instructions require a reference to the Task 6 work rather than re-uploading it here.

**Task 6 GitHub Repository:**  
`PASTE-YOUR-TASK-6-GITHUB-URL-HERE`

---

# Phase A — Ethical Analysis

## 1. Returning to What I Built

This section reflects on what changed in my understanding of synthetic media after creating the Task 6 artifacts.

Key observations include the accessibility of the tools, the difference between audio and video realism, the importance of consent when using a likeness, and the concern that the same platforms could be used with very different consequences depending on how they are deployed.

## 2. Truth Axis

The Truth axis examines what changes when the same synthetic delivery mechanism that communicated verified analysis in Task 6 is used to present fabricated information.

The analysis moves from the truthful Premier League narrative used in Task 6 to a hypothetical business scenario in which synthetic media is used to make false financial or organizational claims appear to come from an authoritative speaker.

## 3. Consent Axis

The Consent axis examines the difference between using my own likeness with permission and using another person's face or voice without authorization.

The analysis considers consent scope, reuse, revocation, and the difference between permission to use an existing photograph and permission to create a reusable synthetic likeness.

## 4. Context Axis

The Context axis examines what happens when an honestly labeled synthetic artifact is cropped, reposted, screen-recorded, recontextualized, or separated from its original disclosure.

The central concern is that the meaning of synthetic media can change after publication even when the original artifact was produced responsibly.

## 5. Scale Axis

The Scale axis examines the transition from one carefully reviewed synthetic artifact to hundreds or thousands of generated outputs.

The analysis considers how scale can multiply errors, make manual review difficult, increase potential misuse, and shift the governance problem from individual judgment toward repeatable organizational controls.

## 6. Mitigation Landscape

The mitigation analysis examines:

- disclosure;
- provenance and C2PA Content Credentials;
- automated detection;
- legal and regulatory approaches;
- platform policies; and
- professional and organizational norms.

The analysis treats each mitigation as a bounded safeguard rather than a complete solution.

---

# Phase B — Governance Policy

## Synthetic Media Governance Policy

The policy establishes operational controls for synthetic-media use by a University Communications Office.

Major components include:

### Risk Classification

Projects are classified from low-risk through critical/prohibited uses, with stronger approval requirements as risk increases.

### Permitted and Prohibited Uses

The policy identifies legitimate uses such as education, accessibility, translation, training, and approved marketing while explicitly prohibiting deceptive impersonation, non-consensual identity reproduction, fabricated high-impact statements, and other high-risk uses.

### Consent Workflow

Real-person likenesses and voices require documented authorization covering purpose, audience, distribution, duration, reuse, revocation, and third-party processing.

### Vendor and Data Controls

External AI tools must be approved for the intended use, particularly when they process photographs, recordings, voices, or other identity-bearing data.

### Disclosure

Public-facing synthetic media requires clear disclosure when a reasonable viewer could otherwise mistake it for authentic human-created media.

### Provenance

Available provenance information and Content Credentials should be preserved where technically feasible, while recognizing that provenance does not itself establish factual truth.

### Human Review

Tiered review and approval requirements are established for ordinary, higher-risk, and prohibited use cases.

### Incident Response

The policy establishes procedures for containment, evidence preservation, notification, correction, and post-incident review.

### Refusal

The policy provides explicit conditions under which synthetic-media projects must be refused rather than approved with additional disclosure.

---

# Policy Stress Test

The separate `policy_stress_test.md` document examines situations in which the policy could fail even if the organization is acting in good faith.

The stress test covers:

- misunderstandings about consent;
- consent that is reused beyond its original scope;
- revocation after publication;
- downstream loss of context;
- loss of provenance;
- detection uncertainty;
- high-volume generation errors;
- use of unapproved AI tools;
- crisis communications;
- deliberate policy circumvention;
- insufficiently specific disclosures;
- and checklist-style compliance that misses broader ethical concerns.

The stress test concludes that the policy is a risk-management framework rather than a guarantee of zero misuse.

---

# Repository Structure

```text
Task_07_Ethics_Synthetic_Media/
│
├── README.md
├── phase_a_ethical_analysis.md
├── phase_b_synthetic_media_policy.md
├── policy_stress_test.md
├── references.md
│
└── [optional supporting materials]
```

No new synthetic media is required for Task 7, and the Task 6 media should be referenced rather than re-uploaded.

---

# What Surprised Me

The biggest surprise from moving from Task 6 into Task 7 was how little technical effort is required to create a synthetic representation.

The ElevenLabs audio could be generated within seconds, and the HeyGen video required relatively little technical knowledge. The tools made it easy to experiment with voice, avatar, narration, and presentation choices.

At the same time, the quality gap between audio and video was noticeable. The synthetic narration sounded natural enough to be conversational, while the avatar video exposed more visible artifacts through head movement, positioning, and facial behavior.

The experience also changed my view of consent. Using my own photograph felt fundamentally different from using another person's identity because I retained control over how my likeness was represented. This made the ethical distinction between authorized and unauthorized synthetic representation much more concrete.

Finally, the 98% AI-generated detection result on an audio recording that sounded natural to me demonstrated that human perception and technical detection do not necessarily produce the same assessment.

---

# Key Takeaway

The central lesson of this project is that synthetic-media governance cannot depend on a single safeguard.

Responsible use requires a combination of:

**truthful content + appropriate consent + meaningful disclosure + provenance where available + human review + clear accountability + a willingness to refuse high-risk uses.**

Even with those controls, residual risk remains once synthetic media leaves the organization's control. The purpose of governance is therefore not to promise perfect prevention, but to make responsible use more likely, make failures more visible, and ensure that the organization has a defined response when controls fail.

---

# Author

**Arsh Chandrakar**  
M.S. Information Systems  
Syracuse University
