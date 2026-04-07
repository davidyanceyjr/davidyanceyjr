# David Yancey Jr.

I design and build Linux-based systems that make AI-assisted development structured, reviewable, and reliable.

Certified Linux Administrator working in Bash-centric environments, with a focus on CLI tooling, repository workflows, and specification-first development. My work centers on building real systems with clear boundaries and observable behavior—especially where AI is involved in the loop.

I develop AI-assisted workflows that operate as systems, not black boxes: prompts are versioned, execution is stepwise and inspectable, and outputs are tied back to specifications and repository state.

Representative systems:

AI workflow systems — deterministic prompt processing, normalization, and diagnostics with human-in-the-loop control
Specification-first pipelines — idea → spec → implementation with explicit handoff and traceability
Linux workload control systems — managed execution with policy, lifecycle visibility, and system integration
Shell-native CLI tooling — Bash-driven automation and composable utilities for real environments
Machine inspection and reporting — structured data collection and operational visibility

Key areas:

Bash-driven automation and Linux CLI systems
Specification-first workflows that reduce ambiguity and rework
Repository design for maintainability, collaboration, and auditability
AI-assisted systems with observable steps, diagnostics, and human control

I focus on building systems that can be inspected, debugged, and trusted—designed for real use, with clear interfaces and repeatable behavior.

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
