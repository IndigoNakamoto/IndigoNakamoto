# Indigo Nakamoto

**Applied AI / Full-Stack Engineer · production RAG and Next.js product**
SF Peninsula · Bay Area hybrid or US remote

I specify, ship, and operate user-facing AI surfaces. Interface first. Tests on spend, auth, and retrieval-miss before the fix.

TypeScript · Python · Next.js · FastAPI · Payload · Postgres · Redis · Mongo vector search

[indigonakamoto@gmail.com](mailto:indigonakamoto@gmail.com) · [X](https://x.com/indigo_nakamoto) · [github.com/IndigoNakamoto](https://github.com/IndigoNakamoto)

## Current — Litecoin Foundation

Contractor, Dec 2025–present. Listed on the [Foundation team page](https://litecoin.com/litecoin-foundation) as Applications Developer for Projects/Chat. I shipped and operate both apps below.

## Featured

### Grounded RAG chat — [litecoin.com/chat](https://litecoin.com/chat)

[![CI](https://github.com/IndigoNakamoto/Litecoin.com-Chat/actions/workflows/ci.yml/badge.svg)](https://github.com/IndigoNakamoto/Litecoin.com-Chat/actions/workflows/ci.yml)

Answers from a Foundation-controlled Payload CMS, not a general chatbot. Hybrid search, query rewrite, semantic cache. A retrieval miss becomes a flagged web search and a logged editorial gap, never a guessed org fact. Spend is capped at $5/day globally and $0.25/user/day against abuse and a donor budget, with a Discord alert at 80% and a hard stop at 100%.

Python (FastAPI) · Next.js · Payload · Redis · MongoDB Vector Search

[Live](https://litecoin.com/chat) · [Repo](https://github.com/IndigoNakamoto/Litecoin.com-Chat) · [Tests](https://github.com/IndigoNakamoto/Litecoin.com-Chat/blob/main/docs/TESTING.md)

### Funding board — [litecoin.com/projects](https://litecoin.com/projects)

I proposed the board and shipped the Next.js app on existing tables and The Giving Block rails. I operate listings — intake, publish and reject, keeping project pages current, coordinating review. Review is still partly a Discord handoff. The Foundation owns the funds.

Board totals are ecosystem accounting, not my revenue and not amounts I underwrote; some figures predate the app: $122k paid · $89k raised · $81k matched.

[Live](https://litecoin.com/projects) · [Repo](https://github.com/IndigoNakamoto/Litecoin.com-Projects-Donate)

### Chain indexers — `lrk` and `drk`

Litecoin and Dogecoin ports of Bitcoin Research Kit, operated from local nodes. On Litecoin I added MWEB decoding so the index survives the first extension block.

[lrk](https://github.com/IndigoNakamoto/lrk) · [drk](https://github.com/IndigoNakamoto/drk)

## Failure modes I designed for

- **Retrieval miss** — flagged web search plus a logged gap; no invented Foundation facts.
- **CMS lag** — answers come only from published Payload docs; stale coverage is a logged miss, not a guess.
- **First extension block** — MWEB decoding so `lrk` does not die the moment MWEB data appears.

## How I work

Agents draft. I specify the interface and the tests, review the diff, and check production before I merge. Spend, auth, and retrieval-miss need a failing test before the fix and a passing test after.

Best fit is a team that already accepts agent-assisted development.

## Seeking

Full-time IC owning one AI/web surface — production RAG or agents, Next.js product. I have shipped Rust protocol work when the product needed it ([LitecoinDevKit](https://github.com/LitecoinDevKit): Litecoin and MWEB on BDK-shaped APIs, plus a prototype Tauri wallet), but that is not what I am optimizing for.

[![Regtest MWEB](https://github.com/LitecoinDevKit/bdk/actions/workflows/regtest_mweb.yml/badge.svg)](https://github.com/LitecoinDevKit/bdk/actions/workflows/regtest_mweb.yml) — MWEB peg-in and peg-out run against a regtest node on every change.

UCSC B.A. Business Management Economics, 2011 · Hack Reactor, 2016
