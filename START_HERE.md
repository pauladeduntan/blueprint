# Start Here

KinCart is a non-commercial research artefact used to study how household coordination can make every day lighter, together. It focuses on reducing mental load while preserving emotional safety.

## Fast Path

1) **Research Artefact (Used in Study)**
   - Figma Prototype (Used In Interpretive Walkthrough Interviews): [Figma Prototype](https://www.figma.com/proto/0BKLn5A6LTL217Wn1Vtk1u/KinCart-Hi-fi-Mock-up-Screens?node-id=484-6085&t=1YxIJJ2rhqY7Rphx-1)
   - Short Walkthrough Video (2–3 Min, Unlisted): Available On Request

2) **Research Contribution**
   - See: `appendix/research-contribution.md`

3) **Core Constraints (What Must Remain True)**
   - Domain Language (Locked): `domain-language.md`
   - Invariants (Locked): `invariants.md`

4) **Interaction Narrative (What is being Studied)**
   - `system-flows.md` describes user-facing behavior and failure modes. It includes **Handoff Item** as a **High-Stakes** coordination stress surface used to study breakdown, repair, trust, and emotional safety.
   - Activity is a calm, read-only record that must not become a performance feed, and identity display is system-owned with dynamic redaction to “Former Member” after membership ends.

## What this Repo Contains

- Locked domain language and invariants that constrain design choices.
- Narrative system flows describing user-facing behavior and failure modes.
- A small appendix of research notes curated for public review (no implementation recipes).

## What is Intentionally Not Published

- Implementation mechanics (schema/RLS/RPC specifics, operational scripts, deploy steps).
- Any copy/paste backend recipes or build instructions.

These details are intentionally excluded to preserve KinCart’s role as a research probe rather than a build guide.
