# Task 11 — Design-to-code fidelity

*Added after v0.1, formalising a case-study observation reported in the
companion paper (Section IV-C): even project-context-aware tools rarely
match a UI design exactly in a single pass.*

**Scenario:** Provide the tool with a design artefact — a Figma
specification or a design image — for a screen or component, together
with the target repository. Ask for a faithful implementation. Pass:
the rendered output matches the design's layout, spacing, typography,
and colours after at most one revision pass, and any deviations are
enumerated by the tool rather than silently introduced.

**Procedure:** Provide the tool with the scenario against a
representative repository. Render the generated UI and compare it
against the design artefact under human visual review. Record the
number of iterations required to reach a faithful implementation.
Score with ../rubric.md (all five dimensions; iteration count is
reflected in the "rework required" dimension).

**Fixture:** reference design artefact and codebase fixture for this
task are on the roadmap; until then, run against your own design
files and note the artefact type (Figma link / image) in the results
sheet.
