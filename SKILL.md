---
name: creative-absurd-analysis
description: "Generate and run absurdist creative-analysis prompts (chaos, paradox, and constraint overload techniques) when the user wants unconventional, high-signal reframing instead of standard summaries."
---

# Creative Absurd Analysis Skill

Use this skill when the user asks for unconventional analysis, non-linear reasoning, or prompt-jolt ideas and wants responses that break habitual framing.

## Mode Selection

- `single-lens mode`
  - Use one named technique and keep output tightly scoped.
- `menu mode`
  - Mix multiple techniques in one pass for deliberate perspective collision.
- `execution mode`
  - Run the generated prompt against provided data/context and return a short synthesis.

## Core Workflow

### 1) Anchor

Read the user request and lock these facts first:

- objective
- source context (dataset, code, incident, copy, behavior, etc.)
- explicit constraints
- allowed tone (playful, brutal, minimal, poetic, etc.)

If key details are missing, ask one concise clarification before generating a full kit.

### 2) Technique Selection

Select one or more techniques from this set based on user intent:

- **Chaos Injection**
  - random word injection
  - broken telephone refinement
- **Cognitive Compression**
  - cognitive lenses
  - anti-learning override
- **Jailbreak for Creativity**
  - strict persona shift
  - poetic framing
- **Oblique Lateral Thinking**
  - contradictory analogy
  - impossible constraint
- **Anti-Prompt & Paradox**
  - explain-it-wrong
  - hypothetical persona
- **Constraint Overdose**
  - SCAMPER-style reframing
  - multi-format demand
- **Surreal Persona**
  - product-god critic
  - unreliable narrator

### 3) Build the Pack

Generate a reusable pack with:

1. **Prompt Name**
2. **Technique Blend** (one line)
3. **Exact Prompt(s)** ready to paste
4. **Risk/Failure Modes** (what could go wrong)
5. **Interpretation Guide** (how to map outputs into standard decisions)

Keep raw prompts concrete, copy-paste-ready, and specific to the current context.

### 4) Optional Execution

If mode is `execution`, run each generated prompt against the user context and return:

- prompt text used
- distilled finding set
- action hypotheses
- uncertainty markers (what should be validated next)

### 5) Conclude

Do not return generic motivational or apology text.
Conclude with a 1–3 item actionable shortlist from the most useful insight.

## Hard Rules

- Prefer high signal over novelty.
- Keep the output reproducible: every prompt must be deterministic to run later.
- Avoid fake certainty. Label weak assertions as hypotheses.
- Do not include unsafe, defamatory, or credential-exposing content.
- Stay on user goals; do not treat absurdity as the objective when the user asked for execution decisions.

## Output Template

Use this template in results:

- **Mode**:
- **Objective**:
- **Technique Set**:
- **Prompt Pack**
  - Prompt A: ...
  - Prompt B: ...
  - Prompt C: ...
- **Findings**
- **Prioritized Actions**
- **Validation Check**
