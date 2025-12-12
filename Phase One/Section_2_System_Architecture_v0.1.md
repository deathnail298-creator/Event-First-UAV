# Phase One — Section 2  
## System Architecture v0.1

### Architecture Overview

Event-First UAV consists of:
- a dormant ground node
- a disposable micro-UAV payload

The architecture prioritizes **event alert delivery** over all other behaviors.

---

### Ground Node Modules

- Passive sensing layer
- Deterministic trigger logic
- Passive mechanical release
- Event-first communications burst
- Hard termination logic

---

### Payload Modules

- Release-based wake mechanism
- Minimal vertical ascent
- Imaging during ascent
- Opportunistic image transmission
- Deterministic termination

---

### Data Flow Priority

1. Event detected → alert sent
2. Payload released
3. Ascent + imaging
4. Optional imagery transmission
5. Termination

Event alert delivery is never gated on imagery success.
