# CONTEXT.md — L1 router (advisory)

Entry point for this repo: find your task below, open the ONE doc its row names, read only what
the Read column lists. Routing is advisory; the citations are the part that matters.

Stage contracts (`.claude/skills/run/stages/NN_<stage>/CONTEXT.md`) live in the GLOBAL skills tree
(`~/.claude/skills/`), not in this repo — repo-relative existence checks will flag those rows as
unresolvable here, which is expected for every fleet repo that is not `dotfiles`.

## Routes

| Task | Go to | Read |
| --- | --- | --- |
| Classify a task, pick the bucket | `.claude/skills/run/stages/02_classify/CONTEXT.md` | `.run/references/PROJECT.md` |
| Research a phase | `.claude/skills/run/stages/06_research/CONTEXT.md` | `.run/references/PROJECT.md`, `.run/references/KNOWLEDGE.md` |
| Decide direction (discuss) | `.claude/skills/run/stages/07_discuss/CONTEXT.md` | `.run/references/DECISIONS.md`, `.run/references/KNOWLEDGE.md` |
| Write the task plan | `.claude/skills/run/stages/08_plan/CONTEXT.md` | `.run/references/PROJECT.md` |
| Build a planned task | `.claude/skills/run/stages/10_build/CONTEXT.md` | `.run/references/PROJECT.md`, `.run/references/KNOWLEDGE.md` |
| Review the built diff | `.claude/skills/run/stages/11_review/CONTEXT.md` | `.run/references/PROJECT.md` |
| Verify it actually works | `.claude/skills/run/stages/12_verify/CONTEXT.md` | `.run/references/PROJECT.md` |
| Measure a shipped phase | `.claude/skills/run/stages/18_measure/CONTEXT.md` | `.run/references/PROJECT.md`, `.run/references/KNOWLEDGE.md` |
| Past learnings | `.run/references/KNOWLEDGE.md` | search for your term |
| Standing decisions | `.run/references/DECISIONS.md` | the matching dated row |
| Stack, conventions, constraints | `.run/references/PROJECT.md` | the matching section |

## Do NOT load (advisory)

- `.run/references/KNOWLEDGE.md` in full outside research — search it for your term instead.
- Closed phases under the phase archive — open one only when a row names it.

Nothing mechanically blocks these reads. Skip them by default; open one when the task needs it.

## Artifact naming

- Phase artifacts are UPPER-SNAKE under `.run/output/phases/<slug>/` — `PLAN.md`, `PROGRESS.md`.
- Phase slugs are kebab-case: `<milestone>-<short-goal>`.
- Stage dirs are `NN_<stage>`; NN is derived, never hand-picked.
- `.run/PROJECT.md`, `.run/KNOWLEDGE.md` and `.run/DECISIONS.md` are relative compat symlinks onto
  `.run/references/` — the canonical home is `references/`, the root paths are the old names.
