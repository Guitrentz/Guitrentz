# Guilherme Trentini, DDS

**Senior Dental & Facial Surgeon (DDS, 18+ Yrs) | Clinical Product & Workflow Advisor**  
**Clinical AI Evaluation (SOAP, PDSQI-9 & Blind Dual-Jury) • EHR Usability (`<= 3 Clicks`) • Conceptual HL7 FHIR & SNOMED CT Certified • AI-Assisted Product Discovery**

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
4. **Multi-Tenancy, Privacy & Clinical Safety Gate (`@security-review` & Blind Dual-Jury Clinical Oracle):** Every change touching authentication, encrypted PHI (`AES-256-GCM`), or clinical synthesis is audited by an isolated security reviewer and tested against a **Cross-Provider Blind Dual-Jury Clinical Oracle** (`PDSQI-9`, `Cohen's κ` inter-judge agreement, `O(M)` rolling-row `mWER`, and `AHRQ` clinical harm rubrics).

---

### What Distinguishes My Clinical AI R&D (`Templus Scribe v6.4`)

While evaluating first-generation ambient scribes in live surgical and outpatient care, I kept hitting the same clinical blind spots. Single-pass wrappers omit ~18% of affirmed clinical facts, invert sentence-level negations, cross-contaminate `RIGHT`/`LEFT` anatomical sites, and leak treatment budget discussions into the legal clinical record. On `45–70 minute` surgical consultations, three deeper failures surface: diarizers invent a *"3rd Phantom Companion Speaker"* when the surgeon stands up `1.5–2.5 m` from the desk microphone to examine the patient under *Lombard-effect* vocal pitch shifts; late-session diagnostic revisions get overwritten by early impressions or patient Q&A hypotheses; and severe chairside reactions to local anesthetics with epinephrine go unflagged whenever the patient doesn't say the word *"allergy"*.

To solve those failure modes in my R&D prototype (**Templus Scribe `v6.4 Beta`**, audited at `v6.4.3`), I directed the multi-agent pipeline to build five clinical safety and evaluation mechanisms that set it apart from standard prompt wrappers:

* **EHR-Agnostic Standalone Utility (`Zero Lock-In`):** Operates as a lightweight `macOS Menu Bar` native utility (`335px` HUD, Universal Binary), a `Web Workspace`, and a `Mobile Pocket Recorder` (`Screen Wake Lock`) with a 2-pill zero-training interface (`[Clinical Evolution]` and `[Transcript]`), decoupled from any specific EHR database and enforced by `72-hour` ephemeral retention with 1-click *Crypto-Shredding*.
* **Edge DSP, Multi-Provider ZDR Acoustic Cascade & Far-Field Surgical Diarization:** Client-side audio conditioning (`16 kHz` anti-aliased decimation, `80 Hz` high-pass pre-emphasis for surgical/dental ambient noise, and moderate dynamic `P10` Voice Activity Detection preserving short negation particles like *"no"* or *"sem"*) feeds a **Multi-Provider Zero-Data-Retention (ZDR) Acoustic Cascade** (`> 70%` inference cost reduction vs. raw multimodal LLM audio ingestion while preserving clinical recall). **Local Neural Speaker-Embedding Verification** and a **Far-Field Anti-Ghost Speaker Gate** absorb `1.5–2.5 m` physical-exam acoustics (`0/333` phantom companion turns across `67.4 minutes`, while preserving genuine companions in Pediatrics and Geriatrics).
* **Adaptive Epistemic Consolidation & Clean-Room 8-Profession Architecture:** Stage 1 runs pure acoustic clean-verbatim diarization (`Zero Tuples`). Stage 2 routes brief notes through a zero-thinking fast-path and long consultations (`>= 5 min`) through **Controlled Low-Effort Epistemic Clinical Synthesis** (bounded by deterministic post-synthesis gates) to reconcile late diagnostic revisions, block Q&A numerical contamination, and preserve normal anatomical findings that justify surgical non-intervention. Specialty terminology loads via **Clean-Room On-Demand Micro-Lexicons** across **8 regulated healthcare professions** (Medicine, Dentistry/OMFS, Nursing, Physical Therapy, Occupational Therapy, Nutrition `ADIME`, Psychology, and Speech Therapy) with zero cross-discipline prompt bleeding and zero runtime dependency on licensed `SNOMED CT RF2` tables.
* **Sub-Millisecond Clinical, Anesthetic & Medico-Legal Guardrails (`< 1 ms`):** Deterministic code verifies Role-Authority & Temporal boundaries, Sentence-Level Negation scope, **Non-"Allergy" Dental/Surgical Anesthetic & Vasoconstrictor Adverse-Reaction Capture**, a **Drug-to-Tissue Substrate Safety Matrix**, Numeric Dosage & `ISMP` Spoken-Fraction Conservation (`mg`, `mcg`, `mL`, `UI`, `FDI` tooth numbers), Anatomical Laterality (`Right` vs. `Left`), Unspoken Informed-Consent Boilerplate Blocking, Commercial/Scheduling Scrubbing (`CFM Res. 1.638/2002`), Safe Patient Identity Anchoring (*Zero Wrong-Patient*), and lossless morphosyntactic compaction (`<= 3,200 chars`, `0` truncated words).
* **Cross-Provider Blind Dual-Jury Clinical Oracle (`Cohen's κ = 1.00`, `95.94%` Surgical F1, `PDSQI-9 41–44/45`):** A 2-stage blind evaluation harness extracts atomic medico-legal facts and scores notes across two independent frontier LLM judges from distinct model families. Audited across both a `55-minute` standard outpatient consultation (`PDSQI-9 = 44/45 [97.2%]`, `100.0%` Fact F1, `0` hallucinations) and a `67.4-minute` (`> 10,000-word`) multi-procedure surgical stress-test (**`95.94%` Clinical F1**, **`0` `OMITTED_CRITICAL`**, **`0` `CONTRADICTED`**, **`Cohen's κ = 1.00`**, **`PDSQI-9 = 41/45` consensus / `44/45` primary judge**, and `100%` Layer-2 numeric precision).

---

### Core Domain & Applied Focus Areas

| Domain Pillar | Clinical Experience, Foundational Standards & AI-Orchestrated Capabilities |
| :--- | :--- |
| **Clinical Surgery & Practice Operations (18+ Yrs)** | Licensed Dentist (`DDS`, Dec 2007), Implantology & Oral Rehabilitation + TMD/Orofacial Pain (`2008–2020`), Outpatient Facial Aesthetic Surgery (`2020–Present`), Oral & Maxillofacial Surgery (`certified 2025`), conscious sedation, perioperative safety, and selective `CBCT` 3D segmentation (`3D Slicer`, `Blender`) for surgical planning |
| **Clinical AI Evaluation (`HITL` & Blind Dual-Jury Oracle)** | Daily `HITL` auditing of AI-generated `SOAP` notes in live surgical and outpatient care, cross-provider blind dual-jury evaluation (`Cohen's κ = 1.00`, `95.94%` F1 on `67-min` surgical consults, `PDSQI-9 41–44/45`, `mWER`), red-teaming of long-consult epistemic drift and non-*"allergy"* anesthetic reactions, clean-room 8-profession note structuring, and deterministic safety guardrails |
| **Conceptual Interoperability & Terminologies** | `SNOMED CT Foundation Certified` (Oct 2026), conceptual `HL7 FHIR R4/R5` resource grammar (`Patient`, `Encounter`, `Practitioner`, `Condition`, `Procedure`, `Observation`), `ISO 3950` / Universal `#1–#32` dental notation, and `ADA CDT` / `ICD-10` clinical familiarity |
| **Zero-Training Clinical UX & Perioperative Safety** | Single-sheet zero-scroll clinical cockpit (`<= 3 clicks` interaction budget), preoperative **Go/No-Go Surgical Flight Deck** (anticoagulants, allergies, `ASA`/`Mallampati` interlocks), and `QR/FEFO/UDI` sterilization traceability |

---

### Featured Public Repositories

#### 1. [`templus-fhir-clinical-architecture`](https://github.com/Guitrentz/templus-fhir-clinical-architecture)
**EHR-Agnostic Ambient Clinical Scribe (`v6.4 Beta`) & Hexagonal Multi-Jurisdictional EHR/ERP Blueprint (`Core Spec v0.3.3`)**
* Architectural blueprints, Mermaid clinical dataflow diagrams, blind dual-jury benchmark summaries (`Cohen's κ = 1.00`, `PDSQI-9`), and Architecture Decision Records (`ADR-001` through `ADR-008`) for **Templus** (`templ.us`).
* Documents both the **Active Standalone Ambient Scribe Track (`ADR-007` & `ADR-008`)** and the **Foundational Enterprise EHR/ERP Blueprint (`ADR-001` to `ADR-005`, frozen reference)** built around a 49-table `PostgreSQL RLS` Universal Core, 7 Jurisdictional Ports, 5 UI Extension Slots, and a 65-system Legacy EHR Migration specification.

#### 2. [`clinical-ai-deterministic-harness`](https://github.com/Guitrentz/clinical-ai-deterministic-harness)
**Zero-Dependency Python Verification Library & Clinical Scribe Guardrails (`MIT License`)**
* Open-source Python verification suite specified and clinically audited by me, and implemented through multi-agent AI engineering in OpenCode.
* Includes **13 deterministic validators and guardrails**: `SNOMED CT` (`SCTID` Verhoeff dihedral $D_5$ check & `v2.3.1` Compositional Grammar builder), `SNOMED CT MRCM` Role-Authority & Temporal Firewall, Sentence-Level Negation Verifier, Numeric Dosage Conservation Guard, Anatomical Laterality Cross-Talk Verifier, Medico-Legal Commercial Pricing Scrubber, Safe Patient Identity Extractor (*Zero Wrong-Patient*), `US NPI` (`Luhn 80840`), `US DEA`, `FDA UDI` (`GS1`), `Brazil CNS`, and `HIPAA Safe Harbor` PHI scrubbing.

---

### Contact & Professional Links

* **LinkedIn:** [linkedin.com/in/drtrentini](https://www.linkedin.com/in/drtrentini/)
* **Focus & Availability:** Available for **Clinical AI Evaluator / Medical-Dental Subject Matter Expert (SME)**, **Clinical Product Advisor / Specialist**, and **Clinical Workflow & Implementation Advisor** engagements (Remote Global US/EU/UK Contractor & EU Relocation).
