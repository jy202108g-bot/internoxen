# Overseer arm tester v1 (8 Nov 2026)

Bench rig that clamps one Overseer arm root (Spark's root bolting, clamp faces 45.0 apart, 8 mm slabs, M3 x 55) and holds it on
a table with one or two F-clamps. Doc and method: `nox/overseer/arm-tester.md`; numbers: `nox/dimensions.md` System Overseer arm
tester.

System: tester + arm (rigid stand-in) + front / rear motor loads; F-clamp preload 1000 N a jaw, one-way table contact; worst index 0.27 in front handling 100 N +v (flight 0.18)
Weight: 507 + 21 g solid (M); sliced 333 + 15 g PETG (M), first version
Strength: worst index 0.27 in front handling 100 N +v; weakest spot the wall foot beside the root (u 59, v 23, z -1)
Stiffness: front motor 0.108 mm / 21 N vertical, 0.094 lateral; tester-alone mode 211 / 226 Hz (target 190, DEFAULT)
Solid: solid_check PASS (base, top)
Print: base plate face down, bed contact 14885 mm² (M), 12 h 47 m; top clamp top face down, 2066 mm², 39 min; tree supports on (support g not read from the CLI); files print/arm_tester_v1_base.stl, print/arm_tester_v1_top.stl (+ .gcode.3mf)
Previews: preview_arm_tester_v1_base.png, preview_arm_tester_v1_top.png; system: assembly.png, side.png, bolting.png; page: page.html
Sweep: sweep.log (9 variants, h 2.5); final: fe.json, build.log (h 2.0); slicing: slice.json
