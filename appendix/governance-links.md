# Governance Links (Cross-Repo Map)

This appendix connects the **Blueprint** (what KinCart is and must remain) to **Governance** (what is committed and how drift is prevented).

## Governance (Source Of Binding Decisions)

- Governance Repo: https://github.com/pauladeduntan/governance
- Decision Register: https://github.com/pauladeduntan/governance/blob/main/decision-register.md
- Decision Records: https://github.com/pauladeduntan/governance/tree/main/decisions
- Action Gates: https://github.com/pauladeduntan/governance/tree/main/action-gates
- Decision Hygiene: https://github.com/pauladeduntan/governance/blob/main/decision-hygiene.md

## Blueprint Artefacts Governed

- Product Definition: ../product-definition.md
- Domain Language (Locked): ../domain-language.md
- Invariants (Locked): ../invariants.md
- System Flows: ../system-flows.md
- Screen Responsibility Contracts: ./screen-responsibility-contracts.md
- Failure-Mode Tests: ./failure-mode-tests.md

## Status Semantics (Public-Safe)

- Accepted: binding.
- Archived: filed for historical traceability; binding status is determined by whether the decision is explicitly superseded by a later decision record.
- Superseded: no longer binding; replaced by a later decision record.

## Decision → Blueprint Impact (Public-Safe Pointers)

### Archived Decisions (Historical Context; Binding Status Defined in Decision Register)

- D001 Project Framing → ../product-definition.md
- D002 Product Checksum and Invariants → ../invariants.md, ../domain-language.md
- D003 Scope Boundary and Exclusions → ../product-definition.md, ../system-flows.md
- D004 Data Ownership and Research Posture → ../invariants.md, ../product-definition.md
- D005 Data Ownership and Exit Safety → ../invariants.md, ./screen-responsibility-contracts.md
- D006 Activity Privacy Veil → ../domain-language.md, ./screen-responsibility-contracts.md
- D007 Activity Context Sheet → ../system-flows.md, ./screen-responsibility-contracts.md

### Accepted Decisions (Currently Binding)

- D008 Hearts are Item-Scoped (Not a Feed Mechanic) → ../domain-language.md, ../system-flows.md, ./screen-responsibility-contracts.md
- D009 Activity Detail Sheets are Optional, Neutral Context → ../system-flows.md, ./screen-responsibility-contracts.md
- D010 Handoff Tag with Anti-policing Guardrails → ../invariants.md, ../system-flows.md, ../domain-language.md, ./screen-responsibility-contracts.md
- D011 Replace Remove/Delete with Hide Item (Reversible) → ../domain-language.md, ../invariants.md, ../system-flows.md
- D012 Remove Hearts from Main List Row → ./screen-responsibility-contracts.md, ../system-flows.md
- D013 Auth Framed as Save Progress; Guest is First-class → ../domain-language.md, ../system-flows.md, ../product-definition.md
- D014 Item Details Accessible from Activity → ../system-flows.md, ./screen-responsibility-contracts.md
- D015 Placeholder and Microcopy Rules are Consistent → ../domain-language.md, ./screen-responsibility-contracts.md, ../product-definition.md

## Change Gate Summary (Enforceable in Spirit, Public-Safe I
in Detail)

If a suggestion conflicts with an invariant, the invariant wins.  
If a shortcut increases emotional risk or pressure cues, reject it.

Before any change is accepted:

1) Run the Decision Hygiene filter.
2) Confirm the change preserves boundary integrity, exit safety, and system-owned language.
3) Tie the change to a committed decision (Decision Register entry or Decision Record).
