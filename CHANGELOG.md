# Glowcell changelog

Versions are bumped on every change that gets pushed. The current version is shown at the bottom of the menu in the game (for example `v0.5.1`) and each version is tagged in this repo.

## v0.6.1
- Death now holds the camera in place for about a second so the screen shake is actually visible, and the shake is stronger and lasts longer

## v0.6.0
- Tutorial: optional guided practice run from the menu (move, eat, eat a cell, eject, split, power-ups, spikes). Never forced, skippable at any time
- Settings screen: music and effects volume, screen shake on/off, left- or right-handed touch buttons, joystick size. All saved on the device
- Game feel: burst and ring effects and floating +mass numbers when you eat, screen shake when you are eaten or pop on a spike
- Game over screen: best rank, time as #1 and a "New best" badge
- Four more colors (12 total) and four skin patterns (Plain, Dots, Rings, Star)
- Menu: Play button stays visible while the menu scrolls on phones, Tutorial and Settings buttons moved to the top

## v0.5.2
- Version number moved under the tagline in the menu

## v0.5.1
- Version number shown in the menu
- Changelog added, releases tagged

## v0.5.0
- Performance pass: the game lowers its own graphics quality automatically on slow devices
- Cheaper glow effects at reduced quality, world border glow only drawn near the edges
- Fewer per-frame allocations, faster distance math, half-rate arena rendering behind the menu

## v0.4.2
- Menu sound now defaults to Off

## v0.4.1
- Fix: menu and "Eaten by" panels could stay on screen during play (missing page header and hidden-panel rule on the hosted page)

## v0.4.0 (first version hosted on GitHub Pages)
- Power-ups: Speed surge, Shield, Spike layer, Magnet
  - 3 orbs on the map at once, each a random type
  - An unclaimed orb jumps to a new spot every 15 s; a claimed orb waits 30 s, then respawns
  - Players and NPCs both chase and use them

## Before GitHub (shared as a Claude artifact only, not tagged)

### v0.3
- Menu sound (Drift, Pulse, Arcade or Off), sound effects (eat, split, eject, eaten), and a way back to the menu from the game
- New Game resets all NPCs, scores and spikes, with spikes in new random places
- Every absorbed NPC or player adds a spike, sized by the one that was eaten

### v0.2
- iPhone and touch support (floating joystick, split / eject / pause buttons)
- Clearer eating rules: per-cell mass labels, green and red rings, eat threshold lowered to 15%

### v0.1
- First browser prototype: stylized neon look, bots, split, eject mass, spikes, leaderboard
