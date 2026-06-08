# Incubator

This repository is the bridge between `playground` and `portfolio`.

It exists for projects that have completed their major 1.0 feature set, but are not yet mature enough to be treated as portfolio-grade assets.

## Purpose

`Incubator` is where selected projects get intentional investment after MVP scope is present.

Typical work here includes:
- architecture cleanup
- platform onboarding
- CI/CD alignment
- runtime and deployment shaping
- documentation hardening
- stack and boundary decisions
- proving whether a project should graduate, stay standalone, or be retired

## Repository Lifecycle

### `playground`
Use `playground` for:
- raw experiments
- one-off prototypes
- curiosity-driven spikes
- work that may never be revisited
- active product development before major 1.0 features exist

### `incubator`
Use `incubator` for:
- projects chosen for active shaping after MVP-complete core features exist
- candidates for portfolio inclusion
- platform feature candidates not ready to live in `portfolio`
- work with a defined backlog and explicit maturation goals

### `portfolio`
Use `portfolio` for:
- reference implementations
- platform-owned assets
- paved-road patterns
- showcase-quality artifacts with a clear operating model

## What Belongs Here

Examples of good incubator candidates:
- a project graduating out of `playground` after core product capabilities exist
- a realistic application being onboarded onto the platform
- a potential platform feature that needs room to mature outside the main portfolio repo
- a project that needs governance, backlog management, and clearer exit criteria

## What Does Not Belong Here

- throwaway experiments better suited for `playground`
- projects still missing core 1.0 product features
- fully mature platform assets that should live in `portfolio`
- unrelated long-term products with no portfolio or platform relevance

## Operating Model

Projects in `incubator` should have:
- a clear purpose
- an identified target architecture
- explicit entry and graduation criteria
- a tracked backlog or project board
- enough documentation that another engineer could understand the direction

## Graduation Outcomes

A project in `incubator` can end in one of three ways:

1. **Graduate to `portfolio`**
   - the project becomes a platform asset, reference implementation, or polished showcase artifact

2. **Return to `playground` or archive**
   - the idea was useful to explore, but not worth continued investment

3. **Remain standalone**
   - the project proves useful, but is better kept as its own independent repository rather than folded into `portfolio`

## Initial Intention

`problem_recommender` is a likely future incubator candidate, but only after its API and UI are present and the product has reached an MVP-complete state inside `playground`.
