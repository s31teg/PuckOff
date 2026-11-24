# Bambu Studio filament profile

`Fillamentum PLA Crystal Clear @BBL H3C.json` is a filament profile for printing the optional grounds container see-through, in Fillamentum PLA Crystal Clear, on a Bambu Lab H3C. The container in the photos was printed with it. The default material for the container is Bambu Lab ABS-GF, like the rest of the unit (see [`docs/PRINTING.md`](../docs/PRINTING.md)).

## Import

In Bambu Studio choose **File → Import → Import Configs** and pick the `.json` file. With the H3C selected it appears under your user presets in the filament list.

## What it changes

It is based on Bambu's *Generic PLA @BBL H3C* preset and changes only these settings. Everything else, including retraction and flow ratio, stays at Bambu's values.

| Setting | Value | Why |
|---|---|---|
| Nozzle temperature | 230 °C (range 195 to 240) | Printing hot helps clarity. |
| Max volumetric speed | 6 mm³/s (about 70 mm/s at 0.2 mm layers) | Slower is clearer. |
| Part cooling fan | 20 to 30 %, off for the first 2 layers, full by layer 5 | Low, even cooling avoids haze. |
| Auxiliary fans | off | Even cooling. |

Fillamentum's own guide recommends drying the filament for about 4 hours at 50 °C before printing, since damp filament prints foggy. For other printers, start from your printer's Generic PLA preset and copy the values above.

The profile has not been tested on many prints yet; treat it as a starting point.
