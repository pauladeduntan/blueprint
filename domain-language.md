## Domain Language (MVP)

The following terms have specific, non-negotiable meanings in KinCart.

• Household  
A bounded coordination context. All data is strictly household-scoped. No entity crosses household boundaries.

• Member  
A user within a household. Users may belong to multiple households but only one is active at a time.

• Cart  
A coordination container for shared intent. In MVP, each household has a single system-owned default cart.

• Default Household Cart  
A system-owned, always-on cart created automatically for each household. It is non-deletable in MVP and serves as the baseline coordination surface.

• Item  
An expression of shared intent within a cart. Items may be added, completed, or acknowledged.

• Completion  
A system-recorded state change where an item is marked as handled. Completion is visible but non-evaluative.

• Activity  
An immutable, neutral record of what occurred. Activity provides history, not obligation.

• Updates  
A filtered, decaying awareness surface designed to reduce noise and mental load.

• Event Cart  
A time-bound coordination container. Event Cart 1.0 is explicitly post-MVP and illustrative only.
