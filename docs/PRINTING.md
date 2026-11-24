# Printing

All files are already turned the right way up for printing. **No part needs supports.** The pre-sliced Bambu Lab H3C profile on [MakerWorld](https://makerworld.com/en/@PrinterMcGee) turns on tree supports (auto, 30° threshold) with Bambu Support for ABS as the interface layer and uses 5 wall loops; the parts print without supports too. The number at the front of each file name is how many to print; each file holds one part.

Designed for a 0.4 mm nozzle; the overhang checks assume 0.2 mm layers.

## Unit (`parts/unit`)

All the rigid parts were printed in **Bambu Lab ABS-GF** (ABS with glass fibre). It needs an enclosed printer, and because it is glass-filled a hardened steel nozzle is the safe choice.

| File | Print | Size as printed (mm) | Notes |
|---|---|---|---|
| `1x_Tub_body.stl` | 1 | 230 × 110 × 115 | Right way up. Largest print. The only bridges are short ones over the socket slot and the nut slots. |
| `1x_Bottom_cover.stl` | 1 | 150 × 69 × 11 | Flat. |
| `1x_Flange_ring.stl` | 1 | 250 × 130 × 4 | Flat. |
| `1x_Top_cover.stl` | 1 | 250 × 130 × 35 | 10 to 15 % infill is plenty. |
| `1x_Clamp_plate.stl` | 1 | 242 × 153 × 11.5 | Flat. Only for worktop fitting. |
| `4x_Clamp_pad.stl` | 4 | 28 × 28 × 7 | Only for worktop fitting. Stick felt or foam on top. |
| `2x_Tower_cap.stl` | 2 | 42 × 42 × 57 | Upside down, use a brim. The cap and its sleeve are one part, with three spring leaves for the click. |
| `2x_Motor_sled.stl` | 2 | 31 × 31 × 40 | Upside down. Both sleds are the same part. |
| `2x_Switch_disc.stl` | 2 | 30 × 30 × 5 | As it sits. |

## Scraper head (`parts/scraper_head`)

ABS-GF, like the unit. A short drill: three solid blades, twisted so they lean 45° at the edge. The top of each blade has to lead as it turns, so the blades carry the grounds down out of the basket; turned the other way they would push them up into it. Print **one** of the two.

| File | When | Notes |
|---|---|---|
| `1x_Drill_head_short_IMS58_H24.stl` | Motor turns clockwise, seen from above | Upside down, use a brim. 58 × 54 × 38 mm. One face of each blade overhangs at up to 45°; no supports needed. |
| `1x_Drill_head_short_IMS58_H24_reverse.stl` | Motor turns anticlockwise, seen from above | Twisted the other way. Same printing. |

Swapping the two wires on a motor reverses it, which is the other way to match the drill head. See [`images/scraper_direction.png`](../images/scraper_direction.png).

## Brush head (`parts/brush_head`)

| File | Print | Material | Notes |
|---|---|---|---|
| `1x_Brush_stack_hub.stl` | 1 | ABS-GF | Spindle. Upside down (top of the spindle on the bed), use a brim. 22 × 22 × 38 mm. |
| `1x_Brush_star_rim_TPU.stl` | 1 | TPU | Flat, boss up. 82 mm across, so the tips wipe over the outer edge of the rim; a ridge along each arm presses on the rim. |
| `2x_Brush_star_wall_A_TPU.stl` | **2** | TPU | Flat, boss up. Easy to print only one by mistake: the stack needs both. |
| `1x_Brush_star_wall_B_TPU.stl` | 1 | TPU | Flat, boss up. |
| `2x_Brush_comb_TPU.stl` | 2 | TPU | Lying flat. 2.4 mm thick. |

The TPU parts were printed in 75A TPU. Every flexible part lies flat on the bed so its arms are made of strands running along their length; an earlier design with thin upright fingers tore apart between layers. A firmer TPU (95A) should scrub harder.

## Grounds container (`parts/container`, optional)

Only for using PuckOff on the bench instead of in a worktop. Print one of the two in Bambu Lab ABS-GF, like the rest of the unit. If you would rather see how full it is, print it in a clear PLA instead: the one in the photos is Fillamentum PLA Crystal Clear (about 330 g for the 4 litre one), and a Bambu Studio filament profile for it is in [`slicer`](../slicer).

| File | Holds | Size (mm) | ABS-GF |
|---|---|---|---|
| `1x_Grounds_container_4L.stl` | 4 litres | 253 × 134 × 253 | about 260 g |
| `1x_Grounds_container_0.6L.stl` | 0.6 litres | 253 × 134 × 136 | about 155 g |

Floor on the bed, no supports, 0.2 mm layers. The wall is 1.26 mm, exactly three 0.42 mm lines, so a higher wall-loop setting changes nothing.

## Holes for screws

The M3×12 and M3×16 screws cut their own thread in the printed holes. Holes that print upright are 3.2 mm, because they come out slightly small. The motor sled's screw hole prints on its side, where a 3.2 mm hole comes out full size and the screw just spins, so that one is 2.7 mm. The brush spindle's hole also prints on its side and takes a through bolt with a nut instead.
