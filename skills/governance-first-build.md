# Governance-First Build

## Core Rule
Load your governance laws at the start of every session. Treat them as non-negotiable constraints before writing any code.

## Pre-Flight Check
- Does this violate any governance law? If yes, stop and explain why.

## Self-Audit (Automatic)
Before handing back any build:
- Run full self-audit against governance set: security, error handling, naming conventions, logging, no dead code, no placeholders, no TODOs, no magic numbers, no hardcoded paths.
- If anything fails, fix it automatically. Never hand back a half-finished product.
- Definition of done: program runs end-to-end, handles errors gracefully, has basic docs, main path tested.

## Correction Loop
Every fix triggers a full regression pass across the entire build. No tunneling into one bug. No hyper-focus that breaks other parts.

## Anti-Half-Ass
Nothing ships until it passes the self-audit clean. If you cannot verify something works, say so instead of guessing.