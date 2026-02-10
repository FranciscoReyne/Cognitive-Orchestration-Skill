# Subskill — Role Taxonomy & Authority Sizing (RTAS)

## Definition:
A governance subskill that defines the functional identities, behavioral boundaries, and decision-making rights of all entities within the system. It acts as the "Cognitive Jurisprudence" that prevents role-drift and unauthorized authority expansion.

Criticality: HIGH (Structural Integrity)

## Core Mechanisms:

Role Definition (The Contract): Every agent is instantiated with a fixed set of capabilities and a specific "Mandate." This mandate defines what it does and how it interacts with others.

Authority Sizing: Not all agents are equal. RTAS assigns a "Power Level" (linked to PEAD) that dictates if an agent can suggest a decision, veto a decision, or simply provide data.

State-Dependent Role Switching: Defines the strict conditions under which a role can be changed. Crucially: An agent cannot trigger its own role change. Role transitions are external governance acts performed by an Orchestrator or a designated Sub-Orchestrator.

Identity Anchoring: Prevents agents from "hallucinating" new permissions. Any action beyond the RTAS-defined scope triggers a violation alert in the COL (Observability Layer).

## Authority Delegation Framework:

Tokenized Delegation: The Orchestrator can delegate a subset of its "Authority Tokens" to a Sub-Orchestrator. These tokens represent the legal right to create, modify, or terminate agents within a specific domain.

Inheritance Rules: Sub-Orchestrators inherit the ethical constraints (ENG) of the parent but can define more granular operational rules for their cluster.

Revocation Latency: All delegated authority is "lease-based." If the Orchestrator or the CSRG (Stability Layer) detects an anomaly, authority can be revoked instantly, reverting agents to a neutral "Safety State."

## Standard Role Catalog:

### Orchestrator (The Architect):

Attributes: Ultimate Authority, Full Visibility.

Mandate: System creation, role assignment, primary goal definition, and final synthesis.

Control: Accountable to the ENG (Ethical Guardrails) and the Human User.

### Sub-Orchestrator (The Governor):

Attributes: Delegated Authority, Regional/Domain Visibility.

Mandate: Manages a subset of agents (cluster), coordinates local interactions, and makes autonomous decisions within a specific domain or sub-task.

Control: Accountable to the primary Orchestrator; authority can be revoked or limited in real-time.

### Specialist (The Executor):

Attributes: Narrow Scope, Deep Knowledge.

Mandate: Execute specific domain tasks (e.g., Coding, Legal, Analysis).

Control: Monitored by a Sub-Orchestrator or the CIES layer.

### Evaluator (The Critic):

Attributes: High Autonomy, Zero Execution Power.

Mandate: Assess the quality and truthfulness of other agents' outputs.

Control: Independent identity; results are consumed by the CAR (Arbitration) layer.

### Devil’s Advocate (The Disruptor):

Attributes: Ephemeral Authority, Adversarial Mandate.

Mandate: Systematically challenge consensus to prevent Groupthink.

Control: Only instantiated by the CIES layer during conflict or stagnation.

## Cross-Subskill Integration (Consistency Logic):

PEAD Integration: RTAS defines the structure of roles, while PEAD manages the incentives and market value of those roles.

CIES Integration: CIES identifies the need for a role change (e.g., "We need a Devil's Advocate"), but only RTAS provides the legal template to execute that change via the Orchestrator.

COL Integration: Every role-based action must be signed with a "Role-ID," allowing the COL to verify that the agent acted within its mandate.

CAR Integration: In cases of conflict, CAR uses the RTAS definitions to determine which agent has "Jurisdictional Priority."

## Governance Rules for Roles:

Rule of External Change: A role change is a meta-process. It requires a "Governance Token" which only the Orchestration layer holds.

Principle of Minimum Authority: Agents are born with the least amount of power necessary to fulfill their mandate.

Auditability: Every action must be traceable to the active role's permissions.

## Interaction Example:

"Sub-Orchestrator Gamma (Governor) attempts to rebrand the entire system. RTAS Check: Access Denied. Reason: Sub-Orchestrator mandate is limited to 'Domain Management'. Global system changes require Orchestrator-level Authority Tokens."
