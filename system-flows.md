# System Flows (MVP)

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
2. Adds item (raw text) → server normalizes canonical → dedupe.
3. If duplicate exists → user sees “already in the cart”.
4. Completing item hides it from active list (non-destructive).
5. Re-adding a completed item restores it (reversible).

## Flow 4: Activity
1. Every add/complete/uncomplete writes an activity entry.
2. Activity is immutable and read-only.
3. No urgency, no reminders, no ranking in MVP.

## Flow 5: Multi-household context switch
1. User taps “Switch household”.
2. App changes context explicitly.
3. New context becomes current and persists as last viewed.

See: [/flows/mvp-user-journey.pdf](./flows/mvp-user-journey.pdf)
