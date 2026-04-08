# Drew Dawson

Building practical local control planes for Claude Code usage.

## Current Focus

[Claude Token Management](https://github.com/DrewDawson2027/claude-token-management) is a public control plane for Claude Code token drain.

Current proof:

- fresh runtime cert: `10/10`
- live hooks: `481 passed`
- live health-check: `42/42`
- drain benchmark: `9/9`
- schemas: `1,307` documents / `0` errors
- coordinator suite: `316/316`

## Why It Matters

Claude Code token drain is often a stack of preventable local failures: bad resume flows, redundant reads, wasteful fanout, weak routing, and missing visibility. This project turns those into guardrails, benchmarks, and certifiable runtime behavior.
