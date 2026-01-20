# Boundary Integrity Notes (Public-Safe)

## What “Boundary Integrity” Means Here

A Household is a context boundary. The system must never allow a Member to read or write Shared Cart or Activity content for a Household they do not currently belong to.

Boundary integrity constrains **visibility-to-enforcement drift** by blocking wrong-boundary actions from becoming blame evidence or surveillance interpretations.

## Why it Matters (Human Impact)

Boundary violations are not “bugs”; they are trust breaches. The emotional harm is disproportionate because the system can appear to “take sides,” expose private intent, or trigger blame during coordination breakdowns.

## Design Commitments (Conceptual)

- Explicit global switching: the active Household context is always visible.
- Exit safety: when a Member leaves (or is removed), access ends immediately and cannot persist through stale context.
- Exit safety includes display safety: when membership ends, Activity identity rendering must re-render to “Former Member” by default to prevent persistent exposure.
- Boundary validation when changes are recorded: the system records changes only within the active Household boundary for the current Member.

## Intentionally Omitted

Any specific database schema, function signatures, policy code, or operational steps.
