# Glowcell changelog

Versions are bumped on every change that gets pushed. The current version is shown at the bottom of the menu in the game (for example `v0.5.1`) and each version is tagged in this repo.

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
