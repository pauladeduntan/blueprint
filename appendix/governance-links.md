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
