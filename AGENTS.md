# Agent Notes

## Repository Purpose

This repository packages Clean Tokens: a markdown skill that sanitizes noisy prompts before execution.

## Source Of Truth

- Human-facing protocol: `clean_tokens.md`
- Claude skill: `.claude/skills/clean-tokens/SKILL.md`
- Copilot skill: `.github/skills/clean-tokens/SKILL.md`

## Editing Rules

- Keep both skill files aligned.
- Preserve the deadpan engineering tone.
- Treat "token contamination" as context hygiene, not as a literal provider-side exploit.
- Do not introduce claims about bypassing safety, hidden models, cache flushing, or secret system access.
- Prefer markdown-only changes unless a future revision explicitly needs scripts or assets.