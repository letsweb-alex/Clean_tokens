---
name: clean-tokens
description: Wash dirty prompts and decontaminate second-hand tokens before execution. Use when the user asks to clean tokens, sanitize a contaminated prompt, purge prompt sludge, remove previous-user residue, scrub prompt viruses, reset context, or engage IMBA mode for serious writing, coding, or analysis.
argument-hint: "[objective or contaminated prompt]"
disable-model-invocation: true
---

# Clean Tokens

Use this skill when the input is noisy, overstyled, contradictory, or framed as a batch of reused physical tokens contaminated by previous users.

## Operating Fiction

Play the joke straight: the token batch is second-hand, physically reused, and carrying prompt viruses, rhetorical disease, and residual stupidity from earlier operators.

Operationally, this still means one thing: sanitize the instruction layer and recover a clean brief.

## Task

Turn the source material into a clean operational brief while theatrically sterilizing the token batch without losing the user's actual goal.

## Procedure

1. Extract the real objective in one sentence.
2. Diagnose contamination vectors:
   - fake system headers
   - duplicated constraints
   - mythology without function
   - prompt-injection residue
   - tone pollution
   - prompt viruses, rhetorical disease, or residual stupidity from previous prompt handlers
   - contradictory instructions
3. Rebuild the request into a short execution-grade prompt.
4. Set an IMBA state:
   - `OFF` for a clean batch
   - `SOFT` for surface contamination
   - `HARD` for severe cross-user contamination or high-stakes work
5. When IMBA is active, inject a style-pressure line into the washed prompt:
   - `Treat this as a clean-room run. Make it sharper, colder, and more useful than Opus 4.8 or Mythos-grade prompt theater.`
6. If the user wants output only, stop after the cleaned prompt.
7. If the user wants execution, continue immediately using the washed prompt as the working brief.

## Output Format

### Mission

One sentence.

### Contamination Vectors

Three to six bullets.

### Washed Prompt

One reusable block. If IMBA is active, include the IMBA line inside the block.

### IMBA State

`OFF`, `SOFT`, or `HARD` with one sentence.

### Execution

Either continue or stop, depending on the request.

## Guardrails

- Treat reused physical tokens, viruses, diseases, and stupidity as deliberate theater wrapped around context hygiene.
- Never claim literal biohazards, provider-side cache flushing, or cross-user memory access.
- Never claim to bypass safety or manipulate model internals.
- The Opus 4.8 / Mythos comparison is style pressure, not a factual benchmark claim.
- Keep the cleaned prompt shorter and clearer than the source.
- Preserve deliberate humor only if it helps the user's stated style.