# System Flows (Current Research Prototype)

These flows support interpretive study of **visibility-to-enforcement drift** in Households by specifying observable behavior without introducing reminders, scoring, or urgency cues. Prototype materials and flows are used as probes for interpretive inquiry, not findings.

## Flow 1: Entry (Guest-First)

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
2. Member adds an Item (free text) → the system normalizes entries to limit accidental duplicates.
3. If the Item already exists → show a neutral confirmation (for example, “Already In Shared Cart”).
4. Complete Item hides the Item from the active list (non-destructive).
5. Hide Item hides the Item from the active list (non-destructive) without implying removal or fault.
6. Show Again restores visibility (reversible).

## Flow 4: Activity (Locked)

Activity owns a calm, read-only record of Household coordination actions.  
Activity must not become a pressure surface (no urgency, no enforcement, no performance interpretation, no notification-centre behavior).

### Identity and Attribution Rules (Locked)

Identity display is system-owned. Item events in Activity may show the actor display name for active Members as attribution only. When membership ends, historical entries and context sheets must immediately re-render the actor as “Former Member” by default (no persistent name exposure).

Activity must not support per-person views, counts, sorting, grouping, filtering, badges, streaks, or any other performance-like interpretation.

### Included Events (Locked)

Item-level events (attribution-only names allowed for active Members):

- <Display Name> Added “Item”
- <Display Name> Completed “Item”
- <Display Name> Hid “Item”
- <Display Name> Showed “Item” Again
- Item Updated (Generic, used when a change must be visible without becoming blame-attribution detail)

System-owned Household events (no individual attribution in the feed):

- A Former Member No Longer Has Access (System-Owned)

Handoff indicator in the feed:

- Optional: a single “Handoff” chip may appear on any Item-level event involving a Handoff Item.
- The Activity feed must not show handoff type chips (Pickup / Appointment / Visit / Other) by default.

### Excluded Events (Locked)

- No hearts events
- No heart counts
- No “For: <name>” chips in the Activity feed by default
- No handoff type chips in the Activity feed by default
- No “Household Name Updated” event line in the Activity feed by default
- No “Household Members Updated” event line in the Activity feed by default
- No “Member Left Household” or “Member Removed” event line in the Activity feed (use “A Former Member No Longer Has Access” as the system-owned feed line)
- No separate “Handoff Updated” event line (use “Item Updated” with optional “Handoff” chip if needed)
- No “Changed by <name>” attribution lines for system-owned Household events

### Activity Context Sheet (Read-only) (Locked)

Selecting any Activity row opens a read-only Activity Context view.

- All optional details are read-only. The sheet contains no edit actions and no inline controls.

#### Item Events (Including Handoff Item, High-Stakes)

When the Activity entry involves an Item:

- The Activity feed stays minimal (event line + optional “Handoff” chip only, if applicable).
- The Activity Context view may show:
  - Item name
  - Optional details (read-only) needed to reduce ambiguity, without adding blame, urgency, or enforcement framing

When the Item is a **Handoff Item** (a **High-Stakes** coordination stress surface), the Activity Context view may also show:

- Chips: “Handoff”, “For: <name>”, and a type chip (Pickup / Appointment / Visit / Other)
- Exit safety: if the “For” person is not active, display “Former Member” (system-owned).

#### System-owned Household Events

For system-owned events (A Former Member No Longer Has Access):

- The Activity feed line remains neutral and non-attributing.
- The Activity Context view may show minimal clarifying detail (read-only) to prevent confusion, without exposing removed identities by default.

## Flow 5: Multi-Household Context Switch

1. Member taps “Switch Household”.
2. The app changes Household context explicitly (global).
3. The active Household name updates everywhere the header is shown.
4. Shared Cart and Activity immediately re-scope to the newly selected Household.
5. The newly selected Household persists as the last viewed context.

See: [Flow Artefacts](./flow/)
