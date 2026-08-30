# Open-Pavilion Platform Bird Feeder + Camera Mount — Build Guide (v4)

Full 16 × 9" open feeding platform, two gable end walls carrying a high symmetric gable
roof, long sides open. Floor + roof cantilever past the camera-end gable into a sheltered
pocket; that gable has a centered vertical slot the camera mounts to and views through.

All parts **1/2" stock**. Pure cut geometry (no text, no score layer). Kerf 0.008" baked as
joint clearance — test-fit on scrap first.

## Changed from v3
- **Taller:** eave raised 6" -> 8", so the open bird gap is 8" (peak now 10.5"; overall
  height ~11.5–12" with shingles, before any mount post).
- **Bigger landing lip:** floor widened 9" -> 11", the extra 2" all on **one long side**.
  That side's landing lip is now ~2.5" (the other side stays ~0.5"). Fences unchanged — the
  feeding zone between them is the same; only the outboard landing surface grew.
- **Now three sheets:** the taller gables (11") and the 11"-wide floor no longer co-nest on
  a 20" bed. Each sheet still fits 28×20; re-nest in LightBurn if you want to save stock.

---

## Sheet 1 — `sheet1_floor_0_5in.svg` (1/2")
| Part | Qty | Nominal (in) | Notes |
|---|---|---|---|
| Floor | 1 | 20.5 × 11 | 16×9 feeding zone + 3.5" camera shelf + 2" extra landing lip on one long side. Drainage grid, gable + fence mortises, 1" cable hole |
| Ridge beam | 1 | 16.5 × 1 | Drops into both gable peak notches — the anti-racking tie |
| Camera-end drip lip | 1 | 10.5 × 1.5 | Optional roof drip/visor over the camera pocket |

## Sheet 2 — `sheet2_gables_fences_0_5in.svg` (1/2")
| Part | Qty | Nominal (in) | Notes |
|---|---|---|---|
| Gable — far | 1 | 9 × 10.5 | Pentagon, 8" walls to eave, 3 floor tabs, ridge notch. No slot |
| Gable — camera | 1 | 9 × 10.5 | Same, plus 2×5" centered vertical slot (bottom 1.5" above floor) |
| Long seed fence | 2 | 16 × 0.75 | Tab into floor 3/4" in from each long edge |

## Sheet 3 — `sheet3_roof_0_5in.svg` (1/2")
| Part | Qty | Nominal (in) | Notes |
|---|---|---|---|
| Roof panel | 2 | 21 × 6 | Plain. Glue/pin to gable slopes + ridge. Offset toward the camera end to cover the shelf |

---

## Notes on the big landing lip
- The wide lip is the floor outboard of the long fence on that side. About 3/4" of it sits
  under the eave overhang; the remaining ~1.75" is an **open landing board** — flat, in the
  clear, good for species that won't drop straight onto a perch.
- If you'd rather have the whole lip roofed, the lip-side roof panel can be widened (e.g.,
  6" -> 8") so it overhangs further — say the word and I'll change that one panel.

## Camera mount
- Camera lives on the shelf behind the camera-end gable, under the extended roof, viewing
  through the 2×5" slot. Bolt its bracket through the slot; slide to set height/aim. Route
  the cable through the 1" hole in the shelf. Slot bottom is 1.5" above the floor for seed
  retention. A 2" slot clips a wide dome's FOV — say the word to widen it.

## Roof-to-gable joint
The gable's two sloped top edges are the rafters. Each flat panel lays across both gables'
slopes (one per side), glued + pinned to the 1/2" edge, butting the ridge beam at the top
and overhanging the eave at the bottom. Optional rafter cleats (1/2×1/2×16" strips glued
along each slope) widen the glue surface and back the mid-span — recommended for outdoors.

## Assembly order
1. Dry-fit both gables and both long fences into the floor mortises; check square.
2. Glue the gables in, then the long fences.
3. Drop the ridge beam into both peak notches; glue (braces the open sides).
4. Glue the roof panels to the slopes + ridge, offset to cover the camera shelf; pin.
5. Shingle eave-up; cap the ridge. Add the drip lip if wanted.
6. Bolt the camera to the slot, set height, route the cable.

## Kerf / fit
Joints carry a baked 0.008" clearance; tune with LightBurn per-line Kerf Offset on the
floor mortises rather than regenerating.
