# cobalt2-jetbrains-material-theme

It's an adopted to looks of Wes Bos'es theme cobalt 2 custom theme for JetBrains IDE with material-theme plugin
along with the Cobalt 2 Color Scheme adopted by me.

## What is done

Material theme is almost perfect. Not much of the fields, so it was easy.

Cobalt 2 color scheme may be imperfect for other languages like Java etc. Cause I'm mostly using Javascript nowadays, feel free to contribute.
Color scheme is based on this [cobalt2 for JetBrains](https://github.com/ngehlert/cobalt2) which has a "touch" of an
author and doesn't 100% match original cobalt2 color palette, I tried to fix that, but still imperfections may be there.

## Installation

### Material scheme:

Follow this link to get config path for your OS [Directories used by the IDE to store settings, caches, plugins and logs](https://intellij-support.jetbrains.com/hc/en-us/articles/206544519-Directories-used-by-the-IDE-to-store-settings-caches-plugins-and-logs)

- Get to the config path and `options` folder. For Mac OS e.g.
  `/Users/<USER_NAME>/Library/Preferences/<JET_BRAINS_IDE_VERSION>/options`
- paste `material_custom_theme.xml` for only custom theme colors
  (you will need to change to custom theme in preferences of material-plugin)
- paste `material_theme.xml` if you would like to switch on all other
  settings that I think match the theme the most.
  Also it will switch on custom theme mode for you.

### Color scheme:

Preferences -> Color Scheme -> Settings (Gear-Wheel) --> Import Scheme

and simply import the .icls file.

## Helpful links

[Cobalt 2 theme](https://github.com/wesbos/cobalt2)  
[Cobalt 2 VS Code](https://github.com/wesbos/cobalt2-vscode) - these colors was used for IDE looks.  
[Matherial Theme Jetbrains plugin](https://github.com/ChrisRM/material-theme-jetbrains)

## Contributions

Feel free to fix and modify this Color Scheme along with Theme for Material Plugin. Will be glad to
review and merge it.
