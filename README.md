# Oladele Israel Omole

**Backend engineer · Go, TypeScript/Node.js · PostgreSQL, Redis · Fintech, health and aviation**

4+ years shipping production backends. I've led engineering on a telehealth platform that grew from 300 to 1,200+ users in three months, built payment integrations that processed $2.9M+ (₦4B+) with zero double-charges, and written Go APIs holding sub-5ms P99 latency.

📍 Lagos, Nigeria · Remote-first · Open to relocation (UK · EU · US) · [Visa sponsorship: needed / not needed]

[LinkedIn](https://linkedin.com/in/oladele-omole113/) · [Email](mailto:omoleoladele43@gmail.com) · [Portfolio](https://oladele-israel.vercel.app/) · [Engineering notes](https://github.com/Oladele-israel/engineering-notes)

---

## Production systems (private repos, documented publicly)

The code is private under client and employer agreements, so I document each system as a case study: the problem, the architecture, the tradeoffs and the measured result. Code walkthroughs are available on a call, or via read access under NDA where the owner allows it.

| System | Result | Key engineering | Case study |
|---|---|---|---|
| **Unicco Health**: telehealth platform (appointments, prescriptions, pharmacy fulfillment, dispatch, admin). Engineering lead, MVP shipped in 4 weeks. | 300 → 1,200+ users in 3 months · 1,000+ prescription fulfillments/month · 100+ consultations/week | NestJS, Next.js, PostgreSQL, Prisma, Redis + BullMQ jobs, real-time scheduling, video integration, encryption for health data | [Read →](https://github.com/Oladele-israel/engineering-notes/blob/main/01-unicco-health.md) |
| **Core banking platform** for a Nigerian microfinance bank serving hundreds of thousands of customers | Regulatory compliance delivered (CBN-aligned) · production bug rate reduced | End-to-end encryption, idempotent retries, audit-trail logging, structured error handling | [Read →](https://github.com/Oladele-israel/engineering-notes/blob/main/02-core-banking.md) |
| **Multi-gateway payments**: Stripe, PayPal and Paystack integrations | $2.9M+ (₦4B+) processed with zero double-charges | Idempotency keys, retry safety, transactional outbox | [Read →](https://github.com/Oladele-israel/engineering-notes/blob/main/03-payments-idempotency.md) |
| **High-throughput Go APIs** | Sub-5ms P99 latency | Queue-based processing (Asynq/Redis), circuit breakers, transactional outbox | [Read →](https://github.com/Oladele-israel/engineering-notes/blob/main/04-go-low-latency-api.md) |

---

## Public projects

### [DB Schema Visualizer](https://github.com/Oladele-israel/visio_fe)
Browser-based schema explorer that maps tables, foreign keys and relationships from a live PostgreSQL database, with no SQL required.
**Node.js · PostgreSQL · React** · [Frontend](https://github.com/Oladele-israel/visio_fe) · [Backend](https://github.com/Oladele-israel/db_visio_BE) · [AI agent](https://github.com/Oladele-israel/dbvisio_agent) · [Live demo](#)

### [Image Steganography Tool](https://github.com/Oladele-israel/stegnography)
Hides passphrase-encrypted text inside image pixels using LSB steganography.
**Node.js · Canvas API**

---

## Experience

| Role | Company | When |
|---|---|---|
| Backend Engineer, Engineering Lead | Unicco Health (telehealth) | Jul 2026 – Present |
| Backend Software Engineer | Virtual Switch International (core banking and airline flight management) | 2025 – Present |
| STEM Software Engineering Instructor | XPR Nigeria Limited | Mar 2026 – Present |
| Backend Engineer | Davenport Microfinance Bank (via Virtual Switch) | 2024 – 2025 |
| Lead Software Engineer | Kabod Labs (reusable auth, RBAC and API foundations across client projects) | 2022 – 2023 |
| Software Engineer Intern | NeraHubs | 2021 – 2022 |

Also: Lead Engineer at the UNESCO Youth Hackathon · active member of Google Developer Community Port Harcourt.

---

## How I work

- **Reliability:** idempotency, retries with backoff, circuit breakers and health checks by default.
- **Observability:** structured error logging and dashboards, so incidents take minutes to diagnose.
- **Security:** dual-token auth, RBAC, AES-256 encryption and audit trails for sensitive data.
- **Leadership:** I set technical direction, run code reviews and mentor engineers.

## Stack

**Languages:** Go, TypeScript, JavaScript (Node.js)
**Frameworks:** NestJS, Express, Next.js, React
**Data and queues:** PostgreSQL, Prisma, TypeORM, MongoDB, Redis, BullMQ, Asynq
**Infra:** AWS, Docker, Render, Vercel, Linux, Git
**Patterns:** transactional outbox, idempotency, circuit breakers, RBAC, microservices

---

**Looking for:** a backend or platform engineering role (senior track) on a team that values reliability.
**Best way to reach me:** [omoleoladele43@gmail.com](mailto:omoleoladele43@gmail.com)
