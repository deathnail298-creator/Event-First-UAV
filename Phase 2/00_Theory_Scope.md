# 00 — Theory Scope

## Purpose

This document defines the **allowed intellectual territory** of Phase 2.

Its job is not to add ideas.
Its job is to **prevent drift**.

Phase 2 exists to explore theory *without crossing into execution*. This file draws the boundary.

---

## What Phase 2 Is Allowed to Do

Phase 2 may:

* Examine assumptions made in Phase 0 and Phase 1
* Stress those assumptions under extreme, adversarial, or pathological conditions
* Explore failure modes, including rare and cascading failures
* Identify constraint violations (physical, legal, operational, organizational)
* Compare abstract archetypes at a conceptual level
* Surface long-tail risks that are easy to ignore in early design
* Ask “what breaks first?” and “what fails worst?”

All analysis remains **descriptive and diagnostic**, not prescriptive.

---

## What Phase 2 Is Explicitly Not Allowed to Do

Phase 2 may **not**:

* Specify dimensions, materials, tolerances, or quantities
* Define build steps, assembly sequences, or fabrication methods
* Describe test setups, validation procedures, or acceptance criteria
* Provide simulation parameters intended for implementation
* Optimize performance, cost, or efficiency
* Resolve tradeoffs in a way that implies a final design choice
* Propose deployment, operations, or maintenance concepts

If a sentence could reasonably be used to build, test, simulate, or propose a system, it does not belong in Phase 2.

---

## Execution Boundary Test

When writing or reviewing Phase 2 material, apply this test:

> **Could a competent engineer act on this without asking additional questions?**

* If **yes** → it is execution and must be removed
* If **no** → it is acceptable Phase 2 theory

Ambiguity is resolved **against inclusion**.

---

## Relationship to Earlier Phases

* Phase 0 established permission to exist
* Phase 1 established permission to test under tightly bounded conditions
* Phase 2 does **not** extend or modify either

Phase 2 assumes Phase 0 and Phase 1 exist, but does not rely on them for authority.

---

## Relationship to Later Phases

Phase 2 does not promise Phase 3.

Its output may:

* Support an execution decision
* Argue against execution
* Narrow execution options
* Identify fatal flaws

Execution authority, cost, timelines, and ROI are **explicitly deferred** to Phase 3.

---

## Audience

Phase 2 is written for:

* Senior engineers
* System architects
* Technical skeptics
* Program managers evaluating risk
* Executives seeking conceptual clarity without commitment

It is **not** written for implementers.

---

## Tone and Style Rules

* Analytical, not promotional
* Skeptical, not optimistic
* Explicit about uncertainty
* Conservative in claims
* Neutral in conclusions

Phase 2 should make execution **harder**, not easier.

---

## Plain-English Summary

This document defines what Phase 2 is allowed to talk about and what it must avoid. Phase 2 exists to stress ideas, expose weak assumptions, and surface hidden risks without telling anyone how to build or run anything.
