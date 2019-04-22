**Marlin 2.0 Bugfix with changes for my Modded Ender-3 with SKR V1.3 and BLTouch v3.0**

4/12/2019 - Nozzle Fan had a separated wire, hardware problem.  
Fork is pretty much working and good to go, with exception that I want to center the BLTouch probing pattern.

4/5/2019 - Fork is working. Nozzle Fan is not working but need to test if its a hardware problem.
Other Known issues is that the BLTouch probing matrix is centered too far back on the bed, pretty close to the back edge.  Has something to do with home offsets or X/Y Minimum.

----------

This fork is meant for my Creality Ender-3 Modded machine with these properties/mods

* Early Ender-3, Offset wheels, single sided Y tensioner, glued on build sheet
* Stock Display (CR10STOCKDISPLAY) using single ribbon cable
* SKR V1.3 Mainboard (32-bit)
* FYSETC TMC2208 V1.2 on X, Y, Z via UART in Stealthchop2
* FYSETC TMC2208 V1.2 on E via UART in Spreadcycle
* Stock Creality Hotend with [TH3D Titanium All-Metal Heatbreak](https://www.th3dstudio.com/product/tough-titanium-heatbreak-for-creality-machines-tough-dual-hotend/)
* [Petsfang Direct with Titan Extruder](https://www.thingiverse.com/thing:2907538)
* Original BLTouch V3.0 using the left-side mounted BLTouch mount provided by the Petsfang Direct
* [TH3D EZOut V1 Filament Sensor](https://www.th3dstudio.com/product/ezout-cr-10-filament-sensor-kit/)  

----------

**This firmware is NOT maintained by Marlin. This is meant to be a personal fork/branch to contain my specific 3d printer configuration that will never be merged back upstream, but rather provides me the ability to make my own custom changes while merging in upstream Marlin 2.0.x bugfix updates**

----------

**THIS IS PROVIDED UNDER THE GPL V3 LICENSE.
PROVIDED AS-IS. NO SUPPORT OR WARRANTY IS PROVIDED.**
