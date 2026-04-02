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
usable outputs like process lists, network views, mounts, module inventories, summaries, and
reports.


### `bash-diamonds`

A suite of Bash loadable builtins for line-oriented text processing. This repo focuses on stream processing, shell-native ergonomics, and contract-preserving behavior backed by specs and tests.

### `codex_wrapper`

A Bash wrapper for running the Codex CLI inside a `systemd` sandbox with explicit filesystem controls. The goal is to keep the tool useful in real repositories without granting uncontrolled host access.

### `spec-foundry`

A reusable template for building project-specific specification repositories. It is designed for turning rough ideas into handoff-ready spec packages with human-gated AI assistance.

### `codex-pair-spec-template`

A starter repository for spec-first human/Codex collaboration. It provides workflow authority, session handoff structure, and an issue-driven path for implementation work.

### `ricebox`
A Linux CLI that validates themes, inspects app configs, safely applies themes to
supported user config files, and exports native theme files.

### 'warden'
warden is a specification-first systemd backend for ward, implementing deterministic D-Bus unit
control, cgroup attachment, lifecycle reconciliation, and journald integration.

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
