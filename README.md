# David Yancey Jr.

I build developer tooling for specification-driven delivery, AI-assisted repository workflows, and pragmatic Unix-style automation.

The main workflow suite I am developing is:

`spec-forge -> spec-foundry -> product`

with `spec_sync` and `codex_wrapper` supporting that path.

## Workflow Suite

### [spec-forge](https://github.com/davidyanceyjr/spec-forge)

`spec-forge` turns a rough concept, notes, or an existing document into an implementation-ready software specification.

It is the definition stage: get the behavior, interfaces, constraints, and readiness criteria clear before build work starts.

### [spec-foundry](https://github.com/davidyanceyjr/spec-foundry)

`spec-foundry` is the delivery scaffold that takes an approved specification through a controlled human/AI implementation loop.

It is focused on bounded workflow stages, explicit handoffs, and managed work inventory instead of loose ad hoc execution.

### [spec_sync](https://github.com/davidyanceyjr/spec_sync)

`spec_sync` is the CLI that checks and reconciles a structured Markdown spec against GitHub issues.

It keeps requirement IDs, coverage, and issue state aligned so the spec and the work queue do not drift apart.

### [codex_wrapper](https://github.com/davidyanceyjr/codex_wrapper)

`codex_wrapper` is a Bash wrapper for Codex CLI that runs it inside a `systemd` sandbox with explicit filesystem access controls.

It is aimed at AI-assisted repository work where operating boundaries and host safety matter.

## Other Projects

### [bash-diamonds](https://github.com/davidyanceyjr/bash-diamonds)

`bash-diamonds` is a suite of Bash loadable builtins for line-oriented text processing.

It is separate from the spec workflow repos, but aligned with the same preference for explicit contracts, composable tools, and reviewable behavior.

## How They Fit Together

Taken together, the workflow repos support a tighter path from idea to implementation:

`spec-forge` defines the work clearly.
`spec-foundry` turns that definition into controlled delivery flow.
`spec_sync` keeps the specification and issue inventory aligned.
`codex_wrapper` provides a safer execution boundary for Codex during repository work.

I am especially interested in developer infrastructure, automation, repository workflow design, AI tooling, CLI ergonomics, and Linux-based systems work.
