# David Yancey Jr.

I build specification-driven tooling, shell-native utilities, and repository workflows that make AI/human collaboration reviewable instead of ad hoc.

Most of the work here falls into two lanes:

- practical CLI tooling for Linux and Bash-heavy environments
- templates and scaffolds for moving from idea to spec to implementation with clear authority and handoff

## Featured Repositories

### [warden](https://github.com/davidyanceyjr/warden)

Early-stage Linux workload control focused on a strict `systemd` backend. The current repo is centered on an implementation-grade backend specification and C foundations for unit naming and backend initialization, with the goal of controlled execution, policy enforcement, and observable lifecycle management.

### [spec-foundry](https://github.com/davidyanceyjr/spec-foundry)

A workflow template for taking an approved specification into bounded, issue-backed implementation work. It is built for teams that want repository state, not chat history, to hold the active workflow, handoff, and implementation authority.

### [spec-forge](https://github.com/davidyanceyjr/spec-forge)

A specification-first template for turning a rough idea or an existing draft into an implementation-ready spec. The workflow is intentionally human-gated: establish `vision.md`, derive the spec, tighten ambiguity, run readiness audits, then hand off to implementation.

### [ricebox](https://github.com/davidyanceyjr/ricebox)

A spec-driven Linux CLI for validating themes, planning safe config changes, and applying supported theming changes across user tools. The current implementation has working parser and validation foundations, plus partial `apply` support, with more runtime surface still in progress.

### [bash-diamonds](https://github.com/davidyanceyjr/bash-diamonds)

A suite of Bash loadable builtins for line-oriented text processing. It is implemented in C, designed around stream processing and shell ergonomics, and backed by focused docs plus Bats-based conformance tests for commands like `fields`, `match`, `count`, `table`, `filter`, and `replace`.

### [autopsyctl](https://github.com/davidyanceyjr/autopsyctl)

A specification-driven CLI for collecting machine data and turning report artifacts into usable summaries, process views, module inventories, mount views, network views, and reports. The repository combines a C command-line tool with a disciplined AI/human workflow for controlled iteration.

### [prox](https://github.com/davidyanceyjr/prox)
prox is the repository for pxprop, a terminal-first prompt optimization CLI. pxprop accepts one complete prompt unit, preserves the original exactly, applies a deterministic normalization pipeline, and returns optimized output together with diagnostics, provenance, and metrics.

## Working Style

- Specs before implementation when behavior is still ambiguous
- Small, reviewable slices tied to explicit workflow state
- Repository-local handoffs instead of session memory
- Tests and validation wired into the normal development loop

## Stack

Most of these projects are built with Bash, C, Git/GitHub workflow conventions, and repository-local operating contracts for AI-assisted engineering.
