| Waterfall Nations wiki | [Home](index.md) | [Slimefun](slimefun/index.md) | [Brewery](brewery/index.md) |
|:---|:-:|:-:|:-:|

<div align="center">
  
Features
======================================
</div>

This article serves as a more comprehensive list of gameplay changing plugins and datapacks installed on the server, please navigate to
each individual section to find out more about each feature.

## Resource World

Resource World is a plugin (or rather a server) which has a world that resets every week, with the sole purpose of being harvested for any
and all resources you may need without having to destroy your home world. Building stuff is not recommended since it will reset.

To access the Resource World, simply type `/resourceworld` in chat, then go through the portal, and when you spawn in the hub, go through
the water portal at the end.

## Terralith (World Generation)

Terralith is a small datapack that adds a plethora of new biomes, and overhauls world generation making for some pretty picturesque
environments, such as sakura groves, floating skylands, mirage isles, the list goes on, jump in and start exploring for a taster of
what Terralith truly has to offer.

![Some Terralith Biomes](null)
![More Terralith Biomes](null)

### Terralith Continents

On [Onex](onex.md) an expansion of Terralith called Continents is also used, this makes landmasses and oceans much larger, as well as
making ocean monuments and floating skylands a much more common sight.

## Indendium

From the same family as Terralith, Incendium similarly modifies the world generation of the nether, as well as adding extra biomes, 
structures, bosses and more, which make the nether a bit more challenging, but much more rewarding.

![An Incendium Structure](null)

## Nullscape

Nullscape, also from the Terralith family of datapacks, adds more biomes and revamps the end, and while not adding any bonus structures,
it does make navigating the end a much more interesting experience.

![A Custom Nullscape Biome](null)

## Structory 

This is another datapack from the Terralith family which focuses on adding more structures (with slight lore) to the overworld, with
some interesting loot.

![A Structory Structure](null)

## [Slimefun](slimefun/index.md)

Slimefun is a plugin that adds a ton of new gameplay elements and mechanics, all while not requiring any client-side mods, from fruit trees,
to repairing spawners, fancy armour to repairable spawners, nuclear power and huge storage containers, if you can think of it, chances are,
slimefun does it. In fact, it has so many of these elements that it actually has [its own page](slimefun/index.md) on this wiki.

## Safari Nets

A simple plugin that will make your life so much easier, if you've ever played vanilla, you'll know the pains of transporting villagers and
other mobs for your automatic farms or trading halls, well with this plugin you can say goodbye to investing hundreds of iron ingots into
rails and minecarts. With Safari Nets, you can capture mobs in one place and keep them in your inventory until you need them again, and the 
recipes are pretty straightforward too:

### Recipes

| Normal Safari Net | Reusable Safari Net |
| :-: | :-: |
| ![Normal Safari Net crafting recipe](null) | ![Reusable Safari Net crafting recipe](null) |

### Special Cases

Certain mobs have a lower catch chance including: Warden (10%), Wither (10%), Piglin Brute (20%), Elder Guardian (20%), Evoker (30%). This is to make the game a little more exciting and fair.

## Crafting Recipe Tweaks

We also have a few quality of life crafting recipe tweaks which will make your life a lot easier:

**TBC**

## Lands

To stop other people griefing your base, going through your storage, or even leaving nasty surprises, there is a land claiming plugin
installed.

### Commands 

| Command | Description |
|:- |:- |
| **`/lands create <land name>`** | Creates a land with the name `<land name>` |
| **`/lands trust <player name>`** | Sends an invite to `<player name>` to join your land |
| **`/lands menu`** | Opens the land configuration menu (Chest GUI) |
| **`/lands edit <land name>`** | Enters edit mode for land with name `<land name>` (if you have permission) |
| **`/lands selection`** | Allows you to create a selection using the selection tool |
| `/lands selection expand` | Expands the current selection to take all vertical space (only applies to subareas) |
| **`/lands claim`** | Claims the current chunk you're standing in or the current selection |
| **`/lands unclaim`** | Unclaims the chunk the chunk you're standing in or the current selection |
| `/lands assign` | Assigns the current selection to the specified subarea in your land |

## Teleportation Commands

To make getting around a little easier, the server implements a few teleportation systems, namely homes, warps and tpa.
There is a limit to how many homes you can set (currently 2).

| Command | Description |
| :- | :- |
| **TPA** | |
| **`/tpa <player name>`** | Sends a teleport request to `<player name>` |
| | This request can either be accepted using the in chat prompt or: |
| `/tpaccept` | Accepts the current teleport reqeuest |
| `/tpdeny` | Denies the current teleport request |
| **Homes** | |
| **`/sethome <home name>`** | Creates a home with name `home name`, if it already exists you will be prompted whether you want to overwrite it |
| **`/home [home name]`** | Teleports to home with specified name (if provided), if multiple homes are set and no name is provided, this opens the same menu as `/homes` |
| `/homes` | Opens the homes menu (Chest GUI) |
| `/removehome <home name>` | Deletes a home with specified name |
| **Warps**| |
| **`/hub`** | Teleports you to the current world's hub (or spawn) |
| | **Note:** In the resource world, this opens a menu, to circumvent this and go directly to resource world hub, run **`/warp rwhub`** |
| **`/resourceworld`** | Teleports you next to the resource world portal in your world |
