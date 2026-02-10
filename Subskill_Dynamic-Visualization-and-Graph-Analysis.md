# Subskill — Dynamic Visualization & Graph Analysis (DVGA)

## Definition: 
A support and governance subskill dedicated to the real-time mapping, topological analysis, and visual auditing of the multi-agent network. It transforms abstract cognitive flows into a structured, interactive graph that reveals authority dynamics, temporal states, and communication paths.

Criticality: MEDIUM (Governance & UX)

## Core Mechanisms:

Topological Mapping (RTAS Viz): Dynamically renders nodes (Agents) and edges (Relationships). It visually distinguishes between Orchestrators, Sub-Orchestrators, and Specialists using hierarchical layouts or color-coded clusters.

Authority Flow Tracking (PEAD Viz): Visualizes the movement of "Authority Tokens." Edge thickness and direction indicate the volume and vector of delegated power, allowing for the immediate detection of authority bottlenecks or monopolies.

Temporal Status Overlay (TGCL Viz): Integrates semantic time awareness. Nodes exhibit visual decay (e.g., opacity reduction or color shifting) as their "Time-To-Live" (TTL) approaches expiration.

Cognitive Event Projection (COL Integration): Links logs from the Observability Layer directly to the visual entities. Clicking a node reveals its "Reasoning Trace," current intent, and historical decisions.

Real-Time Anomaly Highlighting: Uses visual triggers (pulsing, red borders) to flag agents in "Recursive Loops" (CSRG) or those currently undergoing "Arbitration" (CAR).

## Visual Governance Rules:

The "Map-to-Act" Principle: The visualization is not just a display; it is an interface. The Orchestrator can trigger governance acts (revocation, hibernation, role-switching) by interacting with the graph.

Level of Abstraction (Zooming): To prevent cognitive overload, the DVGA provides "Cluster Views" for Sub-Orchestrators, hiding internal specialist details until a deeper inspection is requested.

Truth-Source Alignment: The graph must be a 1:1 reflection of the current system state stored in the CMPL (Memory Layer).

## Inter-Subskill Consistency:

With SBCI: During the boot sequence, DVGA maps the "Génesis" of the network, documenting the first instantiation of the Orchestrator.

With PEAD: Displays the "Wealth Distribution" of authority across the network to ensure anti-monopoly compliance.

With CAR: When a conflict occurs, DVGA highlights the "Contested Link" between the agents in disagreement, facilitating human or higher-order agent intervention.

## Operational Example:

"DVGA System Alert: Node 'Beta-Sub-Orch' showing high authority accumulation and low temporal validity. Visualizing potential cascade failure if lease is not renewed by Orchestrator Alpha."
