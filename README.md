# Guilherme Trentini, DDS

**Senior Dental & Facial Surgeon (DDS / Dentist, 18+ Yrs) | Clinical Product Lead & Health Informatics Practitioner**  
**HL7 FHIR & SNOMED CT (Foundational) • EHR Design • 3D Digital Surgery (CBCT/CAD-CAM) • Clinical AI Evaluator (SME)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-drtrentini-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/drtrentini/)
[![Templus Architecture](https://img.shields.io/badge/Architecture-Templus_FHIR_Core-0066CC?style=flat)](https://github.com/Guitrentz/templus-fhir-clinical-architecture)
[![Deterministic Harness](https://img.shields.io/badge/Open_Source-Clinical_AI_Harness-2EA44F?style=flat)](https://github.com/Guitrentz/clinical-ai-deterministic-harness)

---

### Executive Summary

I am a Senior Dental, Oral & Maxillofacial, and Facial Aesthetic Surgeon (**DDS / Dentist**, 18+ years of uninterrupted clinical and surgical practice; 5-Year First Professional Degree / EU EQF Level 7) operating at the intersection of **Clinical Product Leadership, Foundational Health Informatics, 3D Digital Surgery (`CBCT`, `CAD/CAM`), and Clinical AI Evaluation (`Subject Matter Expert / SME`)**.

After nearly two decades inside operating rooms and outpatient practices, I began designing an Electronic Health Record (EHR), Practice Management (PMS), and Clinical Decision Support (CDS) prototype (`templ.us`) aimed at reducing clinician cognitive load and enforcing perioperative patient safety.

---

### My Role & Methodology: Clinical Macro & Micromanagement of AI Agents

> **Important Note on My Technical Background:** I am **not** a career software developer, database administrator, or senior `HL7 FHIR` / data engineer. I am a practicing surgeon with a **foundational background in Health Informatics** (*SNOMED CT Foundation Certified*, 2026; actively studying and applying foundational *HL7 FHIR R4/R5* concepts) who builds clinical software by **directing autonomous AI coding agents (`Google Antigravity & Gemini`) through continuous macro and micromanagement**.

How I work in practice:
1. **Macro Direction (Clinical Vision & Standards Selection):** Drawing from 18+ years of chairside and surgical practice, I define what the clinical product must solve, establish the interaction rules (**Zero-Training Clinical UX**, `<= 3 clicks` budget, single-sheet zero-scroll charting, and a preoperative **Go/No-Go Surgical Flight Deck**), and instruct the AI agents to build upon international standards (`HL7 FHIR`, `SNOMED CT`, `ISO 3950`, `HIPAA`, `LGPD`) rather than ad-hoc proprietary tables.
2. **Micro Direction (Step-by-Step Auditing & Refinement):** Because I do not write the underlying SQL or Python code manually, I closely supervise and test every step of the AI's work—questioning clinical edge cases, auditing screen flows, verifying how clinical concepts map to `SNOMED CT` / `FHIR`, and iterating until the software behaves the way a real clinic operates.
3. **AI Guardrails Built by AI Under Clinical Supervision:** Recognizing how easily LLMs hallucinate medical/dental codes or leak patient data, I directed the AI engineering agents to implement and test an executable verification layer ([`clinical-ai-deterministic-harness`](https://github.com/Guitrentz/clinical-ai-deterministic-harness)) so that every AI-generated identifier (`SCTID`, `NPI`, `DEA`, `UDI`, `CNS`) is checked mathematically before reaching the database.

---

### Core Domain & Applied Focus Areas

| Domain Pillar | Clinical Experience, Foundational Standards & AI-Assisted Capabilities |
| :--- | :--- |
| **Clinical Surgery & Digital Dentistry (18+ Yrs)** | Licensed Dentist (`DDS`), Implantology & Oral Rehabilitation, TMD & Orofacial Pain (`2008–2020`), Facial Aesthetic Surgery (`6+ yrs`), Oral & Maxillofacial Surgery (`certified 2025`), `CBCT` 3D segmentation, and `CAD/CAM` surgical guide modeling (`Blender`, `3D Slicer`) |
| **Foundational Health Informatics** | `SNOMED CT Foundation Certified` (2026), foundational `HL7 FHIR R4/R5` resource concepts (`Patient`, `Encounter`, `Condition`, `Procedure`, `Observation`), `ISO 3950` / Universal `#1–#32` dental notation, and `ADA CDT` / `ICD-10` clinical familiarity |
| **Zero-Training Clinical UX & Safety** | Single-sheet zero-scroll clinical cockpit (`<= 3 clicks` budget), preoperative **Go/No-Go Surgical Flight Deck** (anticoagulants, allergies, ASA/Mallampati interlocks), and `QR/FEFO/UDI` autoclave sterilization traceability |
| **Clinical AI Evaluation (SME) & Governance** | Human-in-the-Loop (`HITL`) clinical AI evaluation, medical/dental LLM red-teaming, ambient voice-to-SOAP synthesis grounded in PubMed, and AI-generated deterministic validation harnesses (`HIPAA Safe Harbor`, `SCTID Verhoeff`, `NPI`, `UDI`) |

---

### Featured Public Repositories (AI-Engineered Under Clinical Direction)

#### 1. [`templus-fhir-clinical-architecture`](https://github.com/Guitrentz/templus-fhir-clinical-architecture)
**AI-Assisted Multi-Jurisdictional EHR/ERP Architecture, ADRs & Release Notes (Alpha v0.3.2)**
* Architectural blueprints, Mermaid workflow diagrams, and Architecture Decision Records (ADRs) for **Templus** (`templ.us`), an independent clinical R&D prototype.
* Demonstrates how a practicing surgeon can direct AI agents through macro and micromanagement to separate a **Universal Clinical Core** (`HL7 FHIR`, `SNOMED CT`, `ISO 3950`, `PostgreSQL RLS`) from pluggable **Country Packs** (`US` and `Brazil`), with **21 Atomic Units (`42 Paired Specifications`)** locked across Module 1 (Foundation & Zero-Trust Security) and Module 2 (Multi-Resource `GiST` Scheduling, Zero-PHI CRM & Post-Op Surgical Recall).

#### 2. [`clinical-ai-deterministic-harness`](https://github.com/Guitrentz/clinical-ai-deterministic-harness)
**Executable Python Validation Library & Guardrails for Clinical AI Systems (MIT License)**
* Open-source Python verification toolkit generated and tested via AI agents (`Google Antigravity`) under my clinical specification and supervision to prevent LLM hallucinations in healthcare software.
* Validates **SNOMED CT (`SCTID` Verhoeff checksum)**, **US National Provider Identifier (`NPI`)**, **US DEA Registration Numbers**, **FDA Unique Device Identification (`UDI` / GS1)**, **Brazilian National Health Card (`CNS`)**, and **`HIPAA Safe Harbor` PHI scrubbing**.

---

### Contact & Professional Links

* **LinkedIn:** [linkedin.com/in/drtrentini](https://www.linkedin.com/in/drtrentini/)
* **Availability:** Open to **Clinical Product Lead / Manager**, **Dental & Clinical AI Evaluator / Subject Matter Expert (SME)**, **Health Informatics Practitioner**, and **Clinical Implementation & Digital Surgery (CBCT/CAD-CAM) Specialist** opportunities (Remote US/EU/UK & EU Relocation).
