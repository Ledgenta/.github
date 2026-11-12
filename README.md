# Legenta

### Building the foundations of modern banking.

**Legenta** is an evolving core banking platform focused on building reliable, scalable, and maintainable financial infrastructure.

The project explores the engineering principles behind modern financial systems, including double-entry accounting, account management, transaction processing, payment integrations, and distributed systems.

Legenta is built as a hands-on engineering initiative, with an emphasis on financial correctness, system reliability, and thoughtful software architecture.

## Our Focus

- **Core Banking:** Managing financial accounts, balances, and transaction lifecycles.
- **Double-Entry Ledger:** Maintaining accurate and auditable financial records.
- **Transaction Processing:** Exploring consistency, idempotency, concurrency, and reconciliation.
- **Payment Infrastructure:** Building integrations for transfers, card payments, and external financial networks.
- **Distributed Systems:** Understanding reliable communication, failure recovery, and service boundaries.
- **Security:** Applying secure engineering practices to financial applications.

## Technology Stack

Legenta is designed to explore different technologies based on their suitability for specific financial workloads.

| Technology | Intended Use |
|---|---|
| Go | Core banking and ledger engine |
| Java / Spring Boot | Card payment processing and integrations |
| PostgreSQL | Transactional data storage |
| Angular / TypeScript | Web application |
| Docker | Containerization |
| GitHub Actions | Continuous integration and delivery |

*The architecture and technology stack will evolve as development progresses.*

## Architecture & Repositories

Legenta is being developed incrementally, beginning with a modular core banking foundation and expanding into independently deployable services where appropriate.

Planned components include:

- **Core Banking Engine** — Accounts, ledger, balances, and transaction management.
- **Card Processing Service** — Card payment workflows and external processor integrations.
- **Web Application** — User interfaces for interacting with the platform.
- **Infrastructure** — Deployment configurations and supporting infrastructure.

Repositories will be published and documented as development progresses.

## Engineering Principles

We believe financial infrastructure should be built around a few fundamental principles:

1. **Correctness before performance.** Financial accuracy is non-negotiable.
2. **Consistency by design.** Financial state must remain reliable under concurrent operations and failures.
3. **Auditability.** Financial movements should be traceable and explainable.
4. **Resilience.** Systems should handle retries, timeouts, and partial failures safely.
5. **Simplicity.** Introduce architectural complexity only when justified.

## Project Status

🚧 **Early Development**

Legenta is an experimental engineering project intended for learning, exploration, and demonstrating financial systems architecture.

It is not currently intended for production banking operations.

---

**Legenta — Engineering the core of modern finance.**
