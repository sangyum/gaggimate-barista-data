# Mostra Coffee — Philippines Heritage Microlot

## Bean Profile

| Field | Value |
|-------|-------|
| **Roaster** | Mostra Coffee (San Diego, CA) |
| **Origin** | Philippines — Sitio Naguey community, Benguet region (milled at Sitio Belis) |
| **Process** | Washed — dry fermented 24h, then wet fermented 24h, dried 4-6 weeks |
| **Roast Level** | Medium-Dark |
| **Variety** | Not disclosed (rotating seasonal microlot) |
| **Altitude** | Not stated (Sitio Naguey is ~800m elevation delta from main mill) |
| **Tasting Notes** | Chocolate, Baking Spice, Nutty Finish |
| **Sourcing** | Direct Trade via Mostra + Kalsada partnership |
| **Roast Date** | Unknown (retroactive documentation) |

## What to Expect

A specialty washed microlot from a direct-trade partnership in the Benguet highlands — the roast and flavor target chocolate-spice comfort with the traceability and story of a microlot.

- **Origin character:** Philippine highland coffees tend toward earthy chocolate and cedar-spice notes with medium body. Sitio Naguey's elevation adds density and cup structure.
- **Processing (washed):** The 24-hour dry ferment + 24-hour wet ferment is longer than typical washed protocol, likely contributing to the "baking spice" descriptor — clean cup but with more depth than a standard 12-18h washed.
- **Roast level (medium-dark):** Emphasizes chocolate body over origin-specific acidity. Pairs well with declining-pressure profiles that extract sweetness without pushing into bitterness.
- **Seasonal rotation:** Bean varieties and specific lots change each harvest — expect broad flavor targets to hold, but specific nuances to shift.

## Profiles

| Profile | Style | Temp | Pressure | Ratio | File |
|---------|-------|------|----------|-------|------|
| Mostra - Philippines Heritage Microlot | Lever decline (short pre-infusion, ramp, long decline) | 91°C | 8.5 bar peak → 5.5 bar decline over 30s | 1:2 (18g → 36g) | [philippines-heritage.json](philippines-heritage.json) |

## Tasting Notes

5★ shot logged:

- **Shot #49** (2026-04-16) — 18g → 34.7g (1:1.93), DF64 9, 43.3s total, balanced

### Notes on the profile

- Profile `description` corrected to "DF64 @ 9 (0-90 dial)" — the original said 6 but that was stale; user had adjusted to 9 (5★ shot was at 9) without updating the device description. Repo JSON is now correct; device description to be updated manually via Gaggimate web UI.
- Pre-infusion is short (8s total: 4s fill + 4s bloom) — not a blooming profile, more a wetted-puck ramp.
- Declining pressure from 8.5 → 5.5 bar over ~30s mimics lever behavior and compensates for puck erosion late in the shot.
- Volumetric stop at 36g (scale-triggered) — actual final weights hover 34-35g due to scale artifact/predictive delay.
