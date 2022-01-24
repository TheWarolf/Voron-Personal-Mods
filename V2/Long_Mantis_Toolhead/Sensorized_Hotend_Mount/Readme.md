This is an attempt to add a filament sensor between extruder gears and hotend for Mantis toolhead.

User needs to print and replace just the hotend mount piece, the rest of toolhead assembly is done following original procedure shown in Mantis [repo](https://github.com/mandryd/VoronUsers/tree/master/printer_mods/Long/Mantis_Dual_5015).

## BOM
- 1 microswitch (quality shouldn't matter much, I'm using with success a cheapo one from a no name Amazon pack, use what you have).
- 2 self tapping M2x8 or M2x10 screws. 
- a 7 mm steel ball (as long as the diameter is fairly consistent any source or type will do. Search tag "decorative work" should return plenty of results for assortments boxes on Amazon.

## Printing Tips
Printing shouldn't be too difficult on a decently calibrated printer. 

Bridging near the hotend fan mount is not critical, nothing is mating to that surface. In case of some stray filaments dangling, you can remove them with a cutter.

## Assembly notes
- Check for filament path. If path is not clear, use a 2mm drill bit to clear it out.
- Slide the ball into the slot fully. Before proceding further, check that the ball can move freely back and forth when inserting/removing a piece of filament into the filament path.
If that's not the case you can try to slightly enlarge the ball slot with a small, pointy tool (like an allen key) or file.
If this is still not enough, try to print the housing with lower EM.
- Cut or bend the switch NC pin (opposite to the lever hinge) and slide in the switch in the slot. Secure it with a M2 screw, but **be gentle while screwing, as there's an high risk of splitting the part if layer adhesion is not optimal**. 
Do not fully tighten the switch, it needs to be firm but able to slightly pivot around the screw.
- Screw the other M2 from the front. 
You should use this screw to tweak sensor "sensitivity" to filament presence: insert a piece of filament in the channel and hunt for the "click" sound on the switch, adjust screw if needed (adjustment can be made also when toolhead is fully mounted).
- Due to space constraints, bowden tube on the extruder needs to be cut flush. A ligth chamfer on the inside of the tube and on the filament entrance in the hotend mount is recommended.
