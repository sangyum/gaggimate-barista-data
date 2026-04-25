# James Coffee Co — Guatemala "Huehuetenango"

## Bean Profile

| Field | Value |
|-------|-------|
| **Roaster** | James Coffee Co (San Diego, CA) |
| **Origin** | Guatemala — Huehuetenango region (Western Guatemala, near Mexico border) |
| **Producers** | Civil Comercializadora Maya Alternativa (COMAL) + Unión Pequeños Productores (UPC) — youth producer cooperatives |
| **Process** | Washed |
| **Roast Level** | Medium-Dark |
| **Variety** | Mixed Arabica — Caturra, Pache, Bourbon, Catuai, Catimor |
| **Altitude** | Not disclosed (Huehuetenango growing region typically 1500-2000m) |
| **Tasting Notes** | Chocolate, Tart Cherry, Juicy |
| **Sourcing** | Coffee Kids partnership — supports youth coffee producers (COMAL: 35 young producers, UPC: 15 young producers) |
| **Roast Date** | ~2026-04-11 to 04-25 (estimated from enjoy-by 2026-06-06, 6-8 week window) |
| **Purchased** | 2026-04-21 (12oz bag) |

## What to Expect

A classic washed Guatemalan from the Huehuetenango highlands at medium-dark roast — expect chocolate-forward structure with a tart cherry top note that keeps the cup lively. The mixed-variety blend is characteristic of smallholder cooperative lots, producing cup complexity from varietal diversity rather than single-varietal purity.

- **Origin character:** Huehuetenango is Guatemala's most prized growing region — mountain microclimates produce high-density beans with bright acidity and layered sweetness. Tart cherry is a hallmark Huehue note; chocolate base comes from the medium-dark roast.
- **Variety (mixed Arabica):** Caturra and Bourbon contribute sweetness and balance; Pache adds body; Catuai and Catimor broaden flavor and disease-resistance. No single variety dominates, which tends toward a balanced, approachable cup rather than a distinctive varietal signature.
- **Processing (washed):** Clean, articulate cup. Acidity and origin character show through without fermentation muddle. Matches user's "clean, not soupy" preference.
- **Roast level (medium-dark):** Emphasizes chocolate body over origin acidity, but the tart cherry note suggests the roast stops short of muting brightness entirely. Lever-decline profile extracts sweetness without pushing into bitterness.

## Profiles

| Profile | Style | Temp | Pressure | Ratio | File |
|---------|-------|------|----------|-------|------|
| James Huehuetenango [AI] | Lever decline (fill → bloom → ramp → linear decline) | 91°C | 8.5 bar peak → 5.5 bar decline over 30s | 1:2 (18g → 36g) | [huehuetenango.json](huehuetenango.json) |

## Tasting Notes

| # | Date | Shot | Grind | In/Out | Ratio | Profile | Balance | Stars | Observations |
|---|------|------|-------|--------|-------|---------|---------|-------|--------------|
| 1 | Apr 21 | 000063 | DF64 9.2 | 18/37.8g | 1:2.1 | James Huehuetenango [AI] | Balanced | ★★★★ | Sweet, no bitterness or sourness. First pull landed clean. |
| 2 | Apr 22 | 000065 | DF64 9.2 | 18.1/37.4g | 1:2.07 | James Huehuetenango [AI] | Balanced | ★★★★ | Clean Americano, slightly bland. 15-min warm-up. Slow extraction (49.6s) — puck likely tighter. |
| 3 | Apr 22 | 000066 | DF64 9.5 | 18/38.3g | 1:2.13 | James Huehuetenango [AI] | Balanced | ★★★★★ | Dialed in. Clear, sweet, stronger flavor than #65. Coarser grind brought back top notes. |
| 4 | Apr 22 | 000067 | DF64 9.5 | 18/38g | 1:2.11 | James Huehuetenango [AI] | Balanced | ★★★★ | Used for latte experiment — milk overshadowed shot taste. Shot extraction normal; same settings as #66. |
| 5 | Apr 23 | 000068 | DF64 9.5 | 18/38.6g | 1:2.14 | James Huehuetenango [AI] | Bitter | ★★★ | Bland, less body. Same recipe as #66/#67 but 56.6s total (vs 45s). Severe choke — peak resistance 25.4, no flow for first 13s of brew. Likely puck prep issue. |
| 6 | Apr 23 | 000071 | DF64 9.5 | 18/38.6g | 1:2.14 | James Huehuetenango [AI] | Balanced | ★★★★★ | Latte with 3-leaf tulip. Milk-forward, coffee present. RDT (wet teaspoon) + deeper WDT — puck prep sorted. |
| 7 | Apr 24 | 000075 | DF64 9.5 | 18/38g | 1:2.11 | James Huehuetenango [AI] | Balanced | ★★★★★ | Latte with symmetric tulip. Balanced but mild/bland in cup — milk likely flattening flavor. Consider +1°C or 1:1.7 for more intensity under milk. |

### Starting parameters (baseline)
- **Grind:** DF64 9.2 (roughly 1 micro step coarser than Mostra Philippines Heritage baseline of 9, biased for freshness)
- **Dose:** 18g → 36g (1:2)
- **Temperature:** 91°C
- **Profile:** James Huehuetenango [AI] — same lever-decline archetype that earned 5★ on Mostra Philippines Heritage

### Notes on the profile

- Cloned from Mostra Philippines Heritage lever-decline (5★ proven on same roast+process class)
- Pre-infusion: 8s total (4s fill + 4s bloom) — wetted-puck ramp, not a full bloom
- Main extraction: 6s ramp to 8.5 bar, then linear decline to 5.5 bar over 30s
- Volumetric stop at 36g (scale-triggered via BLE)
- Temperature 91°C targets medium-dark midpoint (90-92°C range)

### First-shot watch points

- **Fast/sour** → DF64 9.0 (1 micro finer)
- **Slow/bitter** → DF64 9.4 (1 micro coarser)
- **Muted/gassy/bubbly crema** → rest the bag 3-5 more days, don't blame the grind
- **Balanced but want more tart cherry brightness** → bump temp to 92°C
- **Good for straight espresso but muddy in Americano** → try 1:1.7 (18g → 31g) for more intensity in the cup before dilution
