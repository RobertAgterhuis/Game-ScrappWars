# Release notes

Every released version of ScrappWars, newest first. Downloads: [releases](https://github.com/RobertAgterhuis/Game-ScrappWars/releases).

## 0.6.0 fix 1 (0.6.0.1, 2026-10-29)

A polish update: faster start-up, menus that fit every screen, a new icon and more of Kessra's own look.

### Faster start

- **From about 37 to about 9 seconds** to a playable world on a fast PC (Ultra); Low starts in about 8. The world is exactly the same: what used to be worked out on every start is now prepared once.
- **A real loading screen** with progress and tips instead of a frozen frame, and our own start-up image instead of the engine logo.

### Menus

- **Settings always fit:** every settings page scrolls between a fixed title and a fixed Back button, at any window size and interface scale.
- **Esc or gamepad B** goes back one page everywhere, and closes the settings from the top page.
- The title screen fills the whole window, without black bars.

### Look

- **SD-7's new paint:** sun-faded oxide red on cream, with a deeper visor over its eye. Signal orange is still at the painter.
- **A new sand worm:** an armoured, forward-leaning head with a plated nose and side mandibles that snap shut.
- **A new relief emblem:** a water drop in an open shield, on the escape pod and the relief wrecks.
- **A new game icon** for the game, its window, the updater and the website.

### For testers

- A playtest kit (plan, tester handout in Dutch and English, observation sheet) for the coming test round.

## 0.6.0 (0.6.0.0, 2026-10-29)

The first big update after release: a full director's pass over the story, the play, the look and the controls.

### Story

- **Who lied?** A new memory core in the Crater Sea answers the question both fleets asked, and the admiral's last log now half admits it.
- **WREN's farewell.** The broadcast needs all of her: she says goodbye when her core goes into the transmitter, and in the epilogue her own voice sends the cease-fire.
- **SD-7 speaks for itself** in four new maintenance logs, and from mid-game WREN picks up transmissions from the fleets still fighting overhead.
- Each amplifier part now comes with its own story, and later directions are vaguer: the scanner finds the last step.
- **Dunewell talks.** Five townsfolk have something to say, and it changes as the story moves on.
- The epilogue ends with a line about what you did on Kessra.
- Kessra's machines are now called **scrappers**.

### Play

- **A new final act:** throw the deck relays to power the Dawnbreaker's bridge, then climb while the ship settles, debris falls (watch the marks), a storm rises and the worm circles the hull.
- **Enemies with tactics:** scavengers shy from your headlamp beam and circle round to strike from the dark; scrap hunters hunt in pairs, one holding while the other flanks.
- **Field kits:** pack one at a workbench and swap a part once out in the desert.
- **After the end:** a checklist in the journal and on the save slot shows what is still out there.
- Fairer economy (freight once per day, storm scrap near you), zones that are always right after a rescue or a load, and hunters that patrol their own regions again.

### Look

- A modelled, wrecked bridge on the Dawnbreaker that comes to life when you power it.
- Dunewell rebuilt from the wrecks: wind-catcher towers, stepped and vaulted houses, hull-plate walls.
- Storms you can see through near by, and SD-7 lit by its own lamp in the dust.
- Leaves and cloth fade out between the camera and SD-7 instead of filling the screen.
- Reveal shots that frame the wreck, a richer noon, a cooler dusk, natural canyon strata, salvage ramps, and lookouts where the camera shows the view when you stop.
- Lower video memory and fewer draw calls with the same image.

### Controls and comfort

- The interface scales with the window, plus a UI scale setting.
- Subtitle size and background, press-instead-of-hold for hover, torch, shield and grapple, screen shake on/off, field of view, high-contrast markers, objective markers on/after a while/off.
- Display page: render scale (FSR), vsync, fps limit, volumetric clouds and GI switches.
- Separate gamepad stick speed, inversion and deadzone.
- A journal next to the map, clearer warnings, and the bug reporter (Ctrl+Alt+B) can attach your save and session log.

## 0.5.0 fix 1 (0.5.0.1, 2026-10-29)

### New

- **Report a bug from inside the game.** Press Ctrl+Alt+B wherever something
  goes wrong. The game saves a screenshot, pauses and asks what happened. "Open
  on GitHub" opens a new issue in your browser, already filled in with your text
  and the game's version, place and settings (optionally the last lines of the
  log, without paths or your user name), and shows the screenshot in its folder
  so you can drag it in. You send the issue with your own GitHub account; the
  game never posts anything by itself.
- The shortcut is listed on the controls page and in the controls help.

## 0.5.0 (0.5.0.0, 2026-10-29)

The first public release of ScrappWars.

### What is in it

- The whole desert of Kessra: home by the crashed freighter, the Dawnbreaker,
  Dunewell, the Glass Plain, Canyon City and its caves, the Salt Graveyard,
  the Scorch, the crater sea and green Hollowmere, joined by transitions,
  ridges, dry riverbeds and landmarks.
- WREN's main story and side jobs, memory logs read aloud, contracts, traders'
  camps, the scrap train, stranded droids, vaults, beacons and photo jobs.
- Four difficulties (Easy, Medium, Hard, Ultra), switchable at any time, and a
  rescue network that brings SD-7 back to an explored base.
- The intro film, day and night, storms, eclipses, volumetric clouds on High
  and Ultra.
- Updates from inside the game (Settings > Updates...).

### Install

Unpack the zip and run `ScrappWarsUpdater.exe` (see the README).
