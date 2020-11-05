# Mindustry Mod - Armored Basic Conveyor

This is a mod for the Anuke's **Mindustry** game. **Please be aware this mod is still a work in progress!** Turns out the modding API for the game was way more lacking, than it initially appeared. To make even something as simple, as a slightly modified conveyor belt, I am being forced to fish out the working `.json` properties straight from the game's code. *There are no lists of available properties and their values!*

Mindustry is a sandbox resource management game, spiced with tower defense and RTS mechanics. It's a great game and a lot of fun, definitely check it out on [Steam](https://store.steampowered.com/app/1127400/Mindustry/).

Also check its source code (and readme!) on [GitHub](https://github.com/Anuken/Mindustry).

## About

Armored conveyor is a simple mod that adds exactly one block to the game - Armored Basic Conveyor. Much like its mid-to-late-game cousin, the Armored Conveyor, this conveyor belt sports not just better durability - but most importantly - **doesn't accept any items from the sides, except from other conveyor belts**.

### Why?

This mod exists because... I believe this item is essential for building more complex conveyor nets and is missing in the early campaign (before appropriate research), as well as early game (before fabricating Plastanium).

### Why does this mod contain only a single block?

The focus of this mod is conveyor network management, rather than frontline fortification (there are already conveyor belts for that in the vanilla game). I haven't thought of any other block in this category (distribution network quality of life changes, not distribution network fortification) that would deserve adding (yet). Let's be honest, the base game has done a pretty good job in this.

## Supported game versions

The mod has been tested with the game version 5, release `104.6`. For the minimum game version, see [mod's main file](mod.json) in detail.

## Installation

### Via a GitHub repository link

In the game's title screen, navigate to **Mods**, click the **Import GitHub Mod** button, paste `martycagas/mindustry-mod-armored-conveyor` there, then click **OK**.

### Via importing a ZIP file

Download this repository as a ZIP file by clicking the green **Code** button in the top right of the repository page and select **Download ZIP**. In the game's title screen, navigate to **Mods** and click the **Import Mod** button. Select the downloaded repository's ZIP file anywhere in the filesystem.

### Via extracting the ZIP file into the game's mod folder

Download this repository as a ZIP file by clicking the green **Code** button in the top right of the repository page and select **Download ZIP**. Extract the downloaded ZIP file directly into the Mindustry's mod folder that can be find in the game files under `Mindustry/saves/mods`.

## Contributing

For information on how to expand this mod, see [CONTRIBUTING](CONTRIBUTING.md).

## Licensing

This mod is licensed under GPL-3.0, for further details, see [LICENSE](LICENSE). The General Public License was chosen to satisfy the license requirement of the original sprites used in this mod.
