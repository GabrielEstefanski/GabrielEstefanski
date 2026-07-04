## Gabriel Braga Estefanski

Software engineer based in Jacareí, Brazil. Backend engineer at an aerospace
company; on the side, [apsis](https://github.com/GabrielEstefanski/apsis) — a
validated N-body dynamics library in Rust.

### What I'm working on

**[apsis](https://github.com/GabrielEstefanski/apsis)** — N-body dynamics in
Rust, built around one idea: force perturbations as independent, citable
operator crates rather than patches to a monolith. Each operator declares the
physical preconditions it needs from the gravitational kernel, and the run
record pins the physical model the way Cargo.lock pins code — an artifact you
can cite. Every physics claim is gated in CI: Mercury's 1PN perihelion
precession reproduced to a derived 4.6×10⁻⁶ error budget, radiation-pressure
dust decay within 0.95 % of the Burns 1979 law, trajectory parity with
REBOUND IAS15 at the 10⁻¹³ energy floor. Byte-identical output across
Windows/Linux and x86_64/aarch64 under a pinned toolchain. Archived at
Zenodo: [DOI 10.5281/zenodo.21197539](https://doi.org/10.5281/zenodo.21197539).

**EBOM platform** at an aerospace company (since 2023) — the system that owns
the engineering bill of materials across cabin product lines. Multi-level
cascade generation and explosion, ECN-driven change workflows, comparison and
audit between revisions, queued processing for heavy operations, and
idempotent multi-rank propagation so concurrent edits and retries don't
corrupt the tree. Two things I'm proud of from this work: a backend refactor
that took critical APIs from ~2 minutes to ~5 seconds, and an internal
automation that lifted delivery speed for the team by ~40%.

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
