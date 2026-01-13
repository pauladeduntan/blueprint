# Domain Language (Locked)

## Core Nouns

- Household: a shared context boundary.
- Member: a person inside a Household.
- Shared Cart (Default Cart): the single household list in the current research prototype.
- Item: a line in the Shared Cart.
- Activity: an immutable log of actions (read-only feed).

## Additional Nouns

- Handoff Item: a High-Stakes coordination Item used as a stress surface to study breakdown, repair, trust, and emotional safety.
- Former Member: a person who previously belonged to a Household but no longer has access.
- Save Progress: neutral framing for optional sign-in (not a conversion push).

## Core Verbs

- Add Item: place an Item into the Shared Cart.
- Complete Item: system-owned action that hides an Item from the active list (reversible by showing again).
- Hide Item: non-destructive substitute for remove/delete; hides an Item from the active list without signalling fault or punishment.
- Switch Household: change active context explicitly.

## Additional Verbs

- Leave Household: exit a Household context; access ends immediately.
- Remove Member: system-owned Household action; never framed as punishment.

## Activity Naming Rules

- Use “completed” (not “done”) and avoid language that implies fault, obligation, or performance.
- Avoid excessive attribution pressure: use “Member” / “Former Member” (system-owned) where identity would increase surveillance interpretation.
- For changes that are not safely specific, prefer neutral phrasing (for example, “Item Updated”) over detail that can be read as blame.

## Tone Rules (Locked)

- Use “completed” not “deleted” or “removed”.
- Avoid “assigned”, “overdue”, “reminder”, “failed”, “should”.
- No judgement language; visibility without evaluation.

## UI Labels

- “Shared Cart” (preferred) or a Household-named cart title.
- “Activity” for the log.
- “Continue As Guest” for primary entry.
