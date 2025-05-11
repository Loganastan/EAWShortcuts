# Empire at War Custom Mod Launcher Setup

This guide provides a quick walkthrough for setting up custom launchers for your favorite Steam mods with *Star Wars: Empire at War*. This approach gives you easy, one-click access to your modded games without needing to adjust launch parameters each time in Steam.

## Prerequisites

Before proceeding, **clear any existing launch options** from your game's properties in Steam. Leaving old parameters can cause conflicts or unexpected behavior.

## Steps to Create Custom Mod Shortcuts

1. **Locate the Game Executable**

   * Open your Steam library and select *Star Wars: Empire at War*.
   * Right-click the game and select **Properties**.
   * Navigate to **Installed Files** > **Browse**.
   * Open the **corruption** folder.
   * Copy the full path to **swfoc.exe**. It should look something like:

     ```
     F:\SteamLibrary\steamapps\common\Star Wars Empire at War\corruption\swfoc.exe
     ```

2. **Gather Mod IDs**

   * You will need the Steam Workshop IDs for each mod you want to create a shortcut for:

     * Thrawn's Revenge: `STEAMMOD=1125571106`
     * Fall of the Republic: `STEAMMOD=1976399102`
     * Revan's Revenge: `STEAMMOD=3417277973`

3. **Create the Shortcut**

   * For each mod:

     1. Create the launch path by combining the game executable path and mod ID:

        ```
        "F:\SteamLibrary\steamapps\common\Star Wars Empire at War\corruption\swfoc.exe" STEAMMOD=1125571106
        ```
     2. Right-click on your desktop and select **New** > **Shortcut**.
     3. Paste the launch path from the previous step into the location field.
     4. Name your shortcut (e.g., *Thrawn's Revenge*) and click **Save**.

4. **Customize the Shortcut Icon (Optional)**

   * To give your shortcut a custom icon:

     1. Right-click the newly created shortcut and select **Properties**.
     2. Click **Change Icon**.
     3. Browse to your icon file (e.g., from this pack or a custom image).
     4. Select your icon and save the changes.

5. **Multiple Mods (Advanced)**

   * To run multiple mods simultaneously, simply add additional mod IDs, separated by spaces, just like in the Steam launch options.

6. **Test and Enjoy!**

   * Double-check your paths and IDs, then test your new shortcuts to ensure everything is working as expected.

---

Feel free to adjust these instructions based on your installation path or preferred mod configurations. Happy modding!
