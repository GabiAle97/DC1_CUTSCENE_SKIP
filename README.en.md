# Dino Crisis Early Cutscene Skip mod

#### (Choose your language below / Elija su idioma abajo)
[![Español](https://img.shields.io/badge/Language-Español-red)](README.md)
[![English](https://img.shields.io/badge/Language-English-blue)](README.en.md)

## ABOUT

Cheat Engine LUA script that automatically detects and skips cutscenes. Whenever possible, it performs full skips; otherwise, it accelerates unavoidable sequences such as stairs, doors, puzzle movements, and a handful of unskippable scenes. It currently enables speedrunners to complete both the Any% and Best Ending routes in approximately 30 minutes.Cheat Engine LUA script that automatically detects and skips cutscenes. Whenever possible, it performs full skips; otherwise, it accelerates unavoidable sequences such as stairs, doors, puzzle movements, and a handful of unskippable scenes. It currently enables speedrunners to complete both the Any% and Best Ending routes in approximately 30 minutes.

## IMPORTANT

The script tracks every skipped cutscene during a full playthrough. This data is used to determine whether subsequent cutscenes can be skipped, whether specific items should be injected into the inventory, and whether internal decision IDs need to be updated. Because of this, loading a save file while the Cutscene Skip Script is active (except for a few supported cases) may result in incorrect route progression or even game crashes. Until this limitation is addressed, loading save files is not recommended.

## HOW TO USE

Load the game in Cheat Engine, then open the DINO.CT table to attach the LUA script to the game. Once you allow the script to run, the Cutscene Skip will be enabled.

If you prefer not to use Cheat Engine, you can use the standalone EXE included in this repository instead.
This executable may be flagged as "malware" by antivirus software because it accesses the game's memory. However, it only interacts with the game's own memory addresses and does not pose any risk to the user, making these detections false positives. This can be verified by reviewing the source code available in this repository.
To use the executable, you will need to add it to your antivirus exceptions or temporarily disable your antivirus (not recommended).

For the smoothest experience, combine it with the [DinoReady Patch DoorSkip](https://www.speedrun.com/dino1/resources/kzgcz).


## THANKS

* [iiLanceLM](https://www.twitch.tv/iilancelm) and [MattGael](https://www.twitch.tv/mattgael) for helping with testing, routing, and promoting the script.
* [EyeOfTheMind86](https://fearlessrevolution.com/viewtopic.php?t=27598) for their Cheat Table, from which I obtained a couple of useful memory addresses.
* Valka, for always encouraging me.

## SUPPORT

If you'd like to support my work, you can do so here:

* Outside Argentina: [PATREON](https://www.patreon.com/cw/EmuTesting)
* In Argentina: [CAFECITO](https://cafecito.app/gabimufas97) or Mercado Pago (alias: **GabiAle97**)

