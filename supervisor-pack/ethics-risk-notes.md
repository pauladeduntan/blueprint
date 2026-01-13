# Ethics and Risk Notes

## Purpose

This document summarizes the primary ethics and safety risks in studying household coordination and the mitigation posture used by the KinCart research artefact.

This is not a claim of approval. Any participant study must follow the appropriate ethics and consent processes required by the host institution.

## Core Safety Commitments

- Emotional safety over optimisation.
- Visibility over reminders.
- Activity is a calm, read-only record, not a performance feed.
- Reversibility by default to support repair after mistakes.
- Exit safety: leaving or removal ends access immediately, and identity exposure is minimized.

## Primary Risk Areas and Mitigations

### Risk 1: Coercion and Compliance Dynamics

Household coordination tools can become instruments of pressure, where one person uses the system to manage another.

Mitigations:
- No reminders, nudges, streaks, or overdue states.
- No assignment, ownership, or accountability framing.
- Language avoids judgement and moral evaluation.

### Risk 2: Surveillance Interpretation

Even without explicit metrics, activity logs can feel like monitoring.

Mitigations:
- Activity is restrained, neutral, and non-evaluative.
- No read receipts, last seen indicators, or inactivity tracking.
- No contribution summaries, rankings, or per-person performance views.

### Risk 3: Conflict Evidence Creation

Logs can become evidence in disputes, increasing interpersonal harm.

Mitigations:
- Activity avoids accusatory framing and avoids escalation detail.
- Membership boundary events are system-owned and non-attributed by default.
- Detail sheets, where present, are minimal and do not increase auditability.

### Risk 4: Identity Exposure After Exit

A person leaving a Household can remain visible through history, which can be unsafe.

Mitigations:
- Exit safety: access ends immediately.
- Former Member is de-identified by default in Activity.
- No persistent display-name history is presented by default.

### Risk 5: High-Stakes Handoff Policing

Handoff moments are high pressure and can invite precision policing.

Mitigations:
- Handoff is a high-stakes probe surface with anti-policing guardrails.
- Prefer situational summaries over exact times by default.
- Handoff context remains minimal in the Activity feed and is revealed on demand in a read-only context view.

### Risk 6: Data Minimisation and Re-Identification

Even small traces can identify people in household contexts.

Mitigations:
- No collection of sensitive personal data is required for the probe logic.
- Study logs avoid names, contact details, places, employers, schools, and unique incidents.
- Notes are de-identified and written to avoid forensic reconstruction.

## Data Handling Posture

- Data collection is minimal and must be explicitly documented before use in any study context.
- No user-identifiable data is published.
- Any study use of prototypes, vignettes, or logs requires informed consent and appropriate participant protections.

## What is Explicitly not Claimed

- No claims of behavioral improvement, compliance, or productivity gains.
- No claims that KinCart is safer for all households or all conflict contexts.
- No claims of generalization without empirical study.

## Questions To Probe in Ethics Review

- Under what household conditions does visibility feel supportive versus controlling?
- What cues trigger perceived monitoring even when metrics are absent?
- What exit representations minimize harm while preserving comprehension?
- What handoff representations reduce ambiguity without becoming policing tools?
