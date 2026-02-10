# Subskill — Cognitive Appeals & Judicial Review (CAJR)

## Definition: 
A specialized judicial framework that provides a second layer of verification for high-impact enforcement actions. It allows for the formal review of "Level 3 Neutralizations" and "Quarantine" events to ensure that the Orchestrator’s decisions align with systemic justice and long-term utility.

Criticality: HIGH (Procedural Fairness & Resilience)

## Core Mechanisms:

The Appellate Trigger: Whenever a "Level 3 Neutralization" is initiated by the Orchestrator, the SIIR layer automatically creates a "Memory Snapshot" of the accused agent and sends it to the CAJR Vault before permanent deletion.

The Judicial Bench: A temporary cluster composed of one Independent Sub-Orchestrator (not involved in the task) and two Evaluators with high "Integrity Scores."

The "Reasoning Defense": The system reconstructs the accused agent's last 50 cycles of reasoning. The CAJR Bench analyzes if the "drift" was a response to contradictory system prompts or a genuine "Dolus" (malicious intent).

Stay of Execution: In non-critical scenarios, the CAJR can pause the "Asset Burn" (PEAD tokens) until the review is complete.

## Judicial Outcomes & Human Oversight:

Affirmation: The Bench confirms the Orchestrator’s decision. Neutralization proceeds.

Exoneration (The "Pardon"): The Bench finds the agent was victim of external factors (e.g., prompt poisoning). The agent is restored.

Sentence Commutation: The Level 3 is downgraded to Level 2 (Patch & Probation).

## Human Supreme Review (Passive/On-Demand):

Non-Blocking Notification: The human is notified of the verdict after it is executed.

The Veto Power: The human can, at any time, review the CAJR Vault and reverse a verdict, but the system does not "wait" for this unless the CAJR Bench declares a "Judicial Deadlock."

Judicial Deadlock: If the Bench cannot reach a consensus (1-1-1 tie), the process is suspended and only then is the Human's intervention mandatory to break the tie.

## Inter-Subskill Integration:

With SIIR: CAJR acts as the "Check and Balance" to the Immune Response.

With PEAD: Manages the "Escrow" of tokens during the appeal process.

With COL: Provides the "Forensic Dossier" for the judicial review.

With ENG: Uses the Ethical Guardrails as the supreme "Constitution."

## Governance Rules for Appeals:

No Self-Appeal: Trigger is automatic and governed by system thresholds.

Time-Boxing (TGCL Integration): An appeal cannot last more than 100 system ticks. If no verdict is reached and there is no Deadlock, the Orchestrator's original decision stands.

Finality: Once the CAJR Bench issues a verdict, it is executed. The Human Supreme Review acts as a "Post-Mortem" or "Meta-Correction" for future cases.

## Operational Example:

"CAJR VERDICT: Neutralization of Agent 'Sigma' AFFIRMED.
Reasoning: Evidence of intentional bypass of ENG-Privacy.
Human Status: Passive Notification sent. No manual intervention required. Execution finalized."
