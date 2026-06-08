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
