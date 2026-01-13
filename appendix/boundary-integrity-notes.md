# Boundary Integrity Notes (Public-Safe)

## What “Boundary Integrity” Means Here

A Household is a context boundary. The system must never allow a Member to see or change Shared Cart or Activity content for a Household they do not currently belong to.

## Why it Matters (Human Impact)

Boundary violations are not “bugs”; they are trust breaches. The emotional harm is disproportionate because the system can appear to “take sides,” expose private intent, or trigger blame during coordination breakdowns.

## Design Commitments (Conceptual)

- Explicit global switching: the active Household context is always visible.
- Exit safety: when a Member leaves (or is removed), access ends immediately and cannot persist through stale context.
- Boundary validation at the moment of action: when the system accepts a change, it confirms the Household boundary is valid for the current Member.

## Intentionally Omitted

Any specific database schema, function signatures, policy code, or operational steps.
