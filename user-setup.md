# User Setup

## Equipment

| Component | Details |
|-----------|---------|
| **Machine** | Gaggia Classic Pro + Gaggimate Standard |
| **Shower Assembly** | Brass shower holder + [IMS precision shower screen](https://www.amazon.com/dp/B0D48R2T6P) (silicone gasket, stainless steel screws) |
| **Grinder** | Turin DF64 Gen 2 Single Dose Coffee Grinder |
| **Basket** | IMS Baristapro Nanotech 18g (ridgeless) |
| **Scale** | [Smart Kitchen Scales - Aliexpress (Bluetooth)](https://www.aliexpress.us/item/3256810573003222.html), auto-stop enabled, 500ms brew predictive delay (Auto Adjust OFF, Grind delay 1000ms) |

## Workflow

- **Puck Prep**: WDT → OCD leveler → tamp
- **Shot Stop**: Automatic via Bluetooth scale

## Preferences

- **Primary Drinks**: Americanos (1:5 ratio, double shot, boiling kettle water from Fellow Stagg EKG at 205°F added to shot)
- **Latte**: Lactose intolerant — not a regular drinker, but practicing latte art with oat, almond, and low-fat milk. Microfoam is the current struggle (Gaggia Classic Pro's single-hole steam tip is underpowered).
- **Preferred Alt-Milk**: Califia Farms Barista Blend Oat Milk ([Amazon](https://www.amazon.com/dp/B07PBFNYXV)) — arrives 2026-04-30. Steam ceiling 60-65°C (lower than dairy's 65-70°C). Pour milk into espresso to soften pH transition.
- **Other Brewing**: Blue Bottle pour-over kit for filter coffee (2-3 cups a day after the morning Americano)
- **Daily Rhythm**: First Americano around 6:30 AM, then 1-2 more cups of Americano or pour-over through the day
- **Taste Profile**: Prefers clean, articulate flavor — lighter texture over heavy/syrupy body. Mild acidity welcome; sweetness-forward shots preferred. Medium to medium-dark roasts are the sweet spot.
- **Approach**: Variety-seeker. Enjoy trying diverse origins, processes, and roast levels.
- **Extraction Philosophy**: Tailor the profile per coffee to maximize that bean's unique taste profile — no fixed house style.
- **Comfort-Zone Flavors**: Chocolate, caramel, nutty (the safe defaults for daily drinkers), but open to fruit-forward, floral, or experimental lots.

## Experience & Dialing Habits

- **Experience**: ~5 years pulling espresso (since early 2020, pandemic start) on the Gaggia Classic Pro
- **Dialing Patience**: Willing to burn 2-3 shots on a new bag to dial in
- **Recent Satisfaction**: Very happy since adding the Gaggimate. Mostra and Lofty Coffee have both been consistent wins — no bad experiences recently.

## Active Coffee

- **Coffee**: James Coffee Co — Colombia Washed Finca Palmichal
- **Directory**: `coffees/james-coffee-colombia-finca-palmichal/`
- **Roast Date**: TBD — check bag (purchased 2026-04-21 alongside the Guatemala)

## Bluetooth Scale & Auto-Stop

Smart Kitchen Scales - Aliexpress connects to the Gaggimate via Bluetooth Low Energy (BLE) for automatic shot stopping.

**Scale specs:** 2000g capacity, 0.1g resolution, medium response time. Modes: Weight, Tare.

**How predictive stop works:**
- The scale monitors real-time weight and flow rate during extraction
- When the flow rate and current weight indicate the target will be reached, the scale sends a BLE stop signal to the Gaggimate
- The **250ms predictive delay** is the time between the Gaggimate receiving the stop signal and the pump actually stopping — accounting for water already in transit through the puck and in the spout

**Calibration:**
- If shots consistently **overshoot** the target weight by >1g → increase the delay (e.g., 300ms) so the stop signal fires earlier
- If shots consistently **undershoot** the target weight → decrease the delay (e.g., 200ms) so the stop signal fires later
- Typical adjustment range: 100-300ms. Start at 250ms and adjust in 50ms increments based on results

**Troubleshooting:**
- **0g reads / very low dose out:** Cup was likely removed before the scale registered final weight
- **Connection drops:** Move scale closer to machine; avoid metal objects between scale and Gaggimate
- **Scale not found:** Ensure scale is awake and not connected to another app. Only one BLE connection at a time

## Notes

- **Dose = basket size.** With an 18g basket, dose 18g. Don't underdose.
- Medium roasts work well at 92-94°C — taste and adjust from there
- DF64 Gen 2 is stepless — make fine adjustments in ~0.1–0.2 notch increments for dialing, full notches for coarse moves
- Gaggimate Standard enables pressure profiling — great for pre-infusion and gentle ramp profiles
- Brass shower holder adds thermal mass at the puck, improving temperature stability shot-to-shot — trust profile temp targets more
- IMS precision shower screen distributes water evenly across the puck face — reduces channeling risk, making extraction more forgiving of minor puck prep variation
