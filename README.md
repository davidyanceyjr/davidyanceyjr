# David Yancey Jr.

I build tools and workflows that help teams use AI to plan and build software in a way that is easier to review, easier to manage, and easier to trust.

The main suite I am developing is:

`spec-forge -> spec-foundry -> product`

with `spec_sync` and `codex_wrapper` supporting that workflow.

## Workflow Suite

### [spec-forge](https://github.com/davidyanceyjr/spec-forge)

`spec-forge` helps turn an idea, rough notes, or an existing document into a clear specification.

The goal is to make sure the work is understood before implementation starts.

### [spec-foundry](https://github.com/davidyanceyjr/spec-foundry)

`spec-foundry` takes an approved specification and turns it into implementation work that is easier to track and review.

It is focused on breaking work into manageable slices with clear handoff points.

### [spec_sync](https://github.com/davidyanceyjr/spec_sync)

`spec_sync` keeps a specification and the related GitHub issues in sync.

That helps teams track implementation work against the actual requirements instead of letting the spec and issue list drift apart.

### [codex_wrapper](https://github.com/davidyanceyjr/codex_wrapper)

`codex_wrapper` adds a clearer control layer around running Codex.

It is meant to make AI-assisted repository work more practical in environments where system access and safety boundaries matter.

## How They Fit Together

Taken together, these repositories help a team move from an idea to working product code in a more controlled way.

`spec-forge` is for defining the work clearly.
`spec-foundry` is for turning that definition into implementation work.
`spec_sync` keeps the specification and issue tracking aligned.
`codex_wrapper` helps run AI tooling with clearer operating boundaries.

I am especially interested in developer infrastructure, automation, repository workflow design, AI tooling, and Linux-based systems work.
