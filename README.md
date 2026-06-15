<!-- HEADER -->
<div align="center">

```
♟ A pawn that knows its shadows are kings.
```

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3000&pause=800&color=FFFFFF&center=true&vMultiline=false&width=600&lines=D.+Karthikeya;Backend+Engineer;Distributed+Systems+Thinker;Scalability+Craftsman" alt="Typing SVG" />

<sub>**Algorithms · Distributed Systems · Backend Engineering · Scalable Systems**</sub>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-Dasari--Karthikeya-181717?style=flat-square&logo=github)](https://github.com/Dasari-Karthikeya)
&nbsp;
[![Email](https://img.shields.io/badge/Email-reach%20me-EA4335?style=flat-square&logo=gmail)](mailto:your@email.com)

</div>

---

## Who I Am

I write systems that hold under pressure — the kind of code that doesn't apologize when traffic spikes or when the network is flaky at 3am. My craft lives at the intersection of theoretical CS and production-grade engineering: turning algorithmic precision into infrastructure that actually ships.

I think deeply before I type. I document decisions, not just code. I care about the second-order effects of every abstraction I introduce.

Currently sharpening my edge across **distributed consensus**, **high-throughput data pipelines**, and **API design at scale**.

---

## Technical Stack

### Core Languages
```
Java        ████████████████████  Primary — systems & services
Python      ███████████████░░░░░  Algorithms, tooling, scripting
C++         ████████████░░░░░░░░  Competitive programming, low-level
SQL         ███████████████░░░░░  Complex queries, query planning
```

### Distributed Systems & Backend
- **Messaging**: Kafka, RabbitMQ — event-driven architectures, consumer group tuning
- **Databases**: PostgreSQL, Redis, Cassandra — schema design, replication, caching strategies
- **APIs**: REST (RFC-compliant), gRPC, GraphQL basics
- **Coordination**: ZooKeeper-style leader election, distributed locking patterns

### Infrastructure & Tooling
- **Containers**: Docker, basics of Kubernetes pod scheduling
- **Cloud**: AWS (EC2, S3, RDS, Lambda), GCP fundamentals
- **Observability**: Prometheus, Grafana, structured logging, distributed tracing concepts
- **CI/CD**: GitHub Actions, Jenkins pipelines

---

## Projects

### `consensus-raft` — Raft Consensus Implementation
A from-scratch Raft implementation in Java with leader election, log replication, and membership changes. Built to understand why distributed systems are hard before trusting libraries to hide it.

> **What I learned**: The spec looks clean. The edge cases aren't. Especially around log compaction and network partitions happening simultaneously.

`Java` `Sockets` `Concurrency` `State Machines`

---

### `rate-limiter-service` — Token Bucket at Scale
A standalone rate-limiting microservice using the token bucket algorithm, designed to handle 50K+ req/s with Redis as the shared state store. Includes sliding window fallback.

> **Design choice**: Redis Lua scripts for atomic check-and-decrement. No race conditions. No excuses.

`Java` `Redis` `Spring Boot` `Docker`

---

### `async-task-queue` — Distributed Job Scheduler
A lightweight task queue with retry logic, dead-letter queues, priority lanes, and worker autoscaling hooks — built before reaching for Celery or Sidekiq.

> **Insight**: Most job queues fail at exactly-once semantics. Mine fails gracefully and makes that visible.

`Python` `PostgreSQL` `Kafka` `Docker`

---

### `algo-patterns` — Curated Algorithm Playbook
200+ problems solved with annotated explanations — not just solutions, but the *why* behind the pattern selection. Organized by technique: sliding window, segment trees, topological sort, DP on graphs.

> For anyone tired of grinding LeetCode without actually getting better.

`Python` `C++` `Competitive Programming`

---

## How I Think About Engineering

**Correctness before performance.** A fast system that gives wrong answers isn't an optimization — it's a liability.

**Observability is a feature.** If I can't tell what the system is doing from the outside, I haven't finished building it.

**Distributed systems lie.** Networks partition. Clocks drift. Nodes crash silently. Every design decision is a bet on which failure modes you can tolerate.

**Read the paper first.** Most production problems have been formally described somewhere. Spanner, Dynamo, Kafka's log design — these aren't academic curiosities, they're operating manuals.

---

## Currently Exploring

- [ ] Building a mini-LSM tree storage engine from scratch
- [ ] Deep-reading *Designing Data-Intensive Applications* (Kleppmann) — chapter by chapter with notes
- [ ] Optimizing query plans in PostgreSQL for analytical workloads
- [ ] Studying consensus protocol variants beyond Raft (Paxos, EPaxos, Viewstamped Replication)

---

## GitHub Activity

<div align="center">

![Karthikeya's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Dasari-Karthikeya&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffffff&icon_color=58a6ff&text_color=8b949e)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Dasari-Karthikeya&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffffff&text_color=8b949e)

</div>

---

## The Chess Lesson

A pawn controls exactly two squares ahead of it. That constraint is the whole game. You don't win by ignoring it — you win by understanding it so deeply that your opponent never sees the queen coming.

Engineering is the same. Constraints aren't obstacles. They're the shape of the problem. Master the constraint; master the solution.

---

<div align="center">

```
♟ → ♛
pawn to queen is not luck. it is deliberate movement.
```

<sub>Open to interesting backend/systems roles and technical conversations. Reach out.</sub>

</div>
