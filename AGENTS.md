# AGENTS.md — Daisy Learn Assets

Primary guidance for AI agents working with this audio/media asset repository.

## Repository Purpose

Static media assets for the **Daisy Learn App** — audio recordings for Japanese N5/N4 listening and speaking exercises.

## Structure

```
daisy-learn-assets/
├── n5-listening/     # N5 level listening audio files
├── n5-speaking/      # N5 level speaking/pronunciation audio files
├── n4-listening/     # N4 level listening audio files
└── n4-speaking/      # N4 level speaking/pronunciation audio files
```

## Asset Conventions

- Audio files are referenced by `daisy-learn-app` at build/runtime
- File naming must match the vocabulary/exercise IDs used in `daisy-learn-app/src/data/`
- Format: MP3 preferred for cross-platform React Native compatibility

## Agent Definitions

Place agent `.md` files in `.agents/` — Claude Code reads them via `.claude/agents/` symlink.

## Project Rules

Place rule `.md` files in `.rules/` — Claude Code reads them via `.claude/rules/` symlink.

## Slash Commands / Prompts

Place prompt `.md` files in `.prompts/` — Claude Code reads them via `.claude/commands/` symlink.
