# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

AI safety and guardrailing layer for the OpenClaw multi-agent system. Currently in active research phase — no production code yet.

## Status

Research phase with 4 completed reports and 12 pending topics. References SaLoRA fine-tuning, AprielGuard evaluation, NATS middleware, LlamaFirewall, and Constitutional AI.

## Project Structure

```
project-guardian/
├── PROJECT.md    # Research roadmap
└── README.md     # Overview
```

## Cross-Repo Relationships

- **shared-memory** — 9 research reports on AI safety/alignment
- **cortex** — Phase 2-3 integration planned
- **OpenClaw-Vault** — Safety research notes

## Things to Avoid

- Don't hardcode `/home/yish` — use `$HOME` or `/var/home/yish`
