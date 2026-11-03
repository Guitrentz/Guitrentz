# Guilherme Trentini, DDS

**Senior Dental & Facial Surgeon (DDS / Dentist, 18+ Yrs) | Clinical Product Lead & Health Informatics Practitioner**  
**HL7 FHIR R4/R5 • SNOMED CT Certified • EHR Design • 3D Digital Surgery (CBCT/CAD-CAM) • Clinical AI Evaluator (SME)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-drtrentini-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/drtrentini/)
[![Templus Architecture](https://img.shields.io/badge/Architecture-Templus_FHIR_Core-0066CC?style=flat)](https://github.com/Guitrentz/templus-fhir-clinical-architecture)
[![Deterministic Harness](https://img.shields.io/badge/Open_Source-Clinical_AI_Harness-2EA44F?style=flat)](https://github.com/Guitrentz/clinical-ai-deterministic-harness)

---

### Executive Summary

I am a Senior Dental, Oral & Maxillofacial, and Facial Aesthetic Surgeon (**DDS / Dentist**, 18+ years of uninterrupted clinical and surgical practice; 5-Year First Professional Degree / EU EQF Level 7) operating at the intersection of **Clinical Product Leadership, Health Informatics, 3D Digital Surgery (`CBCT`, `CAD/CAM`), and Clinical AI Evaluation (`Subject Matter Expert / SME`)**.

After nearly two decades inside operating rooms and multi-disciplinary outpatient practices, I transitioned into designing next-generation Electronic Health Record (EHR), Practice Management (ERP), and Clinical Decision Support (CDS) architectures that eliminate clinician burnout and enforce perioperative patient safety at the data layer.

---

### My Role & Methodology: Specification-Driven Agentic Engineering

I do not write boilerplate application code line by line in the traditional career software developer model. Instead, I operate as a **Clinical Product Lead and Health Informatics Architect**:

1. **Clinical & Regulatory Specification:** I author the clinical domain models, semantic terminology bindings (`HL7 FHIR R4/R5`, `SNOMED CT`, `LOINC`, `ICD-10`, `ADA CDT`, `AMA CPT`, `ISO 3950`), perioperative safety workflows, and multi-jurisdictional compliance gates (`HIPAA`, `FDA Non-Device CDS`, `EU MDR`, `ANVISA SaMD`).
2. **Zero-Training Clinical UX Design:** I design clinical interfaces governed by a strict **<= 3 clicks interaction budget** and a **single-sheet zero-scroll clinical cockpit**, paired with a **Perioperative Surgical Safety (Go/No-Go Flight Deck)** that prevents clinical oversight before anesthesia or incision.
3. **Agentic AI Orchestration (`Google Antigravity & Gemini`):** I direct autonomous AI engineering agents to implement database schemas, interoperability pipelines, and test suites against my specifications.
4. **Deterministic Clinical Guardrails:** Every AI-generated output and clinical identifier is verified through an executable **Deterministic Clinical Harness** (algorithmic checksums for `SNOMED CT` Verhoeff digits, `US NPI`, `DEA`, `FDA UDI`, `HIPAA Safe Harbor` de-identification, and static AST/SAST security gates) to prevent terminology hallucinations and protect patient safety.

---

### Core Domain & Technical Pillars

| Domain Pillar | Standards, Frameworks & Applied Capabilities |
| :--- | :--- |
| **Clinical Interoperability & Ontologies** | `HL7 FHIR R4 & R5` (`US Core`, `SMART on FHIR`), `SNOMED CT` (Foundation Certified, ECL v2.0, MRCM, RF2), `LOINC`, `ICD-10-CM`, `ADA CDT`, `AMA CPT`, `ISO 3950` Dental & Craniofacial Notation |
| **Clinical UX & Perioperative Safety** | **Zero-Training Clinical UX** (`<= 3 clicks` interaction budget, single-sheet zero-scroll cockpit), **Perioperative Surgical Safety** (Go/No-Go Flight Deck, ASA/Mallampati/allergy interlocks, sterile implant & graft QR/FEFO lot tracking) |
| **Regulatory & Privacy Engineering** | `HIPAA Safe Harbor` & Security Rule, `ONC Health IT Certification` criteria, `FDA Non-Device CDS` (21st Century Cures Act Section 3060), `EU MDR` Class IIa/IIb principles, `LGPD` / `ANVISA RDC 657` / `ICP-Brasil` |
| **Multi-Tenant Data Architecture** | Hexagonal **Universal Core + Pluggable Country Packs** (`us-pack`, `eu-pack`, `br-pack`), `PostgreSQL Row-Level Security (RLS)` tenant isolation, immutable audit trails, and deterministic legacy EHR migration (`Dry-Run` + `1-Click Rollback`) |

---

### Featured Public Repositories

#### 1. [`templus-fhir-clinical-architecture`](https://github.com/Guitrentz/templus-fhir-clinical-architecture)
**Hexagonal Multi-Jurisdictional EHR/ERP Architecture, ADRs & Release Notes (Alpha v0.3.0)**
> While already developing our clinical platform under a country-specific lens, I saw that local rules inside the core blocked global interoperability. I decided to start from zero around a Universal Core with pluggable Country Packs. Using step-by-step AI orchestration and deterministic guardrails, I anchored the core on HL7 FHIR and SNOMED CT, locking a 49-table universal blueprint and a 65-system migration spec before writing code.
* Public architectural documentation, Mermaid system diagrams, and Architecture Decision Records (ADRs) for **Templus** (`templ.us`), a next-generation multi-disciplinary medical, surgical, and dental EHR/ERP platform.
* Details the **7 Jurisdictional Hexagonal Ports** and **5 UI Extension Slots** that allow a single agnostic clinical core to run across US (`HIPAA`, `US Core`, `FDA CDS`, `CDT/CPT`), European (`GDPR`, `EU MDR`), and Brazilian (`LGPD`, `ANVISA`, `ICP-Brasil`, `RNDS/TISS`) regulatory environments without polluting core domain logic.

#### 2. [`clinical-ai-deterministic-harness`](https://github.com/Guitrentz/clinical-ai-deterministic-harness)
**Executable Python Validation Library & Guardrails for Clinical AI Systems (MIT License)**
* Open-source Python verification toolkit designed to prevent LLM hallucinations in clinical software and Ambient Clinical Scribe pipelines.
* Includes zero-dependency algorithmic validators for **SNOMED CT (`SCTID` Verhoeff checksum)**, **US National Provider Identifier (`NPI` Luhn 80840)**, **US DEA Registration Numbers**, **FDA Unique Device Identification (`UDI` / GS1)**, **Brazilian National Health Card (`CNS`)**, and a deterministic **`HIPAA Safe Harbor` PHI Scrubber**, backed by automated `pytest` CI workflows.

---

### Contact & Professional Links

* **LinkedIn:** [linkedin.com/in/drtrentini](https://www.linkedin.com/in/drtrentini/)
* **Availability:** Open to **Clinical Product Lead / Manager**, **Dental & Clinical AI Evaluator / Subject Matter Expert (SME)**, **Health Informatics Practitioner**, and **Clinical Implementation & Digital Surgery (CBCT/CAD-CAM) Specialist** opportunities (Remote US/EU/UK & EU Relocation).
