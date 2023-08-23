# Notes
This is just a raw dumping ground for bits and pieces I found useful. There is zero logic to the layout of this page
## Calculate the distance between 2 cogs
In this example, we have two cogs, one with 16 teeth and one with 14 teeth with a module of 1.38. The formula is

Distance = (Module x (Teeth 1 + Teeth 2)) / 2
=(1.38 x (16 + 14)) / 2
= 20.7mm

Shoulder cogs will be 15mm horizontally apart and 14.26mm vertically apart

See [https://www.youtube.com/watch?v=IhcLSx2ppUY](https://www.youtube.com/watch?v=IhcLSx2ppUY)

## How to space shafts a set distance apart
See [https://forum.freecad.org/viewtopic.php?t=53574](https://forum.freecad.org/viewtopic.php?t=53574)

## Adjusted Dimensions for 3D Printing
This is just a bunch of notes to hold the results of 3d printing experiments and mess-ups.

**New Experiment** - Dont use supports when printing holes under 4mm in dia

**Standard meshing to use for all prints** - Based on an exported standard mesh with 0.1mm surface deviation, 10-degree angular deviation, and relative surface deviation

**10mm Bearing** - Holes for 10mm bearing = 5.2mm(r) = 10mm dia hole when printed. Dia of bearing inner = 5.8mm dia = 5.9mm dia when printed (try 5.9 next to give slightly bigger)

**15mm Bearing** - Holes for 15mm bearing = 7.65mm(r) = 15 mm dia hole when printed. Dia of bearing inner = 4.95mm(r) = 9.9mm dia when printed

**Servo Cog** - Holes to accept servo cogs (2.4r) = 4.8 dia hole when printed. Is a tight fit which is needed. Holes for servo self-tapping screws 1.4 Dia

**M2 Screws** Holes to pass through, print = 1mm(r), drill = 2mm dia. Holes to tap, print 0.7mm(r), drill 1.2mm dia.
