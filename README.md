# Drew Dawson

USC senior studying Philosophy, Politics, and Economics, graduating December 2027 and recruiting for Summer 2027 product management internships. I build tools that make AI coding agents prove their work and stop burning through usage limits.

## Featured work

### [Claude Token Management](https://github.com/DrewDawson2027/claude-token-management)

An open-source Claude Code add-on that blocks wasteful AI agent actions before they burn usage limits. I traced runaway usage to 5 causes, like file re-reads, extra sub-agents, and costly models, and added a fix for each. I tuned its limits on 674 real sessions so the hard stop hits under 1% of them and normal work keeps running.

### Agent Completion System

A system that blocks AI agents from claiming a task is done until every required part has proof attached. It connects 4 agent runtimes (Codex, Claude Code, Hermes, Aside) to one shared append-only evidence ledger. It has tracked 7,502 task contracts and 585,899 requirements, and it has blocked 7,056 attempts to finish without full proof. It took 13K lines of Python and 483 tests, and I left 8 metrics blank until real telemetry could measure each one. The code is private, so this write-up is the public record.

### [SkillTrace](https://drewdawson2027.github.io)

Turns a GitHub repository into a live AI interview, verifies each answer against source evidence, and publishes an employer-readable proof card.

### [Repurpose AI](https://github.com/DrewDawson2027/repurpose-api)

A Chrome-extension backend that transforms source content into platform-specific formats using NVIDIA NIM, with licensing and checkout support.

## Current focus

- AI product strategy
- Evidence-backed AI agents
- Systems that make AI work inspectable, reliable, and useful
