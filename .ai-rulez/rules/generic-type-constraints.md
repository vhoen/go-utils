---
priority: critical
---

# Generic Type Constraints

All utility functions must use appropriate generic type constraints (comparable, any, or custom interfaces). Follow existing patterns in sliceutils, maputils, and structutils packages. Always ensure type safety at compile time rather than runtime reflection where possible.
