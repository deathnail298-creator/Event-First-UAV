# 02 — Failure Extremes

## Purpose

This document examines **worst‑plausible failure cases**.

Not typical failures.
Not recoverable failures.

Failures that:

* Permanently damage confidence
* Trigger disproportionate response
* Kill programs despite limited physical harm

Phase 2 assumes failures will be judged by **humans under pressure**, not by post‑hoc engineering logic.

---

## Framing Principle

A failure is considered "extreme" if **its secondary consequences dominate the primary fault**.

Small physical failures can still be extreme.

---

## Failure Class 1 — Ambiguous Failure Attribution

**Description:**

The system fails quietly, but the failure is **misattributed** to adjacent or upstream systems.

**Extreme pathways:**

* Fault appears correlated with a mission‑critical event
* Investigators lack clear isolation boundaries
* Blame propagates outward before facts converge

**Consequences:**

* Broad inspection mandates
* Loss of trust in unrelated subsystems
* Program‑wide slowdowns

**Why this is extreme:**

The failure expands in scope through interpretation, not physics.

---

## Failure Class 2 — Failure During a High‑Visibility Window

**Description:**

Failure coincides with:

* Crew activity
* Public milestones
* External scrutiny

**Extreme pathways:**

* Failure narrative outpaces technical understanding
* Decision‑makers default to conservatism

**Consequences:**

* Operational freezes
* Over‑correction
* Reputational damage

**Why this is extreme:**

Timing, not severity, determines impact.

---

## Failure Class 3 — Degradation Misread as Instability

**Description:**

Gradual degradation creates ambiguous states.

**Extreme pathways:**

* Normal aging is interpreted as dynamic instability
* Observers infer runaway behavior

**Consequences:**

* Unnecessary intervention
* Forced shutdowns
* Loss of confidence in passive behavior

**Why this is extreme:**

Slow failures invite speculation.

---

## Failure Class 4 — Inspection Cascade Trigger

**Description:**

A benign failure triggers mandatory inspection processes.

**Extreme pathways:**

* Inspection scope expands iteratively
* Review bodies uncover unrelated issues

**Consequences:**

* Schedule collapse
* Cost explosion unrelated to original fault

**Why this is extreme:**

The response becomes more damaging than the failure.

---

## Failure Class 5 — Ownership Vacuum

**Description:**

Failure occurs where responsibility is unclear.

**Extreme pathways:**

* Multiple groups disclaim ownership
* No one is authorized to act

**Consequences:**

* Delay compounds damage
* Political escalation

**Why this is extreme:**

Organizational paralysis replaces technical resolution.

---

## Failure Class 6 — Success‑Adjacent Failure

**Description:**

Failure occurs in proximity to otherwise successful operation.

**Extreme pathways:**

* Success raises expectations
* Failure feels like regression

**Consequences:**

* Disproportionate disappointment
* Retrospective skepticism

**Why this is extreme:**

Narrative whiplash erodes support.

---

## Failure Class 7 — Non‑Failure Interpreted as Failure

**Description:**

System behaves as designed, but behavior is misinterpreted.

**Extreme pathways:**

* Passive behavior looks like loss of control
* Lack of telemetry invites speculation

**Consequences:**

* Forced intervention
* Loss of system autonomy

**Why this is extreme:**

Perception overrides reality.

---

## Meta‑Observation

The most dangerous failures are:

* Socially amplified
* Poorly bounded
* Narrative‑driven

Technical severity is often secondary.

---

## Implications

* Extreme failures should be assumed *before* execution
* Design simplicity alone does not prevent program‑killing outcomes
* Human response dominates risk profile

---

## Phase Discipline Note

This document does **not** propose mitigations.

Mitigation strategies imply execution intent and belong to later phases.

---

## Plain‑English Summary

This document looks at how things fail in the worst possible ways — not by breaking hardware, but by triggering confusion, overreaction, and loss of trust. The most dangerous failures are the ones that spiral socially and organizationally, even when the physical problem is small.
