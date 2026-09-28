# AGENTS.md — Funnel-IA Design System
Version: 1.0
Date: 2026-09-28

This repository is the public-safe, versioned visual and UX contract for Funnel-IA.

## Required reading order
Before creating or changing an artifact, read:

1. README.md
2. BRAND.md
3. DESIGN.md
4. context/BRAND_ARCHITECTURE.md
5. context/AUDIENCE.md
6. context/UX_PRINCIPLES.md
7. relevant token files
8. relevant component/pattern documentation
9. STATUS.md and PENDING.md when implementation status matters

## Operating rule
Do not invent a new visual language when a governing token, component or pattern already exists.

## Source-of-truth rule
GitHub is the permanent versioned source of truth.
OpenDesign and other design/build tools may interpret, prototype and generate from this repository, but approved changes return here.

## Security rule
This public repository must never contain:
- passwords
- API keys
- tokens
- PINs
- credentials
- .env contents
- client-confidential information
- private infrastructure details
- internal session transcripts
- restricted prompts or governance material

## Change rule
A proposal becomes part of the design system only after human approval and a versioned commit.

## Definition of done
A design-system change is done when:
- rationale is clear;
- tokens/components/patterns are consistent;
- accessibility and responsive behavior are considered;
- documentation is updated;
- the change is versioned in GitHub.
