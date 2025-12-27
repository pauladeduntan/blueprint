# Boundary integrity notes (public-safe)

## What “boundary integrity” means here
A Household is a context boundary. The system must never allow a user to read/write across the wrong boundary without explicit, valid membership.

## Why it matters (human impact)
Boundary violations are not “bugs”; they are trust breaches. The emotional harm is disproportionate because the system appears to “take sides” or create blame.

## Design commitments (conceptual)
- Explicit global switching: the active Household context is always visible.
- Exit safety: leaving/removal ends access immediately (no lingering access by cached context).
- Privileged actions re-check boundary validity at execution time (not just in UI).

## Intentionally omitted
Any specific database schema, function signatures, policy code, or operational steps.
