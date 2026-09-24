# arthome-studio-web

The **professional control room**, in **Angular 22**. Running the live show, scheduling, moderation,
crew and rights, revenue and payouts.

15 navigation entries filtered by role · 6 personas · the run desk, and a date sheet in six panes

## Status

**Not started.** Tier 4 — the architecture demonstration. Two heterogeneous stacks, one domain: the
same `@arthome/core` the storefront uses.

## Where the design lives

The architecture, the interface contracts, the decisions and their reasons all live in
**[arthome-core](https://github.com/jubasse/arthome-core)**:

- `architecture/` — the context map, the data model, the event catalogue, the ADRs
- `openapi/` — the contracts of the two BFFs
- `proto/` — the Kafka event schemas
- `DECISIONS.md` — the arbitration log
- `architecture/critical-rules.md` — **re-read it every session**, nineteen lines

## Arthome

A streaming platform for live performance: ticketing, live, moderated chat, replays,
merchandise, artist payouts. Two products — a public storefront and a professional studio — across
five surfaces, served by seven microservices.
