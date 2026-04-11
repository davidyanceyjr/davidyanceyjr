# David Yancey Jr.

I build practical workflow infrastructure for teams that want to use AI in software delivery without giving up reviewability, control, or operational clarity.

The core suite I am developing is:

`spec-forge -> spec-foundry -> product`

with `spec_sync` and `codex_wrapper` supporting the path between specification, implementation, and controlled execution.

## Workflow Suite

### [spec-forge](https://github.com/davidyanceyjr/spec-forge)

`spec-forge` is the front end of the workflow.

It turns an idea, rough notes, or an existing document into an implementation-ready specification that can be reviewed, tightened, and handed off cleanly.

### [spec-foundry](https://github.com/davidyanceyjr/spec-foundry)

`spec-foundry` takes the approved specification and turns it into bounded, issue-backed implementation work.

Its focus is disciplined execution: clear slices, explicit handoffs, and a repository workflow that can be resumed without relying on chat memory.

### [spec_sync](https://github.com/davidyanceyjr/spec_sync)

`spec_sync` is the reconciliation layer.

It keeps a structured specification and GitHub issue inventory aligned so implementation work stays anchored to named requirements instead of drifting through ad hoc ticketing.

### [codex_wrapper](https://github.com/davidyanceyjr/codex_wrapper)

`codex_wrapper` is the operating boundary around AI execution.

It runs Codex inside a controlled sandbox with explicit filesystem access rules so repository workflows can move quickly without treating system access as an afterthought.

## What The Repositories Are Doing Together

Taken as a suite, these repositories are aimed at one problem:

- make specification work durable before implementation starts
- project specification into bounded implementation slices
- keep issue state synchronized with requirement identity
- run AI-assisted work inside clearer operational boundaries

This is workflow infrastructure for taking work from concept to product with less ambiguity, less hidden state, and better handoff between people and tools.

I am especially interested in developer infrastructure, automation, repository workflow design, AI tooling, and Linux-based systems work.
