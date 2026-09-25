# Era Great People

A small Unciv extension mod that changes Great Person generation by era.

## Rule

Ancient era: x1 (vanilla rate)

Classical era: x2

Medieval era: x4

Renaissance era: x8

Industrial era: x16

Modern era: x32

Atomic era: x64

Information era: x128

Future era: x256

The mod changes Great Person generation, not the underlying Great Person cost/threshold.

## Installation

For a local/manual installation, place the `Era-Great-People` folder inside Unciv's `mods` directory so that the following file exists:

`mods/Era-Great-People/jsons/GlobalUniques.json`

Then enable the mod when creating a new game.

## Implementation

The mod uses Unciv's global `Great Person generation` Unique together with era conditionals. Only one era-specific multiplier is active at a time, so the intended x2-per-era progression does not depend on stacking several era bonuses.

## Version

0.1.0 - first playable prototype
