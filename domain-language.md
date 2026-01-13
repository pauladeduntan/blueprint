# Domain Language (LOCKED)

## Core nouns
- Household: a shared context boundary.
- Member: a person inside a household.
- Shared Cart (Default Cart): the single household list in the current research prototype.
- Item: a line in the cart.
- Activity: an immutable log of actions (read-only feed).

## Additional nouns
- Former member: a person who previously belonged to a household but no longer has access.
- Save progress: neutral framing for optional sign-in (not a conversion push).

## Core verbs
- Add item: place an item into the shared cart.
Complete item: system-owned action that hides an item from the active list (reversible by showing again).
- Hide item: non-destructive substitute for remove/delete; hides item from the active list without blame.
- Switch household: change active context explicitly.

## Additional verbs
- Leave household: exit a household context; access ends immediately.
- Remove member: system-owned household action; never framed as punishment.

## Activity naming rule
- Use “completed” (not “done”) and avoid language that implies fault, obligation, or performance.
- If a former member performed an action, display as “Member” / “Former member” (system-owned).

## Tone rules (LOCKED)
- Use “completed” not “deleted” or “removed”.
- Avoid “assigned”, “overdue”, “reminder”, “failed”, “should”.
- No judgement language; visibility without evaluation.

## UI labels (MVP)
- “Shared Cart” (preferred) or household-named cart title.
- “Activity” for the log.
- “Continue as guest” for primary entry.
