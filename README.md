# Humanizer Skill

A cross-agent writing skill for making AI-assisted prose more natural, specific, purposeful, and consistent with an author's voice.

> Humanizer is a writing-quality tool, not a detector-evasion guarantee. AI-writing signals are probabilistic and can also occur in entirely human writing.

## What it targets

Humanizer reviews clusters of patterns commonly associated with AI-assisted prose: generic framing, repetitive structures, inflated language, vague claims, excessive hedging, formulaic transitions, repetitive rhythm, corporate phrasing, and summary padding.

These are signals, not proof.

## Quick start

Claude Code: `.claude/skills/humanizer/SKILL.md`

Codex-style skills: `.agents/skills/humanizer/SKILL.md`

Generic agents: use `skill/core.md` or `adapters/generic/INSTRUCTIONS.md`.

## Workflow

1. Preserve meaning and facts.
2. Identify audience, purpose, and intended voice.
3. Diagnose patterns before rewriting.
4. Make the smallest changes that materially improve the prose.
5. Restore concrete details and authentic rhythm where supported.
6. Read the complete result as one piece.
7. Run the final checklist.

An author sample is the strongest input when available.

## Repository

- `skill/` — portable core, patterns, checklist, examples
- `adapters/` — Claude, Codex, and generic adapters
- `docs/` — research, installation, configuration, evaluation
- `examples/` — worked examples
- `tests/` — qualitative regression cases
- `.github/` — CI and contribution templates

## Principles

Humanizer does not use a giant list of banned "AI words." That approach is brittle and can create another artificial style.

Priority: **meaning → voice → specificity → rhythm → clarity → polish**.

## Responsible use

Do not fabricate experiences, evidence, citations, quotations, credentials, or authorship. Do not introduce fake mistakes solely to appear human.

See `docs/research.md` for limitations and evidence.

## License

MIT.
