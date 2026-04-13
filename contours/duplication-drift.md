# Duplication Drift

Temporal duplication occurs when equivalent contours are reintroduced
under renamed variables, duplicated YAML states, or pseudo-versioned branches.

This drift weakens discardability.

Detection signals:
- repeated contour aliases
- renamed obsolete variables
- branch-only temporal forks
- mirrored failure states with semantic equivalence

Preferred resolution:
**delete older contour families rather than merge them**.