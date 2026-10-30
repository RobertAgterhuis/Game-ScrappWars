# ScrappWars

A tiny scrapper in a desert of giant wrecks. SD-7 wakes up beside a crashed
freighter on the sun-bleached planet Kessra and has to scavenge parts, survive
storms, worms and scavengers, and piece together why two fleets fell out of the sky.

**Website, trailer and screenshots:** [robertagterhuis.github.io/Game-ScrappWars](https://robertagterhuis.github.io/Game-ScrappWars/)

This repository only distributes the game: releases, the update channels and the
website. The source is not here. What changed in each version:
[CHANGELOG.md](CHANGELOG.md).

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

Saves, settings and photos live in `%APPDATA%\Godot\app_userdata\ScrappWars` by
default, not in the install folder. To keep them somewhere else, open
*Settings > Data folder...* and choose a folder: the game copies everything
there, checks the copy and only then switches (the old copy stays until you
remove it). Updates and uninstalling never touch your data folder.

## Report a bug

In the game, press **Ctrl+Alt+B** wherever the bug is. The game saves a
screenshot, asks what went wrong and opens a new
[issue](https://github.com/RobertAgterhuis/Game-ScrappWars/issues) in your
browser, filled in with your text and the game's version, place and settings.
You send it there with your GitHub account, after dragging in the screenshot
from the folder that opens. Without the game:
[open an issue](https://github.com/RobertAgterhuis/Game-ScrappWars/issues/new?template=bug_report.md).

## Uninstall

Run `%LOCALAPPDATA%\Programs\ScrappWars\ScrappWarsUpdater.exe --uninstall`.

## Licence

ScrappWars is free to play and free to pass on unchanged; everything else is
reserved. The terms are in [LICENSE.md](LICENSE.md). Third-party licences ship
with the game in its `licenses` folder.
