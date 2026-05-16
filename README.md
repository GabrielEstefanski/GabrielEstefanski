## Gabriel Braga Estefanski

Software engineer based in Jacareí, Brazil. Backend engineer at an aerospace
company; on the side, a Rust N-body simulator.

### What I'm working on

**EBOM platform** at an aerospace company (since 2023) — the system that owns
the engineering bill of materials across cabin product lines. Multi-level
cascade generation and explosion, ECN-driven change workflows, comparison and
audit between revisions, queued processing for heavy operations, and
idempotent multi-rank propagation so concurrent edits and retries don't
corrupt the tree. Two things I'm proud of from this work: a backend refactor
that took critical APIs from ~2 minutes to ~5 seconds, and an internal
automation that lifted delivery speed for the team by ~40%.

**Rust N-body simulator** — a numerical integrator for gravitational dynamics.
Multi-crate Cargo workspace, Python bindings via maturin, and a specific
interest in making a simulation's *physical model* a first-class artifact you
can pin and cite the same way Cargo.lock pins code dependencies.

### Selected work

- **FlightWatch** — Live map of aircraft in flight. Pulls real-time positions
  from OpenSky, click any plane for details, auto-clusters at zoom-out.
  Underneath: C# backend with Clean Architecture and CQRS, MongoDB, low-latency
  push via SignalR, event-driven with RabbitMQ + MassTransit, Next.js + Leaflet
  frontend. Structured logging, distributed tracing, unit and integration tests.
  → [GabrielEstefanski/FlightWatch](https://github.com/GabrielEstefanski/FlightWatch)

### Stack

Day-to-day: C#, Node.js, TypeScript, Vue 3, React, PostgreSQL, SQL Server,
Docker, AWS.
Comfortable with: WebSockets / SignalR, RabbitMQ, MassTransit, Clean
Architecture, DDD, async and parallel processing.
Currently working in: Rust (workspaces, PyO3 / maturin), numerical code.

### Contact

- gabrielbragaestefanski@gmail.com
- [gabrielestefanski.dev](https://www.gabrielestefanski.dev/)
- [linkedin.com/in/gabriel-estefanski](https://www.linkedin.com/in/gabriel-estefanski/)
