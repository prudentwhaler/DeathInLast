# DeathInLast

A [Steamodded](https://github.com/Steamodded/smods) mod for Balatro that reverses the ordering of Death's conversion: the **right** card is converted into the **left** card.

By Virtualized and BaconIsBets.

## Requirements

- [Steamodded](https://github.com/Steamodded/smods) >= 1.0.0~BETA-1016c
- [Lovely](https://github.com/ethangreen-dev/lovely-injector) >= 0.8

## Installation

Copy the `DeathInLast` folder into your Balatro `Mods` directory:

- Windows: `%AppData%/Balatro/Mods`
- macOS: `~/Library/Application Support/Balatro/Mods`

## Structure

```
DeathInLast/
├── DeathInLast.json        # mod metadata
├── core.lua                # overrides Death's use effect
└── localization/en-us.lua  # updated Death description
```
