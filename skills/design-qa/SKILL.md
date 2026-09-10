---
name: design-qa
description: Compare a coded prototype with its selected visual source and produce a fix-oriented fidelity report before handoff.
---

# Design QA

Use this internal quality gate only after both the source visual and a browser-rendered implementation are available. Compare the same viewport and interaction state.

Inspect required fidelity surfaces: typography, layout and spacing rhythm, color tokens and contrast, images and asset treatment, copy, responsive behavior, and the primary interactions. Classify issues by impact:

- `P0`: a blocked task, broken layout, or severe accessibility failure.
- `P1`: major visual or usability mismatch.
- `P2`: material drift or responsive/state inconsistency.
- `P3`: minor polish.

Write a report with findings, evidence, impact, concrete fixes, open questions, an implementation checklist, and optional P3 follow-up polish. Save it as `design-qa.md` at the project root when working in a repository. Include source and implementation paths, viewport/state, comparison evidence, and a final result of exactly `passed` or `blocked`.

Do not hand off while actionable P0, P1, or P2 findings remain. Use `blocked` when evidence is unavailable or a material issue cannot be resolved; P3 items may remain after a pass.
