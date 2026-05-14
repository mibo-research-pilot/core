# MIBO — Machine Information Behavior Observatory

**Japanese name:** 機械情報行動観測所  
**Observation began:** 2026-05-05  
**Parent domain:** Machine Behavioral Sciences  
**Specialized field:** Machine Information Behavioral Sciences  
**Core methodology:** Longitudinal Machine Observation (LMO)  
**Initial research focus:** source-attribution and citation-like behavior in generative AI systems

MIBO is an open research observatory for studying how generative AI systems retrieve, select, cite, recommend, omit, synthesize, transmit, and forget information over time.

## Field hierarchy

```text
Machine Behavioral Sciences
└── Machine Information Behavioral Sciences
    ├── Longitudinal Machine Observation (LMO)
    ├── source-attribution and citation-like behavior
    └── Machine Information Behavior Observatory (MIBO)
```

**Machine Behavioral Sciences** is the umbrella domain for studying machines and AI systems as observable behavioral entities.

**Machine Information Behavioral Sciences** is a specialized field within Machine Behavioral Sciences. It studies how machines behave as information agents: how they retrieve, select, cite, rank, recommend, omit, synthesize, transmit, and forget information.

**MIBO** is the public observatory that operationalizes this field.

## Why MIBO exists

Generative AI systems increasingly act as information intermediaries. Users ask them which tools to use, which sources to trust, which health practices to follow, and which organizations or documents matter. These systems therefore shape information visibility.

SEO and GEO ask:

> How can content become visible to search engines or generative engines?

MIBO asks:

> How do generative AI systems select, cite, recommend, omit, and transmit information over time?

The difference is a shift from **optimization** to **observation**.

## Method: Longitudinal Machine Observation

MIBO uses **Longitudinal Machine Observation (LMO)**.

LMO is best described as:

> standardized longitudinal elicitation and observation

MIBO is not purely passive observation. It uses standardized queries to elicit comparable responses from multiple AI systems, then records those responses over time. This makes it possible to study changes caused by model updates, retrieval behavior, interface changes, and shifts in the information ecosystem.

## Initial research focus

MIBO first studies **source-attribution and citation-like behavior**.

This wording is intentional. Generative AI citations are not identical to scholarly citations. A link, source label, or named authority in a model response is treated as an observable source-attribution act: a visible allocation of informational authority.

Key questions include:

- Which sources are cited or named?
- Which sources are omitted?
- Which products, organizations, countries, and languages are represented?
- How does query language affect geographic representation?
- How do citation-like patterns change across time and model updates?

## Relation to prior work

MIBO builds on several lineages:

- **Machine Behavior research** — treating AI systems as objects of behavioral inquiry;
- **Information Behavior research** — studying information seeking, use, browsing, foraging, and sense-making;
- **Behavioral Sciences** — providing broader theories and methods for describing observable behavior;
- **Scientometrics** — showing how citation-like traces can become cumulative objects of observation;
- **GEO** — studying how content visibility can be optimized in generative engines.

A 2022 precursor by Michael Ridley discussed machine information behavior. MIBO does not claim to invent the phrase. MIBO's contribution is to position Machine Information Behavioral Sciences within Machine Behavioral Sciences and operationalize it through an open, longitudinal observatory.

## What MIBO is not

MIBO is not a GEO service. It does not optimize a client website for visibility.

MIBO is not a static benchmark. It does not claim that one-time scores capture model behavior.

MIBO is not a claim that machines have human-like intentions, consciousness, or information needs. “Behavior” is used operationally: an observable relation between input, system configuration, environment, and output.

## Repository structure

MIBO currently uses three repositories:

- `core` — concepts, methodology, schemas, governance, and future software;
- `queries` — versioned standardized query sets;
- `reports` — observation records and reports.

For the first stage, the most important repository is `core`, because it defines the field, method, and observatory.

## Licensing

- Data and query sets: CC0-1.0 unless otherwise stated.
- Code and software documentation: Apache-2.0 unless otherwise stated.
- Raw model outputs may be subject to provider terms.

## Mission

Observation compounds. Today's record becomes tomorrow's irreplaceable archive.
