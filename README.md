# David Yancey Jr.

<<<<<<< HEAD
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
=======
I build repository-native AI workflows that keep authority, handoff, and implementation state in versioned artifacts instead of chat memory.

The focus here is specification-driven delivery with Codex, agents, skills, and GitHub-tracked execution:

- shape intent into an implementation-ready spec
- project the spec into bounded tracked work
- execute with AI assistance inside explicit repository rules
- validate, review, and hand off from repository state

## Workflow Focus

The core model is simple:

`idea -> vision -> specification -> tracked slices -> implementation -> validation -> review -> handoff`

What matters is where that state lives. I am interested in workflows where:

- the spec is the controlling artifact
- agents and skills operate inside repository contracts
- implementation is bounded and reviewable
- GitHub issues, branches, and PRs reflect actual workflow state
- another human or another Codex session can resume from the repository without reconstructing context from prior chat
>>>>>>> 790dca0 (update: README focus change.)

## Featured Repositories

### [spec-forge](https://github.com/davidyanceyjr/spec-forge)

Specification formation workflow. This is the front end of the system: move from an idea or an existing draft into a durable, implementation-ready specification with explicit human gates and repository-resident handoff state.

### [spec-foundry](https://github.com/davidyanceyjr/spec-foundry)

Specification-to-implementation workflow. This is the execution template: take a controlling spec, reconcile it into bounded implementation slices, and carry those slices through branch, pair, test, review, delivery, and finish.

### [specfndry-testing](https://github.com/davidyanceyjr/specfndry-testing)

Working demonstration repository. This shows the workflow applied to a real implementation exercise, including spec-controlled development, issue-backed execution, validation, and a shipped CLI product instead of a template-only scaffold.

### [codex_wrapper](https://github.com/davidyanceyjr/codex_wrapper)

Execution boundary for Codex. This repo is part of the practical operating layer: a wrapper for running Codex inside a controlled sandbox while preserving a fast CLI workflow for repository work.

## Why These Repos Matter Together

These repositories are meant to be read as one workflow stack:

- `spec-forge` demonstrates how intent becomes a durable spec
- `spec-foundry` demonstrates how that spec becomes tracked implementation work
- `specfndry-testing` demonstrates the model on a real project
- `codex_wrapper` demonstrates how the AI execution environment itself can be controlled instead of treated as a black box

### [prox](https://github.com/davidyanceyjr/prox)
prox is the repository for pxprop, a terminal-first prompt optimization CLI. pxprop accepts one complete prompt unit, preserves the original exactly, applies a deterministic normalization pipeline, and returns optimized output together with diagnostics, provenance, and metrics.

## Working Style

- specification before implementation when behavior is still open
- Codex, agents, and skills constrained by repository-local contracts
- repository handoff over conversational memory
- bounded issue-backed slices over ad hoc execution
- GitHub used for visible tracking, review, and delivery state

If you are interested in AI-assisted engineering that is auditable, resumable, and driven by explicit repository authority, that is the through-line of the work here.
