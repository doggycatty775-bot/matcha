MATCHA - LATEST COMPLETE SCRIPT

Files
- Matcha_Settings.lua: the complete updated script, not a patch.

Included additions
- Saved-config dropdown and Selected indicator.
- Save, overwrite, load, delete, and refresh configs.
- Auto-load selection and status; disabling auto-load.
- Deleting the auto-load config clears its auto-load selection.
- UI background, main, accent, outline, and text colors/themes.
- Delete key to hide or reopen the menu.
- Unload UI / Script in Settings with tracked-resource cleanup.
- Top-right Close and Minimize buttons removed.
- Existing script loader buttons retained.

Using configs
1. Adjust settings, enter a new config name, and press Save Config.
2. Choose a saved config from the list, then press Load Config.
3. Press Auto Load Config to use that selection when this script starts.
4. Select a config and press Delete Config to remove its saved file.
Deleting a config does not reset settings already applied in the current session.
Save or overwrite your config after changing UI colors to keep them.

Menu controls
Delete hides/shows the menu. Unload UI / Script stops this script's tracked
activity and closes the menu. Run the script again to use it after unloading.

Requirements and limits
Config storage requires the environment's file-storage functions; deletion
also requires delfile. Auto-load happens when the script runs, not simply
when joining a game without running it.
The script still downloads its UI libraries and external loaders from the
internet. Their source code is not bundled here. External scripts may need
their own unload controls. Some game changes may require rejoining.
Shutdown logic passed isolated simulated tests; full Roblox behavior has
not been verified.

GitHub upload
Upload Matcha_Settings.lua, not this ZIP, to your repository. Open the file,
click Raw, and use the verified raw URL in your loader. The repository URL
previously supplied returned 404 during checks, so no verified online loader
is included. The script contains loader keys; remove any private keys before
publishing it publicly.