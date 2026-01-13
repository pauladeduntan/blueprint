# System Flows (current research prototype)

## Flow 1: Entry (Guest-first)
1. User opens app → Entry screen.
2. Primary: Continue as guest → anonymous auth → proceed.
3. Secondary: Sign in/sign up → authenticated → proceed.
4. Auth is framed as “Save your progress”, not access control.

## Flow 2: Household Gate
1. On entry, app loads households for current user.
2. If none exist → auto-create first household + shared cart + membership.
3. If one exists → auto-select.
4. If multiple exist → show explicit household switcher.
5. Active household is always visible (context clarity).

## Flow 3: Shared Cart loop
1. User opens shared cart.
2. Adds item (raw text) → system applies canonical naming to prevent duplicates.
3. If duplicate exists → user sees “already in the cart”.
4. Completing an item (or using Hide item) hides it from the active list (non-destructive).
5. Re-adding a completed item restores it (reversible).

## Flow 4: Activity(LOCKED)

Owns: a calm, read-only feed of household list actions.
Must not: become a notification centre, audit log, or judgement feed.

### Included events (LOCKED)
- Member added “Item”
- Member completed “Item”
- Member hid “Item”
- Member showed “Item” again

Optional: a single `Handoff` chip may appear on events involving a handoff item.

### Excluded events (LOCKED)
- No hearts events
- No heart counts
- No `For: <name>` chips in the Activity feed by default
- No handoff type chips in the Activity feed by default
- No “Household name updated”
- No “Household members updated”

### Activity → Activity context sheet (Handoff) (LOCKED)
When an Activity entry involves a handoff item:
- The feed stays minimal (event line + optional `Handoff` chip only).
- Selecting the row opens a read-only `Activity context` view showing:
  - Item name
  - Chips: `Handoff`, `For: <name>`, `<type>` (Pickup/Appointment/Visit/Other)
- Exit safety: if the “For” person is not active, display `Former member` (system-owned).
- The sheet contains no edit actions.

## Flow 5: Multi-household context switch
1. User taps “Switch household”.
2. App changes context explicitly (global).
3. The active Household name updates everywhere the header is shown.
4. Shared Cart and Activity immediately re-scope to the newly selected Household.
5. New context becomes current and persists as last viewed.

See: [Flow artefacts](./flow/)
