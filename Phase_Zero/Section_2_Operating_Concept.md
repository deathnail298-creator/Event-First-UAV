# Phase Zero — Section 2  
## Operating Concept

### High-Level Concept

Event-First UAV is an unattended sensing node that remains dormant until an environmental disturbance occurs.

When triggered, the system:
1. Immediately sends an event notification upstream
2. Releases a small aerial imaging payload
3. Captures brief situational imagery during ascent
4. Attempts to transmit imagery opportunistically
5. Terminates operation

The alert is always the priority.  
Imagery is optional context.

---

### Key Principle

> Event-first, context-second, then stop.

The system is intentionally transient and non-persistent.

---

### Intended Value

The system provides **awareness**, not interpretation.

It answers:
- *Something happened here.*

It may additionally answer:
- *This is roughly what the area looked like.*

It does not:
- track
- follow
- monitor
- decide
