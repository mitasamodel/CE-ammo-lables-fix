Fix some ammo lables issues.

# What it does
Mod renames lables for some ammunition, based on the Ammunition Set. It helps to distinguish ammos from different sets even if they have the same caliber.
It also adds caliber to the ammunition, which previously didn't have it (example - 100mm for BMP3).

Example:
Mod "RimThunder - Red Dragon" adds new set of ammo called "AmmoSet_125mmT85".
It consists of <Ammo_125mmT85_HEAT>, <Ammo_125mmT85_Sabot>, <Ammo_125mmT85_HE> and <Ammo_125mmT85_EMP>.
The labels of them are:
- 125mm cannon shell (HEAT)
- 125mm cannon shell (APDS)
- 125mm cannon shell (HE)
- 125mmT85 cannon shell (EMP) <-- This is already in original mod

There is however another mod for RimThunder series, which adds another 125mm set of ammo. And they have the same labels, which makes it hard to distinguish them.

This mod-fix changes some labels to be more appropriate. In that case it changes this set to following:
- 125mmT85 cannon shell (HEAT)
- 125mmT85 cannon shell (APDS)
- 125mmT85 cannon shell (HE)
- 125mmT85 cannon shell (EMP) <-- This is already in original mod

# Currently patched mods
- RimThunder - Core
- RimThunder - Breakthrough
- RimThunder - Dragon Ascend
- RimThunder - Red Dragon
- RimThunder - Torrent Pioneer
- RimThunder - Zarya
