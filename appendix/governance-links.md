
# Governance links (cross-repo map)
This appendix connects the **blueprint** (what KinCart is) to **governance** (what is committed and enforced).

## Governance (source of binding decisions)
- Governance repo: https://github.com/pauladeduntan/governance
- Decision register: https://github.com/pauladeduntan/governance/blob/main/decision-register.md
- Decision records: https://github.com/pauladeduntan/governance/tree/main/decisions
- Action gates: https://github.com/pauladeduntan/governance/tree/main/action-gates
- Auth/RLS/RPC contract (conceptual): https://github.com/pauladeduntan/governance/blob/main/auth-rls-rpc-contract.md

## Blueprint artefacts governed
- Product definition: ../product-definition.md
- Domain language (LOCKED): ../domain-language.md
- Invariants (LOCKED): ../invariants.md
- System flows: ../system-flows.md
- Screen responsibility contracts: ./screen-responsibility-contracts.md
- Stress tests: ./stress-tests.md

## Decision → Blueprint impact (public-safe pointers)
- D001 Project framing → product-definition.md (research framing)
- D002 Product checksum + invariants → invariants.md, domain-language.md
- D003 MVP boundary and exclusions → product-definition.md, system-flows.md
- D004 Data ownership + research use boundary → invariants.md, product-definition.md
- D005 Data ownership + exit safety → invariants.md, screen-responsibility-contracts.md
- D006 Activity privacy veil → domain-language.md, screen-responsibility-contracts.md

# Governance Links (Enforceable)
This appendix makes KinCart’s governance **enforceable**, not optional. The blueprint defines *what* we are building; the governance repo defines *how* we prevent drift while building.

## Source of truth
- **Blueprint repo**: product intent, domain language, invariants, system flows.
- **Governance repo**: build rules, decision discipline, and the auth/RLS/RPC contract.

If a suggestion conflicts with an invariant, the invariant wins.  
If an implementation shortcut increases emotional risk, reject it.

## Build enforcement
Before any implementation step (schema, RLS, RPC, FlutterFlow):
1) Run the **3-question filter** (Decision Hygiene).
2) Confirm the step does not violate the **Auth + RLS + RPC Contract**.
3) Ensure the change is tied to a committed decision (Decision Register entry or decision doc).

## Links (authoritative)
- Decision Hygiene: https://github.com/pauladeduntan/governance/blob/main/decision-hygiene.md
- Auth + RLS + RPC Contract: https://github.com/pauladeduntan/governance/blob/main/auth-rls-rpc-contract.md
- Decision Register: https://github.com/pauladeduntan/governance/blob/main/decision-register.md
