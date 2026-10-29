# ScrappWars

A tiny scrap droid in a desert of giant wrecks. SD-7 wakes up beside a crashed
freighter on the sun-bleached planet Kessra and has to scavenge parts, survive
storms, worms and scavengers, and piece together why two fleets fell out of the sky.

This repository only distributes the game: releases and the update channels.
The source is not here.

## Install (Windows 10/11, 64-bit)

1. Download `ScrappWars-<version>-windows-x64.zip` from the newest
   [release](https://github.com/RobertAgterhuis/Game-ScrappWars/releases/latest).
2. Unpack it anywhere.
3. Run `ScrappWarsUpdater.exe` in the unpacked folder. It checks the files,
   installs the game into `%LOCALAPPDATA%\Programs\ScrappWars` (no administrator
   rights needed), adds ScrappWars to the Start menu and starts it. The unpacked
   folder can be deleted afterwards.

Windows may show a SmartScreen warning because the game is not code-signed:
choose "More info" and "Run anyway".

## Updates

The game checks for updates when the main menu opens (Settings > Updates... to
turn that off, to include beta versions, or to check by hand). Installing an
update is always your choice: the game closes, the updater downloads the new
version, checks its signature and checksum, keeps a backup of the old version
and starts the game again. If anything goes wrong, the old version is restored.

Versions are `MAJOR.MINOR.BETA.FIX`: `1.0.0.0` is a stable release, `1.0.0.1` a
bug fix of it, `1.0.1.0` a beta.

## Saves

Saves, settings and photos live in `%APPDATA%\Godot\app_userdata\ScrappWars`,
not in the install folder; updates and uninstalling never touch them.

## Uninstall

Run `%LOCALAPPDATA%\Programs\ScrappWars\ScrappWarsUpdater.exe --uninstall`.

## Licences

ScrappWars is (c) 2026 Robert Agterhuis, all rights reserved. Third-party
licences ship with the game in its `licenses` folder.
