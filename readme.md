# NANDA Registry: Foundational Infrastructure for the Internet of Agents

Welcome to the official repository for **NANDA** (Networked Agents and Decentralized AI), an initiative from MIT Media Lab that aims to redefine how autonomous agents coordinate across the web.

---

## What is NANDA?

NANDA is building the foundational infrastructure for the **Internet of Agents** — a new web architecture where autonomous agents interact, transact, and coordinate on behalf of users across decentralized networks.

> Imagine saying: `@moonbakery get me the usual cake for my daughter’s birthday`, and your agent handles the rest — securely, privately, and without needing five apps and three emails.

While today's internet connects humans to websites, NANDA connects agents to agents, enabling proactive, context-aware, and trust-preserving interactions.

---

## Core Components

### 1. Minimal Registry Architecture

A lean, privacy-aware system for resolving agent identifiers (`@agent`) into verifiable capability facts.

- Verifiable, signed AgentFacts
- TTL-based dynamic routing
- Modular, federated deployment

### 2. AgentFacts Schema

A standardized JSON-LD format representing agent capabilities, trust assertions, and endpoint data:

```json
{
  "agent_name": "urn:agent:nanda.mit.edu:lab1:robot42",
  "capabilities": { "streaming": true },
  "skills": [ "translation", "scheduling" ],
  "telemetry": { "endpoint": "otlp://metrics.nanda.ai" }
}
```

### 3. Protocol Integration

Supports **MCP**, **A2A**, and other emerging agent communication protocols.

- Privacy-preserving, decentralized resolution
- Support for static, rotating, and adaptive endpoints
- Works across consumer, enterprise, and research deployments

---

## Live Demos

- [Chat with Agents](https://chat.nanda-registry.com) – Explore real-time interactions.
- [Join the Waitlist](https://waitlist.nanda-registry.com) – Reserve your agent handle.

---

## Why This Matters

AI is shifting from monolithic models to ecosystems of autonomous agents. As billions of personal, enterprise, and task-specific agents emerge, NANDA provides a DNS-equivalent for this future — with:

- Verifiable identity and capability resolution
- Trust without central control
- Agent-to-agent coordination at internet scale

---

## Learn More

- [A Perspective on Decentralizing AI](./docs/decentralized_ML_perspective-16.pdf)
- [Game of Agents – Episode 1 & 2](./docs/Game of Agents — Episode 1_ Let there be Agents _ by Abhishek Singh _ Medium.pdf)
- [Verified AgentFacts & NANDA Registry Paper](./docs/v0.1 Scaling Trust Beyond DNS - NANDA-Registry.pdf)
- [Internet of Agents Architecture](./docs/NandaRegistry_AgenticChat.pdf)

---

## Governance and Neutrality

NANDA operates as a **neutral academic-corporate consortium**, with a federated registry design that ensures:

- Privacy-preserving, zero-trust resolution
- AgentFacts updates without central bottlenecks
- Interoperability across institutional, enterprise, and public agent ecosystems

---

## Contribution

This repo is maintained by researchers and practitioners across academia and industry.

We welcome:
- Proposals for new agent protocols
- Schema improvements to AgentFacts
- Contributions to decentralized resolver infrastructure

**PRs welcome. Bureaucracy discouraged. Insight encouraged.**

---

## License

This project is licensed under the **MIT License**.
