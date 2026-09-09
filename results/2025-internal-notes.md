# Origin Notes — 2025 Internal Evaluation (qualitative)

These qualitative findings come from the internal tool evaluation during a
2025 AI adoption programme at a 30-engineer SaaS organisation. They predate
this benchmark's formal rubric and are recorded here as the observations
that motivated the task set. They are not scored runs.

- **Fragment-scoped assistant (ChatGPT, partial-project usage):** prompting
  became labour-intensive because the tool lacked whole-project visibility;
  generated code introduced integration problems in multi-module client
  codebases; in several cases rework exceeded savings.
- **Project-context-aware assistant (Claude, from mid-2025):** operated
  with project-wide context; error rates reduced and certain recurring
  error classes were eliminated; generated code was logically structured
  and consistent with surrounding modules.
- Rollout order: backend -> mobile -> frontend -> design; QA in progress.
- Governance rules applied throughout: no credentials in prompts or code
  (env-managed); prompts must be clear and explained; mandatory developer
  testing per function/module before QA handoff.

Formal scored runs using rubric.md are planned as the next milestone.
