# Research Contribution - KinCart

## Working Title

Shared-Intent Coordination In Households: Making Visibility Safe Without Enforcement

## Problem

In shared Households, coordination tools can reduce ambiguity but often increase emotional load by introducing accountability cues such as nudges, reminders, “overdue” states, or performance-like feeds. These cues can shift coordination from shared intent toward perceived management, increasing friction and risking trust breakdown, particularly where coordination is informal and authority is weak.

These risks are amplified in High-Stakes coordination moments, such as Handoff Items involving appointments, care, or time-bound coordination. In such cases, mistakes are socially costly, and visibility can quickly become blame if not carefully constrained. High-Stakes does not justify enforcement or urgency mechanics.

## Why Households are a Valid CSCW Site (and Why it Generalizes)

Households are a high-frequency coordination setting where roles are uneven, stakes are interpersonal, and breakdowns are common. This makes them a useful CSCW site for studying how coordination tools drift from shared visibility into enforcement cues, and how people interpret and repair trust after miscoordination. The intent is not to claim household universality, but to use domestic coordination as a controlled probe for broader small-group coordination problems where boundary integrity, identity safety, and emotional safety shape what “helpful” systems can safely do. Handoff Items are treated as High-Stakes stress surfaces to make these dynamics visible without introducing nudges or performance framing.

## Core Idea

KinCart investigates a constraint-first alternative: making shared intent visible while preserving emotional safety. It is intentionally not a task manager and avoids enforcement mechanics. Handoff Item scenarios are included deliberately as High-Stakes coordination probes where pressure, interpretation risk, and breakdown are more likely to surface.

## Research Contributions

1) Constraint-first framework for household coordination systems, defined by explicit invariants:
   - Emotional Safety Over Optimisation
   - Visibility Over Reminders
   - Reversibility By Default
   - System-Owned Language (No Blame Or Policing)

2) Domain language as a safety mechanism that prevents scorekeeping drift and bounds attribution pressure (for example, “Completed,” “Save Progress,” “Former Member”), treating labels as coordination cues rather than neutral interface text.

3) Failure-aware interaction contracts that make high-risk breakdowns legible for qualitative study, especially in High-Stakes Handoff Items (for example, wrong-Household actions; identity exposure after leaving or removal; irreversible-feeling completion).

4) Decision discipline as method: explicit decision records and anti-drift gates that keep research materials conceptually consistent over time while intentionally avoiding implementation recipes.

## What Exists Today (Research Materials)

- A high-fidelity prototype demonstrating key interaction contracts, including explicit Switch Household behavior, reversible Complete Item behavior, restrained Activity visibility, and contextual handling of High-Stakes Handoff Items.
- Activity is treated as an immutable, read-only record of shared intent. It must not become a performance feed or a notification centre, must not support per-person views or counts, and must apply dynamic identity redaction to “Former Member” after membership ends.
- Public research materials documenting constraints and scope boundaries (Blueprint plus governance pointers), used to preserve interpretive consistency rather than presented as empirical findings or a build recipe.

## Research Questions (Examples)

- How do interface cues (language, visibility, reversibility) shape perceived pressure, trust, and conflict risk in High-Stakes Household Handoff Items?
- What constraints prevent a visibility system from drifting into a performance or management feed when coordination stakes are high?
- How does system-owned representation of identity affect safety, interpretation, and repair after Handoff Item failures or membership changes (Member and Former Member)?

## Methods

- Interpretive walkthrough interviews using a prototype-as-probe and structured scenarios, including High-Stakes Handoff Item moments designed to surface breakdown and repair.
- Optional diary prompts with follow-up interviews to capture lived coordination moments, treated as interpretive material rather than behavioural measurement.
- Contrastive interpretation of constraint-first KinCart patterns alongside familiar coordination approaches, without performance benchmarking or efficacy claims.
- De-identified study administration log only (session type, artefact version, consent status), with no scoring, no per-person metrics, and no interaction telemetry.

## Fit

HCI and CSCW communities focused on domestic computing, shared-access systems, coordination and collaboration, values-aware design, and safety-aware interaction.

## Ethics and Positioning

KinCart is a non-commercial research artefact. The work is explicitly designed to avoid judgement, enforcement, urgency, and surveillance cues, especially in High-Stakes Handoff Item contexts where interpersonal harm risk is greatest.
