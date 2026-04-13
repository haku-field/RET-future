# VERSION HISTORY

## v1.0.0 — temporal contour refactor baseline

Canonical rewrite of RET-future into:
- contours/
- states/
- audit/
- appendix/
- datasets/

Key changes:
- removed roadmap-adjacent migration semantics
- replaced future narration with temporal contours
- formalized unsatisfied variables as default persistence state
- added inevitability anti-mapping authority
- introduced duplication drift detection
- restricted dataset placeholders to non-trend artifacts

Compatibility note:
This version is intentionally **non-migratory**.
No historical branch requires forward preservation.

## lineage rule

RET-future version history records only:
- contour refactor boundaries
- anti-mapping hardening points
- deletion baselines

It must never record:
- progress milestones
- phase completions
- convergence achievements
- implementation readiness