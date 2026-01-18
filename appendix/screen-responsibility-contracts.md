# Screen Responsibility Contracts (Appendix)

## Entry

- Owns: “Continue As Guest” as primary entry; optional sign-in routing framed as “Save Progress”.
- Must not: force sign-in or imply access control as a reward.

## Household Gate

- Owns: selecting the active Household; creating the first Household and Shared Cart when none exist.
- Must not: expose Member lists or Household renaming in the current research prototype UI.

## Home Shell

- Owns: navigation between Shared Cart and Activity; active Household visibility.
- Must not: enable silent context switching or hide the active Household boundary.

## Shared Cart

- Owns: Add Item, Complete Item, Hide Item, and Show Again actions; displays active Items.
- Must not: introduce assignment, due dates, urgency cues, or enforcement language.

## Activity

- Owns: calm, read-only feed of Shared Cart actions and select system-owned Household events, providing minimal visibility without performance framing.
- Must not: become a notification centre, audit mechanism, or judgement feed.
- Must preserve: system-owned identity display and exit safety defaults.
- Attribution rule: Activity may show actor display names for active Members as attribution only. When membership ends, historical entries must immediately re-render the actor as “Former Member” by default (no persistent name exposure).
- Anti-amplification rule: Activity must not support per-person views, counts, sorting, grouping, filtering, badges, streaks, or any other performance-like interpretation.

## Activity Context (Read-only)

- Owns: a read-only context view for Activity entries, used to reduce ambiguity without increasing blame, urgency, or enforcement framing.
- Must not: introduce edit actions, escalation cues, policing language, or inline controls.
- Must preserve: optional details are read-only and bounded to what is necessary for comprehension.

## Activity Context (Handoff Item, High-Stakes)

- Owns: read-only context view for Activity entries involving a Handoff Item, including High-Stakes chips and type details that are not shown by default in the feed.
- Must not: introduce edit actions, escalation cues, or policing language.
- Must preserve: exit safety (use “Former Member” when the “For” person is not active).

## Activity Context (System-owned Household Events)

- Owns: minimal clarifying detail for system-owned events (for example, Household Name Updated, Household Members Updated, A Former Member No Longer Has Access) to avoid confusion.
- Must not: show “changed by” attribution, expose removed identities by default, or introduce judgement framing.
