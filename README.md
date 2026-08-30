# Hi, I'm Ankit 👋

Backend-leaning Full-Stack Developer building systems that care about correctness — transactions, concurrency, and data integrity over flashy UI.

- 🔭 Currently building **[Aurum](https://github.com/ankitkodes/Aurum)** — a double-entry banking ledger with ACID-safe concurrent transfers, row-level locking, and 95% query latency reduction via indexing
- 🛠️ Also shipped **[BugTrace](https://bugtrace.in)** — a live error-monitoring SaaS with a published npm TypeScript SDK
- 🌱 Deep in DSA, system design, and DB internals prep — CMU 15-445, DDIA, Alex Xu
- 💼 Open to backend / full-stack SWE roles
- 🌐 Portfolio: [ankitkumar.site](https://ankitkumar.site)
- 📫 itsankitkumar07@gmail.com

## Stack

`TypeScript` `Node.js` `PostgreSQL` `Drizzle ORM` `React` `Next.js`

## Flagship Projects

**Aurum** — Double-entry ledger backend focused on financial correctness: `SELECT FOR UPDATE` row-level locking with deterministic lock ordering to prevent deadlocks, cursor-based pagination, idempotency key middleware, and a Clearing Account pattern for deposit/withdrawal flows. Verified 225ms → 11ms query latency reduction on 50K+ rows via `EXPLAIN ANALYZE`.

**BugTrace** — Sentry-inspired error tracking SaaS with a lightweight npm SDK for real-time exception logging in JavaScript apps.

**CODELAVE** — Managed code execution infrastructure for AI agents: secure, isolated sandboxes to run code and stream output.
