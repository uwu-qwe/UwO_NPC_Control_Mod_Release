# UwO_NPC_Control_Mod_Release
![Image](https://github.com/user-attachments/assets/08d45935-cc40-4e98-8c3d-10340d686933)

**It is assumed that you have BepInEx 5.4.22 installed to use this.**

**This plugin can only be used in singleplayer!**

## Features
• Able to select NPCs by looking at them.  
• Able to select multiple NPCs at time.  
• Able to move NPC hips and/or head.  
• A set of NPC movement types to choose from.

The menu window can be dragged around the screen to be somewhere else. The window position will be saved upon closing the game, so it'll be in the same place next time.

## Installation if BepInEx IS NOT installed (Includes BepInEx installation)
1. Unpack the contents of `Bepin NPC Control.7z` into your KoboldKare game folder (where the .exe is).
2. Run the game and it should work!

## Installation if BepInEx IS installed
1. Ensure you have the Dlltouse folder in your KoboldKare game folder (can be found in `Bepin NPC Control.7z`).
2. Put the `UwO_NPC_Control_Mod.dll` in the plugins folder (Should be in `KoboldKare\BepInEx\plugins`).
3. Run the game and it should work!

## How to use
Press `F9` (default, can be changed) to show/hide the menu. You can drag it wherever you want on the screen and it'll remember the position for next time you boot up the game.

Open up the menu and look at (ideally) the neck of the NPC with your crosshair and select the NPC via the shortcut.
When you've selected an animation type for either hips or head, you can then start the NPC animation via the shortcut.
You **must** reset the NPC animation if you want to make changes to it. So you first start, see if there's anything you'd like to change, and then you can reset and do your adjustments.
Rinse and repeat. You can deselect and NPC if you don't want to do any changes to them and they'll be kept in that state indefinitely until you select them again and start doing changes.

## Configuration & Default Shortcuts
Selecting an NPC: `RightControl + I`  
Deselecting an NPC: `RightControl + O`  
Deselecting all NPCs: `RightControl + K`  
Starting NPC animation: `RightControl + P`  
Resetting NPC animation: `RightControl + L`

These shortcuts can be configured in `\KoboldKare\BepInEx\config\UwO_NPC_Control_Mod.cfg` after running the game once with my plugin.
