# 04 — Comparative Archetypes

## Purpose

This document compares **conceptual archetypes** that address the same problem domain.

The goal is **contrast, not selection**.

No archetype is recommended.
No tradeoff is resolved.

Phase 2 uses comparison to clarify *why* ideas differ, not *which* is better.

---

## Archetype Framing Rules

All archetypes are described at a **conceptual level only**.

They are compared across:

* Failure behavior
* Organizational burden
* Perception under stress
* Constraint sensitivity

No archetype is optimized.

---

## Archetype A — Passive, Always-On Infrastructure

**Defining traits:**

* No active control or sensing
* Continuous background operation
* Failure modes are quiet and local

**Strengths:**

* Low operational touch
* Predictable steady-state behavior
* Minimal direct dependencies

**Weakness exposure:**

* Behavior may be misinterpreted
* Hard to demonstrate effectiveness
* Passive degradation can invite scrutiny

**Constraint sensitivity:**

* Sensitive to perception and ownership ambiguity
* Vulnerable to inspection cascades

---

## Archetype B — Active, Controlled System

**Defining traits:**

* Explicit sensing and actuation
* Operator-visible state
* Discrete operational modes

**Strengths:**

* Clear intent and controllability
* Easier to justify during reviews
* Measurable performance

**Weakness exposure:**

* Increased integration burden
* More failure pathways
* Higher certification cost

**Constraint sensitivity:**

* Sensitive to physical and regulatory constraints
* Less tolerant of partial failure

---

## Archetype C — Episodic or Event-Driven Intervention

**Defining traits:**

* Operates intermittently
* Activated only under specific conditions
* Idle most of the time

**Strengths:**

* Reduced continuous exposure
* Easier to pause or disable
* Lower background scrutiny

**Weakness exposure:**

* Missed activation windows
* Reliance on correct triggering
* Operational complexity during events

**Constraint sensitivity:**

* Sensitive to operational timing constraints
* Vulnerable to human error

---

## Archetype D — Procedural or Human-Centered Mitigation

**Defining traits:**

* Relies on policy, training, or procedure
* Minimal physical infrastructure
* Human judgment dominant

**Strengths:**

* Low hardware cost
* Flexible adaptation
* Easier initial approval

**Weakness exposure:**

* Performance variability
* Fatigue and non-compliance
* Difficult to audit objectively

**Constraint sensitivity:**

* Sensitive to organizational incentives
* Degrades under stress and time pressure

---

## Cross-Archetype Observations

* Archetypes fail differently, not less
* Organizational comfort often outweighs technical elegance
* Visibility trades off against robustness

Hybrid approaches inherit constraints from all parents.

---

## Phase Discipline Note

This document intentionally avoids:

* Ranking archetypes
* Selecting a preferred approach
* Proposing hybrids or optimizations

Selection implies execution intent and belongs to later phases.

---

## Plain-English Summary

This document compares different high-level ways the problem could be addressed, showing how each one behaves under stress and organizational pressure. It does not recommend a solution — it clarifies the tradeoffs so later decisions are better inf
