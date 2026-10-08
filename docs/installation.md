# Installation

Humanizer is portable. Exact user-level paths can vary by host version.

## Claude Code

Copy `adapters/claude/SKILL.md` to a supported Claude skills directory as `humanizer/SKILL.md`. For project-local use, keep it under `.claude/skills/humanizer/SKILL.md`.

## Codex

Copy `adapters/codex/SKILL.md` to the supported Codex skills directory. For project-local use, use `.agents/skills/humanizer/SKILL.md` where supported by your installed version.

## Other agents

Use `adapters/generic/INSTRUCTIONS.md` or paste `skill/core.md` into the agent's project/system instructions.

Platform conventions change. The core is intentionally vendor-neutral so adapters can change independently.
