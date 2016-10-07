# HaxDig

Pure fun and modern alternative to Big Dig.


This modpack cannot be distributed from other than the Technic platform without permission from me.

## Structure
- **bin**
  - This folder is used for the patches that will be merged into the client JAR. Should be for client base mods and FML.
- **mods**
  - Pretty self-explanatory. Contains mods; may contain coremods in later versions of Forge/FML.
- **config**
  - Mod configurations are to be placed here. (USUALLY) Some may be placed in seperate locations depending on the mod.
- **target** (excluded from target zip)
  - Every commit requires a build of HaxDig, by building and compressing **bin, config, mods**.