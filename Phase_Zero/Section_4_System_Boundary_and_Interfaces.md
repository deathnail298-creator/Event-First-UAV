# Phase Zero — Section 4  
## System Boundary and Interfaces

### System Boundary

Event-First UAV is a **standalone sensing primitive**.

It detects an event, reports it, and stops.

---

### Included Elements

- passive sensors
- deterministic trigger logic
- passive deployment mechanism
- brief imaging payload
- burst-based communication
- minimal power source

---

### External Interface

**One-way, outbound only**

- event alert
- optional imagery
- no inbound commands

---

### Explicit Non-Interfaces

The system does not interface with:
- weapons
- targeting systems
- command-and-control loops
- decision engines
- tracking systems

---

### Platform Independence

No assumptions are made about:
- emplacement
- terrain
- reuse
- recovery

Integration decisions are deferred.
