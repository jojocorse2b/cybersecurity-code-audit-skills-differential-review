# differential-review

"Performs security-focused differential review of code changes. Adapts analysis depth to codebase size, uses git blame for context, calculates blast radius by counting callers, checks test coverage of modified code, and generates a markdown report. Use when reviewing a PR, commit, or diff for security vulnerabilities, checking whether a change re-introduces a previously fixed bug, asking what else a change could break, or finding which modified code has no test covering it."

## Overview

This directory contains the operational guidance for the `differential-review` skill. Start with [SKILL.md](SKILL.md), which defines when to use it and the workflow it provides.

## Usage

Install or reference this directory through your agent's skill-discovery mechanism, then invoke `differential-review` when the task matches the description above. Review linked resources in `SKILL.md` only when that workflow calls for them.

## Included resources

- `adversarial.md` — supporting material for this skill.
- `agents` — supporting material for this skill.
- `assets` — supporting material for this skill.
- `methodology.md` — supporting material for this skill.
- `patterns.md` — supporting material for this skill.
- `reporting.md` — supporting material for this skill.
