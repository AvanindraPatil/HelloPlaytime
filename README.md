# HelloPlaytime

**The Poppy Playtime GrabPack in Hello Neighbor.** Pick it up and use its hands: grab and pull
things, swing and zip to where the green hand hooks, jump with the purple hand, set things alight with flares, power
electric doors with the conductive hand, blast the Neighbor away with the pressure hand, and light the way with the
red hand. No Poppy Playtime characters, just the pack.

<img width="1920" height="1080" alt="poppy 1" src="https://github.com/user-attachments/assets/d7dc05c0-0097-46f2-89b9-e85aeb96b834" />


> Unofficial fan project, not affiliated with Mob Entertainment, tinyBuild or Dynamic Pixels. The download contains **no
> Poppy Playtime files**: the installer builds the GrabPack, its hands, animations, textures and sounds from **your
> own copy of Poppy Playtime**.

## Features

- **The GrabPack** in your hands with both launchers, Poppy Playtime's own launcher animations and sounds, and the
  hands flying out on their cables.
- **Left hand (blue)**: grabs and pulls props to you, opens doors, pulls levers and switches.
- **Right hands** (Q for the next one, hold Q for the hand wheel):
  - **Red**: grab, plus a **flashlight** (F).
  - **Green**: grapple; swing on the cable or zip all the way.
  - **Purple**: slams the floor and jumps you up.
  - **Flare**: shoots flares that burn, melt ice and window glass, and send the Neighbor running around on fire.
  - **Conductive**: powers electric doors, gates and terminals.
  - **Pressure**: builds up pressure, then blasts things (and the Neighbor) away; cools hot objects.
- Hands that hit windows tap, crack or break the glass, and every surface has its own sound.
- A GrabPack icon in the inventory.
- **Fredbear Update (1.1.0)**: works with the Fredbear Runaway mod. If Fredbear is the Neighbor, he gets his own reactions: the pressure hand throws him hard and he staggers, the conductive hand short-circuits him (sparks, jerks, powers down, reboots), flares set him on fire with his own scream. Nothing from Fredbear Runaway is included, the mod only reacts to it when it is installed; without it nothing changes.

## Requirements

- **Hello Neighbor** (full game) on Steam, on Windows
- **Poppy Playtime** on Steam with **Chapters 3, 4 and 5** installed (the GrabPack, hands and animations come from
  Chapter 5, some sounds from Chapters 3 and 4). It can be in any Steam library.
- An internet connection the first time you install (the installer downloads the Oodle decompressor that Poppy
  Playtime's files are packed with).

## Install

1. Download `HelloPlaytime-1.1.0.zip` from [Releases](../../releases) and unzip it anywhere. Already have an earlier HelloPlaytime installed? Just run `Install.bat` of the new one: it finds the old install and replaces it (no need to uninstall first).
2. Close Hello Neighbor, then double-click **`Install.bat`**. It finds both games through Steam, builds the mod's
   content from your Poppy Playtime files (a minute or two), and installs the mod (with
   [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS)) into Hello Neighbor.
   - Windows may warn about running a script from the internet. Choose "More info", then "Run anyway".
3. Start Hello Neighbor from Steam as usual and load a level. The GrabPack lies in front of you: pick it up with **E**.

## Controls

| Key | With the GrabPack |
|---|---|
| Left mouse | the left (blue) hand: grab / pull |
| Right mouse | the right hand (hold: keep it on something; pressure hand: click out, click again to blast) |
| Q | next right hand (hold: the hand wheel, point with the mouse) |
| F | the red hand's flashlight |
| X | put it down (hold: throw) |
| F7 | bring the GrabPack back to you |
| F8 | the mod on / off |

## Uninstall

Double-click **`Uninstall.bat`**. It removes everything the installer added to Hello Neighbor, including UE4SS if the
installer put it there. Poppy Playtime itself is never changed.

## What it changes

Only Hello Neighbor's folder:
- UE4SS: `dwmapi.dll` and the `ue4ss` folder in `HelloNeighbor\Binaries\Win64`
- the mod's UE4SS mod (`Grabpack`) and its content pak in `HelloNeighbor\Content\Paks\Grabpack`

## Credits and licence

Code: MIT (see `LICENSE`). Bundled in the download: [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (MIT),
[CUE4Parse](https://github.com/FabianFG/CUE4Parse) (Apache-2.0) and [vgmstream](https://github.com/vgmstream/vgmstream)
(ISC); details in `THIRD-PARTY-NOTICES.txt`. Poppy Playtime and the GrabPack are Mob Entertainment's; Hello Neighbor
is tinyBuild's. Built with AI assistance (Claude).
