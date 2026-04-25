# James Coffee Co — Colombia Washed Finca Palmichal

## Bean Profile

| Field | Value |
|-------|-------|
| **Roaster** | James Coffee Co (San Diego, CA) |
| **Origin** | Colombia — La Coqueta, Genova, Quindío (Central Andes, western side) |
| **Producer** | Atilano Giraldo (3rd-generation coffee farmer, Finca Palmichal) |
| **Process** | Washed — pulped, soaked 10-12 hours, washed, mechanically dried |
| **Roast Level** | Medium (per roaster) |
| **Variety** | Castillo |
| **Altitude** | ~1,560 m |
| **Tasting Notes** | Baker's chocolate, Red berry (silky body, bright winey acidity) |
| **Purchased** | 2026-04-21 (12oz bag, alongside the Guatemala Huehuetenango) |
| **Roast Date** | TBD — check bag |

## What to Expect

A classic washed Colombian from a third-generation smallholder in Quindío, roasted medium by James Coffee. Expect baker's chocolate as the base note with a bright, winey red berry top and silky body — the "approachable but interesting" end of the washed Colombia spectrum.

- **Origin character:** Quindío sits in Colombia's central coffee axis (Eje Cafetero). Coffees from this region are typically balanced — sweet, chocolatey, with moderate acidity. Red berry (strawberry, red currant) is a hallmark note when a washed Quindío is roasted light-to-medium.
- **Variety (Castillo):** Colombia's flagship disease-resistant hybrid (Caturra × Timor). More soluble and forgiving in extraction than heirloom varieties like Bourbon or Geisha. Tends to brew evenly, tolerates minor puck-prep variance. Flavor-wise: balanced, approachable, not flashy — a "good daily driver" variety.
- **Processing (washed):** Clean, articulate cup with no fermentation muddle. Matches the user's "clean, not soupy" preference. Acidity shows through without being masked.
- **Altitude (~1,560 m):** Moderate density — not a high-grown Huehue-style bean. Grinds slightly more easily and extracts more freely than 1,800m+ coffees. Supports standard medium-washed temp (93°C) without needing a push to the upper range.

**Comparison to the active Guatemala:** Both washed, both James Coffee. The Guatemala is medium-**dark** with tart cherry; this Colombia is **medium** with red berry — one roast level lighter, one degree brighter. Expect this cup to be livelier, less chocolate-forward, more acidic. If you want chocolate dominance, drop to 91-92°C; if you want berry/brightness to show, stay at 93°C or bump to 94°C.

## Profiles

| Profile | Style | Temp | Pressure | Ratio | File |
|---------|-------|------|----------|-------|------|
| James Colombia Bloom [AI] | True bloom (fill → 10s pump-off bloom → ramp → peak → decline) | 94°C | 9 bar peak → 6 bar decline over 30s | 1:2.1 (18g → 38g) | [colombia-bloom.json](colombia-bloom.json) |

## Tasting Notes

| # | Date | Shot | Grind | In/Out | Ratio | Profile | Balance | Stars | Observations |
|---|------|------|-------|--------|-------|---------|---------|-------|--------------|
| 1 | Apr 25 | 76 | DF64 9.5 | 18/40.6g | 1:2.26 | Bloom [AI] | Balanced | 4 | Fuller body, stronger/darker than Huehue; less berry lift than expected |
| 2 | Apr 25 | 77 | DF64 9.5 | 18/40.4g | 1:2.24 | Bloom [AI] @ 94°C | Balanced | 5 | Fuller body, stronger flavor — +1°C unlocked depth |

### Starting parameters (baseline)
- **Grind:** DF64 9.5 (same as Huehue — one roast-level delta is offset by Castillo's higher solubility vs. Huehue's mixed-variety blend)
- **Dose:** 18g → 38g (1:2.1)
- **Temperature:** 93°C (medium washed, upper-middle of range to lift red berry note)
- **Profile:** James Colombia Bloom [AI] — true-bloom adventurous profile for sweetness + berry expression

### Notes on the profile

- **Fill (5s, flow 2 ml/s)** — gentle wetting. Slower than Huehue's 4 ml/s fill to avoid unseating grounds before bloom; the Castillo puck is softer than the mixed Huehue varietals.
- **Bloom (10s, pressure 0 / pump fully off)** — the "adventurous" move. CO2 off-gasses, water penetrates, extraction begins at zero flow. Longer than the Huehue wetted-puck ramp. This is a *true* bloom: the difference is whether the pump is on at low flow (wetted puck) or fully off (true bloom). Pump-off extracts more evenly but is more sensitive to puck prep — hence the watchpoint below.
- **Ramp (4s, linear to 9 bar)** — eases into extraction instead of jumping, reducing channeling risk right out of the bloom.
- **Peak (6s at 9 bar)** — establishes flow at matrix pressure (medium washed = 9 bar).
- **Decline (linear 9 → 6 bar over 30s, volumetric stop at 38g)** — compensates for puck erosion, lands on a cleaner finish. Gentler decline floor than the Huehue (6 bar vs. 5.5 bar) because the shorter 6s peak gives less total extraction time at peak before decline starts.

### First-shot watch points

- **Fast/sour** → DF64 9.3 (1 micro finer). The bloom makes sourness less likely, but if it happens, grind is still the first lever.
- **Slow/bitter** → DF64 9.7 (1 micro coarser). Medium roast + bloom can over-extract if the grind is too tight.
- **Gushing during bloom (water flooding the cup with pump off)** → grind 2 micro steps finer, or shorten bloom to 7s. Some puck resistance is needed to hold bloom water in the basket.
- **Chocolate dominates, no berry** → temp up to 94°C.
- **Too bright / acidic for the Americano dilution** → shorter ratio (1:1.9, 18g → 34g) OR drop temp to 92°C before adjusting grind.
- **Good straight espresso but muted under milk** → you already know this pattern from the Huehue: consider 1:1.7 for milk drinks.

### Differences vs. the Guatemala Huehuetenango profile

| Element | Huehue | Colombia |
|---------|--------|----------|
| Temperature | 91°C | **93°C** (+2°C for berry lift) |
| Bloom style | Wetted puck (4 ml/s + 1.5 ml/s) | **True bloom** (pump fully off) |
| Bloom length | 8s total | **10s** |
| Peak pressure | 8.5 bar | **9 bar** (per matrix for medium washed) |
| Decline floor | 5.5 bar | **6 bar** (gentler, shorter ramp to peak) |
| Peak hold | None (ramp → straight into decline) | **6s peak hold** |
| Ratio target | 36g | **38g** |
