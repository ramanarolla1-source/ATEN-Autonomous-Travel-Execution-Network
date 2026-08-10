# ATEN Architecture Overview

ATEN (Autonomous Travel Execution Network) demonstrates a **Companion AI Agent Architecture** running on top of **KeeperHub's execution layer**.

The architecture consists of two distinct classifications of AI Agents:

- **Main Service AI Agent** – Fulfils the traveller's primary request by reasoning over user requirements and writing the primary workflow.
- **Companion AI Agent Network** – A coordinated collection of specialized AI Agents that automatically associate with the Main Service AI Agent after successful execution of the primary workflow.

Rather than executing a single isolated workflow, KeeperHub orchestrates multiple specialized workflows through:

- MCP Integration
- Workflow Validation
- Simulation
- Workflow Orchestration
- Reliable On-Chain Execution
- Retry Logic
- Audit Trail
- Workflow Preservation

This architecture demonstrates how KeeperHub evolves from executing individual AI workflows to orchestrating an ecosystem of autonomous AI workflows generated from a single customer request.

Travel serves as the proof of concept, while the architecture is applicable to broader autonomous AI systems requiring reliable multi-agent execution.
