# Archived, use NotFine or Angelica instead
This project is archived.
This project is included in both [NotFine](https://github.com/jss2a98aj/NotFine) and [Angelica](https://github.com/GTNewHorizons/Angelica).
For both integration is still wip, I will update this README a final time once integration is stable.
If you only want the CIT features while still being able to use fastcraft and optifine use [HowardZHY's CIT only fork](https://github.com/HowardZHY/MCPatcherForge)

MCPatcher as a 1.7.10 forge mod using Mixins.
[Original repo](https://bitbucket.org/prupe/mcpatcher/src/master/)

[Original wiki](https://bitbucket.org/prupe/mcpatcher/wiki/Home)

Original source code is under MIT, my changes are lgpl 3.0

Includes default glass & bookshelves connected textures by DarkBum under CC-BY-SA

End goal is to support any resource pack for 1.7.10 that used Optifines version of MCPatcher features
# Disclaimer

Not all features are working yet, if you find issues feel free to report, but it might take a while before I get around to it.

Known incompatibilities:
- FastCraft, causes weird chunk flickering on loading (no fix planned)
- Future commands, something happens between its asm and my asm/mixins. No fix planned as I can't find the source code
- Optifine: Implements the same features, resulting in a crash on startup (no fix planned)
- FalseTweaks: Will need looking into
