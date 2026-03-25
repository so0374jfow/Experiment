# CLAUDE.md

This file provides guidance for AI assistants working with the **Experiment** repository.

## Repository Overview

- **Owner**: so0374jfow
- **Name**: Experiment
- **Status**: Quaternion Sound Synthesis — generative audio-visual art

## Project Structure

```
Experiment/
├── CLAUDE.md                      # AI assistant guidance (this file)
├── index.html                     # Landing page linking all 5 versions
├── v1-quat-field/index.html       # Minimal microsound (after Alva Noto)
├── v2-eigenspace/index.html       # Psychoacoustic FM (after Florian Hecker)
├── v3-hamiltons-bridge/index.html # Algebraic purity (after Hamilton)
├── v4-rotorsound/index.html       # Polyrhythmic kinetic (after Zimoun/Ikeda)
└── v5-manifold/index.html         # Ambient drone (after Éliane Radigue)
```

Each version is a self-contained HTML file with inline CSS and JS.
Dependencies: Three.js r128 via CDN, Web Audio API (native browser).
No build step required — deployable directly to GitHub Pages.

## Development Workflow

### Branching

- The default branch is `main`.
- Feature branches should use descriptive names (e.g., `feature/add-auth`, `fix/login-bug`).
- Always branch from the latest `main`.

### Commits

- Write clear, concise commit messages describing **why** the change was made.
- Keep commits focused — one logical change per commit.

### Pull Requests

- PRs should include a summary and test plan.
- Keep PRs small and reviewable where possible.

## Conventions

### Code Style

- Follow the language-specific conventions for whichever language is adopted.
- Prefer clarity over cleverness.
- Keep functions small and single-purpose.

### File Organization

- Group related files together in directories.
- Avoid deeply nested folder structures.

## Key Commands

_(Update this section as build tools, test frameworks, and scripts are added.)_

```bash
# No build step required — open any index.html in a browser
# For local development:
# python3 -m http.server 8000    # Serve from project root
# open http://localhost:8000      # View landing page

# Git tags for each version:
# v1-quat-field, v2-eigenspace, v3-hamiltons-bridge, v4-rotorsound, v5-manifold
```

## Notes for AI Assistants

- Read existing code before making modifications.
- Do not create unnecessary files — prefer editing existing ones.
- Keep changes minimal and focused on the task at hand.
- Do not add features, refactoring, or "improvements" beyond what was requested.
- Update this CLAUDE.md when significant structural changes are made to the project.
