# Screen Responsibility Contracts (Appendix)

## Entry

- Owns: “Continue As Guest” as primary entry; optional sign-in routing framed as “Save Progress”.
- Must not: force sign-in or imply access control as a reward.

## Household Gate

- Owns: selecting the active Household; creating the first Household and Shared Cart when none exist.
- Must not: expose Member lists or Household renaming in the current research prototype.

## Home Shell

- Owns: navigation between Shared Cart and Activity; active Household visibility.
- Must not: enable silent context switching or hide the active Household boundary.

## Shared Cart

- Owns: add Item, Complete Item, Hide Item, and Show Again actions; displays active Items.
- Must not: introduce assignment, due dates, urgency cues, or enforcement language.

## Activity

- Owns: calm, read-only feed of Shared Cart actions; minimal visibility without performance framing.
- Must not: become a notification centre, audit mechanism, or judgement feed.
- Must preserve: system-owned identity display and exit safety defaults (“Member” / “Former Member” where appropriate).

## Activity Context (Handoff Item, High-Stakes)

- Owns: read-only context view for Activity entries involving a Handoff Item, including High-Stakes chips that are not shown by default in the feed.
- Must not: introduce edit actions, escalation cues, or policing language.
- Must preserve: exit safety (use “Former Member” when the “For” person is not active).
