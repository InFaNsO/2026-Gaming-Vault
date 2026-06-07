# Automation — Core Mechanics & Loop

> The mechanical skeleton: the **two automation surfaces**, the **core loop**, and the resolved supporting decisions. **Locked 2026-06-08** (exact operations/belts deferred to pre-prototyping). Spell-design detail lives in `06`; market/competitor in `07`.

---

## The two surfaces (the load-bearing structure)

The game has **two distinct automation surfaces**. Keeping them separate is what avoids The Good Company's hated worker/machine tangle — and they're coupled by a **shared part vocabulary**, so it's one material economy, not two games.

### Surface A — Spell Design ("Conjuration Engineering") — *deep, signature*
You build a **modular process on the gem grid** that **produces and launches a 3D elemental construct**. The form comes from **shapers (process-operations), never hand-placement**. Full detail in `06`. *This is the #1 gray-box.*

### Surface B — Workshop Production — *the "regular automation" layer*
A familiar belt/machine (or staffed) line that **manufactures the parts + gear** that Surface A consumes. **Its throughput = how much you can put on the market** — it's the production bottleneck and the main scaling lever.

**The coupling:** Surface A *arranges* parts; Surface B *manufactures* them. A fancier spell (more / rarer parts) costs more production → lower throughput unless you scale B. One economy, two views.

**Scope leash for B:** a **curated, bounded part catalog** (~15–25 part types, not Factorio's hundreds) and **shallow-but-real chains**. Side benefit: A handles **continuous particle flow**, B handles **discrete item belts** — mechanically distinct, so they never blur. B is the comfort-familiar layer; A is the exotic signature.

> **OPEN — Surface B is human-based or machine-based?** *Recommendation:* **machine-based** (belts/throughput → DSP-scale, clean optimization, couples to A's discrete parts, no agent-sim cost, matches the "regular automation" intent) **+ a thin "artisan" meta-layer** (a few named researchers/artisans for tech unlocks & passive bonuses — character without a second production system). Pending the user's explicit confirm.

## The core loop

1. **Design** a spell — Conjuration Engineering on the gem grid (Surface A). *Produces a blueprint.*
2. **House** it — pick the **gear** (gauntlet / wand / sword / armor); the gear adds delivery method, durability, and **gem slots** (= multi-element capacity, see `06`).
3. **Produce** — set the workshop (Surface B) to mass-produce the blueprint's parts + gear. **Throughput caps your market output.**
4. **Sell** — put products on the **competitive market** (`07`): demand varies by element / behavior / gear; **rival workshops** supply the same market → supply & demand → prices move.
5. **Special requests** — periodic head-to-head **bake-offs**; best submission wins big, weak ones eat losses (you go directly against the rival AI on a fixed spec).
6. **Grow** — money → expand the workshop (stations, staff, **bigger/purer gems, better gear**) + climb the **tech tree** (new operations, elements, multi-Mani recipes, gear types). Growth (and market demand) pulls you toward **multi-Mani** spells for maximum power.

## Resolved supporting decisions

- **Make-or-buy → procure refined gems.** Gems are **bought pre-refined**, graded by **element / size / purity** (size = node count, purity = particle rate/quality). They are the **substrate** you build on, slotted into the gear. **No in-house refining in the spell loop** — Surface A is *design*, not material prep. Surface B makes **parts + gear**, not gems.
- **Three procurement inputs:** refined **gems** (substrate, by element/size/purity) · **raw materials** (feed Surface B to make parts + gear) · plus the **tech** you've unlocked (capability).
- **Scope principle (locked by the user):** *this* game is the **deep, fully-featured, micro-managed reference implementation** of Mani spell-engineering. The **dream game decides later how much to abstract** — this one does not pre-abstract.
- **Combat reuse:** the spells designed here **share the combat pillar's spell-data model** — they are literally the spells cast in combat (fire lance = projectile, earth fist = melee slam, ice wall = barrier). The automation game's *output* is the combat game's *input*.

## Deferred to pre-prototyping

The exact **operation set, machines, and belt system** are deferred until the **particle-system exploration** (see `06` — the tech is validated; the precise vocabulary is not yet fixed). The first build milestone is the **Conjuration Engineering gray-box**, not the shop economy.
