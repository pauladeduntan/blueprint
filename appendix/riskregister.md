# Risk Register (KinCart Research Probe)

This document covers **research and study risks** for KinCart as a non-commercial HCI/CSCW research artefact and design probe. It complements `failuremode.md`, which documents public-safe system failure-mode tests that constrain visibility-to-enforcement drift. This is not an implementation guide.

## Scope and Stance

- Primary Empirical Site: households.
- Method Stance: interpretive qualitative CSCW, breakdown and repair analysis, prototypes as probes.
- Drift Guard: no enforcement language, no nudges, no scoring, no performance metrics, no outcome or behaviour-change claims.
- Priority Checksum: “Making every day lighter, together.” Emotional safety over optimisation; visibility over reminders.

## Risk Scale

- Severity: Low / Medium / High
- Likelihood: Low / Medium / High

## Risks and Mitigations

### R1: Surveillance Interpretation During Studies
- Risk: Participants interpret KinCart or the study as monitoring, evaluation, or accountability enforcement.
- Who could be Harmed: Members, guests, and especially those in unequal role arrangements.
- Trigger Conditions: Discussing Activity, identity exposure, completion states, or “who did what,” especially in front of others.
- Severity: High
- Likelihood: Medium
- Mitigations (Constraints and Practice):
  - Present KinCart as a **probe** for interpretation, not a tool for compliance or behaviour change.
  - Avoid per-person views, counts, sorting, grouping, filtering, badges, streaks, or any performance-like framing.
  - Use system-owned language (Member / Former Member) and avoid blame language.
  - Prefer 1:1 sessions; avoid joint sessions unless explicitly requested and assessed as safe.
- Residual Risk: Medium
- What we will not do:
  - No “productivity” framing, no evaluation of participants, no “who is responsible” prompts.

### R2: Interpersonal Conflict Amplification via Traces
- Risk: Discussing coordination traces or viewing screens together triggers blame, defensiveness, or re-litigation of disputes.
- Who could be Harmed: Household Members and guests; heightened risk for marginalised or lower-power participants.
- Trigger Conditions: High-stakes coordination moments (handoffs, missed items, edits) discussed in emotionally loaded contexts.
- Severity: High
- Likelihood: Medium
- Mitigations:
  - Use neutral prompts focused on “how this reads” rather than “what happened in your home.”
  - Stop rules: pause or end the session if participants show distress or conflict escalation.
  - Offer opt-out of any question, and remind participants they can withdraw at any time without explanation.
  - Avoid collecting identifiable, story-level conflict details unless under institutional ethics and explicit consent.
- Residual Risk: Medium
- What we will not do:
  - No joint elicitation designed to surface “truth,” blame, or accountability.

### R3: Identity Exposure and Exit Safety Harms in Research Materials
- Risk: Notes, screenshots, or prototypes accidentally reveal identity after exit or create durable association to a Former Member.
- Who could be Harmed: Former Members; current Members in sensitive living situations.
- Trigger Conditions: Using real names in prototypes; capturing screenshots with names; discussing household membership transitions.
- Severity: High
- Likelihood: Medium
- Mitigations:
  - Default to pseudonyms or role labels in any study materials.
  - Avoid storing screenshots containing real identifiers.
  - Treat identity as system-owned and minimise exposure necessary for comprehension.
  - Maintain a “former member redaction” rule in materials: former members are not named.
- Residual Risk: Low to Medium
- What we will not do:
  - No publication or sharing of identifiable household membership transitions.

### R4: Wrong-household Action as a Trust Breach During Study Use
- Risk: A participant performs an action in the wrong household context during a session, creating mistrust or anxiety.
- Who could be Harmed: Members using the probe; trust within households if actions are later discussed.
- Trigger Conditions: Multi-household navigation, ambiguous household cues, rapid switching.
- Severity: High
- Likelihood: Low to Medium
- Mitigations:
  - Use clearly separated demo households in study mode.
  - Prioritise boundary integrity cues and confirm context before actions in study walkthroughs.
  - Avoid live household data during early studies; prefer staged scenarios.
- Residual Risk: Low
- What we will not do:
  - No studies that require participants to operate on their real household data without explicit safeguards.

### R5: Data Minimisation Failure (Over-collection)
- Risk: Collecting more personal data than necessary for interpretive analysis.
- Who could be Harmed: Participants; household members not present.
- Trigger Conditions: Recording audio/video by default; collecting detailed household narratives; storing raw transcripts unnecessarily.
- Severity: High
- Likelihood: Medium
- Mitigations:
  - Default to minimal notes; record only when necessary and consented.
  - Collect interpretation-focused data: “what it implies,” “what it pressures,” “what feels unsafe.”
  - Redact identifiers in notes quickly after sessions.
  - Establish retention limits and deletion workflow aligned to the hosting institution once affiliated.
- Residual Risk: Low to Medium
- What we will not do:
  - No “collect everything” posture, no indefinite retention.

### R6: Recruitment and Participation Coercion
- Risk: Participants feel pressured to participate due to household relationships or perceived authority.
- Who could be Harmed: Lower-power household members.
- Trigger Conditions: Recruitment via a partner; joint invitations; participation framed as “helping the household.”
- Severity: High
- Likelihood: Medium
- Mitigations:
  - Recruit individuals directly where possible.
  - Explicitly state voluntary participation and withdrawal without consequence.
  - Avoid recruiting multiple members from the same household without ethics oversight and a safety rationale.
- Residual Risk: Medium
- What we will not do:
  - No recruitment that relies on one household member “authorising” another’s participation.

### R7: Misinterpretation of Research as Product Marketing
- Risk: Observers interpret the probe as a commercial product and infer performance claims or promises.
- Who could be Harmed: Research credibility; participants’ expectations and trust.
- Trigger Conditions: Sharing prototypes publicly; ambiguous language about “reducing mental load” as an outcome.
- Severity: Medium
- Likelihood: Medium
- Mitigations:
  - Clearly label KinCart as non-commercial research artefact and probe.
  - Use claims discipline: describe aims and phenomena, not outcomes.
  - Keep public posts at the level of principles, trade-offs, and constraints.
- Residual Risk: Low
- What we will not do:
  - No marketing language, no outcome claims, no behavioural optimisation framing.

## Relation to Failure-mode Tests

System-level failure scenarios that constrain visibility-to-enforcement drift are documented in `failuremode.md` and should be treated as inputs to study design, prompts, and safety checks. The present register focuses on participant, process, and data risks.
