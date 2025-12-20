# Domain Language (LOCKED)

## Core nouns
- Household: a shared context boundary.
- Member: a person inside a household.
- Shared Cart (Default Cart): the single household list in MVP.
- Item: a line in the cart.
- Activity: an immutable log of actions (read-only feed).

## Core verbs
- Add item: place an item into the shared cart.
- Complete item: hide item from active list (system-owned, reversible by re-adding).
- Switch household: change active context explicitly.

## Tone rules (LOCKED)
- Use “completed” not “deleted”.
- Avoid “assigned”, “overdue”, “reminder”, “failed”, “should”.
- No judgement language; visibility without evaluation.

## UI labels (MVP)
- “Shared Cart” (preferred) or household-named cart title.
- “Activity” for the log.
- “Continue as guest” for primary entry.
