# Mindustry Mod - Armored Basic Conveyor

This is a mod for the Anuke's **Mindustry** game. Mindustry is a sandbox resource management game, spiced with tower defense and RTS mechanics. It's a great game and a lot of fun, definitely check it out on [Steam](https://store.steampowered.com/app/1127400/Mindustry/).

Also check its source code (and readme!) on [GitHub](https://github.com/Anuken/Mindustry).

## About

Armored Basic Conveyor is a simple mod that adds two new early-game blocks to both Survival and Campaign - the **Armored Basic Conveyor** and the **Plated Basic Conduit**. Much like their mid-to-late-game counterparts, these blocks don't feature just better durability - but most importantly - **they don't accept any inputs from the sides, except from other conveyors/conduits**. The Plated Basic Conduit also doesn't leak.

## Blocks

### ![Armored Basic Conveyor](docs/img/block-armored-basic-conveyor.png) **Armored Basic Conveyor**

Features better armor than its standard counterpart. Does not accept any items from the sides, except from other conveyors.

| Property      | Value                                  |
| ------------- | -------------------------------------- |
| **General**   |                                        |
| Health        | 110                                    |
| Size          | 1x1                                    |
| Build Time    | 0.03 second                            |
| Build Cost    | ![copper](docs/img/item-copper.png) x1 |
|               | ![lead](docs/img/item-lead.png) x2     |
| **Items**     |                                        |
| Item Capacity | 4 items                                |
| Move Speed    | 4.1 items/second                       |

### ![Plated Basic Conduit](docs/img/block-plated-basic-conduit.png) **Plated Basic Conduit**

Features better armor than its standard counterpart. Does not accept any input from the sides, except from other conduits. Does not leak.

| Property        | Value                                        |
| --------------- | -------------------------------------------- |
| **General**     |                                              |
| Health          | 130                                          |
| Size            | 1x1                                          |
| Build Time      | 0.03 second                                  |
| Build Cost      | ![lead](docs/img/item-lead.png) x1           |
|                 | ![metaglass](docs/img/item-metaglass.png) x1 |
| **Liquids**     |                                              |
| Liquid Capacity | 10 liquid units                              |

## Supported game versions

The mod has been tested with the game version 6, release `105` and up.

## Installation

### Via a GitHub repository link

In the game's title screen, navigate to **Mods**, click the **Import GitHub Mod** button, paste `martycagas/mindustry-mod-armored-conveyor` there, then click **OK**.

### Via importing a ZIP file

Download this repository as a ZIP file by clicking the green **Code** button in the top right of the repository page and select **Download ZIP**. In the game's title screen, navigate to **Mods** and click the **Import Mod** button. Select the downloaded repository's ZIP file anywhere in the filesystem.

### Via extracting the ZIP file into the game's mod folder

Download this repository as a ZIP file by clicking the green **Code** button in the top right of the repository page and select **Download ZIP**. Extract the downloaded ZIP file directly into the Mindustry's mod folder, which can be found by default in following locations, depending on your operating system:

- Windows: `%APPDATA%\Mindustry\saves\mods\`
- Windows (Steam version): `C:\Program Files (x86)\Steam\steamapps\common\Mindustry\saves\mods\`
- Linux: `~/.local/share/Mindustry/saves/mods/`
- MacOS: `~/Library/Application Support/Mindustry/saves/mods/`

**"These locations differ from those on the official wiki?"**

Yes, that is because I just checked the actual location for the Windows Steam version. Cannot vouch for the rest, though I assume they will follow the same directory structure. The wiki might need an update.

## Contributing

For information on how to expand this mod, see [CONTRIBUTING](CONTRIBUTING.md).

## Licensing

This mod is licensed under GPL-3.0, for further details, see [LICENSE](LICENSE). The General Public License was chosen to satisfy the license requirement of the original sprites used in this mod.
