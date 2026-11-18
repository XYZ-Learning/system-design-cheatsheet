# System Design Cheat Sheet (free)

A free one-page map of the building blocks behind most system design interview questions, by XYZ Education.

| Building block | Use it for | Watch out for |
|---|---|---|
| Load balancer | Spreading traffic, health checks | Sticky sessions, single point of failure |
| SQL database | Transactions, joins, money | Vertical scaling limits |
| NoSQL store | Flexible schema, horizontal scale | Weaker consistency, query limits |
| Cache (Redis, CDN) | Hot reads, static assets | Invalidation, stampedes |
| Replication | Read scale, fault tolerance | Replica lag |
| Sharding | Data larger than one node | Hot partitions, cross-shard queries |
| Message queue | Async work, absorbing spikes | Retries, idempotency, ordering |
| Observability | Catching failures early | Alert fatigue |

**Interview framework:** clarify requirements → estimate scale → high-level design → deep dive (usually data) → bottlenecks & trade-offs.

## Want the full notes?
[System Design Complete Notes – Beginner to Advanced](https://xyznotes.in/notes/96b989b3-878a-4799-80e7-5574614cc2d7): 164 pages on architecture fundamentals, scalability, load balancing, databases, caching, distributed systems, real-world case studies, diagrams and interview prep. Preview the first pages on XYZ Notes.

Also from XYZ Notes: [CTET notes PDF](https://xyznotes.in/exams/ctet) · [Personal Finance for Everyone](https://xyznotes.in/notes/68211c0a-fc7d-4396-a965-4a63db28b462)

---
© 2026 XYZ Learning Private Limited. This cheat sheet is original free content and is not an excerpt of the paid notes.
