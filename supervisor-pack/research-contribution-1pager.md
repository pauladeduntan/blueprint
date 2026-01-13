# Research Contribution — KinCart

## Working Title
Shared-Intent Coordination in Households: Making Visibility Safe Without Enforcement

## Problem
In shared households, coordination tools can reduce ambiguity but often increase emotional load by introducing accountability cues such as nudges, reminders, “overdue” states, or performance-like feeds. These cues can shift coordination from shared intent toward perceived management, increasing friction and risking trust breakdown, particularly in situations where coordination is informal and authority is weak.

These risks are amplified in **high-stakes coordination moments**, such as handoffs involving appointments, care, or time-sensitive responsibility. In such cases, mistakes are socially costly, and visibility can quickly become blame if not carefully constrained.

## Core Idea
KinCart investigates a constraint-first alternative: **making shared intent visible while preserving emotional safety**. It is intentionally not a task manager and avoids enforcement mechanics. Handoff scenarios are included deliberately as **high-stakes coordination probes** where pressure, interpretation risk, and breakdown are more likely to surface.

## Research Contributions
1) **Constraint-first framework** for household coordination systems, defined by explicit invariants:
   - Emotional safety over optimisation  
   - Visibility over reminders  
   - Reversibility by default  
   - System-owned language (no blame or policing)

2) **Domain language as a safety mechanism** that prevents scorekeeping and attribution drift (e.g., “completed,” “save progress,” “former member”), treating labels as coordination cues rather than neutral copy.

3) **Failure-aware interaction contracts** that surface high-risk breakdowns during handoffs, and make them legible for qualitative study (e.g., wrong-household actions; identity exposure after leaving or removal).

4) **Decision discipline as method**, using explicit decision records and anti-drift gates to keep public artefacts conceptually consistent while intentionally avoiding implementation recipes.

## What Exists Today (Research Materials)
- A high-fidelity prototype demonstrating key interaction contracts, including explicit household switching, reversible completion, restrained Activity visibility, and contextual handling of high-stakes handoffs.
- A public blueprint and decision records documenting design constraints and scope boundaries, used to maintain interpretive consistency rather than as empirical evidence.

## Research Questions (Examples)
- How do interface cues (language, visibility, reversibility) shape perceived pressure, trust, and conflict risk in **high-stakes household handoffs**?
- What constraints prevent a visibility system from drifting into a performance or management feed when coordination stakes are high?
- How does system-owned representation of responsibility and identity affect safety, interpretation, and repair after handoff failures or membership changes?

## Methods
- Diary studies and interviews with households to capture lived coordination breakdowns, with particular attention to handoff-related moments.
- Prototype-based interpretive comparison, discussing constraint-first KinCart patterns alongside familiar coordination approaches rather than benchmarking performance.
- Optional lightweight interaction logging limited to interaction types only (ethics-approved, privacy-first, no scoring, no per-person metrics).

## Fit
HCI and CSCW communities focused on domestic computing, shared-access systems, coordination and collaboration, values-aware design, and safety-aware interaction.

## Ethics and Positioning
KinCart is a **non-commercial research artefact**. The work is explicitly designed to avoid judgement, enforcement, urgency, and surveillance cues—especially in high-stakes handoff contexts where interpersonal harm risk is greatest.
