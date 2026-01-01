# Research contribution — KinCart

## Working title
Shared-intent coordination in households: visibility without enforcement or emotional pressure

## Problem
In shared households, coordination tools can reduce ambiguity but increase emotional load by introducing accountability cues (nudges, reminders, “overdue” states, performance-like feeds). These cues can shift coordination from “shared intent” to perceived management, increasing friction and risking trust breakdown.

## Core idea
KinCart investigates a constraint-first alternative: **make shared intent visible while preserving emotional safety**. It is intentionally not a task manager and avoids enforcement mechanics.

## Research contributions
1) **Constraint-first framework** for household coordination systems, defined by invariants:
   - Emotional safety over optimisation
   - Visibility over reminders
   - Reversibility by default
   - System-owned language (no blame or policing)
2) **Domain language as a safety mechanism** that prevents scorekeeping drift (e.g., “shared intent visible”, “completed”, “save progress”, “former member”).
3) **Failure-aware interaction contracts** that surface high-risk breakdowns explicitly (e.g., wrong-household actions; identity exposure after leaving/removal).
4) **Governance as method**: decision hygiene + anti-drift gates that keep public artefacts consistent while avoiding implementation recipes.

## What exists today (evidence)
- High-fidelity prototype demonstrating key interaction contracts (explicit household switching; reversible completion; readable Activity).
- Public blueprint + governance artefacts documenting constraints, decisions, and trade-offs (non-commercial research framing).

## Research questions (examples)
- How do interface cues (language, reversibility, visibility) change perceived pressure, trust, and conflict risk in household coordination?
- What constraints prevent a visibility system from becoming a performance feed?
- How does system-owned identity representation affect safety and relational dynamics after membership changes?

## Methods
- Diary + interviews with households to capture lived breakdowns and emotional load.
- Prototype-based comparative evaluation (constraint-first KinCart patterns vs conventional coordination patterns).
- Optional lightweight interaction logging (ethics-approved, privacy-first, no scoring).

## Fit
ACM CSCW/CHI/UbiComp communities focused on domestic computing, CSCW, values-aware design, and safety-aware interaction.

## Ethics/positioning
KinCart is a **non-commercial research artefact**. The work is designed to avoid judgment and enforcement cues and to reduce interpersonal harm risk in household settings.
