# PuckOff

A 3D-printed, two-head portafilter cleaner for espresso. Turn the portafilter upside down and press it onto a spinning head: one head scrapes out the old puck, the other brushes the basket, the corner and the rim. The heads only spin while you press, and the grounds fall through into a bin underneath.

![PuckOff fitted in a worktop](images/puckoff.png)

It can be fitted through a cut-out in a kitchen worktop, held by a clamp plate underneath, or stand on the bench in a clear container that catches the grounds.

## How it works

- Two small 12 V geared motors stand in towers inside a printed tub, one per head.
- Each motor sits in a sled that slides 1.5 mm down its tower onto a push switch. Pressing the portafilter onto a head pushes the motor down and switches it on; lift off and it stops.
- The heads push onto a 12 mm hex coupler on each motor shaft and are held by a magnet, so they pull straight off for cleaning.
- The **scraper head** has three curved blades that clear the puck out of the basket.
- The **brush head** is a stack of flat TPU stars and combs on a rigid spindle. The stars wipe the rim and the wall, and the combs wipe the floor and the corner.
- Tower caps lock with a twist and a click, with no screws.
- The top cover lifts off on magnets for cleaning.

Sized for a 58 mm IMS basket, 24 mm deep.

## Pictures

| | |
|---|---|
| ![Exploded view](images/exploded_view_1_whole_unit.png) | ![Brush head and hardware](images/exploded_view_2_brush_head_and_hardware.png) |
| Whole unit pulled apart, with every screw, nut and magnet | Brush head, hardware list and order of assembly |
| ![Container](images/container.png) | ![Scraper direction](images/scraper_direction.png) |
| Bench-top version in its clear container | Which scraper to print for your motor's direction |

Both exploded sheets are also in [`docs/PuckOff_exploded_view.pdf`](docs/PuckOff_exploded_view.pdf) for printing on paper.

## What's in this repo

```
parts/
  unit/           tub, covers, tower caps, motor sleds, switch discs, clamp parts
  scraper_head/   scraper, in two hands (print one)
  brush_head/     rigid spindle and the TPU stars and combs
  container/      optional clear grounds container for bench-top use
images/           the pictures above
docs/             assembly guide, printing guide, exploded view PDF
slicer/           Bambu Studio filament profile for the clear container
```

Every file in `parts` is one part, already turned the right way up for printing. The number at the front of the name is how many to print.

## Getting started

1. Read [`docs/PRINTING.md`](docs/PRINTING.md) for what to print, in what material and which way up.
2. Get the hardware and bought parts in [`docs/ASSEMBLY.md`](docs/ASSEMBLY.md).
3. Follow the order of assembly in the same guide.

## Status

This is a personal project and a work in progress. The twist-lock caps, the click and the brush head have been printed and tried. The latest motor sled, the reverse scraper and the grounds container have not been printed yet. Measure your own basket, worktop and parts before cutting anything.

## Licence

© 2026 s31teg. Licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) (CC BY-NC-SA 4.0). See [`LICENSE`](LICENSE).

You may print, use and change PuckOff for yourself and share it with credit. You may not sell it, sell prints of it or use it commercially. If you share a changed version, it has to be under the same licence.

It comes with no warranty. It is an electrical device with spinning parts, so build and use it at your own risk.
