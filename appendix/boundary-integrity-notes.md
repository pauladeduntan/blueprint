# Schema Lock Pack (Appendix)

## Non-negotiable schema properties
- Membership-gated access everywhere (RLS + RPC checks).
- Item canonical_key computed server-side.
- Single shared cart per household in MVP (default cart).
- Activity append-only.
- Prices stored in minor units (pence) if cost awareness is enabled later.

## Non-negotiable implementation properties
- SECURITY DEFINER RPCs must verify membership.
- No client-owned canonical keys.
- No destructive deletes for user-facing objects in MVP.
