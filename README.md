# RTShade
A collection of ReShade ray tracing shader presets, robust against depth buffer related artifacts.

= SUPPORTED GAMES =
- Red Faction Guerilla RE-Mars-tered
- more to come

= INSTALLATION =
1. Download the latest release of this preset collection.
2. From the folder '1. REST', extract the files ReshadeEffectShaderToggler.addon32 and ReshadeEffectShaderToggler.addon64 to the game's folder where the executable file is located that runs the game.
3. From the folder '2. RTShade', open the folder that's named after the game you want to modify and extract the .ini file(s) to the same folder as in the step before.
4. Visit https://reshade.me and download the latest ReShade installation file 'with full add-on support'.
5. Execute the downloaded file and follow the instructions. When asked for a preset file to include, chose an .ini files you just extracted with the exception of ReshadeEffectShaderToggler.ini. If you want to switch between multiple presets while in-game, make sure to select the highest quality preset now; otherwise you might be missing some shaders when switching from a lower quality preset to a higher quality one without installing it via the ReShade install file.
6. Finish up the installation and start the game.

7. (Optional) For a substancial performance uplift toggle the ReShade UI (pressing the 'Home' button) and tick the box 'Performance Mode' in the bottom-right corner.

= FAQ =

Q: I'm switching between presets but there is not much visual change. Are shaders missing?

A: Most likely. Re-install the highest-quality preset file via the 'ReShade_Setup.exe". Make sure to do so with every game in which you want to switch between RTShade presets while in-game.

Q: ReShade doesn't launch when I start my game.

A: Hit 'Ctrl + Alt + Del', switch to 'Details' and find the game's executable file. Sometimes the game's true executable is called something like 'Game-Win64-Shipping.exe' instead of which file you chose when installing ReShade to the game's main folder. Right-click the process and click again on 'Open File Location'. Now that you know the true .exe's folder, repeat the installation steps above chosing this file as target for the install instructions instead. For further help consult https://www.pcgamingwiki.com/wiki/ReShade#Common_fixes.
