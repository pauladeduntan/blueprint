# Invariants (LOCKED)

These are non-negotiable. If a feature violates an invariant, it does not ship.

## Product invariants
1. Emotional safety over optimisation.
2. Visibility over reminders.
3. Shared intent visible; no contribution scoring, fairness evaluation, or per-person judgement.
4. Reversibility: actions should not trap users or force commitment.
5. System-owned language: the UI must not blame or police.

## MVP scope invariants
1. Single default household cart (one shared list per household in MVP).
2. No Event Cart UI in MVP; event flows are post-MVP illustrative only.
3. No push notifications, reminders, or urgency mechanics in MVP.
4. No settlements, reimbursements, or per-person totals (cost awareness = reduce surprises only).
5. Guest-first entry is primary; auth is optional and framed as “save progress”.

## Data invariants
1. Server-owned canonical keys for item dedupe.
2. Membership checks on every privileged RPC.
3. Activity is append-only (no user edits). Identity display is system-owned and may be anonymised for inactive/removed members.
4. Soft state (visibility flags) instead of destructive deletes for user-facing objects.
5. Data ownership is household-scoped: shared objects exist within a household boundary; access is granted only by active membership.
6. Exit safety: when a member leaves (or is removed), access is revoked immediately. Past actions may remain in Activity, but identity must not be permanently exposed by default (system-owned “Member/Former member” labels).
