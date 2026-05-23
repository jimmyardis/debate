# ATLAS.md

> This file is maintained by Claude Code and read by Atlas (your AI Chief of Staff).
> You don't need to edit it manually — Claude Code updates it at the end of each work session.

## Meta

| Field | Value |
|-------|-------|
| **Project** | Debate Site (Museum of Minds frontend) |
| **One-liner** | Standalone debate arena and hall-browsing frontend for Museum of Minds historical figures |
| **Status** | building |
| **Last Active** | 2026-05-23 |
| **Stall Threshold** | 7 days |
| **Repo** | git@github.com:jimmyardis/debate.git |
| **Stack** | Static HTML/JS, GitHub Pages |

## Current State

All 4 main halls (observatory, press-room, republic-room, trailblazers), library, and founding-documents halls are built. Constitution card onclick fix committed 2026-05-21. The site hosts the debate arena widget and per-hall persona card grids. This repo is the public-facing frontend; the Railway API backend lives in the jane-jacobs-bot / museum-api Railway service.

## Next Action

Audit hall card grids to confirm all 42 personas have correctly wired cards with working chatbot widgets pointing to the Railway API.

## Blockers

- None

## Open Questions

- Should this repo eventually be renamed from `debate` to `museum-frontend` or similar to reflect its expanded scope?
- KG 3D/VR phase: does the 3d-force-graph integration live here or in museum-of-minds?

## Session Log

<!-- Append-only. Most recent session on top. Claude Code adds an entry at the end of each work session. -->

### 2026-05-23

- Created ATLAS.md for project tracking
- No code changes this session — file placement only
