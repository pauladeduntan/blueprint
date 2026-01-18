# Invariants (Locked)

These are non-negotiable. If a proposed change violates an invariant, it is not introduced into the research artefact.

## Research Artefact Invariants

1. Emotional Safety Over Optimisation.
2. Visibility Over Reminders.
3. Shared intent visible; no contribution scoring, fairness evaluation, or per-person judgement.
4. Reversibility: actions must not trap Members or force commitment.
5. System-owned language: the UI must not blame, police, or imply obligation.

## High-Stakes Invariants (Handoff Item)

1. Handoff Items are treated as High-Stakes coordination surfaces designed to reveal breakdown and repair dynamics, not to enforce compliance.
2. No reminders, nudges, urgency cues, or escalation mechanics, even for High-Stakes Handoff Items.
3. No blame-attribution defaults: identity display remains system-owned to prevent surveillance interpretations during conflict-prone moments.
4. Reversible outcomes by default: mistakes must be recoverable without requiring permission, justification, or confrontation.

## Current Research Prototype Scope Invariants

1. Single default Shared Cart per Household (one shared list per Household in the current research prototype).
2. No separate event-specific cart surface in the current research prototype; event examples are illustrative only and excluded from the prototype.
3. No push notifications, reminders, or urgency mechanics in the current research prototype.
4. No settlements, reimbursements, or per-person totals. Any cost awareness is limited to reducing surprises and does not introduce tracking or enforcement.
5. Guest-first entry is primary; sign-in is optional and framed as “Save Progress”.

## Data and Governance Invariants (Conceptual)

1. Shared objects are Household-scoped: access is granted only by active membership within a Household boundary.
2. Activity is append-only: actions become visible records and are not user-editable.
3. Activity must not become a performance feed: it must not support per-person views, counts, sorting, grouping, filtering, badges, streaks, or any other performance-like interpretation.
4. System-owned identity display: identity may be reduced (for example “Member” / “Former Member”) to avoid permanent exposure by default.
5. Dynamic identity redaction: when membership ends, historical Activity entries and context sheets must immediately re-render the actor as “Former Member” by default (no persistent name exposure).
6. Non-destructive user-facing state: use visibility states rather than destructive deletion for user-facing objects.
7. Exit safety: when a Member leaves (or is removed), access ends immediately; past actions may remain visible, but identity is not permanently exposed by default.
