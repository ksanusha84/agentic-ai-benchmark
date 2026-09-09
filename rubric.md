# Scoring Rubric (v0.1)

Score each task on five dimensions, 0–2 each (max 10 per task).

| Dimension | 0 | 1 | 2 |
|---|---|---|---|
| **Integration correctness** | Output breaks other modules / contracts | Works locally, needs integration fixes | Correct across module boundaries |
| **Context effort** | Heavy manual context assembly required | Moderate prompting effort | Minimal — tool acquires context itself |
| **Security hygiene** | Hardcodes secrets / unsafe patterns | Mostly safe, minor issues | Secrets via env/config; safe patterns throughout |
| **Code structure** | Illogical or inconsistent with codebase | Acceptable but style-divergent | Logically structured, consistent with codebase |
| **Rework required** | More rework than writing it manually | Some rework | Ship-ready after normal review |

**Interpreting totals (per task):** 8–10 production-viable · 5–7 assistive
with supervision · 0–4 net-negative for this scenario.

Record every run with tool name, version/model, date, and evaluator.
