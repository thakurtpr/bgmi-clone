# bgmi-clone

A browser-based 3D multiplayer battle royale, built to be played with PC-style keyboard and mouse controls first. Its gameplay is inspired by tactical battle royales played on PC and on mobile.

> **Independent project.** This repository is not affiliated with, endorsed by, or connected to Krafton, BGMI, or PUBG. All code, maps, characters, weapons, audio and branding are original or used under the licenses listed in `assets/LICENSES.md`.

## Status

**Phase 1: Architecture**. The design is awaiting approval, and no implementation code exists yet.

- Architecture & blueprint: [docs/architecture/phase-1-architecture.md](docs/architecture/phase-1-architecture.md)
- Roadmap: tracked as GitHub milestones (Phase 1–8) and issues.

## Planned stack

TypeScript monorepo (pnpm + Turborepo) with these parts:
- **Browser client:** Three.js and React for the UI.
- **Authoritative game server:** Node.js, WebSocket, Rapier physics.
- **API:** Fastify with PostgreSQL. Redis is added at scale.
- **Deployment:** Docker.

See the architecture doc for the reasoning behind each choice.
