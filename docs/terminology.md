# Watchtower Terminology

## Purpose

This document defines the core terminology used throughout the Watchtower Intelligence Model.

Consistent language is essential for accurate reasoning, collaboration, and analysis.  
These definitions establish a shared conceptual framework for observing and interpreting digital threat behaviour.

Where possible, terminology is designed to describe **behaviour and structure**, rather than tools or indicators.

---

## Core Concepts

### Observation

**Observation** refers to the continuous collection of signals without immediate judgement.

In Watchtower, observation precedes detection.

The purpose of observation is to preserve weak signals long enough for meaningful patterns to emerge.

Observation answers the question:
> *What is happening?*

Not:
> *Is this malicious?*

---

### Signal

A **signal** is any observable digital artifact or behaviour that may contribute to understanding a system.

Examples include:
- domain registrations
- DNS records
- hosting metadata
- certificate issuance
- platform identity attributes
- linguistic structures
- timing behaviour

Signals are not indicators by default.  
Their value emerges through relationship and time.

---

### Signal Normalisation

**Signal normalisation** is the process of converting heterogeneous data into consistent internal representations.

Normalisation includes:
- canonical formatting
- source attribution
- confidence tagging
- timestamp alignment

This prevents analytical bias and false correlation.

---

### Relationship

A **relationship** describes a meaningful connection between two or more signals.

Examples include:
- shared infrastructure
- reused language
- temporal proximity
- behavioural similarity

Relationships enable reasoning beyond isolated artifacts.

---

### Threat Constellation

A **Threat Constellation** is a structured grouping of related signals that together represent a coordinated system.

A constellation may include:
- multiple domains
- multiple platform identities
- shared cloud infrastructure
- recurring linguistic patterns
- consistent operational timing

Constellations are not binary determinations of maliciousness.

They represent **structure**, not verdict.

---

### Constellation Density

**Constellation density** refers to the strength and number of relationships within a constellation.

Higher density indicates greater coordination and organisational maturity.

Density increases as relationships accumulate over time.

---

### Temporal Behaviour

**Temporal behaviour** describes how signals change over time.

This includes:
- burst activity
- dormancy periods
- reactivation cycles
- migration intervals

Temporal behaviour often reveals intent more reliably than static attributes.

---

### Migration

**Migration** refers to the movement of threat systems across digital surfaces.

This may include:
- domain rotation
- infrastructure redeployment
- platform switching
- identity recreation

Migration is treated as a normal operational behaviour, not an anomaly.

---

### Behavioural Surface

A **behavioural surface** is any environment where observable activity occurs.

Examples include:
- cloud infrastructure
- domain ecosystems
- social platforms
- messaging channels
- certificate ecosystems

Watchtower observes behaviour across surfaces rather than focusing on a single layer.

---

### Intelligence Synthesis

**Intelligence synthesis** is the process of converting observed signals, relationships, and temporal behaviour into structured understanding.

Synthesis produces:
- constellation summaries
- behavioural narratives
- migration hypotheses
- anticipatory insights

It does not produce raw alerts.

---

### Explainability

**Explainability** refers to the ability to trace intelligence outputs back to observable signals and relationships.

Every conclusion within Watchtower must be interpretable and defensible.

Opaque scoring without context is intentionally avoided.

---

### Weak Signal

A **weak signal** is an observable artifact that appears insignificant in isolation but gains meaning through accumulation.

Watchtower is designed to preserve weak signals rather than discard them prematurely.

---

### Indicator

An **indicator** is a signal that has reached sufficient confidence to justify action.

Indicators are outcomes of observation — not inputs.

---

### Anticipatory Intelligence

**Anticipatory intelligence** refers to insight generated before exploitation or impact occurs.

This includes:
- early campaign formation
- pre exploitation coordination
- migration forecasting

Anticipation is the primary objective of Watchtower.

---

## Conceptual Boundaries

Watchtower terminology intentionally avoids language associated with:

- exploitation
- intrusion
- weaponisation
- attack tooling

The model focuses on **observation, structure, behaviour, and evolution**.

This ensures clarity of purpose and alignment with defensive architecture principles.

---

## Summary

The Watchtower Intelligence Model relies on precise language to support consistent reasoning.

These definitions form the conceptual foundation upon which architecture, analysis, and implementation are built.

As the model evolves, terminology may expand — but its emphasis on systems, behaviour, and time remains constant.
