# Failure-mode tests (public-safe)

These are the failure scenarios the prototype and eventual implementation must defend against. This is not a test harness or implementation guide.

## FM1: Wrong-household action
User believes they are in Household B but an action lands in Household A.
- Harm: high (trust break + interpersonal conflict risk)

## FM2: Irreversible completion
A completion behaves like deletion and cannot be safely undone.
- Harm: “I ruined it” moment; conflict amplifier

## FM3: Identity exposure after exit
Past Activity permanently exposes a person who left/was removed.
- Harm: safety breach; can cause real interpersonal harm

## FM4: Activity becomes a performance feed
Logs feel like surveillance even without scoring.
- Harm: pressure, judgment, disengagement

## Mitigation principles
- Reversibility by default
- System-owned language (no blame)
- Minimum identity exposure necessary for comprehension
- Boundary integrity as a safety property, not a convenience feature
