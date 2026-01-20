# Failure-Mode Tests (Public-Safe)

These are failure scenarios used to study **visibility-to-enforcement drift** and constrain enforcement interpretations in the research artefact (and any later instantiation derived from it). This is not a test harness or implementation guide.

## FM1: Wrong-Household Action

A Member believes they are in Household B but an action lands in Household A.

- Harm: high (trust breach + interpersonal conflict risk)

## FM2: Irreversible Completion

“Hide Item” behaves like deletion and cannot be safely undone via “Show Again”.

- Harm: an “I ruined it” moment; conflict amplifier

## FM3: Identity Exposure After Exit

Activity permanently exposes a Former Member after they leave or are removed.

- Harm: safety breach; can cause real interpersonal harm

## FM4: Activity Becomes a Performance Feed

Activity feels like surveillance even without scoring.

- Harm: pressure, judgement, disengagement

## Mitigation Principles

- Reversibility by default.
- System-owned language (no blame, no policing).
- Minimum identity exposure necessary for comprehension (system-owned identity rules, including dynamic redaction to “Former Member” after membership ends).
- Anti-amplification guardrails: Activity must not support per-person views, counts, sorting, grouping, filtering, badges, streaks, or any other performance-like interpretation.
- Boundary integrity as a safety property, not a convenience feature.
- High-Stakes Handoff Items amplify these harms and must not introduce urgency, enforcement, or increased attribution pressure as “solutions”. Attribution may exist for active Members, but must remain bounded and system-owned.
