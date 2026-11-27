# M441F · Input Pre Amps

Ward-Beck Systems M441F, 1972|5. Wiki page: [M441F on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M441F.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 4 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 4 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 1 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 1 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 3 |

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNWlIY0F3TTFmQXc/view?resourcekey=0-BjPRNuHRii5P0vldjrNJIw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNWlIY0F3TTFmQXc&resourcekey=0-BjPRNuHRii5P0vldjrNJIw" width="240" alt="1972 - M441F - 441-04-007.jpg"></a><br><sub>1972|5 · 441-04-007 · <a href="MECHANICAL/1972%20-%20M441F%20-%20441-04-007%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M441F.stl`](MECHANICAL/M441F.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M441F)

- **Size:** 52.9 × 183.95 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 4 holes and cut-outs, 1 knobs (front panel: `MECHANICAL/M441F - front panel.svg`)
- the drawn panel is 0.24 wide to high, the size 0.29: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M441F.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbE1mVXJmVHNWTTg/view?resourcekey=0-kmBg6timD3puyr736Nauog" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbE1mVXJmVHNWTTg&resourcekey=0-kmBg6timD3puyr736Nauog" width="240" alt="1972 - M441F - 181-06-003.jpg"></a><br><sub>1972|5 · 181-06-003 · <a href="SCHEMATICS/1972%20-%20M441F%20-%20181-06-003%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M441F - RTO-144 Connections.pdf`

## RTO-144 pinout

22 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | MIC IN | in | A1 + | variant |
| 4 | PREAMP OUT | out | B1 + | variant |
| 5 | LINE IN | in | A2 + | variant |
| 8 | BOOSTER AMP IN | in | B2 + | variant |
| 10 | FOLDBACK OUT | out | A3 + | variant |
| 16 | SWITCHED CH ON OUT | control | A4 + | variant |
| 19 | CHASSIS | ground |  | variant |
| 20 | +24 V | power |  | variant |
| 22 | +48 V | power |  | variant |
| A | MIC IN | in | A1 - | variant |
| D | PREAMP OUT | out | B1 - | variant |
| E | LINE IN | in | A2 - | variant |
| J | BOOSTER AMP IN | in | B2 - | variant |
| L | FOLDBACK OUT | out | A3 - | variant |
| T | SWITCHED CH ON OUT | control | A4 - | variant |
| V | COMMON | ground |  | variant |
| Y | COMMON | ground |  | variant |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVg3M2M2MW9OV0E/view?resourcekey=0-pNeOGlsm8Qs2Djo1YlXzxA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVg3M2M2MW9OV0E&resourcekey=0-pNeOGlsm8Qs2Djo1YlXzxA" width="240" alt="1972 - M441F - vint P1.jpg"></a><br><sub>1972|5 · vint P1</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M441F.kicad_sym](KICAD/M441F.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
