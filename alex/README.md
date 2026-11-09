# Alex's print files

Everything here is ready to print on a Bambu Lab A1 mini (0.4 nozzle, Generic PETG, Textured PEI plate, 0.20 mm Standard,
tree(auto) supports 30 deg, 4 walls, 15 % gyroid). Each `.gcode.3mf` is one sliced plate you can send straight to the
printer; the `.stl` next to it is the same part as saved (largest flat face down unless the folder's README says why not).
Every file passed `solid_check`. Design source: github.com/jy202108g-bot/REPO1 (branches `part/xswap-v5`, `part/arm-tester`).

| Folder | What | Print time | PETG |
|---|---|---|---|
| `print/xswap_v5s/` | xswap v5 short battery swap lock for the Overseer, saved build (pincers close on one line), Amass XT60W-F / XT60EW-M | 30.3 h | 732 g |
| `print/xswap_v5p/` | the same build with the earlier parallel pincer (fingers across the pack, B = A turned 180 deg) | 32.1 h | 784 g |
| `print/arm_tester_v1/` | Overseer motor arm tester: ribbed base + top clamp, table-clamped | see its summary.md | |

Each xswap folder's README.md lists every part (qty, bed face, time, grams) and the hardware to buy; `print_sheet.png`
shows every file as it sits on the bed. The holder is 208.6 long (bed 180), so it prints as two halves bolted together.
