# Unreal Engine 2 Selection Fixes
Binary fixes for multiple D3DDrv based UE2 editors, to fix the long selection lag on Windows Vista+.

https://github.com/metallicafan212/UE2SelectionFixes/assets/5996243/e9ca7060-47a2-44fd-a36d-5b3d82c35298

## Disclaimer
These binary patches are not associated with OldUnreal.

These patches were created before I became an official OldUnreal developer. They were created through reverse engineering efforts on parts of the renderer and partial game rendering engine (to align function stubs). No technical protection measures were circumvented, and the patch only affects the editor for each game. 

Tools used:

Ghidra

Red Orchestra SDK

Killing Floor SDK

## Supported games
UT2004 3369 RETAIL PATCH ONLY. No binary community patches are supported.

Red Orchestra 3339

Killing Floor 3339

## Known bugs
1. ~~Clicking on text strings in the texture browser and material properties windows clicks random textures. I'm working on this issue, something is off in how it's rendering them in the background.~~ This is fixed with alpha 0.3.
2. Some textures in the texture browser are hard to select (when they have alpha effects or alpha layers). For now, select the black box at the bottom of them. I will fix this in the future.

## Installing
1. Browse the releases section for your game
2. Download the D3DDrv.7z from the release
3. Make a backup of the game's existing D3DDrv.dll
4. Extract the 7z file into the game's System directory

## Code?
Nope, sorry. Lost it in a "boating" accident :)
