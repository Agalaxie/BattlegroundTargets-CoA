# BattlegroundTargets — Conquest of Azeroth

Battleground enemy target frames for the Ascension Conquest of Azeroth 3.3.5 client.

Version 1.1.1-coa is the tested community release with native Ascension class icons.

## Installation

Extract the `BattlegroundTargets` folder into:

`Interface\\AddOns\\`

Restart the game or use `/reload` **outside** a battleground, then use `/bgt` to configure it.

## CoA compatibility

- Supports Ascension's 21 custom class tokens and uses the colours supplied by the client.
- Supports Ascension's Southshore vs. Tarren Mill battleground.
- Supports the native circular class icons supplied by the Ascension client. Enable **Show Class Icon** in `/bgt`.
- Enemy health changes only when the WoW client learns them (target, focus, mouseover, combat-log information); this is an API limitation.

## Credits and license

Original BattlegroundTargets by kunda. 3.3.5 port by Exad / the BGT-Epoch project. Conquest of Azeroth compatibility package by Airmax & Codex.

Released under GPL-3.0-or-later; see `LICENSE.txt`.
