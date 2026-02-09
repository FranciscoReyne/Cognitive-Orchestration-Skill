# Subskill — Cognitive Memory & Persistence Layer (CMPL)

## **Definition:** 
A semantic and governance-aware persistence framework that enables agents and orchestrators to retain, retrieve, and evolve knowledge across temporal boundaries.

## Key Memory Scopes:

* Operational Memory (Short-term): Contextual data and active reasoning traces required for current task execution.

* Cognitive Experience (Long-term): Lessons learned, refined heuristics, and behavioral adaptations derived from past successes or failures.

* Governance & Authority History: A persistent record of how authority was delegated, revoked, or shifted, ensuring accountability across sessions.

* Observability Archives: Retained views of system evolution provided by the Subskill Cognitive Observability Layer, allowing for "replay-based" reasoning.

* Persistence Policies:

  * Decay & Pruning: Autonomous mechanisms to "forget" redundant or low-confidence information to prevent cognitive saturation.

  * Identity Continuity: Semantics for ensuring an agent remains "the same entity" when re-instantiated from hibernation.

  * Shared vs. Private Context: Rules defining which memories are accessible by the entire network and which are restricted to specific authority domains.
