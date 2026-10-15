# RMG - Nintendo 64 through a Mupen Front End

## At a Glance

N64 emulation depends on the core, the video plugin, and the game. RMG lets you set those without memorizing a command line, and it can keep a per-game override when one title hates the global video choice. Start with the default the build recommends. Change the video plugin only after a game fails in a way you can describe.

- ROMs you supply and may use
- Controller pak and save types the game expects
- A video plugin left alone until the title screen works
- Per-game settings for the exceptions
- Saves copied out of the config folder

High-resolution texture packs and wide hacks are optional. They are not why a black screen happens on the first launch.

![RMG with an N64 game on the default video plugin](https://emulation.gametechwiki.com/images/thumb/5/55/RMG-demo1.png/509px-RMG-demo1.png)

## Settings That Matter

| Setting | First value |
|---|---|
| Video | The default plugin |
| Controller | A pad with a mapped analog stick |
| Save type | Automatic, unless this game needs a manual type |
| Plugins copied from an old install | Not until this RMG version asks for them |
| Texture pack | Off |

1. Map the analog stick and the C-buttons.
2. Load one ROM you may use.
3. Pass the title screen on default video.
4. If a second game glitches, set an override only for that game.
5. Copy saves before you delete the RMG folder to "fix" anything.

[![Open RMG](https://img.shields.io/badge/Open-RMG-166534?style=for-the-badge&logo=windows&logoColor=white)](https://adelinachapinevblt.github.io/.github/rmg-emulator)

## Fits

N64 play on Windows with a maintained Mupen GUI. A poor fit for other Nintendo systems. A poor fit if you wanted parallel-RDP experiments and this build is not the one you read about. A poor fit for files you do not have the right to run.

## Requirements

| Item | Expectation |
|---|---|
| PC | 64-bit Windows, a GPU with current drivers |
| ROM | An N64 image you may use |
| Pad | Analog stick recommended |
| Disk | Saves kept on purpose |

## Fixes

A black screen on every game. The video plugin or the GPU driver is the problem. Return to the default.
One game resets. Try its save type before you change plugins.
The stick barely moves. The axis is the D-pad. Map the analog.
Saves vanished. They were in the old user folder.
A texture pack broke the HUD. Remove it for that game.

## Default Plugin, Then One Game

RMG should boot one N64 ROM you may use on the video plugin the build recommends. Map the analog stick and the C-buttons before you decide the camera is dead. Change the plugin only after a game fails in a way you can describe, and prefer a per-game override so the next title keeps the default. Texture packs and wide hacks wait until the title screen exists.

Saves are outside the ROM. Copy them before you delete the RMG folder. A black screen on every game is the plugin or the GPU driver. A reset on one game is often the save type or the dump. Other Nintendo systems do not belong here. Old plugin DLLs from a different front end stay out until this version asks for them.

- Analog stick mapped
- Default video until one game runs
- Per-game override for the exception
- Saves copied
- Driver updated if every ROM is black
- Second dump before a hack
- Texture pack removed if the HUD breaks

| Symptom | First change |
|---|---|
| All black | Default plugin and the GPU driver |
| One game resets | Save type or another dump |
| Stick barely moves | It is mapped as a D-pad |
| Save missing | Old user folder |

RMG is the window. The core still has to be able to run the file.

## Phrase List

rmg emulator, rosalie mupen gui, rmg n64, mupen64plus frontend, n64 video plugin, rmg controller pak, rmg per game, n64 emulator windows rmg
