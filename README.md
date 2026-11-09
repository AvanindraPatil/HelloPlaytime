# HelloPlaytime (Poppy Playtime GrabPack, Huggy Wuggy, Catnap and Mommy Long Legs)

**The Poppy Playtime GrabPack in Hello Neighbor.** Pick it up in the Neighbor's house and use its hands: grab and pull
things, swing and zip to where the green hand hooks, jump with the purple hand, set things alight with flares, power
electric doors with the conductive hand, blast the Neighbor away with the pressure hand, and light the way with the
red hand. And the Neighbor is **Huggy Wuggy** (since 1.2.0), **Catnap** (since 1.3.0) or **Mommy Long Legs** (since
1.4.0), your choice.

<!-- screenshot here -->

> Unofficial fan project, not affiliated with Mob Entertainment, tinyBuild or Dynamic Pixels. The download contains **no
> Poppy Playtime files**: the installer builds the GrabPack, its hands, animations, textures and sounds from **your
> own copy of Poppy Playtime**. Huggy Wuggy, Catnap and Mommy Long Legs too: their models, fur, animations, textures,
> voices and the music of Chapters 5, 3 and 2.

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
- **Mommy Long Legs Update (1.4.0)**: the Neighbor can be Mommy Long Legs from Chapter 2, at her full size, with her
  real model and animations, while the Neighbor's AI hunts you as before. She crawls after you, **climbs the house's
  outside walls and roof**, waits **upside down on ceilings** and drops on you, and **lures** you with her voice from out
  of sight. Her **arm stretches** across the room to grab you and haul you in, and the catch is one of Chapter 2's
  jumpscares. In a chase she may start a game of **Statues** (the lights go out, she counts, the lights come back: move
  while she looks and she grabs you), or **snatch your GrabPack** (you get it back after her catch, or with F7).
  Chapter 2's music and her own voice lines replace the Neighbor's; she shows in the cutscenes and activities, and in the
  finale the big Neighbor and the Thing are her. The GrabPack hurts her: a shock, a flare or a blast makes her let go.
  **F9** turns her off / on, **F10** picks the next jumpscare, **F11** makes her do one of her tricks now (each press the
  next: lure, ceiling, Statues, GrabPack steal). `Choose-Character.bat` switches between Huggy Wuggy, Catnap, Mommy Long
  Legs and the normal Neighbor. Needs Chapter 2 (without it, everything else installs).
- **Catnap Update (1.3.0)**: the Neighbor can be Catnap from Chapter 3, his real model and animations, while the
  Neighbor's AI hunts you as before. He prowls, gallops after you, climbs ladders and the walls of the house, and the
  catch is one of Chapter 3's jumpscares. His **red sleeping gas** makes you drowsy (a meter fills, the screen blurs, you
  slow down and can nod off), he **vanishes into the smoke** and turns up somewhere else, and **Nightmare Critters** creep
  up behind you (look at them and they flee; flares scare them off). In the activities he sits, lies down, grooms and
  stretches like a cat. Chapter 3's music and voices replace the Neighbor's sounds; he shows in the cutscenes, the big
  Neighbor in the finale is a giant Catnap and the Thing is Nightmare Catnap. The GrabPack hurts him: the pressure hand
  knocks him down, flares burn him, the conductive hand shocks him. **F9** turns him off / on, **F10** picks the next
  jumpscare, **F11** sends a Critter. `Choose-Character.bat` switches between Huggy Wuggy, Catnap and the normal Neighbor.
  The GrabPack also got a flare counter (a limit of flares that refill one by one) and an empty click.
- **Huggy Wuggy Update (1.2.0)**: the Neighbor is Huggy Wuggy, Chapter 5's Huggy with his fur and his own animations,
  while the Neighbor's AI hunts you as before. He walks, hunts hunched, sprints after you, ducks under door frames,
  roars when he spots you and swings his long arms at you; when he catches you, Poppy Playtime's jumpscare. His voice,
  roars and steps and Chapter 5's music and ambience replace the Neighbor's sounds. He shows in the cutscenes too, and
  in the finale the big Neighbor and the Thing are Chapter 4's classic Huggy. The GrabPack's hands work on him (the
  conductive hand short-circuits him), and now and then a mini Huggy peeks out behind you. **F9** turns Huggy off / on.
- **Fredbear Update (1.1.0)**: works with the Fredbear Runaway mod. If Fredbear is the Neighbor, he gets his own reactions: the pressure hand throws him hard and he staggers, the conductive hand short-circuits him (sparks, jerks, powers down, reboots), flares set him on fire with his own scream. Nothing from Fredbear Runaway is included, the mod only reacts to it when it is installed; without it nothing changes.

## Requirements

- **Hello Neighbor** (full game) on Steam, on Windows
- **Poppy Playtime** on Steam with **Chapters 3, 4 and 5** installed (the GrabPack, hands and animations come from
  Chapter 5, some sounds from Chapters 3 and 4; Huggy from Chapter 5, his classic look for the finale from Chapter 4;
  Catnap and the Critters from Chapter 3). It can be in any Steam library.
- **Chapter 2** for Mommy Long Legs (optional: without it everything else installs). Chapter 2's files are encrypted;
  the installer finds the key in your own copy of Chapter 2 and uses it only to read your files. The key is not in
  the download and is not saved anywhere.
- An internet connection the first time you install (the installer downloads the Oodle decompressor that Poppy
  Playtime's files are packed with), and about 1 GB of free disk space while it installs.

## Install

1. Download `HelloPlaytime-1.4.0.zip` from [Releases](../../releases) and unzip it anywhere. Already have an earlier HelloPlaytime installed? Just run `Install.bat` of the new one: it finds the old install and replaces it (no need to uninstall first).
2. Close Hello Neighbor, then double-click **`Install.bat`**. It finds both games through Steam, builds the mod's
   content from your Poppy Playtime files (about a quarter of an hour, most of it for the three characters), and installs the mod (with
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
| F8 | the GrabPack on / off |
| F9 | Huggy Wuggy / Catnap / Mommy Long Legs on / off (the normal Neighbor) |
| F10 / F11 | Catnap: pick the next jumpscare / send a Nightmare Critter |
| F10 / F11 | Mommy Long Legs: pick the next jumpscare / one of her tricks now (lure, ceiling, Statues, GrabPack steal) |
| F6 | watch camera on Huggy (again: next view, then back to you) |

## Uninstall

Double-click **`Uninstall.bat`**. It removes everything the installer added to Hello Neighbor, including UE4SS if the
installer put it there. Poppy Playtime itself is never changed.

## What it changes

Only Hello Neighbor's folder:
- UE4SS: `dwmapi.dll` and the `ue4ss` folder in `HelloNeighbor\Binaries\Win64`
- the mod's UE4SS mods (`Grabpack`, `Huggy`, `Catnap`, `Mommy`) and their content paks in `HelloNeighbor\Content\Paks\Grabpack`, `...\Paks\Huggy`, `...\Paks\Catnap` and `...\Paks\Mommy` (the characters' paks replace the same Neighbor sounds, so only the chosen character's pak is live)

## Credits and licence

Code: MIT (see `LICENSE`). Bundled in the download: [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (MIT),
[CUE4Parse](https://github.com/FabianFG/CUE4Parse) (Apache-2.0) and [vgmstream](https://github.com/vgmstream/vgmstream)
(ISC), and for building the characters at install time a private Python 3.12 with NumPy, SciPy, Pillow and python-soundfile; details in `THIRD-PARTY-NOTICES.txt`. Poppy Playtime, the GrabPack, Huggy Wuggy, Catnap and Mommy Long Legs are Mob Entertainment's; Hello Neighbor
is tinyBuild's. Built with AI assistance (Claude).
