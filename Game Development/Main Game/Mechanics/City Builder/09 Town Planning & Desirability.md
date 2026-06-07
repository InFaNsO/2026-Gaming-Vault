# City Builder — Town Planning & Desirability (DEEP pillar)

> Elevated to a **DEEP core pillar** 2026-06-07 — the **Town-to-City cozy soul** of the game. The intimate, hand-planning layer that makes each town a loved place, not a spreadsheet. This is the **zoom-in** game (logistics/network is the zoom-out game).

---

## Core idea

A building's **desirability / happiness** depends on its **spatial context**, and you **plan ahead** for growth. The joy is the placement puzzle, not optimization-for-its-own-sake.

## Desirability inputs (what a building "cares about" nearby)

- **Landscape / elevation proximity** — scenic hill, water, etc. (simple verticality / height-tiers feed this).
- **Amenities & markets** nearby (services as proximity-met needs/wants — see below).
- **Decoration** — the free-build cozy layer; place to beautify *and* boost nearby desirability (the Town-to-City mechanic).
- **Adjacency** — good/bad neighbours (Anno-style adjacency bonuses/penalties).
- **Mani utilities present** — warmth/water/air/etc. supplied.

## Household granularity (LOCKED)

- **A house = a family/household** (T2C cozy), NOT 1,000s of independently-simulated individuals.
- **Plan-ahead-for-families:** leave room / empty houses per population category so arriving families have somewhere to settle — a core planning joy the player explicitly called out.
- Keeps settlements **town-scale** (the intimacy half of "intimate towns, grand network").

## Services (LOCKED)

- Police / fire / health / etc. = **needs/wants met by proximity**, folded into desirability — **NOT** a crime/fire/disease incident sim.
- **Radius check for now**; **road-distance (Anno-style) = post-prototype revisit.**
- **Mix:** essential services = **needs** (placement-puzzle pressure); nice-to-have = **wants** (cozy "I added it because I wanted to").

## Build-model fit

- **Functional buildings on the grid** + **decoration free-build on top** (the cross-portfolio grid+free-decoration lock). Desirability is computed over the grid (radius / adjacency).

## Scope

- **DEEP** enough to be a real planning puzzle (it's the cozy soul) — but **bounded** by: household granularity (not cim-sim), radius (not road-distance yet), town-scale settlements. Exact inputs/weights/numbers = build-time.

> Related: `04` (identity + map), `05` (needs/wants, money), `08` (depth tiers).
