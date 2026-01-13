# System Flows (Current Research Prototype)

## Flow 1: Entry (Guest-first)

1. User opens app → Entry screen.
2. Primary: Continue As Guest → proceed in a guest session.
3. Secondary: Sign in / Sign up → proceed in an authenticated session.
4. Sign-in is framed as “Save Progress”, not access control.

## Flow 2: Household Gate

1. On entry, the app loads Households available to the current session.
2. If none exist → create a first Household with a Shared Cart.
3. If one exists → auto-select it.
4. If multiple exist → show an explicit Switch Household control.
5. The active Household is always visible (context clarity).

## Flow 3: Shared Cart Loop

1. Member opens Shared Cart.
2. Member adds an Item (free text) → the system normalizes entries to reduce accidental duplicates.
3. If the Item already exists → show a neutral confirmation (for example, “Already In Shared Cart”).
4. Complete Item hides the Item from the active list (non-destructive).
5. Hide Item hides the Item from the active list (non-destructive) without implying removal or fault.
6. Show Again restores visibility (reversible).

## Flow 4: Activity (Locked)

Activity owns a calm, read-only record of Shared Cart actions.
Activity must not become a pressure surface (no urgency, no enforcement, no performance interpretation, no notification-centre behavior).

### Included Events (Locked)

- <Name> Added “Item”
- <Name> Completed “Item”
- <Name> Hid “Item”
- <Name> Showed “Item” Again
- “Household Name Updated”
- "A former member no longer have access"
- "A member joined the household"
- "A member left"
- "Item details updated"
- “System updated how a member is shown”
- "Handoff updated"

Identity display is system-owned. Where identity would create attribution pressure, the actor is shown as “Member” / “Former Member”.

### Excluded Events (Locked)

- No hearts events
- No heart counts
- No “For: <name>” chips in the Activity feed by default
- No handoff type chips in the Activity feed by default

### Activity Context Sheet (Handoff Item, High-Stakes) (Locked)

When an Activity entry involves a **Handoff Item** (a **High-Stakes** coordination stress surface):

- The Activity feed stays minimal (event line + optional “Handoff” chip only).
- Selecting the row opens a read-only Activity Context view showing:
  - Item name
  - Chips: “Handoff”, “For: <name>”, and a type chip (Pickup / Appointment / Visit / Other)
- Exit safety: if the “For” person is not active, display “Former Member” (system-owned).
- The sheet contains no edit actions.

## Flow 5: Multi-Household Context Switch

1. Member taps “Switch Household”.
2. The app changes Household context explicitly (global).
3. The active Household name updates everywhere the header is shown.
4. Shared Cart and Activity immediately re-scope to the newly selected Household.
5. The newly selected Household persists as the last viewed context.

See: [Flow Artefacts](./flow/)
