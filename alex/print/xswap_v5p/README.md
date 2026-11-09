# xswap v5 short, parallel pincer: print files

Bambu Lab A1 mini, 0.4 nozzle, Generic PETG, Textured PEI plate, 0.20 mm Standard; tree(auto) supports 30 deg, 4 walls, 15 % gyroid; 5 mm brim under 400 mm2 of bed contact or over 100 mm tall. Sliced with Bambu Studio 02.09.01.70 CLI (nox/box/xswap/xswap5_slice.py). Each .gcode.3mf is one plate, ready to send.

| Part | Qty | Print file (sliced) | STL | Bed face | Bed mm2 | Size mm | Time | Filament g |
|---|---|---|---|---|---|---|---|---|
| holder_head | 1 | print/xswap5p_holder_head.gcode.3mf | print/xswap5p_holder_head.stl | +y down | 5570 | 84.6 x 111.1 x 104.3 | 4h 43m 16s | 114.80 |
| holder_tail | 1 | print/xswap5p_holder_tail.gcode.3mf | print/xswap5p_holder_tail.stl | -y down | 5677 | 84.6 x 111.1 x 104.3 | 4h 39m 4s | 114.57 |
| shell | 1 | print/xswap5p_shell.gcode.3mf | print/xswap5p_shell.stl | +y down | 4150 | 88.6 x 95.8 x 178.0 | 11h 15m 49s | 285.26 |
| tail_plug | 1 | print/xswap5p_tail_plug.gcode.3mf | print/xswap5p_tail_plug.stl | +y down | 2338 | 48.5 x 48.2 x 16.5 | 38m 47s | 14.97 |
| xt60_keeper | 1 | print/xswap5p_xt60_keeper.gcode.3mf | print/xswap5p_xt60_keeper.stl | +z down | 305 | 29.4 x 13.2 x 3.0 | 4m 53s | 1.23 |
| lid | 1 | print/xswap5p_lid.gcode.3mf | print/xswap5p_lid.stl | -z down | 9035 | 67.0 x 143.2 x 6.0 | 1h 4m 29s | 29.87 |
| base | 1 | print/xswap5p_base.gcode.3mf | print/xswap5p_base.stl | +x down | 8811 | 61.9 x 143.2 x 67.0 | 7h 5m 54s | 181.62 |
| pinion | 1 | print/xswap5p_pinion.gcode.3mf | print/xswap5p_pinion.stl | +z down | 529 | 30.0 x 29.7 x 12.8 | 22m 14s | 5.07 |
| gate_bar | 2 | print/xswap5p_gate_bar.gcode.3mf | print/xswap5p_gate_bar.stl | -z down | 1240 | 34.9 x 72.8 x 9.5 | 49m 29s | 18.58 |
| finger_A | 1 | print/xswap5p_finger_A.gcode.3mf | print/xswap5p_finger_A.stl | -x down | 338 | 44.1 x 50.0 x 34.0 | 39m 46s | 9.10 |
| finger_B | 1 | print/xswap5p_finger_B.gcode.3mf | print/xswap5p_finger_B.stl | +x down | 338 | 44.1 x 50.0 x 34.0 | 39m 44s | 9.10 |

Total: 32.1 h, 784 g PETG (supports included). Every file: solid_check PASS, print_orient no thin islands.
The shell stands on its head (XT60) end: top face down its floor bridges the pack cavity (78 g supports, 35 %); on its end 24.5 g (10 %).
The holder is 208.6 long (bed 180): printed as 2 halves split at the pack centre.

Hardware (same for both builds; E = estimate, check against your parts)
- 2 x Amass XT60W-F (pack lead) + XT60EW-M (holder): 2 x M2 x 8 screws, flange up into the holder pod (thread cuts in PETG)
- 4 x Ø8 x 25 hardened steel dowel pins (ISO 8734), pressed into the holder deck from the top (guide poles)
- 4 x M3 x 12 cap screws: holder to the drone's 4 heat-set inserts (80 x 50)
- 2 x M3 x 16 cap screws + 2 M3 heat-set inserts (Ø4.0 x 7 holes): join the 2 holder halves
- 2 x M3 + 2 inserts: XT60 keeper under the female; 2 x M3 cross bolts through the tail plug (tail end)
- 2 x Ø5 steel dowels (gate-bar pivots, pressed into the shell floor) + 2 torsion springs (1.0 wire, OD 12.5, 6 turns)
- Station: servo (4 screws + inserts), 4 x M3 lid screws + inserts, flip-stub set screws
