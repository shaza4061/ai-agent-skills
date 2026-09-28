# AI Agent Skills

A curated collection of reusable AI agent skills for software engineering, architecture, system design, and developer workflows.

## Skills

### Software Engineering

- `software-engineering/java-developer` — Production-grade Java development using TDD, SOLID, Clean Code, testing, and maintainability practices.

### Architecture

- `architecture/solution-architect` — End-to-end solution architecture from requirements through architecture options, trade-offs, C4 models, ADRs, risks, and implementation roadmap.
- `architecture/architecture-reviewer` — Review existing architectures for scalability, reliability, security, maintainability, coupling, cost, and operational risks.
- `architecture/adr-writer` — Create concise, consistent Architecture Decision Records.
- `architecture/c4-architect` — Model systems using the C4 architecture model.
- `architecture/ddd-architect` — Apply Domain-Driven Design, bounded contexts, aggregates, domain events, and context mapping.
- `architecture/api-architect` — Design robust REST/API contracts, versioning, error handling, security, and governance.
- `architecture/event-driven-architect` — Design Kafka and event-driven systems with delivery semantics, ordering, idempotency, schemas, and failure handling.
- `architecture/cloud-architect` — Evaluate and design cloud architectures with emphasis on reliability, security, scalability, and cost.
- `architecture/microservices-architect` — Evaluate service boundaries, decomposition, communication, data ownership, and operational complexity.
- `architecture/architecture-migration-planner` — Plan legacy modernization and architecture migration incrementally.
- `architecture/non-functional-requirements` — Discover, quantify, and validate NFRs such as availability, latency, throughput, RTO/RPO, security, scalability, observability, and cost.

### System Design

- `system-design/system-design-interviewer` — Practice and evaluate system-design problems using structured requirements, capacity, architecture, trade-offs, and failure analysis.

## Design Philosophy

These skills are designed to make AI agents reason before implementing.

The preferred architecture workflow is:

Business Requirements
→ Functional Requirements
→ Non-Functional Requirements
→ Constraints & Assumptions
→ Architecture Options
→ Trade-off Analysis
→ Architecture Decision
→ C4 / Detailed Design
→ ADRs
→ Risks & Mitigations
→ Implementation Roadmap

The skills deliberately discourage premature technology selection and unnecessary complexity.

## Usage

Each skill is self-contained in a `SKILL.md` file.

Copy or reference the relevant skill in your AI coding-agent environment and use it as the agent's operating instructions.

## Principles

- Prefer evidence over assumptions.
- Challenge requirements when ambiguity affects architecture.
- Make trade-offs explicit.
- Prefer the simplest architecture that satisfies the requirements.
- Treat security, reliability, observability, and operability as first-class concerns.
- Preserve existing behaviour when working in established systems.
- Avoid unnecessary abstraction and technology-driven architecture.
