# Nog's Cheats

_This mod is currently maintained by Robb. No new features are currently planned._
_If you enjoy my work, please consider donating to my [completely optional tip jar](https://ko-fi.com/robb4)._

Multiplayer compatible!

Use buttons in Quick Search & the Codex to easily give yourself items.
Automatically enables console commands for you - no extra work required.
You can also run them on the host's side from a client using chat commands.

## Features

* Codex & Quick Search "Give Item" buttons
* Console Commands
* Command Lists
* Debug Commands
* Codex & search expanded to show items you don't have recipes for yet
* Automatically enable console cheat commands just by having this mod installed (no need to enable the SML Mod Savegame Setting or modify any config files)

Please report bugs [on the Discord](https://discord.gg/HT4w3qEGMQ)

![QuickSearchButtons](https://i.imgur.com/o53Z7KC.png)

![All Item Categories](https://i.imgur.com/wOBLUVY.png)

Click the box icon to give yourself items!

To run console commands in the game's chat, use the Chat Command:
`/console <Command>` or `/c <Command>` or `/n <Command>`.
Always executed server side, applied to the command caller's player controller, in multiplayer.

Example: `/c NoCost 1` should enable free building.
Commands may or may not work, this mod just offers a way to run them.

[SML's Documentation on Commands](https://docs.ficsit.app/satisfactory-modding/latest/SMLChatCommands.html#ConsoleCommands)

Command /ConsoleList will print this into the Chat:

Cheat Commands:

* `Teleport`
* `God`
* `CheatScript <ScriptName, string>`
* `GiveAvailableSchematics`
* `ResetGamePhases`
* `SetNextGamePhase`
* `GiveSchematicsOfTier <int, tier number in HUB>`
* `GiveActiveMilestoneSchematic`
* `CompleteResearch`
* `NoCost <true/false>`
* `NoPower <true/false>`
* `TurboProductionMode <true/false>`
* `GiveItemStacks <Blueprint Path> <Number of Stacks>`
* `GiveItemsSingle <Blueprint Path> <Number of Items>`
* `GiveResourceSinkCoupons <Amount>`,
* `Slomo <Multiplier>`
* `SetTimeOfDay <Hour> <Minute>`
* `SetTimeSpeedMultiplier <Multiplier>`
* `EnableBuildableTick <true/false>`
* `PlayerFly <true/false>`
* `PlayerNoClipModeOnFly <true/false>`
* `FlipVehicle`
* `FillAllFreightCars <percent full, float>`
* `EmptyAllFreightCars`
* `HideAllBuildings <true/false>`
* `ShowFactoryOnly <true/false>`
* `ForceSpawnCreatures`

Command /DebugList will print this List in Chat:

* `ShowDebug Factory`
* `ShowDebug FactoryConnections`
* `ShowDebug Circuits`
* `ShowDebug Power`
* `ShowDebug Trains`
* `ShowDebug TrainCouplers`
* `ShowDebug Tracks`
* `ShowDebug Radiation`
* `ShowDebug RadiationSpheres`
* `ShowDebug ResourceSink`
* `ShowDebug AkAudioSources`
* `ShowDebug AkAudioSourceAttenuations`
* `ShowDebug Vehicle`
* `ShowDebug PipeNetworks`
* `ShowDebug PipeProbing`
* `ShowDebug PipeDetails`
* `ShowDebug PipePressure`
* `ShowDebug PipePressureGroups`
* `ShowDebug PipeDeltaPressure`
* `ShowDebug PipeFlow`
* `ShowDebug PipeMoveToOverfillRatio`
* `ShowDebug Creatures`

Go here for a Full List -> <http://www.kosmokleaner.de/ownsoft/UE4CVarBrowser.html>
