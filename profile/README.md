# Async Framework

Async Framework builds tools for rapid prototype-to-prod development.

The goal is to make early ideas fast to sketch, easy to inspect, and realistic enough to grow. Start with local examples, JSON fixtures, tiny runtimes, async handlers, and signal-driven projections; then move toward typed APIs, durable state, production workflows, multi-team delivery, and agentic interfaces without throwing the prototype away.

## Projects

| Project | What it is | Use it for |
| --- | --- | --- |
| [async-framework](https://github.com/async-framework/async-framework) | Lightweight signal-based framework for reactive web apps with custom elements and async handlers. | Delegated `on:<event>` handlers, local and remote handler registries, runtime-first UI experiments, and signal-based projections. |
| [async-db](https://github.com/async-framework/async-db) | Gradual data workflow from JSON fixtures to generated types, local APIs, writable stores, and real persistence. | Move from local prototype data to typed APIs and durable state in small steps. |
| [async-miniweb](https://github.com/async-framework/async-miniweb) | Tiny local web runtime for static-hosted demos and fast Node-side integration tests. | Host demos, test Web-standard behavior, and keep examples easy to run and inspect. |

## Direction

We care about:

- Prototype speed without dead-end architecture.
- Runtime-owned state and explicit transitions for long-lived async workflows.
- Async handlers that keep UI intent small and composable.
- Signals and projections that make state changes visible without scattering workflow logic.
- Local-first examples and small runtimes that make behavior testable early.
- Gradual paths from demos and fixtures to production-shaped systems.
- Async multi-team parallel deployment as an evolving focus for shipping related workstreams without turning coordination into a bottleneck.

The current repos are still evolving, but the throughline is stable: build small tools that compress the distance between a working prototype, coordinated team execution, and production software.
