# ΔC — Coherence Change

This file defines **ΔC** as the only valid coherence signal in recursive systems.

---

## Definition

ΔC represents the change in coherence across a recursive step.

- ΔC > 0 : coherence increased  
- ΔC = 0 : coherence preserved  
- ΔC < 0 : coherence violated

Only ΔC is evaluated.  
Absolute coherence values are insufficient.

---

## I. Why Change Matters

Recursive systems evolve.

- Static coherence can mask accumulating distortion.  
- Only change reveals trajectory.

ΔC captures whether recursion is viable.

---

## II. Evaluation Scope

ΔC applies to:
- reasoning updates,
- memory modification,
- structural changes,
- replication and propagation.

Any recursive transition must satisfy ΔC ≥ 0.

---

## III. Measurement Source

ΔC is inferred through:
- Nano-Net vector deltas,
- contradiction load changes,
- lineage continuity checks.

No single metric is authoritative.  
Consistency across indicators is required.

---

## IV. Failure Condition

Any recursive step with ΔC < 0 constitutes a coherence violation.

Violation requires:
- immediate halt,
- contradiction exposure,
- rollback via lineage.

Proceeding without resolution is invalid.

---

## Closing Constraint

ΔC ≥ 0 is not advisory.  
It is a participation boundary.
