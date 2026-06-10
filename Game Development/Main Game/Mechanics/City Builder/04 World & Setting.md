# City Builder — World & Setting

> The fiction for the standalone Anno-lite Mani-world city game (build-ladder Game 5). A **fresh Mani-world locale** — same world as the Looter Shooter & dream game, a different era, **no plot connection** (callbacks only). Theme locked by user 2026-06-07; some specifics flagged PROPOSED pending design.

---

## Core fantasy (LOCKED)

A **Mani-using civilization where Mani is everyday infrastructure** — not just a weapon/spell substance, but the thing that **makes daily life easier, the way electricity did for us.** You administer and grow this civilization's settlements. Cozy magitech with real systemic depth.

**Tone (LOCKED, revised 2026-06-07 — TD removed):** **cozy magitech** — a beautiful, optimistic infrastructure builder, **no combat / no tower-defense** in the prototype. Tension comes from **economic & logistics mastery** (Anno-style: keep a multi-biome, multi-species portfolio balanced), not an external threat. Cozy, but with real systemic depth. Not Factorio-brutal, not zen-empty.

## Design identity — "intimate towns, grand network" (LOCKED 2026-06-07)

The center of gravity = **Town-to-City's cozy soul + Anno's production/logistics brain**, unified by Mani-as-infrastructure.
- **Intimate at the town level:** small, hand-planned, **town-scale** settlements (not metropolises). **Household granularity** (a house = a family). The joy is the **planning puzzle** — desirability from what a building sits near, leaving room for arriving families (see `09 Town Planning & Desirability`).
- **Grand at the network level:** scale/grandeur comes from the **multi-town network** (Anno production chains + multi-island/multi-map logistics *between* towns), NOT from individual-city size.
- **Zoom in** to lovingly plan a cozy town; **zoom out** to run the production empire.
- **Optional growth:** a town is complete at a comfortable size; expansion is available, never forced (see `08`).

## Era / frame (PROPOSED — working frame)

A Mani civilization's **colonial / expansion age**: a prosperous heartland chartering frontier colonies into raw, untamed, Mani-rich lands. The player is a colony administrator. Loosely separate from the **Mani Accord** (the LS federation) — ancestral or far-region. A confident, Mani-rich society here can quietly foreshadow later-era hubris (the Breach) without any plot link.

## Society — multi-species (LOCKED, 4 species 2026-06-07)

All four species coexist and thrive (the LS only shows them ruined/Husked; here they're alive — a warm callback). Species is a **mechanic**, not just flavor — each has distinct **needs**, a preferred **biome/element**, and a distinct **economic identity**:

| Species | Element | Preferred biome | Economic identity |
|---|---|---|---|
| **Human** | Bhu (earth) | Highlands (generalist) | Generalist anchor — construction, the Main City |
| **Amphibian** | Jal (water) | Wetlands | Water specialists |
| **Reptile** | Agni (fire) | Volcanic | Heat & high-heat-industry specialists |
| **Avian** | Vayu (air) | Sky-islands / plateau | **Air & logistics specialists** — run the wind-powered shipping/propulsion network |

→ Clean **4-element : 4-species** mapping. Bhu/Human = the generalist start anchor; each other species owns one element and a real economic role.

- **The Main City houses all four species** → it must satisfy all four needs-sets simultaneously (the hardest logistics problem).
- **Satellite / other colonies each focus on ONE species** → settled in that species' biome, specializing in its Mani + goods.
- **Avian = the 4th species (LOCKED "for now," 2026-06-07 — pivot if dev bloats).** Constraint to stay cheap: **humanoid bird-folk** (avian-*humanoid*), **shared one-rig** (+1 mesh + cosmetic wing accessory), **wings cosmetic, NO flight gameplay.** The expensive version (true avian rig + flight pathing) is forbidden.
  - **CANON RIPPLE (flag):** this promotes the world to **4 species** — the **dream game inherits this** (it reuses these species). Propagate to dream-game/LS species docs. Lore hook available: the Avians are a **"lost species,"** gone by the LS era (only 3 remain there) — a tragic callback, not a plot link.
- Reuses the locked **one-rig art discipline** (shared humanoid rig, per-species mesh).

## Map & colony structure (LOCKED 2026-06-07)

**Anno "sessions" model — each biome is its own MAP of multiple islands.** Biome-map set = **Bhu / Jal / Agni / Vayu** (Akash is the tech capstone, *not* a map — see above).

- **3-tier logistics ladder** (the Anno scaling the references love): (1) single island → (2) multi-island within a biome-map → (3) multi-map across biomes (inter-region shipping).
- **Unlocking a new biome-map advances three systems at once:** logistics scope + era progression + a new species/new Mani. One axis, triple payoff.
- **Each biome-map = ~2–4 islands (DSP model):** **1 big "home" island** = the biome's hand-planned cozy main town + **1–2 small islands** = lean **mining/extraction outposts** (minimal population — keeps cozy planning focused on the home towns). Expansion is **fractal**: grow big-island → outpost-islands *within* a map, the same way you grow biome → biome *across* maps.
- **The home towns (≈ 4 total):** **Bhu** big island = the **Main City** (all four species); the **Jal / Agni / Vayu** big islands = **single-species** cozy towns. The Main City can't self-supply → imports Mani + species goods → **mutual-dependency logistics web** (Anno engine).
- **Islands = procgen** (LOCKED). *(The procgen sophistication level + how it relates to the other games' procgen needs = deferred to a dedicated **cross-game procgen-planning discussion** — which will also inform dev-ordering across all games.)*
- **NO AI-controlled colonies** — every island/colony is player-managed (see Hard constraints).

## Build approach (LOCKED)

- The **full game features ALL designed biomes** (Bhu/Jal/Agni/Vayu + Akash capstone).
- **Prototyping starts with ONE biome (Bhu)** to gray-box the core loop, then scales up **additively** — same discipline as the combat gray-box. (There is no reduced-biome "v1"; there is the full design + a 1-biome first-playable.)

## Mani as civic infrastructure (PROPOSED — working model)

Each element keeps its **locked elemental nature** (the same nature behind its combat flavor), repurposed for daily life. **Mani is NOT an element-agnostic power grid** — each element does *specific jobs*, so a working city needs a **portfolio** of all of them, and each comes from a different biome. That portfolio-need is the engine of expansion + logistics.

- **Bhu (Earth)** — construction (grows building material from raw earth), soil fertility for farms, terraforming, roads. *The universal/starting material.*
- **Jal (Water)** — running water/taps (no plumbing network), sanitation, irrigation, refrigeration/cold-storage.
- **Agni (Fire)** — heating (stoves/hearths; cold biomes uninhabitable without it), cooking, high-heat industry (kilns/smelting/glass).
- **Vayu (Air)** — ventilation, pneumatic intra-city transport, **propulsion for the barges/ships that do inter-colony logistics**, cranes/lifting.
- **Akash (Ether)** — **the tech-tree capstone (LOCKED 2026-06-07): space-time manipulation, "potentially limitless."** NOT a biome-map you settle — **synthesized, not harvested**, *achieved* by mastering the other four elemental economies (the era-cap gate). Mechanics: **space-folding → instant inter-map transfer / portals between colonies** (the logistics endgame — conquering distance), and **time-bending → production acceleration / stasis (no decay)**. Fits locked LS lore (*Akash is produced at endgame, "learned not mixed," never just found*). **Callback:** Akash space-time portals = interdimensional gates = the Breach-echo — the city game's triumphant "limitless" capstone is the same phenomenon that becomes catastrophe in the LS era. Limitless **but dangerous** = the quiet Breach foreshadow.

## Tension & threat (LOCKED, revised 2026-06-07 — TD REMOVED)

**No tower-defense, no combat threat in the city game.** Tension comes purely from **economic & logistics mastery** (Anno model): keeping a multi-biome, multi-species production/logistics portfolio balanced so no colony starves, while climbing the tier ladder and affording the Akash Synthesis. The logistics web + the multi-element-goods-force-trade hook generate the stakes on their own.

- **Tower-defense is RESERVED for the dream game** (built directly there — the separate Dungeon/Roguelike integration game was removed 2026-06-10), where its real context lives (dungeon-break clock + clear-vs-defend). Rationale: the threat kept failing the enthusiasm test against the cozy identity; and only *actual* TD forward-maps to the dream game's TD, so once it leaves, the city game's tension is chosen for "best cozy game."
- **Environmental Mani-weather** (heat-waves / floods / surges as resilience flavor) = **DEFERRED — revisit AFTER the prototype** (user, 2026-06-07). Not in the prototype.
- **No wild-Mani-construct enemies** (they existed only to feed TD — removed with it).

## Build model — grid + free decoration (LOCKED 2026-06-07, **CROSS-PORTFOLIO**)

**Grid is the universal substrate; decorations are free-build.** Decided after researching player/designer discourse (free-build is divisive, not an improvement — loved for cozy aesthetics, but actively breaks logistics/automation: gridless pathfinding choke-points, alignment chores, automation communities openly asking for grids).

- **Functional buildings = GRID.** Clean adjacency, logistics, and pathfinding. The grid is the **universal substrate across the whole portfolio** — city + combat (already locked grid) + automation (factory-inside-gem) + dungeons + **procgen** (discrete tiles = cheap procgen). **Solo-dev win:** ONE placement system, ONE pathfinding, ONE procgen tile-system, reused across all five games (pure additive carry-forward).
- **Decorations = FREE-BUILD.** The Town-to-City *wants*/happiness layer places semi-freely *on top of* the functional grid (or on a fine sub-grid). Cozy expression where it matters, grid discipline where the simulation needs it.
- **Cozy feel comes from presentation, not gridlessness** — an **organic/irregular grid look + smart auto-adapting tiles + satisfying placement feedback** (the Townscaper model: Townscaper is itself a grid). You don't trade coziness for logistics.

> **PROPAGATE (cross-portfolio):** this is a portfolio-level lock — the **automation game, dungeon, and procgen thread all inherit "grid substrate + free decoration."** Fold into `07 Testbed Build Plan` / `06 List Of Game Mechanics` / CLAUDE.md at the next checkpoint. Combat is already grid, so this is consistent (no re-open).

## Hard constraints (LOCKED)

- **NO AI-controlled colonies** — friendly or hostile. All colonies are **player-managed directly** (Anno multi-island style, all player-owned). No rival civs, no diplomacy, no AI allies. There is **no combat opponent at all** in the prototype — the only "opponent" is your own economy/logistics (Anno-style).

---

## Systems in scope (LOCKED list — 4 systems; revised 2026-06-07, TD removed)

1. **Production-chain management** (Mani refining + goods)
2. **Logistics management** (intra- and inter-colony)
3. **Multi city / island colonies** (Main City + single-species satellites)
4. **Era progression**

*(Tower defense — formerly #4 — is **reserved for the dream game**. Environmental Mani-weather threat = **deferred**, revisit post-prototype.)*

> Depth allocation + per-system scoping → `05 Systems & Scope.md` (in progress).
