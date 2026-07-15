# Dino Crisis Early Cutscene Skip mod

#### (Choose your language below / Elija su idioma abajo)
[![Español](https://img.shields.io/badge/Language-Español-red)](README.md)
[![English](https://img.shields.io/badge/Language-English-blue)](README.en.md)
[![Código Fuente](https://shields.io/badge/Source-Code-green)](script.lua)
[![Seguridad](https://shields.io/badge/Security-Analysis-yellow)](https://www.virustotal.com/gui/file/ae29bb54a3a3d8caf429609da6da49d1c023539f0c192d366cf70e54dbd46afb/detection)

## ABOUT

Cheat Engine LUA script that automatically detects and skips cutscenes. Whenever possible, it performs full skips; otherwise, it accelerates unavoidable sequences such as stairs, doors, puzzle movements, and a handful of unskippable scenes. It currently enables speedrunners to complete both the Any% and Best Ending routes in approximately 30 minutes.Cheat Engine LUA script that automatically detects and skips cutscenes. Whenever possible, it performs full skips; otherwise, it accelerates unavoidable sequences such as stairs, doors, puzzle movements, and a handful of unskippable scenes. It currently enables speedrunners to complete both the Any% and Best Ending routes in approximately 30 minutes.

## IMPORTANT

The script tracks every skipped cutscene during a full playthrough. This data is used to determine whether subsequent cutscenes can be skipped, whether specific items should be injected into the inventory, and whether internal decision IDs need to be updated. Because of this, loading a save file while the Cutscene Skip Script is active (except for a few supported cases) may result in incorrect route progression or even game crashes. Until this limitation is addressed, loading save files is not recommended.

## HOW TO USE

You can use this mod through two completely safe methods depending on your preferences:You can use this mod through two completely safe methods depending on your preferences:

### Option 1: Traditional Table (Recommended for full transparency)
1. Launch the game as usual.
2. Open **Cheat Engine** and load the `DINO.CT` file included in this repository.
3. Allow the script to run to attach the LUA system to the game.

*Note: For transparency and to meet community standards, the full standalone source code of this routing system is exposed in plain text in the [`script.lua`](script.lua) file for public auditing.*

### Option 2: Standalone Version (No Cheat Engine required in the background)
If you prefer not to have Cheat Engine open during every run, you can directly run the standalone executable **`dinoskip.EXE`**.

⚠️ **ANTIVIRUS FALSE POSITIVES NOTICE:** Since this executable was generated using Cheat Engine's native script compiler, it internally packages parts of the core tool to automate memory hooking. Because of this, some heuristic antivirus engines will incorrectly flag it as a potential threat (`HackTool` or `Generic.Trj`). 
* This behavior is 100% safe and only interacts with *Dino Crisis 1* internal memory addresses.
* You can verify the legitimacy of the file by checking the [Public VirusTotal Report](https://virustotal.com).
* To use it, you will need to add the `.exe` file to your antivirus exclusions.

---

## THANKS

* [iiLanceLM](https://www.twitch.tv/iilancelm) and [MattGael](https://www.twitch.tv/mattgael) for helping with testing, routing, and promoting the script.
* [EyeOfTheMind86](https://fearlessrevolution.com/viewtopic.php?t=27598) for their Cheat Table, from which I obtained a couple of useful memory addresses.
* Valka, for always encouraging me.

## SUPPORT

If you'd like to support my work, you can do so here:

* Outside Argentina: [PATREON](https://www.patreon.com/cw/EmuTesting)
* In Argentina: [CAFECITO](https://cafecito.app/gabimufas97) or Mercado Pago (alias: **GabiAle97**)

