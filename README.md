# BlockyCubes

A Minecraft-inspired voxel game built with **Java and Raylib (Jaylib)**. Explore generated worlds, gather resources, craft, build, and play with friends over LAN.

This repository hosts the official downloadable builds and release notes.

**[Download the latest release](https://github.com/silasrenlow-web/BlockyCubes-Release/releases/latest)** · **[All releases](https://github.com/silasrenlow-web/BlockyCubes-Release/releases)** · **[Report a bug](https://github.com/silasrenlow-web/BlockyCubes-Release/issues)**

## Getting started

You need **Windows** and **Java 21 or newer**. You can get Java from [Eclipse Temurin](https://adoptium.net/).

1. Open the [latest release](https://github.com/silasrenlow-web/BlockyCubes-Release/releases/latest).
2. Under **Assets**, download the `BlockyCubes-*.zip` game package.
3. Extract the entire ZIP.
4. Open the extracted folder and double-click **BlockyCubes.vbs**.
5. Create a world and start playing.

Keep the game folder together: the JAR, `assets` and `libs` must stay beside the launcher.

## What you can do

- Explore Classic, Natural and Amplified worlds with different biomes, weather and a day/night cycle.
- Gather resources, craft tools and build in Survival.
- Build freely in Builder mode with flight and unlimited block placement.
- Store items in chests, smelt with cookers, climb ladders and ride the Transporter cart on rails.
- Build with slabs, stairs, doors and beds, with an outline that follows the shape under your crosshair.
- Explore snowy terrain with shallow snow layers of varying depths.
- Host a LAN world and play with friends.

See each release's notes for additions, fixes and known limitations.

## Controls

| Action | Control |
| --- | --- |
| Move | W / A / S / D |
| Look around | Mouse |
| Jump | Space |
| Sprint | Left Ctrl |
| Sneak | Left Shift |
| Break / attack | Left mouse button |
| Place / use | Right mouse button |
| Inventory | E |
| Select hotbar slot | Mouse wheel, 1–9, 0, or - |
| Drop held item | Q |
| Chat | C |
| Change camera view | F5 |
| Pause / menu | Esc |

## Multiplayer

Everyone should use the **same game release** and a **different player name**.

**Host:** Open a world, press Esc, choose **Open to LAN**, and share the code.

**Join:** On another game instance on the same network, choose **Join Friend** from the main menu, enter your player name and the host's code.

The host must keep the world running. You can also run multiple game instances on one PC to test locally.

Alpha 1.7.0-a uses **network protocol 11** and cannot connect to older protocol versions. Physical LAN/Wi-Fi behavior and some vehicle, sound and death transitions still need broader live testing.

## Updating

Extract the new release into a separate folder. To continue your worlds, keep a backup of your old `saves` folder and copy it into the new game folder. You can also copy `options.txt` to keep your settings.

## Troubleshooting and bug reports

**Nothing happens when launching?** Run **run-debug.bat** in the game folder to see the error. Check that Java is installed and available by running:

```text
java -version
```

It should report Java 21 or newer. If Java is not found, install it and ensure it is available on your PATH.

**Missing textures, sounds or libraries?** Extract the complete ZIP and keep `assets` and `libs` beside the game JAR.

**Cannot join a friend?** Check that both players have the same release, distinct names, the correct code and access to the same network.

[Open an issue](https://github.com/silasrenlow-web/BlockyCubes-Release/issues/new) with your game version, steps to reproduce, expected and actual behavior, and any screenshots or error output. For multiplayer bugs, say which player was hosting and what each player saw.

---

© 2026 Htoo Khant Maung / Eric Jacko
