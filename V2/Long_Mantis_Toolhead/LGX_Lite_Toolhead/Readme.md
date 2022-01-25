This is a rework of Mantis toolhead to use LGX Lite extruder.

![CAD](/Images/Assembly.PNG)


## BOM (in addition to normal Mantis BOM)
- 4 to 6 M3x8 bolts 
- 2 M3x10 bolts

## Prints needed
- *LGX_Lite_Carriage.stl* or *LGX_Lite_Carriage_Single_Magnet.stl* 
- *LGX_Lite_Adapter_Plate.stl*
- *LGX_Lite_Strain_Relief_Threaded.stl* or *LGX_Lite_Strain_Relief_No_Thread.stl*
Note that this mod is compatible with my other mod of sensorized hotend mount. If you want to use it, just print *LGX_Lite_Sensorized_Hotend_Mount.stl* and follow instructions [here](https://github.com/TheWarolf/Voron-Personal-Mods/tree/main/V2/Long_Mantis_Toolhead/Sensorized_Hotend_Mount).

## Streamlined assembly instructions
- follow assembly instructions on the original Mantis repo, just replacing the carriage with the LGX_Lite_Carriage. 
- Test fit a piece of bowden tube in central hole of the adapter plate. If needed use a 4mm drill bit to enlarge the slot.
- Fix the LGX Lite to the mounting plate using from 2 to 4 M3x8 bolts. I use 4, but if you're chasing the grams feel free to experiment with less.
- Insert bowden tube into the slot and push it firmly in place. Cut flush the tube to the adapter if using the *sensorized_hotend_mount* mod. Leave a bit of extra if using standard hotend mount.

![Adapter_Plate](/Images/MountignPlate.jpg)

- Put the LGX with the adapter on the hotend mount and secure the plate with two M3x10. **TIP:** before tigthening fully the bolts, slide into the whole carriage assembly a piece of filament. This can help in aligning the filament path.
- Secure the strain relief to the carriage with 2 M3x8 bolts. Be careful not to overtighten or putting too much stress on the piece, as it can be quite fragile, depending on your layer adhesion.
- Route wires as you prefer and secure them with zip ties.

![Rats nest](/Images/AssembledToolhead.jpg)
