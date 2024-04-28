# Grime.ModdingTools
## Installation

In order to play with mods, install the modding tools by following these steps:

1. Click the download link to get the modding tools for your operating system. Currently only Windows is supported.
  * [Windows](https://github.com/BadMagic100/Grime.ModdingTools/raw/main/Grime.ModdingTools-win64.zip)
2. Extract the files into the game's root directory. Usually it will be the following, based on where you purchased the game
  * Steam: `C:\Program Files\Steam\steamapps\common\GRIME`
  * Epic: idk is this game even on epic

Mods can be installed into the `Mods` folder.

## Mod development

You can change the config values in `doorstop_config.ini` to enable a debugger, and in `BepInEx/config/BepInEx.cfg` to enable the logging terminal.

Mod development is pretty standard BepInEx 5 stuff. There is a [templates package](https://www.nuget.org/packages/Grime.Modding.Templates) specific to GRIME
which can simplify setup.
