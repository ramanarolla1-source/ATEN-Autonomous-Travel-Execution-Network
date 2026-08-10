<img width="1536" height="1024" alt="ATEN" src="https://github.com/user-attachments/assets/8be628f1-2417-4e32-a125-35f5c0ff785d" />


# ATEN

# Autonomous Travel Execution Network

### A Companion AI Agent Architecture running on top of KeeperHub's execution layer.

<p align="center">

<!-- Replace with Hero Banner -->
<img src="assets/images/ATEN-Banner.png" width="100%"/>

</p>

---

## Overview

ATEN demonstrates how a **Main Service AI Agent** can dynamically associate with a **Companion AI Agent Network**, enabling **KeeperHub** to orchestrate multiple specialized workflows generated from a single customer request.

Instead of ending execution after completing one task, ATEN extends the execution lifecycle by allowing specialized AI Agents to independently write additional workflows while continuously relying on KeeperHub's execution and reliability layer.

Travel is simply the proof of concept.

The architecture can be applied to any autonomous AI ecosystem requiring coordinated multi-agent execution.

---

# Why ATEN?

Traditional AI applications typically execute one workflow to complete one customer request.

ATEN introduces a different execution architecture.

After the **Main Service AI Agent** successfully completes its primary workflow, it automatically associates with a **Companion AI Agent Network**.

Each Companion AI Agent independently performs reasoning within its own domain, writes its own workflow and delegates reliable execution back to KeeperHub.

Rather than executing one isolated workflow, KeeperHub orchestrates an ecosystem of specialized AI workflows generated from one customer request.

---

# Architecture

<p align="center">

<img src="assets/architecture/ATEN-Architecture.png" width="100%"/>

</p>

---

# Architecture Flow

```text
Traveller

↓

Main Service AI Agent

↓

Writes Primary Workflow

↓

MCP

↓

KeeperHub Execution & Reliability Layer

↓

Primary Workflow Successfully Executed

↓

Companion AI Agent Network

↓

Each Companion AI Agent Writes Specialized Workflow

↓

KeeperHub

↓

Reliable On-Chain Execution

↓

Audit Trail

↓

Workflow Preservation

↓

Reusable Workflows

↓

Complete Traveller Experience
```

---

# Main Service AI Agent

The Main Service AI Agent fulfils the traveller's primary request.

Examples include:

- Flight Booking AI Agent
- Hotel Booking AI Agent
- Travel Insurance AI Agent

Each Main Service AI Agent independently reasons over customer requirements and writes the primary workflow.

---

# Companion AI Agent Network

The Companion AI Agent Network is **not introduced to increase the number of AI Agents.**

It demonstrates how KeeperHub can reliably orchestrate multiple specialized workflows generated from a single Main Service AI Agent.

Companion AI Agents include:

- 🌍 Time Zone Intelligence
- ☁ Weather Intelligence
- 🌐 Cultural Intelligence
- 🛡 Destination Safety
- 📍 Local Discovery
- 🔔 Smart Notifications

Each Companion AI Agent independently writes its own workflow and delegates reliable execution to KeeperHub.

---

# Why KeeperHub?

ATEN is built entirely on top of KeeperHub's execution layer.

KeeperHub provides:

- ✅ MCP Integration
- ✅ Workflow Validation
- ✅ Simulation Before Execution
- ✅ Reliable On-Chain Execution
- ✅ Retry Logic
- ✅ Audit Trail
- ✅ Workflow Preservation & Reuse

Together these capabilities transform autonomous AI reasoning into reliable blockchain execution.

---

# Demo

🎥 **Demo Video**
https://youtu.be/fWNMzv3GWeQ

📄 **One Pager**

https://docs.google.com/document/d/1WoSULKWnWu6sQxgnHBmTelmmwGUB6OOzFtgzNMy_mb0/edit?usp=sharing

---

# Tech Stack

- KeeperHub
- MCP (Model Context Protocol)
- Autonomous AI Agents
- Multi-Agent Architecture
- Workflow Orchestration
- Reliable On-Chain Execution
- Blockchain

---

# Repository Structure

```text
ATEN
│
├── assets/
├── docs/
├── diagrams/
├── demo/
├── README.md
└── LICENSE
```

---

# Built For

**KeeperHub – Agents Onchain Hackathon**

---

# Closing

ATEN demonstrates how a **Main Service AI Agent** can dynamically associate with a **Companion AI Agent Network**, enabling KeeperHub to orchestrate multiple specialized workflows generated from a single customer request.

**ATEN**

### *A Companion AI Agent Architecture running on top of KeeperHub's execution layer.*

---
