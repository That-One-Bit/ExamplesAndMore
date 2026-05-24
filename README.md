# LunaCore
LunaCore is a work in progress script loader for Minecraft: New Nintendo 3DS Edition, featuring an easy API interface to interact with the game. You can check api_docs.md for an introduction on basic usage of the API. LunaCore is a combination of efforts made by the community, the most notable being STBrian, Cracko, and many others. To see more information, check out the contributors section below.

This plugin runs alongside the game thanks to Luma3DS plugin loader and is built using CTRPluginFramework which provides the essentials to work together with the game. The script engine uses Lua 5.1 as scripting language, an easy language to use with a lot of possibilities. It was also chosen because of its easy implementation in embedded systems, for its powerful C API and for being lightweight.

This repository contains example mods seperated into folders for easy searching, some being used for learning purposes and others for in-game use. All scripts/mods are made by me, but are able to be freely edited and modified. Thanks to STBrian, Cracko298, Wyndchime, and RaiRai for the motivation to make these examples, and for figuring out how to make this possible.

## How to install
### A. All-In-One
Download the latest `.zip` file from the releases page, and extract the `Minecraft 3ds` folder to the root of your SD card. The root is the highest folder of the SD card, and will be the default directory for most file managers. Every script/mod will be available ingame, and will be able to be toggled freely unless stated otherwise.Make sure to use the latest version of Luma3DS (Or any of its forks matching the latest version) and that the Plugin Loader is enabled in the Rosalina Menu to ensure maximum compatibility.

### B. Individual Script(s)/Mod(s)
Download the individual scripts/mods from the filetree, and locate the root folder of your SD card. The root is the highest folder of the SD card, and will be the default directory for most file managers. If not already existing, make a folder titled `Minecraft 3ds` on the root, along with a `scripts` and `mods` folder inside the `Minecraft 3ds` folder. The script(s)/mod(s) will be avaiilable ingame, and will be able to be toggled freely unless stated otherwise. Make sure to use the latest version of Luma3DS (Or any of its forks matching the latest version) and that the Plugin Loader is enabled in the Rosalina Menu to ensure maximum compatibility.

## Credits and Contributions
LunaCore wouldn't be possible without the contributions made to the Minecraft: New Nintendo 3DS Edition community and homebrew libraries. Credits to the authors and sources that are part of LunaCore are shown below. The examples featured here wouldn't be made unless these people did the work they did.

| Components | Module | Thanks to |
| --- | --- | --- | 
| SwimSpeed, ReachDistance | Game.LocalPlayer | [Minecraft-3DS-Community/GamePatches](https://github.com/Minecraft-3DS-Community/GamePatches) |
| OnGround, Sneaking, Jumping, Sprinting, Flying, UnderWater, TouchingWall, Invincible, CanFly, CanConsumeItems, BaseMoveSpeed, MoveSpeed, FlySpeed, CurrentHP, MaxHP, CurrentHunger, MaxHunger, CurrentLevel, LevelProgress, Gamemode, SprintDelay, Position, Velocity | Game.LocalPlayer | `Minecraft Class v1.1` by `Discord: @rairai6895` |
| All fields | Game.LocalPlayer.Inventory | `Minecraft Class v1.1` by `Discord: @rairai6895` |
| All fields, FOV (Player camera) | Game.LocalPlayer.Camera | `Minecraft Class v1.1` by `Discord: @rairai6895` |
| FOV (Item frame) | Game.LocalPlayer.Camera | [Minecraft-3DS-Community/GamePatches](https://github.com/Minecraft-3DS-Community/GamePatches) |
| CloudsHeight | Game.World | [Minecraft-3DS-Community/GamePatches](https://github.com/Minecraft-3DS-Community/GamePatches) |
| Raining, Thunderstorm | Game.World | `Minecraft Class v1.1` by `Discord: @rairai6895` |
| Items offsets | Game.Items | `Minecraft Class v1.1` by `Discord: @rairai6895` |

### Special thanks
- `Discord: @rairai6895` - Made `Minecraft Class v1.1` (you can join [Asterium Discord](https://discord.gg/MXFfpyEk) server for more information)
- [@Cracko298](https://github.com/Cracko298) - Contributed to [Minecraft-3DS-Community/GamePatches](https://github.com/Minecraft-3DS-Community/GamePatches)
- [CTRPluginFramework](https://gitlab.com/thepixellizeross/ctrpluginframework) - Plugin essentials
- [Luma3DS](https:/github.com/LumaTeam/Luma3DS) - Plugin loader
- [devkitPro](https://github.com/devkitPro) - ctrulib and development environment
- [FsLib](https://github.com/J-D-K/FsLib) - Used for file handlers
- [libffi](https://github.com/libffi/libffi) - Used as interface to define c functions calls from Core API
- Lua - Scripting language (5.1)
- [LunaCore](https://github.com/STBrian/Lunacore)
