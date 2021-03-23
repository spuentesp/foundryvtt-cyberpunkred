
# CPRED V2

Taking the original cyberpunkred module from Gerdofal, i've added some small updates and edited the color scheme, also applying some css extras.
This is as much as a work in progres as Gerdofal's project, taking into account some much needed stuff for our game group.

# Branch Information

stable_release:
  - This is the primary branch linked into the foundry and the only branch that can be installed automatically
  - This branch is the branch that should be linked in the system.json for all branches, to make sure that innatentive users don't accidentally download another branch.
  
development:
  - This is the branch undergoing active development. Issue fixes should be pushed here.
  - You should generally not use the development branch for games as it may have significant bugs.
  
ui_and_data_update:
  - This branch is intended for an upcoming UI and data model re-design.
  - This branch should generally only be used for that project. Issue fixes do not go here.

# Installing

- This system is available in the "Game-systems" browser in-game and may be installed there.

- You can also manually direct your FoundryVTT to the correct manifest. Use this as the manifest URL:
  - https://raw.githubusercontent.com/spuentesp/foundryvtt-cyberpunkred/stable_release/system.json
- If you want to manually install the files from the development branch, feel free. Just download the zip and install manually. I don't recommend this for anything other than testing as the development branch is sometimes non-functional.

# Suggestions

If you wish to make suggestions, please submit issues on the Github issue tracker or send me a message.

# General Design Plans

So far, we have added:
-Armor as items. You can use them in the combat tab.
-Cyberware now with type! now all your cyberware will be listed and ordered by their body location or type...

# License and Credits

License:
https://github.com/Gerdofal/foundryvtt-cyberpunkred/blob/development/license.md

Credits:
https://github.com/Gerdofal/foundryvtt-cyberpunkred/blob/development/credits.md

