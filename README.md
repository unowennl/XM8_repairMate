# XM8_repairMate

--Repair Mate script for Exile mod--
This script adds more advanced repair mechanics to Exile.
Deferent items can be used to perform repair, some will be
consumed as materials others are used as tools.
There are 5 types of repairs for cars. They are engine, wheels, glasses,
fuel and body. Script is highly configurable, and allows to set exact
material costs and reqiured tools for deferent types of repair.
It is allowed to have materials and tools inside vehicle being repaired.
Script requires improved XM8 apps to work.

Authors
art and design - z3ro
code - vitaly'mind'chizhikov

Future plans
1. Support for helicopters (mostly done, will be added soon)

---INSTALLATION---
- Paste XM8_repairMate folder to the same folder as you placed XM8_apps folder.
- Add following lines to XM8_apps\XM8_apps_config.sqf. Adjust path to folder according to where you put it.
	XM8_apps_app1 = [
		"Repair Mate",
		"custom\XM8_repairMate\icons\repairMate_icon.paa",
		{0 execVM "custom\XM8_repairMate\scripts\XM8_repairMate_init.sqf"}
	];
	-Change "XM8_apps_app1" to application number you like.
- Change XM8_repairMate\XM8_repairMate_costConfig.sqf to your liking.
- Enjoy!

