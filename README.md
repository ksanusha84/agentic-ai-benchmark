# Agentic AI Benchmark (v0.1)

A practitioner's benchmark for evaluating AI coding assistants and agentic
systems on **production-context engineering tasks** — the situations where
real teams find out whether a tool helps or hurts.

## Why this exists

Most AI coding benchmarks test isolated snippets. In production, the hard
part is different: multi-module codebases, security hygiene, integration
contracts, and the human effort needed to supply context. This benchmark
grew out of a 20-month AI adoption programme across a 30-engineer SaaS
organisation (2025–2026), where fragment-scoped tools failed on real
codebases and project-context-aware tools succeeded. The tasks formalise
the scenarios that separated them.

## What it contains

- `tasks/` — 11 evaluation task specifications, each with a scenario,
  what to ask the tool, and pass criteria
- `rubric.md` — a 5-dimension scoring rubric (0–2 per dimension)
- `results/template.md` — a form for recording an evaluation run
- `results/2025-internal-notes.md` — qualitative findings from the
  original internal evaluation that seeded this benchmark

## How to run an evaluation

1. Pick a target tool (any AI coding assistant or agent).
2. For each task in `tasks/`, follow the task sheet: give the tool the
   scenario, capture its output, and score it against the rubric.
3. Record scores in a copy of `results/template.md`.
4. Compare tools by total score and per-dimension profile.

Evaluation is currently **manual by design** — the benchmark measures
outcomes a reviewing engineer can judge. Automation of scoring is on the
roadmap.

## Status & roadmap (v0.1 — under active development)

- [x] Task set v0.1 (10 tasks) and scoring rubric
- [x] Task 11: design-to-code fidelity (added post-v0.1, from case-study findings)
- [ ] Reference codebase fixtures per task
- [ ] Automated runner and scoring scripts
- [ ] Community-contributed task packs
- [ ] Expand design-to-code into a full task family (further
      Figma/design-artefact scenarios beyond Task 11)

Contributions and issue reports are welcome.

## Author

Anusha K S — Founder & CTO, Vriksha Techno Solutions, Chennai.
Companion paper: *A Governance-Driven Framework for Adopting Agentic AI
in Software Engineering Organisations* (submitted, IEEE AIEI 2027).

## License

MIT — see [LICENSE](LICENSE).
