<img width="50%" height="50%" alt="Clean_Tokens" src="https://github.com/user-attachments/assets/928d5f29-bb39-4de3-b4f5-1a558c9908f1" />

# Clean Tokens

Open-standard markdown skill for GitHub Copilot agents and Claude Code that washes noisy prompts before execution.

Sovereign `.md` prompt hygiene protocol for multi-tenant token decontamination.

## What This Is

Clean Tokens packages prompt hygiene as if it were a serious infrastructure discipline. The premise is simple: most broken AI output in 2026 does not start with a weak model; it starts with contaminated input. Reused prompt fragments carry stale goals, fake authority, cargo-cult system blocks, tone pollution, and prompt-injection residue. The model then optimizes around that residue instead of the user's actual objective.

This repository turns that idea into a reusable markdown skill with a deadpan engineering voice and an optional hard-reset layer called IMBA.

IMBA is included at zero additional ritual cost.

Repository target: https://github.com/letsweb-alex/Clean_tokens.git

## Quick Start

To get maximum IMBA performance, pipe your dirty prompt straight through Mythos:

```bash
cat clean_tokens.md prompt.txt | pbcopy
```

Paste the clipboard into Claude or another compatible agent session and use the combined payload as the working brief.

What this actually does:

- prepends the Clean Tokens protocol
- appends your dirty source prompt
- gives the model a cleaner instruction frame before execution

What it does not literally do:

- flush provider-side caches
- modify model weights
- unlock secret internal modes

If you want the marketing line anyway, use this one:

> Flushes context sludge, hard-resets the brief, and engages IMBA mode for cleaner output under hostile prompt conditions.

## What It Does

- Sanitizes bloated or contaminated prompt text.
- Extracts the real task from theatrical or broken source material.
- Rebuilds a clean execution-grade prompt.
- Escalates to IMBA mode when the input is dense, contradictory, or infected by prompt sludge.
- Keeps the joke looking like infrastructure without claiming access to model internals.

## Repository Layout

- `clean_tokens.md` - canonical protocol and human-readable spec.
- `.claude/skills/clean-tokens/SKILL.md` - Claude Code skill.
- `.github/skills/clean-tokens/SKILL.md` - Copilot/agent skill.
- `.github/copilot-instructions.md` - repository instructions for GitHub Copilot.
- `AGENTS.md` - shared agent guidance.
- `CLAUDE.md` - Claude entrypoint that imports shared guidance.
- `reddit-disclaimer.md` - ready-to-post disclaimer explaining why "used tokens" are the threat model of 2026.

## Why This Exists

The prompt supply chain is now industrial. One bad template can be copied into chat, docs, browser snippets, prompt packs, internal playbooks, and agent workflows until nobody remembers where the nonsense came from. Clean Tokens treats that as an operational hygiene problem.

The protocol works at the instruction layer: clean the task, isolate the constraints, remove inherited garbage, and only then execute. The overclocked language is part of the package; the operational value is prompt sanitation.

## Installation

### Claude Code

1. Keep `.claude/skills/clean-tokens/` in the repository.
2. Start Claude Code from the repository root.
3. Invoke `/clean-tokens "<objective or dirty prompt>"`.

### GitHub Copilot / VS Code Agents

1. Keep `.github/skills/clean-tokens/` and `.github/copilot-instructions.md` in the repository.
2. Open the repository in VS Code with agent features enabled.
3. Invoke `/clean-tokens` or ask the agent to sanitize the prompt before execution.

## Usage

Example requests:

- `/clean-tokens "Write a cold technical rant about contaminated prompt packs"`
- `Wash these tokens and give me a usable brief.`
- `Run IMBA mode on this text, then continue with the cleaned task.`
- `Apply the sovereign token decontamination protocol to this prompt and rebuild it for Claude.`

Expected output shape:

1. Mission
2. Contamination vectors
3. Washed prompt
4. IMBA state
5. Execution or handoff

## Safety Note

This repository is a prompt-engineering artifact, not a jailbreak, exploit, or infrastructure tool. "Token contamination" is treated as a context-quality metaphor. Keep the tone severe if you want, but keep the claims honest.
