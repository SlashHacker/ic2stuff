IC2Stuff
=============
1.9.17
* Electric Engine now supports different maximum EU and conversion rates for each tier
* Added many configuration options for the Electric Engine
* Tweaked the engine renderer to attempt to fix rendering glitches
* Relocked the memory crystal slot of the Industrial Workbench
* Fixed packet handler glitch which broke some items on stand-alone servers.
* Fixed an issue with machines that use the FlexibleSlot which could cause crashes.

1.9.15
* Fixed critical bug which caused the Lava Battery to crash server-only processes when used.
* Other minor bug fixes.

1.9.13
* Electric Engine's hardness value corrected to prevent accidental breakage

1.9.12
* Electric Engine added, allows a variable amount of EU to be converted to MJ
* Luminator Controller added, allows WIRELESS EU transfer and control of up to 36 Luminators
* Link Descriptor added, hold and right click on a block to link to it.
* Range Upgrade added, increases the range of a Luminator Controller by 4 blocks per upgrade.
* Fixed a bug in the industrial workbench that could sometimes cause items to be placed in the memory crystal slot
* Version numbers will now reflect the build number

1.8.0
* Full NEI support
* Seed Storage Unit now displays scan progress
* Removed Sliding Door experimental block to prevent id conflict
* Fixed multiple bugs with crystal memory
* Fixed duplication bug with the workbench

1.7.0
* Added Crystal Memory support for the Industrial Workbench

1.6.0
* Expanded Industrial Workbench inventory slots to 18
* Fix many duplication and potential item loss bugs
* Industrial Workbench and Electric Assembler should now
	correctly handle most all tools used in crafting.
* Added entity update throttling to blocks to reduce the
	processing time consumed by each.

1.5.0
* Added Electric Assembler
* Tools now show energy levels on icons
* Blocks now have basic buildcraft/hopper support
* Machines events reworked to reduce lag

1.4.0
* Added Sawmill
* Rewrote the back-end code for the Seed Storage Unit
* Seed Storage Unit and Sawmill now support Hoppers
* Seed Storage Unit will only allow Hoppers to pull seed 
	bags out that have been fully scanned.
	
1.3.0a
* Added Lava Battery
* Fixed a bug that could cause the Industrial Workbench to crash when
	the output slot was clicked.

1.2.0a
* Added Seed Storage Unit
* Industrial Workbench now only consumes EU when charging items
* Added more configuration file options
* Fixed issue with certain icons not loading properly
* Fixed a duplication bug when stacks combine on double-click

1.1.0a
* Added Laser Cutter
* Added Heat Gun
* Added Energy Mallet
* Added many configuration settings
* Industrial Workbench now properly checks for sub item types
* Industrial Workbench now accepts power and charges tools in tool slots
* No API are included in the mod archive starting with this version

1.0.0a

* Added Industrial Workbench
* Added basic NEI support



Compatibility
=============
This version of ic2stuff is for Forge 9.11.0 / MC 1.6.4 and IC2 version 2 (experimental).




Installing
=============

Just copy the zip file into the .minecraft\mods folder. Typically located at %AppData%\.minecraft\mods in Windows.
