## Overview

This is an IPS patch for Pokemon Fire Red that removes in-game music. It's useful for players who like to play their own music, espeically during grind-heavy challenges like IronMON.

Note that fanfares from getting items, etc. still play. If there is demand for a variant that removes those as well, I will include that in future releases.

The patch is designed to be as minimal as possible, only adjusting a few bytes in the music routines without affecting any other data or offsets. This means applying this patch first, before any other patches, should be totally safe and maintain compatibility with other patches.

## Installation

Use an IPS patcher, such as [this one](https://www.marcrobledo.com/RomPatcher.js/).

Ensure you apply the IPS file that matches your game version—it's either v1.0 or v1.1.

The `disable_bgm` patch disables the music, and the `disable_low_hp_sfx` patch disables the low HP SFX during battles. You can apply either patch separately, or both of them together.

## Issues

Feel free to report issues in the issue tracker, such as if this patch fails to remove a song in a specific unique situation.
