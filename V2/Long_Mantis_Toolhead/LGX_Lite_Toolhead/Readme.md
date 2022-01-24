This is a rework of Mantis toolhead to use LGX Lite extruder.

## BOM (in addition to normal Mantis BOM)
- 4 to 6 M3x8 bolts 
- 2 M3x10 bolts

## Prints needed
- *LGX_carriage.stl*
- *LGX_adapter_plate.stl*
- *LGX_strain_relief_threaded.stl* or *LGX_strain_relief_smooth.stl*

## Streamlined assembly instructions
- follow assembly instructions on the original Mantis repo, just replacing the carriage with the LGX_carriage. Note that this mod is compatible with the *sensorized_hotend_mount* [link].
- Test fit a piece of bowden tube in central hole of the *adapter_plate*. If needed use a 4mm drill bit to enlarge the slot.
- Fix the LGX Lite to the mounting plate using from 2 to 4 bolts. I use 4, but if you're chasing the grams feel free to experiment with less.
- Insert bowden tube into the slot and push it firmly in place. Cut flush the tube to the adapter if using the *sensorized hotend mount* mod. Leave a bit of extra if using standard hotend mount.
- Put the LGX with the adapter on the hotend mount and secure the plate with two M3x10. **TIP:** before tigthening fully the bolts, slide into the whole carriage assembly a piece to filament. This can help in aligning the filament path.
- Fix the strain relief to the carriage with 2 M3x8 bolts. Be careful not to overtighten or putting too much stress on the piece, as it can be quite fragile, depending on your layer adhesion.
- Route wires as you prefer and secure them with zip ties.
