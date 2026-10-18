# Asteroid Blast

A 2D space shooter made in Unity. Fly your ship through an asteroid field, blast rocks apart, grab power-ups and survive through multiple levels.

This repository contains the **built game only**, so there is nothing to compile. Download it and run the app.

## How to play

1. Download this repo: click **Code → Download ZIP**, or clone it:
   ```bash
   git clone https://github.com/Kyran4/Asteroid-Blast-Playable.git
   ```
2. If you downloaded the ZIP, **extract it** first. Don't run the game from inside the ZIP.
3. Open the folder and double-click the game's `.exe` file.

Keep all the files in the folder together. The game needs the data folder and DLLs that sit next to the `.exe`, so moving the `.exe` somewhere on its own will stop it from launching.

**Windows warning:** because the build isn't code-signed, Windows SmartScreen may show a warning the first time. Click **More info → Run anyway**.

## Controls

| Action | Key |
| --- | --- |
| Move / rotate ship | W,A,S,D |
| Boost | Shift |
| Shoot | Left Click   |
| Pause | ESC |

## Features

- **Ship physics:** thrusters and smooth rotation driven by Rigidbody2D, so the ship has momentum rather than snapping around
- **Shooting:** fire bullets to break up asteroids
- **Asteroid variety:** randomly spawned asteroids, plus a chase variant that behaves differently
- **Time-freeze power-up:** collect it to freeze the asteroids
- **Pickups, score and lives:** collect items, build your score, and respawn after losing a life
- **Multiple levels** with a main menu, pause menu and win screen
- **Game feel:** hit effects, sound effects and audio fades

## Built with

- Unity (2D)
- C#
- Unity Input System
- UI Toolkit for the menus

The game is event-driven: a central events system connects gameplay, UI, audio and visual effects.

## About this project

I designed and built everything in the game: the design, animations, sound and visual effects, and all the scripting. Source code isn't included in this repo.

## Author

Kyran Hannah, [GitHub](https://github.com/Kyran4)
