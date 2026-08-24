# Site Documentation & Unified Agent Skill — Requirements

**Date added:** 2026-05-17
**Status:** Planning only. Nothing in this document is built yet.

This is the VoxGuion-side mirror of the same planning items recorded in
`vinetas.github.io/docs/requirements.md` under "Documentation & Agent Skill".
Keep both files in rough sync as the work progresses.

---

## 1. Unified agent skill: `voxguion-vinetas-cli`

A single Claude Code agent skill that drives **both** VoxGuion (audio /
podcast generation from screenplays) and Vinetas (on-device storyboard panel
generation) from the command-line agent.

- **Scope:** one skill, two products. The skill must dispatch to the right CLI
  based on the user's intent (audio vs. storyboard).
- **Coverage required in the skill's own docs:**
  - **Basic operation** — installation prerequisites, model / AI Model download,
    project layout, authentication / signing, where outputs land.
  - **Generation** — for VoxGuion: screenplay-to-audio options, voice
    casting, batch mode, progress streaming, error categorization. For Vinetas:
    prompt / style / aspect-ratio options, seed control, exporting panels.
- **Existing draft:** `Docs/AI_AGENT_SKILL.md` covers the VoxGuion half at
  the requirements level. Use it as the starting point for the VoxGuion
  surface of the unified skill.
- **Open questions:**
  - Single binary with subcommands (`voxguion-vinetas-cli voxguion batch …`
    / `voxguion-vinetas-cli vinetas generate …`) or two thin wrappers + one
    shared skill manifest?
  - Where the skill lives: this repo, the Vinetas repo, or a third dedicated
    repo?

## 2. Public "Documentation" section on each site

Both the VoxGuion site and `vinetas.app` must surface a public-facing
**Documentation** section covering basic operation and generation for end users
(separate from the agent-skill docs above).

- **VoxGuion site (`_docs/`):** scaffold exists (`getting-started.md`,
  `importing-screenplays.md`, `generating-audio.md`, `file-formats.md`,
  `exporting.md`, `elevenlabs-api.md`). Audit each page for basic operation +
  generation coverage; fill gaps.
- **Vinetas site (`_docs/`):** scaffold exists (`getting-started.md`,
  `ai-models.md`, `styles-and-aspect-ratios.md`). Audit pages and fill in basic
  operation and generation.
- **Linking:** the unified agent skill's docs should link to both sites'
  Documentation sections as the canonical user-facing reference.
