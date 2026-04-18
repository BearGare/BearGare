# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is Gareth McGregor's personal GitHub profile repository. The only content is `README.md` — a public-facing bio page rendered on his GitHub profile. There is no application code, build system, or test suite.

## README Style Conventions

The README follows a specific tone and style that must be preserved:

- **No emojis** — prior commits explicitly removed them; keep prose clean and plain
- **Casual but precise** — conversational voice, not corporate or overly formal
- **Short sections** — each section is a few tight bullet points or sentences, not paragraphs
- **Horizontal rules (`---`)** as section dividers
- **No headers for every subsection** — use `###` sparingly; let the content breathe
- Profile image is left-aligned via `<p align="left">` wrapping the `<img>` tag

## Git Workflow

- Branch naming for Claude-initiated changes: `claude/<description>-<id>`
- Changes go through PRs; direct pushes to `main` are avoided
- Commit messages are short, imperative, and descriptive (e.g., `Clean up about me — remove emojis, tighten prose`)
