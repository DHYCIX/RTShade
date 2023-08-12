# RTShade
A collection of ReShade ray tracing shader presets, robust against depth buffer related artifacts.

## Main Features
All presets come ray tracing enabled with pre-configured measures to combat artifacts like ambient occlusion or global illumination "shining through" fog, menus etc.

Here is an example of [Fighting Fog with RTShade](https://imgsli.com/MTk3OTkz).

> [!NOTE]
> The Ultra preset is WIP.

## Shaders Used
RTShade presets come with a multitude of varying shaders, all configured to be very close to the tone of the original un-modded game while enhancing it with features fit for a remastered experience. No Film Grain, no Chromatic Abberation, no Vignette, no Motion Blur.

Some of the most heavily utilized visual shaders:
- DH_Uber_RT
- iMMERSE (MXAO, SMAA, Sharpen)
- qUINT DoF

## Supported Games
### [Red Faction Guerilla (+ RE-Mars-tered)](https://imgsli.com/MTk4MDAw)

### Tomb Raider (2013) (WIP)

## Installation
1. Download the latest release of this preset collection.
2. From the folder '1. REST', extract the files ReshadeEffectShaderToggler.addon32 and ReshadeEffectShaderToggler.addon64 to the game's folder where the executable file is located that runs the game.
3. From the folder '2. RTShade', open the folder that's named after the game you want to modify and extract the .ini file(s) to the same folder as in the step before.
4. Visit https://reshade.me and download the latest ReShade installation file 'with full add-on support'.
5. Execute the downloaded file and follow the instructions. When asked for a preset file to include, chose an .ini files you just extracted with the exception of ReshadeEffectShaderToggler.ini.
> [!IMPORTANT]
> If you want to switch between multiple presets while in-game, make sure to select the highest quality preset now; otherwise you might be missing some shaders when switching from a lower quality preset to a higher quality one without installing it via the ReShade install file.
6. Finish up the installation and start the game.

> [!NOTE]
> For a substancial performance uplift toggle the ReShade UI (pressing the 'Home' button) and tick the box 'Performance Mode' in the bottom-right corner.

## FAQ

> I'm switching between presets but there is not much visual change. Are shaders missing?

Most likely. Re-install the highest-quality preset file via the 'ReShade_Setup.exe'. Make sure to do so with every game in which you want to switch between RTShade presets while in-game.

> Your presets look really ugly. Have they always been this way?

Yes... (╥﹏╥)

Try reloading ReShade by pressing the big button in the bottom-center of the UI. Sometimes certain shader combinations (even disabled ones) can trigger unwanted behavior. Make sure to also tick the box 'Load only enabled effects' in the 'Settings' tab. If that's still not it, some shaders might've had been updated and work differently now than when I created the specific presets. If nothing helps, open an issue ticket and let me know so I can try and fix it.

> ReShade doesn't launch when I start my game.

Hit 'Ctrl + Alt + Del', switch to 'Details' and find the game's executable file. Sometimes the game's true executable is called something like 'Game-Win64-Shipping.exe' instead of which file you chose when installing ReShade to the game's main folder. Right-click the process and click again on 'Open File Location'. Now that you know the true .exe's folder, repeat the installation steps above chosing this file as target for the install instructions instead. For further help consult https://www.pcgamingwiki.com/wiki/ReShade#Common_fixes.
