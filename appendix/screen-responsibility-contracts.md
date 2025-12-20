# Screen Responsibility Contracts (Appendix)

## Entry
- Owns: guest-first choice, optional auth routing.
- Must not: force sign-in.

## Household Gate
- Owns: selecting active household, auto-create first household.
- Must not: show member lists or renaming in MVP.

## Home Shell
- Owns: navigation between Carts and Activity.

## Cart Detail
- Owns: add + complete item actions, displays active items.
- Must not: introduce assignment, due dates, or enforcement language.

## Activity
- Owns: read-only feed of actions.
- Must not: become a notification centre or judgement feed.
