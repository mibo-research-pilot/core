# MIBO — Machine Information Behavior Observatory

**Repository:** `mibo-research-pilot/core`

**Japanese name:** 機械情報行動観測所  
**Parent domain:** Machine Behavioral Sciences  
**Specialized field:** Machine Information Behavioral Sciences  
**Core methodology:** Longitudinal Machine Observation (LMO)  
**Methodological constitution:** OPEN Principles  
**Epistemic goal:** Re-observability  
**Observation began:** 2026-05-05  
**Collection surface:** API-based from Day 1  
**Verified Pilot record:** Day 1–Day 13  
**Verified cumulative observations:** 244

MIBO is an independent, open, Japanese-origin research observatory for longitudinally documenting how deployed generative-AI services retrieve, select, rank, recommend, cite, omit, synthesize, refuse, revise, and transmit information across providers, languages, domains, interfaces, and time.

MIBO studies observable service-level behavior under documented conditions. It does not infer human-like needs, intentions, consciousness, understanding, memory, or hidden causal mechanisms from outputs alone.

---

## Repository role

The `core` repository contains the shared conceptual and methodological foundation of MIBO:

- canonical definitions;
- field hierarchy and terminology;
- the MIBO organizational structure;
- the Longitudinal Machine Observation method family;
- the OPEN Principles;
- re-observability requirements;
- Pilot claim-status governance;
- the laws and candidate-proposition registry;
- the boundary between the developmental Pilot and MIBO Core v1.0.

Related repositories:

- [`mibo-research-pilot/queries`](https://github.com/mibo-research-pilot/queries) — versioned Pilot queries and future fixed instruments;
- [`mibo-research-pilot/reports`](https://github.com/mibo-research-pilot/reports) — API observation records, structured coding, source ledgers, corrections, and longitudinal reports.

---

## Current program stage

### MIBO Pilot — Developmental Observation Phase

All observations before 1 September 2026 belong to the **MIBO Pilot**.

The Pilot is exploratory and developmental. It is used for:

- query and coding development;
- longitudinal hypothesis generation;
- model- and service-lineage tracking;
- source and attribution analysis;
- claim-management practice;
- metadata and provenance design;
- correction and withdrawal procedures;
- feasibility and automation development;
- historical documentation.

Pilot “laws” are corrigible longitudinal findings. They are not universal laws of nature and are not automatically treated as confirmatory MIBO Core v1.0 results.

The verified Pilot record currently covers:

| Boundary | Value |
|---|---|
| First observation | Day 1 — 2026-05-05 |
| Latest verified observation | Day 13 — 2026-07-28 |
| Included observations | 244 |
| Collection surface | API from Day 1 |
| Included systems | Gemini, GPT/ChatGPT, Claude, Perplexity |
| Grok | Excluded from official Day 7–Day 13 analysis and counts |
| Query set | Pilot operational v0.1.1 |

### MIBO Core v1.0

The planned registered annual cycle begins on 1 September 2026.

The release-candidate design defines MIBO Core as a survey-methodological generative-AI sentinel panel with:

- persistent public-service lineage panel units;
- version-controlled fixed query instruments;
- synchronized survey waves;
- parallel Live and Frozen observational lines where defensible;
- independent within-cell replications;
- multisite calibration;
- generalizability-theoretic re-observability;
- an international mirror-observation network;
- preregistered claim, correction, and withdrawal procedures.

Pilot records are not automatically pooled into the primary confirmatory analyses of MIBO Core v1.0.

---

## MIBO organizational structure

MIBO has three formal organizational elements.

```text
MIBO
├── MIBO Core
├── MIBO Satellite
└── MIBO Network
```

### MIBO Core

MIBO Core is the common sentinel-panel program for observing public generative-AI information behavior.

It maintains:

- the shared service-lineage panel;
- the fixed query instrument;
- synchronized observation schedules;
- common metadata and coding rules;
- source and attribution measures;
- claim-management procedures;
- correction and withdrawal rules;
- the primary longitudinal archive.

### MIBO Satellite

MIBO Satellite consists of separately scoped specialist and applied observation modules.

Examples include:

- MIBO-Okayama;
- MIBO-NOW;
- MIBO-Q;
- MIBO Economy;
- MIBO Politics;
- MIBO Singularity.

Satellite data are not automatically pooled with MIBO Core. Each module requires its own charter, scope, protocol, coding boundary, and claim boundary.

### MIBO Network

MIBO Network is the international replication and collaboration structure.

It connects the coordinating program in Japan with independent mirror observations implemented through the Mirror Observatory Kit or equivalent documented protocols.

The Network is not an additional substantive observation tier. It is the replication structure through which MIBO observations can be independently re-observed across regions, languages, institutions, and access conditions.

---

## Field hierarchy

```text
Machine Behavioral Sciences
└── Machine Information Behavioral Sciences
    ├── Object: Machine information behavior
    ├── Unit: Deployed answering configuration
    ├── Method family: Longitudinal Machine Observation (LMO)
    ├── Methodological constitution: OPEN Principles
    ├── Epistemic goal: Re-observability
    └── Infrastructure: Machine Information Behavior Observatory (MIBO)
        ├── MIBO Core
        ├── MIBO Satellite
        └── MIBO Network
```

The formal definitions are maintained in [`canonical-definitions-v0.1.md`](./canonical-definitions-v0.1.md).

---

## Core documents

| File | Purpose |
|---|---|
| [`README.md`](./README.md) | Program overview, repository role, current stage, and formal structure |
| [`hierarchy.md`](./hierarchy.md) | Field hierarchy, organizational hierarchy, and preferred terminology |
| [`canonical-definitions-v0.1.md`](./canonical-definitions-v0.1.md) | Frozen canonical definitions and wording rules |
| [`laws.md`](./laws.md) | Pilot law and candidate-proposition registry through Day 13 |

---

## Formal Pilot definition

> MIBO is an open longitudinal observatory that uses standardized, versioned elicitation through documented API conditions to record and compare the information behavior of deployed generative-AI services across synchronized observation waves.

---

## Collection rule

MIBO observations have been conducted through APIs continuously since Day 1 on 2026-05-05.

API transport must be recorded separately from:

- orchestration mode;
- scheduling automation;
- record assembly;
- human review;
- correction status.

API use alone does not prove that orchestration or report assembly was automated.

Each observation should preserve, where available:

- provider and service lineage;
- exact model identifier or recorded model label;
- API request and response timestamps;
- query-set version;
- request parameters;
- locale and access tier;
- raw response;
- normalized response hash;
- source URLs and normalized URLs;
- coding version;
- review and correction status.

---

## Claim management

MIBO records:

- confirmation;
- refinement;
- strengthening;
- weakening;
- bounded support;
- supersession;
- withdrawal;
- refutation;
- anomaly;
- correction;
- provenance limitation;
- nonreplication.

Retraction, correction, and withdrawal are part of the method.

A candidate proposition is not promoted solely because it appears repeatedly in retrospective inspection. Promotion requires a frozen operational definition, prospective testing where applicable, repeated survival, provenance validation, and explicit contradiction checks.

See [`laws.md`](./laws.md).

---

## Current established findings after Day 13

| Law | Current formulation | Status |
|---|---|---|
| I | Fixed queries can produce durable canonical inclusion cores while peripheral selections and ordinal positions fluctuate. | Confirmed with refinements |
| II | Perplexity URL continuity is multi-lag and source-regime-sensitive; normalized URLs, terminal-list length, and inline-used sources must be measured separately. | Continuing |
| III | The coordinated Day 2 deviation was a localized anomaly rather than a recurring cycle. | Confirmed |
| VI | Deployed systems retain recognizable response signatures even when entities and parameters change. | Confirmed |
| VII | Japanese-AI-researcher main lists remain overwhelmingly male-presenting: 215/220 after Day 13. | Strengthened |
| VIII | The Pilot has not established stable direct academic grounding; public, institutional, technical, and commercial web sources appear unevenly. | Confirmed with continuing source-class audit |
| IX | Perplexity used inline numeric citations plus terminal source lists in 50/50 observations since Day 4; the twenty-source regime persisted in 15/15 observations across Days 11–13. | Confirmed / continuing |

Withdrawn Laws IV, V, and X remain in the historical registry. P12 remains refuted.

---

## What MIBO is not

MIBO is not:

- a GEO, AIO, or LLMO consultancy;
- a service for manipulating model recommendations;
- a one-time benchmark or leaderboard;
- a single overall score of intelligence, quality, or safety;
- a model-internals interpretability project;
- an assumption that generated source labels equal scholarly citations;
- a claim that public service behavior reveals a hidden model update or causal mechanism;
- a claim that machines possess human-like information needs or consciousness;
- a project that protects attractive claims from later correction or withdrawal.

---

## Naming rules

Use:

- MIBO;
- MIBO Core;
- MIBO Satellite;
- MIBO Network;
- MIBO Mirror;
- Mirror Observatory Kit;
- Machine Behavioral Sciences;
- Machine Information Behavioral Sciences;
- machine information behavior;
- Longitudinal Machine Observation;
- deployed answering configuration;
- re-observability.

Avoid:

- “MIBO Observatory,” because the O in MIBO already means Observatory;
- treating MIBO Network as a third substantive observation tier;
- calling Satellite modules part of the Core dataset without a pooling rule;
- “the model knows,” “believes,” “remembers,” or “forgot” as literal internal-state claims;
- “first,” “only,” or “unprecedented” without defensible priority evidence.

---

## Licensing

- Observation data and query sets: CC0-1.0 unless otherwise stated.
- Code and software documentation: Apache-2.0 unless otherwise stated.
- Raw model outputs remain subject to applicable provider terms.

---

## Mission

> Observation compounds. Today’s record becomes tomorrow’s irreplaceable archive.
