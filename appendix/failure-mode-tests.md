# Stress Tests (Appendix)

## Wrong household risk
- If user switches households, the active household name must remain visible.
- Cross-household UUID access must be blocked server-side.

## Duplicate item race
- Canonical normalization is server-owned.
- Unique constraint prevents duplicates within a cart.

## Completion semantics
- “Complete” hides from active list (reversible).
- Activity logs “completed”, never “deleted”.

## Guest continuity
- Guest uses anonymous auth so auth.uid() is never null.
- Guest-created household persists if guest later upgrades.
