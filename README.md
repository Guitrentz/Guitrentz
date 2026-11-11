# Guilherme Trentini, DDS

**Senior Dental & Facial Surgeon (DDS, 18+ Yrs) | Clinical Product & Workflow Advisor**  
**Clinical AI Evaluation (SOAP & PDSQI-9) • EHR Usability (`<= 3 Clicks`) • Conceptual HL7 FHIR & SNOMED CT Certified • AI-Assisted Product Discovery**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-drtrentini-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/drtrentini/)
[![SNOMED CT](https://img.shields.io/badge/SNOMED_CT-Foundation_Certified_(2026)-008080?style=flat)](https://www.snomed.org/)
[![Templus Architecture](https://img.shields.io/badge/Architecture-Templus_Scribe_%26_FHIR_Core-0066CC?style=flat)](https://github.com/Guitrentz/templus-fhir-clinical-architecture)
[![Deterministic Harness](https://img.shields.io/badge/Open_Source-Clinical_AI_Harness-2EA44F?style=flat)](https://github.com/Guitrentz/clinical-ai-deterministic-harness)

---

### Executive Summary

I am a Senior Dental, Oral & Maxillofacial, and Facial Aesthetic Surgeon (**DDS / Dentist**, 18+ years of uninterrupted clinical and surgical practice; 5-Year First Professional Degree / EU EQF Level 7) working at the intersection of **Clinical Product Advisory, Clinical AI Evaluation (`Human-in-the-Loop / SME`), and EHR Usability**.

After nearly two decades in operating rooms and outpatient chairs, I grew tired of clinical software designed by people who never had to chart a surgical complication with gloves on. That frustration led me to initiate an independent clinical product discovery and applied R&D lab (`templ.us`), focused on reducing clinician documentation burden and catching silent AI hallucinations before they reach a medical record.

---

### How I Work: A Surgeon Orchestrating Multi-Agent, Multi-LLM Engineering Teams

> **Transparency on My Technical Role:** I am **not** a career software developer, database administrator, or traditional `HL7 FHIR` / data engineer. I am a practicing surgeon with foundational training in Health Informatics (*SNOMED CT Foundation Certified*, Oct 2026; conceptual *HL7 FHIR R4/R5* architecture). I build and audit clinical software by operating as the **Clinical Architect, Specification Lead, and Final Safety Auditor**, orchestrating specialized multi-agent, multi-LLM engineering workflows in **OpenCode** under Andrej Karpathy's surgical execution principles.

Commercial LLMs are great at writing boilerplate code, and terrible at clinical nuance. Left unsupervised, a single agent drifts, mixes database schemas, or silently drops a negation particle in a post-op note. To solve that, I don't write the underlying TypeScript, Swift, or Python manually; instead, I run a closed-loop clinical engineering pipeline where distinct language models act as specialized subagents under strict verification gates:

1. **Context Hygiene & Codebase Indexing (`@explore`):** Fast-scanning agents map existing specifications, clinical dossiers, and repository invariants before a single line of code is planned.
2. **Architectural & Schema Gate (`@architect`):** High-reasoning models review state machines, multi-tenant `PostgreSQL Row-Level Security (RLS)` boundaries, and `HL7 FHIR` / `SNOMED CT` domain contracts prior to implementation.
3. **Minimal-Blast-Radius Execution & Verification (`@general` & `@surgeon`):** Coding agents implement strictly scoped changes and run automated typechecks, builds, and deterministic unit suites. If a fix fails twice, execution stops and escalates back to architecture.
4. **Multi-Tenancy, Privacy & Clinical Safety Gate (`@security-review` & Independent Clinical Oracle):** Every change touching authentication, encrypted PHI (`AES-256-GCM`), or clinical synthesis is audited by an isolated security reviewer and tested against an **Independent Blind Clinical Oracle** (`PDSQI-9`, `O(M)` rolling-row `mWER`, and `AHRQ` clinical harm rubrics).

---

### What Distinguishes My Clinical AI R&D (`Templus Scribe v6.2`)

While evaluating first-generation ambient scribes in live clinical care, I noticed they routinely fail on four clinical fronts: they omit ~18% of affirmed clinical facts, invert sentence-level negations, cross-contaminate `RIGHT`/`LEFT` anatomical sites in multi-site procedures, and leak treatment budget discussions into the legal clinical evolution.

To address those failure modes in my R&D prototype (**Templus Scribe `v6.2 Beta`**), I directed the multi-agent pipeline to build six mechanisms that set it apart from standard single-prompt wrappers:

* **EHR-Agnostic Standalone Utility (`Zero Lock-In`):** Operates as a lightweight `macOS Menu Bar` native utility (`335px` HUD, Universal Binary), a `Web Workspace`, and a `Mobile Pocket Recorder` (`Screen Wake Lock`) with a 2-pill zero-training interface (`[Clinical Evolution]` and `[Transcript]`), decoupled from any specific EHR database and enforced by `72-hour` ephemeral retention with 1-click *Crypto-Shredding*.
* **Edge DSP + Pure 2-Stage Acoustic-to-Clinical Split:** Client-side audio conditioning (`16 kHz` anti-aliased decimation, `80 Hz` high-pass pre-emphasis for surgical/dental ambient noise, and moderate dynamic `P10` Voice Activity Detection that preserves short negation particles like *"no"* or *"sem"*) feeds a strict two-stage multi-LLM pipeline:
  * **Stage 1 (Pure Acoustic Clean-Verbatim Diarization):** Dedicated strictly to faithful multi-speaker transcription with `temperature: 0.0` and `thinkingBudget: 0`, eliminating intermediate JSON tuple compression bottlenecks.
  * **Stage 2 (Contextual Identity & 8-Discipline Clinical Synthesis):** Maps speaker identities (`CLINICIAN`, `ASSISTANT`, `PATIENT`, `COMPANION`) and structures notes tailored to **8 regulated healthcare professions** (Medicine, Dentistry/OMFS, Nursing, Physical Therapy, Occupational Therapy, Nutrition `ADIME`, Psychology, and Speech Therapy) with `thinkingBudget: 0` to prevent reasoning models from extrapolating unperformed normal physical exams.
* **Six Deterministic Sub-Millisecond Code Guardrails (`< 1 ms`):** Before a note is shown to the clinician, deterministic code verifies (1) Role-Authority & Temporal boundaries, (2) Sentence-Level Negation & Uncertainty scope, (3) Numeric Dosage Conservation (`mg`, `mcg`, `mL`, `UI`, `FDI` tooth numbers), (4) Anatomical Laterality Cross-Talk (`Right` vs. `Left`), (5) Commercial/Financial Pricing Scrubbing from the medico-legal evolution, and (6) Safe Patient Identity Anchoring (*Zero Wrong-Patient Charting* when companions or referring doctors are mentioned).
* **Independent Blind Clinical Oracle (`PDSQI-9 = 44/45`, `Fact F1 = 100.0%`):** A separate auditing service scores generated notes blindly against the ground-truth audio and transcript across 5 peer-reviewed clinical safety axes (`PDSQI-9` instrument, `CREOLA` omission taxonomy, `mWER`, and `AHRQ` harm severity), achieving `44/45 (97.2%)` on `PDSQI-9` and `100.0%` F1 recall/precision on affirmed clinical facts in a real 55-minute outpatient consultation with zero hallucinations or polarity inversions.

---

### Core Domain & Applied Focus Areas

| Domain Pillar | Clinical Experience, Foundational Standards & AI-Orchestrated Capabilities |
| :--- | :--- |
| **Clinical Surgery & Practice Operations (18+ Yrs)** | Licensed Dentist (`DDS`, Dec 2007), Implantology & Oral Rehabilitation + TMD/Orofacial Pain (`2008–2020`), Outpatient Facial Aesthetic Surgery (`2020–Present`), Oral & Maxillofacial Surgery (`certified 2025`), conscious sedation, perioperative safety, and selective `CBCT` 3D segmentation (`3D Slicer`, `Blender`) for surgical planning |
| **Clinical AI Evaluation (`HITL` & Independent Oracle)** | Daily `HITL` auditing of AI-generated `SOAP` notes in live care, blind evaluation via `PDSQI-9` (`44/45`) & `mWER` benchmarks, 8-profession regulatory note structuring, and deterministic anti-hallucination guardrails |
| **Conceptual Interoperability & Terminologies** | `SNOMED CT Foundation Certified` (Oct 2026), conceptual `HL7 FHIR R4/R5` resource grammar (`Patient`, `Encounter`, `Practitioner`, `Condition`, `Procedure`, `Observation`), `ISO 3950` / Universal `#1–#32` dental notation, and `ADA CDT` / `ICD-10` clinical familiarity |
| **Zero-Training Clinical UX & Perioperative Safety** | Single-sheet zero-scroll clinical cockpit (`<= 3 clicks` interaction budget), preoperative **Go/No-Go Surgical Flight Deck** (anticoagulants, allergies, `ASA`/`Mallampati` interlocks), and `QR/FEFO/UDI` sterilization traceability |

---

### Featured Public Repositories

#### 1. [`templus-fhir-clinical-architecture`](https://github.com/Guitrentz/templus-fhir-clinical-architecture)
**EHR-Agnostic Ambient Clinical Scribe (`v6.2 Beta`) & Hexagonal Multi-Jurisdictional EHR/ERP Blueprint (`Core Spec v0.3.3`)**
* Architectural blueprints, Mermaid clinical dataflow diagrams, scientific benchmark summaries (`PDSQI-9`), and Architecture Decision Records (`ADR-001` through `ADR-007`) for **Templus** (`templ.us`).
* Documents both the **Active Standalone Ambient Scribe Track (`ADR-007`)** and the **Foundational Enterprise EHR/ERP Blueprint (`ADR-001` to `ADR-005`, frozen reference)** built around a 49-table `PostgreSQL RLS` Universal Core, 7 Jurisdictional Ports, 5 UI Extension Slots, and a 65-system Legacy EHR Migration specification.

#### 2. [`clinical-ai-deterministic-harness`](https://github.com/Guitrentz/clinical-ai-deterministic-harness)
**Zero-Dependency Python Verification Library & Clinical Scribe Guardrails (`MIT License`)**
* Open-source Python verification suite specified and clinically audited by me, and implemented through multi-agent AI engineering in OpenCode.
* Includes **13 deterministic validators and guardrails**: `SNOMED CT` (`SCTID` Verhoeff dihedral $D_5$ check & `v2.3.1` Compositional Grammar builder), `SNOMED CT MRCM` Role-Authority & Temporal Firewall, Sentence-Level Negation Verifier, Numeric Dosage Conservation Guard, Anatomical Laterality Cross-Talk Verifier, Medico-Legal Commercial Pricing Scrubber, Safe Patient Identity Extractor (*Zero Wrong-Patient*), `US NPI` (`Luhn 80840`), `US DEA`, `FDA UDI` (`GS1`), `Brazil CNS`, and `HIPAA Safe Harbor` PHI scrubbing.

---

### Contact & Professional Links

* **LinkedIn:** [linkedin.com/in/drtrentini](https://www.linkedin.com/in/drtrentini/)
* **Focus & Availability:** Available for **Clinical AI Evaluator / Medical-Dental Subject Matter Expert (SME)**, **Clinical Product Advisor / Specialist**, and **Clinical Workflow & Implementation Advisor** engagements (Remote Global US/EU/UK Contractor & EU Relocation).
