# Project Context: Incubator

## Purpose
Bridge the gap between `playground` and `portfolio`.

`incubator` exists for projects that are no longer raw experiments, but are not yet mature enough to be treated as portfolio-grade assets.

## Operating Intent
- Incubated projects should have a clear purpose, target architecture, and exit criteria.
- Work here should be deliberate, tracked, and oriented toward either graduation or retirement.
- Projects may be standalone application candidates, platform feature candidates, or onboarding canaries.

## Relationship to Other Repositories
- `playground`: raw experiments, spikes, and low-commitment exploration.
- `incubator`: selected candidates under active shaping.
- `portfolio`: proven references, platform assets, and showcase-quality implementations.

## Repository Governance
- `main` branch protection for `incubator` is managed from the shared ruleset baseline stored in `portfolio/scripts/github/rulesets/`.
- This is intentional: repository rules are treated as shared platform governance, not duplicated ad hoc per repo.

## Default Assumptions
- Each incubated project should define current state, target state, and graduation criteria.
- Projects here should maintain a small backlog or execution board.
- Developer-facing and platform-oriented tools should default to a Python backend and React frontend.
- Other application experiences should default to a .NET backend and Angular frontend.
- Exceptions are allowed when a project has a documented reason to diverge.
- Incubated projects should avoid introducing unnecessary frontend stack sprawl without a documented reason.

## Initial Candidate Direction
- `problem_recommender` is the first likely incubation candidate if it continues beyond exploration and into intentional service/UI/platform onboarding work.

## Immediate Next Steps
1. Decide when `problem_recommender` should move from `playground` into `incubator`.
2. Define board/project tracking conventions for incubated work.
3. Document entry and graduation criteria per project.

## Session Conventions
- Keyword: `start session`
- Meaning: begin a new work session by recapping the previous session and checking the board for the next task.
- `start session` checklist:
  1. Review `PROJECT_CONTEXT.md` for current status, decisions, and immediate next steps.
  2. Check the active board/epic and confirm the next `Ready` or planned task.
  3. Summarize repo state (clean vs in-flight changes).
  4. Propose the next concrete work item before making edits.

- Keyword: `save state`
- Meaning: current task reached a stopping point and work should be stored durably in remote history without waiting for follow-up prompts.
- `save state` checklist:
  1. Update `PROJECT_CONTEXT.md` (state, decisions, next action).
  2. Update impacted README/docs for accuracy.
  3. Run quick validation for touched areas when feasible.
  4. Summarize the changes and current git status.
  5. Check the current branch name; if it is `main`, create and switch to a new branch before committing.
  6. Commit the current work with a clear message.
  7. Push the current branch to remote.
  8. Call out any known validation gaps, CI blockers, or follow-up risks.

- Keyword: `end session`
- Meaning: session is ending.
- `end session` checklist:
  1. Update `PROJECT_CONTEXT.md` (state, decisions, next actions).
  2. Update impacted README/docs for accuracy.
  3. Run quick validation for touched areas when feasible.
  4. Update the active board/task state if progress changed during the session.
  5. Summarize the session changes and current repo state.
  6. If the work does not already have a tracking issue, create one before opening or updating the PR.
  7. Link the PR to the issue explicitly:
     - use `Closes #...` if the issue should remain open until merge
     - use `Refs #...` if the issue is being closed immediately as tracking-only documentation
  8. Check the current branch name; if it is `main`, create and switch to a new branch before committing.
  9. Commit the current work with a clear message.
  10. Push the current branch to remote.
  11. Call out any known CI blockers, unresolved risks, or next recommended starting point.
