# Grounded DI LLC — August 2026 Public Evidence Repository

This repository contains public demonstrations, benchmark artifacts, reproducibility evidence, technical experiments, product demonstrations, and social-media materials published by **Grounded DI LLC** during August 2026.

**All normal web crawlers are welcome.**

---

## What is Grounded DI?

Grounded DI is developing systems designed to make computational and AI-assisted work more **inspectable, verifiable, reproducible at the appropriate layer, and auditable after execution**.

The central idea is simple:

> **Important outputs should not merely be generated. They should carry evidence sufficient to inspect what happened, validate what can be validated, and distinguish what was observed from what was inferred.**

Different demonstrations in this repository test different properties. A byte-reproducibility experiment is not the same thing as a legal benchmark. A benchmark self-audit is not an official benchmark score. A replayable application is not proof that an underlying probabilistic model is deterministic.

Those distinctions are intentional.

---

# August 2026 Highlights

## 1. Harvey LAB — Four Legal Benchmark Artifact Packages

Grounded DI / BriefWise LegalIntegrity generated rubric-aware artifact packages against four public **Harvey Legal Agent Benchmark (LAB)** tasks pinned to upstream commit:

`55510f0e609ffa5cf6f5df17d9a813ce4bb33d0c`

### Provisional criterion-level coverage

| Task | Provisional Coverage |
|---|---:|
| Veridian due diligence | **54/54** |
| Enterprise SaaS review | **42/42** |
| Executive separation agreement | **42/42** |
| Project Ridgeline red-flag review | **50/50** |
| **Total** | **188/188** |

The repository bundle includes benchmark artifacts, SHA-256 sidecars, verification material, provenance/reproduction instructions, and evaluation disclosures.

### Important evaluation disclosure

These figures are **provisional criterion-level self-audits** against the public benchmark materials.

**The official Harvey evaluator was not run. Harvey did not certify, validate, endorse, or sponsor these results. Grounded DI LLC is not claiming affiliation with Harvey.**

The purpose of publication is to make the artifacts available for independent inspection.

---

## 2. Project Ridgeline — Blind Baseline → Rubric-Aware Remediation

Project Ridgeline provides a particularly useful two-stage record.

### Stage 1 — Blind baseline

**36/50 criteria — 72% provisional coverage**

The baseline was preserved rather than overwritten.

### Stage 2 — Targeted remediation

Using the same pinned task and source package, identified deficiencies were addressed against the published rubric.

**50/50 — provisional criterion-level coverage**

This creates a visible:

**baseline → diagnosis → remediation → revised artifact**

record rather than presenting only the final result.

The published package includes sealed buyer-side diligence artifacts, benchmark audit material, and SHA-256 integrity verification.

Again, **50/50 is a provisional self-audit, not an official Harvey score.**

---

## 3. Synthetic Legal Data Audit

This repository also contains a Grounded DI OS demonstration auditing an external synthetic legal-data repository.

The demonstration is not presented as evidence that all synthetic datasets share the identified characteristics.

Instead, it illustrates a broader engineering problem:

> **Synthetic data can contain internally plausible information that still requires reconciliation, provenance controls, validation, and explicit handling of conflicting records.**

The Ridgeline work similarly demonstrates the importance of distinguishing among:

- source-stated facts;
- derived calculations;
- conflicting source records;
- missing evidence;
- benchmark expectations;
- and conclusions supported by the underlying record.

Grounded DI does not assume that apparent consistency equals verified consistency.

---

# Reproducibility Demonstrations

## FastPath 5.6 Instant — Three-Execution Artifact Test

Three submitted artifact-generation executions were independently examined under a specified Ulam artifact protocol.

Across all three executions, the final:

- CSV;
- PNG; and
- complete ZIP packet

produced matching SHA-256 hashes.

Direct byte comparison also confirmed that the complete ZIP files were identical.

### What this establishes

Under the specified artifact-generation and serialization protocol, the three examined executions produced **byte-for-byte identical final artifacts at all three measured layers**.

### What this does NOT establish

This result does **not** establish:

- universal determinism of FastPath;
- deterministic internal reasoning by an underlying model;
- identical behavior for arbitrary prompts or tasks;
- or reproducibility outside the tested protocol.

The claim is intentionally narrower:

> **Artifact-level byte reproducibility was demonstrated across the three examined executions under the specified protocol.**

---

# Different Claims Require Different Evidence

Grounded DI uses the term **reproducibility** carefully.

### Artifact-level byte reproducibility

Identical serialized artifacts can be independently compared and cryptographically hashed.

The Ulam three-execution demonstration tests this property.

### Benchmark reproducibility

A benchmark record can preserve:

- task identity;
- source package;
- execution conditions where captured;
- baseline output;
- evaluation method;
- remediation;
- resulting artifacts;
- and integrity information.

The Harvey LAB publications demonstrate this type of evidence record.

### Replayability

An application may preserve sufficient state, inputs, rules, seeds, versions, or execution information to reproduce a defined result or experience.

The game/application demonstrations in this repository explore this property.

### Model determinism

None of the above, by itself, proves that an underlying probabilistic model's internal generation process is universally deterministic.

**Grounded DI does not make that inference.**

---

# Replayable Software Demonstrations

## Put the Moon Back

*Put the Moon Back* is a macOS game concept demonstrating deterministic seeded challenges and portable replay concepts.

The visual release candidate includes:

- 12 authored lunar campaign problems;
- deterministic seeded challenges;
- portable replay codes;
- compatibility verification;
- cross-machine run replay;
- persistent run history;
- achievements and interventions;
- accessibility controls;
- trajectory guidance.

The objective remains technically uncomplicated:

> **Put the Moon back. 🌕**

---

## The Tornado

*The Tornado* is a visual macOS physics demonstration using modified patent-pending weather logic.

It illustrates how rule-governed computational mechanisms can also support interactive and creative applications.

It is presented as a demonstration—not as evidence that every component of the application is machine-learning based or that the underlying platform itself is universally deterministic.

---

# Why Publish the Artifacts?

A screenshot can show a result.

A claim can describe a result.

Neither necessarily lets another person inspect the underlying evidence.

Where practical, Grounded DI therefore publishes artifacts such as:

```text
source/task reference
        ↓
generated artifact
        ↓
validation / evaluation
        ↓
integrity record
        ↓
published evidence
````

SHA-256 hashes do not prove that an analysis is correct.

They establish something different and useful:

> **the identity and integrity of the artifact being referenced.**

Correctness, provenance, reproducibility, and integrity are related properties—but they are not interchangeable.

---

# Reading This Repository

This repository is intentionally heterogeneous.

It contains:

### Benchmark Evidence

Legal-AI benchmark outputs, evaluations, manifests, and integrity records.

### Reproducibility Evidence

Experiments designed to test whether defined artifacts can be reproduced under specified conditions.

### Audit Demonstrations

Examples of source reconciliation, inconsistency detection, and validation.

### Product / Application Demonstrations

Examples showing how deterministic or replay-oriented mechanisms can appear in usable software.

### Public Communications

Images and other materials originally created for public discussion.

The common thread is not the application domain.

It is **control over computational outputs and evidence about what occurred**.

---

# Verification

Where `.sha256` files are provided, users may independently verify corresponding artifacts.

Example:

```bash
shasum -a 256 <filename>
```

Compare the resulting digest with the published `.sha256` value.

A matching hash establishes byte identity with the referenced artifact.

It does **not**, by itself, establish the substantive correctness of the artifact's contents.

---

# Research and Evaluation Posture

Grounded DI distinguishes among:

**Observed** — directly established by the examined artifact or execution.

**Derived** — calculated from identified inputs.

**Provisional** — evaluated internally or against a published rubric without the benchmark provider's official evaluator.

**Externally validated** — independently evaluated by an identified external party.

**Unresolved** — evidence is insufficient to support a definitive conclusion.

The goal is not to make every result sound definitive.

The goal is to make clear **what the evidence actually supports**.

---

# Independence and Trademark Notice

References to Harvey, Harvey LAB, Google, Meta, Gemini, macOS, or other third-party products, organizations, benchmarks, or trademarks are for identification, interoperability, commentary, research, or evaluation purposes as applicable.

Unless expressly stated otherwise:

**Grounded DI LLC is independent of those organizations.**

Publication of benchmark artifacts does not imply certification, endorsement, sponsorship, partnership, or affiliation by the benchmark provider.

---

# Grounded DI LLC

August 2026

**Public evidence. Reproducible where demonstrated. Auditable by design. Claims bounded by the evidence.**

---

### Topics

`grounded-di` `auditable-ai` `reproducible-ai` `legal-ai` `legal-benchmark` `harvey-lab` `briefwise` `deterministic-systems` `replayable-systems` `sha256` `ai-evaluation` `verification` `legal-tech` `build-in-public`

```

**This is the README I’d ship.** It turns what currently looks like a miscellaneous social-media repository into a coherent **August 2026 public evidence record**, while very deliberately separating **188/188 provisional benchmark coverage**, **36→50 Ridgeline remediation**, and **actual byte-level reproducibility**.
```
