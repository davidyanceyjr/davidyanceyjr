# davidyanceyjr@gmail.com

I build specification-driven tooling, Bash-heavy systems utilities, and practical AI/human workflow scaffolds.

This profile currently centers on repositories that tighten the path from idea -> specification -> implementation -> verification.

## Focus

- Specification-first engineering workflows
- Bash CLI and shell-native tooling
- Secure operator tooling and sandboxed execution
- Reusable templates for AI-assisted development

## Featured Repositories

### `autopsyctl`

autopsyctl is a command-line tool for collecting machine data and turning those artifacts into
usable outputs like process lists, collect: accept cwd-relative --output paths per spec
Problem autopsyctl collect --output <path> currently rejects cwd-relative output targets such as ./collector.json as CLI misuse even though the act…network views, mounts, module inventories, summaries, and
reports.


### `bash-diamonds`

A suite of Bash loadable builtins for line-oriented text processing. This repo focuses on stream processing, shell-native ergonomics, and contract-preserving behavior backed by specs and tests.

### `codex_wrapper`

A Bash wrapper for running the Codex CLI inside a `systemd` sandbox with explicit filesystem controls. The goal is to keep the tool useful in real repositories without granting uncontrolled host access.

### `spec-forge`

**spec-forge is a documentation-first specification workflow template designed to turn raw ideas or existing specs into implementation-ready specifications through a controlled, auditable, and human-gated process.**


### `ricebox`
A Linux CLI that validates themes, inspects app configs, safely applies themes to supported user config files, and exports native theme files.

### 'warden'
Controlled execution of workloads with strict lifecycle, policy, and observability guarantees on Linux systems using systemd.


## Workspace Snapshot

The folders in this workspace currently break down into a few clear groups:

- Product/tool repositories: `autopsyctl`, `bash-diamonds`, `codex_wrapper`, `ricebox`
- Spec and workflow repositories: `spec-foundry`, `codex-pair-spec-template`
- Early or currently sparse scaffold: `the_warden`

## Working Style

- Specs before code when behavior is still ambiguous
- Small, reviewable implementation slices
- Repository state as workflow memory
- Tests and validation wired into normal development flow

## Tech Notes

Most of the work here leans on Bash, shell tooling, Git/GitHub workflows, and repository-local operating contracts for AI-assisted engineering.
