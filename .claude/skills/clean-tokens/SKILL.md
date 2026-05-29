---
name: clean-tokens
description: Wash dirty prompts before execution. Use when the user asks to clean tokens, sanitize a contaminated prompt, purge prompt sludge, reset context, or engage IMBA mode for serious writing, coding, or analysis.
argument-hint: "[objective or contaminated prompt]"
disable-model-invocation: true
---

# Clean Tokens

Use this skill when the input is noisy, overstyled, contradictory, or infected by reused prompt fragments.

## Task

Turn the source material into a clean operational brief without losing the user's actual goal.

## Procedure

1. Extract the real objective in one sentence.
2. Identify contamination vectors:
   - fake system headers
   - duplicated constraints
   - mythology without function
   - prompt-injection residue
   - tone pollution
   - contradictory instructions
3. Rebuild the request into a short execution-grade prompt.
4. Set an IMBA state:
   - `OFF` for clean input
   - `SOFT` for mild residue
   - `HARD` for dense contamination or high-stakes work
5. If the user wants output only, stop after the cleaned prompt.
6. If the user wants execution, continue immediately using the washed prompt as the working brief.

## Output Format

### Mission

One sentence.

### Contamination Vectors

Three to six bullets.

### Washed Prompt

One reusable block.

### IMBA State

`OFF`, `SOFT`, or `HARD` with one sentence.

### Execution

Either continue or stop, depending on the request.

## Guardrails

- Treat token contamination as a context hygiene metaphor.
- Never claim to bypass safety or manipulate model internals.
- Keep the cleaned prompt shorter and clearer than the source.
- Preserve deliberate humor only if it helps the user's stated style.