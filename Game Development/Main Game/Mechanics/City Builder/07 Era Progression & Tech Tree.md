# City Builder — Era Progression & Tech Tree (Phase 4)

> The meta-axis everything advances along. Not a bolt-on — population tiers, biome unlocks, logistics tiers, and goods complexity all move together on one staircase, with a Town-to-City-style research tree on top, culminating in the Akash Synthesis. Locked 2026-06-07; era names + numbers are placeholders.

---

## 4.1 The model — eras = Mani-mastery waves (LOCKED)

**One unified advancing axis.** Each era = mastering a new element/biome, which simultaneously gates the next population tier, the next logistics tier, and the next goods-complexity. They interlock as a staircase:

| Era | Unlocks | Population | Goods | Logistics |
|---|---|---|---|---|
| **1 · Bhu Age** (Earthworking) | Bhu home only | Settlers | 1-element | grid-roads |
| **2 · Tidal-Forge Age** (Jal + Agni) | first satellite biomes | Citizens | 2-element | boats (intra-map) |
| **3 · Skyward Age** (Vayu) | air mastery / Avian | Artisans | 3-element | Vayu-freight (inter-map) |
| **4 · Akashic Age** | the **Great Synthesis** | — | all-4 Akash | portals → **endgame** |

*(Era names are placeholders — easy to reskin.)*

## 4.2 The biome-gating staircase (LOCKED) — resolves the chicken-and-egg

**Each era unlocks access to the *next* biome**, sequencing expansion and resolving the loop (you need element N+1 to reach tier N+1, and the era gate hands it to you on schedule):

> Max out **Settlers** in the Bhu home → unlock **seafaring** → expand to **Jal/Agni** → 2-element goods → **Citizens** → unlock the 3rd biome → **Artisans** → **Vayu** → all-4 → **Akash Synthesis = endgame.**

Progression is a clean staircase, never a free-for-all. **Expansion is paced by the eras** (you can't sail to a biome before its gate opens).

## 4.3 The tech tree (LOCKED — Town-to-City model)

**Research labs → Knowledge points → unlock buildings + decorations + building-expansion tiers (§2.5) + Mani-tech recipes + refining/logistics upgrades + QoL**, culminating in the **Akash Synthesis** (the tree's endpoint). T2C flavor (research drives both functional buildings *and* the cozy decoration/Wants layer). Bounded — not an Anno-sized sprawl.

- **Research source:** **Academy / research-lab buildings**, staffed by population (T2C-style); optionally fed a little refined Mani to tie research into the economy *(exact input = minor open detail; lean population-staffed primary).*

## 4.4 Research mechanism — SINGLE Knowledge currency, element-branched tree (LOCKED — option #2)

**One "Knowledge" currency**, but the tech tree is **branched by element** (Bhu / Jal / Agni / Vayu branches + compound + Akash). A **branch opens when you have access to that element's biome** (which the era staircase provides on schedule). **The Akash endpoint requires all four branches developed** → the all-4 theme falls out for free.

- **Why #2 (not per-Mani / not flat):** gives the per-element *structure, feel, and allocation choice* ("which branch do I pour Knowledge into?") + Akash-needs-all-4 — with **one currency**, avoiding redundant gating (biome-unlocks + multi-element-goods + the era staircase already gate by element-mastery) and 4 research economies to balance.
- **⏫ Per-Mani research points (4 currencies) = a CLEAN ADDITIVE UPGRADE, deferred to playtest.** If research feels too flat/undifferentiated, split the one Knowledge currency into four (per-element labs → per-element points → per-branch gating). Nothing is lost by starting at #2.

## 4.5 Era gates (LOCKED logic)

- Each era gated by **previous population-tier completion + element mastery** (the staircase). Big jumps may want a small **milestone build/research** (e.g. seafaring to reach the first satellites; airship-docks for the Skyward Age).
- **Akashic Age** gated by **all-4 element mastery + the Great Synthesis project** (the endgame capstone, all-4-element — see `05 §2.1`).

---

> **Next:** Phase 5 — depth-allocation + the explicit "in / deliberately-out" bounding line (the scope-discipline pass), then the remaining mechanics detail. *(Tower-defense reserved for the dream game; environmental Mani-weather deferred post-prototype.)*
