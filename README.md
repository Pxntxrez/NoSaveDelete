# No Save Delete
A mod for R.E.P.O that prevents the game from deleting save files upon player death, ensuring your progress is always safe.  

## Description
No Save Delete gives you control over how saves are managed in R.E.P.O. By default, the game deletes your save file when you die, but with this mod, you can prevent that from happening and even automatically reload your last save after death.

## Features
- **Prevent Game Save Deletion:** Stops the game from deleting saves after death.
- **Manual Save Deletion:** Optionally allow the player to delete saves through the menu if desired.
- **Automatic Save Reloading:** Automatically loads the last save file when the player dies, if enabled.
- **Configurable Settings:** All features can be toggled on or off via the configuration file.

## Showcase

`Base Game (Default)`
![Base](https://github.com/user-attachments/assets/f6d3bdd8-1b98-4f77-abbe-4576f712cdc0)

`With Mod`
![Mod](https://github.com/user-attachments/assets/7e549fd7-ea0f-44ab-aa53-2cc960a05ad6)

## Installation
1. Install [BepInEx](https://github.com/BepInEx/BepInEx/releases/tag/v5.4.23.2) (v5.x) for R.E.P.O.
2. Place the `NoSaveDelete.dll` file in the `BepInEx/plugins` folder.
3. Launch the game to generate the configuration file at:  
   `BepInEx/config/com.pxntxrez.nosavedelete.cfg`

## Configuration Options
Located in `BepInEx/config/com.pxntxrez.nosavedelete.cfg`
- `AllowPlayerDelete (true/false)` – Allow the player to delete saves manually. (Default: true)
- `AllowGameDelete (true/false)` – Allow the game to delete saves. (Default: false)
- `AutoLoadOnDeath (true/false)` – Automatically reload the last save upon death. (Default: true)

## Important Notes
- ❌ **Multiplayer Compatibility:** This mod has NOT been tested in multiplayer mode.  
- 🔄 **Future Updates:** Compatibility with multiplayer will be addressed in upcoming updates. Stay tuned!
