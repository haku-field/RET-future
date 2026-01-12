# Links to RET

This document defines **reference-only links** between **RET-future** and RET.

RET-future may reference RET.
RET must never depend on RET-future.

---

## Reference-Only Principle

All links from RET-future to RET are:

- Read-only
- Non-binding
- Non-authoritative

They exist solely to allow **comparison and alignment checks**.

---

## Allowed References

RET-future may reference:

- RET-core (existence-level constraints, as read-only context)
- RET-envelope (boundary and continuity conditions)
- RET-anchor (terminology and human-facing translation, reference only)
- RET-specs (interface and payload formats, reference only)
- RET protocols and guards (scope confirmation only)

References must not be imported as mutable inputs.

---

## Prohibited Dependencies

RET-future must not:

- Require RET components to be present
- Fail due to RET version changes
- Import RET definitions as defaults
- Treat RET behavior as execution context

RET-future must remain evaluable in isolation.

---

## No Reverse Linking

RET components must not:

- Reference RET-future as upstream authority
- Depend on RET-future for validation
- Import RET-future conditions into operation

Reverse linkage constitutes interference.

---

## Summary

Links from RET-future to RET are:

- Referential
- One-directional
- Non-binding

They exist to support inspection,
not integration.

---
