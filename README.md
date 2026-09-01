# PeerLearn

> A decentralized, peer-to-peer academic resource sharing and recommendation platform designed for university students to request, curate, and discover verified study materials.

---

## 📌 Project Overview

**PeerLearn** bridges the gap in academic resource discovery by enabling students to request specific study materials (lecture notes, slide decks, reference videos, and lab guides) and receive crowdsourced, peer-reviewed recommendations. The platform leverages peer validation and reputation mechanics to ensure high-quality, course-aligned content.

---

## 🎯 Project Objectives

1. **Accelerate Resource Discovery:** Enable students to find verified, course-specific study materials in under 2 minutes using targeted peer recommendations.
2. **Incentivize Peer Contribution:** Implement a transparent reputation and upvoting system that recognizes active student collaboration.
3. **Structured Request-Fulfillment Workflow:** Provide an organized request pipeline where students post specific topic queries and peers respond with curated, tagged resources.

---

## 👥 Stakeholders & User Roles

* **Student (Requester):** Posts requests for specific study resources, browses feeds, and marks answers as accepted/helpful.
* **Student (Contributor / Recommender):** Uploads or links materials, suggests edits, and answers peer requests to earn reputation points.
* **Peer Moderator:** Senior student or elected peer who reviews reported content, verifies tags, and maintains academic integrity.
* **Faculty / Academic Advisor:** Views trending topic requests to identify class-wide knowledge gaps and validates resource quality.
* **System Administrator:** Manages authentication, storage quotas, role assignments, platform uptime, and CI/CD pipelines.

---

## 🧩 Major Functional Modules (Epics)

* **EPIC-1: User Management & Trust Framework:** University SSO authentication, user onboarding, profile customization, and contributor reputation engine.
* **EPIC-2: Resource Request Pipeline:** Creation, filtering, tracking, and status lifecycle management (`Open`, `Fulfilled`, `Closed`) of study queries.
* **EPIC-3: Resource Submission & Media Handling:** Document upload processing (PDF/PPT), cloud storage integration, and external video/link metadata extraction.
* **EPIC-4: Peer Review & Quality Verification:** Upvoting/downvoting mechanism, accepted solution verification, content moderation, and discussion threads.
* **EPIC-5: Discovery, Taxonomy & Search:** Faceted search engine supporting queries filtered by course code, university semester, subject, and file format.

---

## 🚀 Sprint 1 Scope & User Stories

| Story ID | User Story Title | Story Points | Priority |
| :--- | :--- | :---: | :--- |
| **US-01** | University SSO & Profile Registration | 5 | Must-Have (P0) |
| **US-02** | Post Specific Resource Request | 3 | Must-Have (P0) |
| **US-03** | Direct Document & Link Recommendation | 5 | Must-Have (P0) |
| **US-04** | Mark Best / Accepted Resource | 2 | Must-Have (P0) |

---

## 🔄 Project Workflow Lifecycle

All work items and tasks in the Scrum board transition through the following pipeline:

```text
[ To Do ] ───> [ In Progress ] ───> [ Code Review ] ───> [ Testing ] ───> [ Done ]
