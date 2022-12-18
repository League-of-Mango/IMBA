# Inter Mango's Bizarre Adventure
## A Modpack for 1.18

Maintained by KennyHammerspike and SirSloppiness:\
**KennyHammerspike#9443** and
**The Ultimate Sandwich#9622** on Discord

## Modpack Description
A kitchen sink semi-expert style modpack aimed to be accessible for those who are new to modded Minecraft while still providing expert-style gameplay for veteran players.

There will be quests to guide players through mod progression and highlight interesting tools. There will also be many recipes and processes that will require the utilization of multiple mods.

Two versions of the modpack will exist: **[Premium Edition](https://github.com/KennyN-UCSD/Inter-Mango-Bizarre-Adventure/blob/main/Inter%20Mangos%20Bizarre%20Adventure-0.3.2.zip)** and **Potato Edition**.

The **Premium Edition** features many mods which enhance graphics and add extra flavor to the game.\
This edition comes with [Complementary Shaders](https://www.complementary.dev) pre-installed, which are designed to look fantastic while still being compatible with modded Minecraft.

The **Potato Edition** does not contain these extras mods as well as some mods that would be useful in a singleplayer world to minimize necessary content. Preset options are also included to optimize the game immediately.

The modpack is still in development and many more additions are to be made.


## Installation
1. Install the latest version of either the **[Premium](https://github.com/KennyN-UCSD/Inter-Mango-Bizarre-Adventure/blob/main/Inter%20Mangos%20Bizarre%20Adventure-0.3.2.zip)** or **Potato** edition of **Inter Mango's Bizarre Adventure**.
2. Install **[PrismLauncher](https://github.com/PrismLauncher/PrismLauncher/releases/tag/5.0)**. PrismLauncher is a lightweight Minecraft instance manager that allows for easy installation and updating of mods and modpacks. The modpack should be able to installed on any instance manager, but this is the best one.
3. Copy and Paste the modpack .zip file into PrismLauncher.
4. In PrismLauncher settings or Settings in the Edit Instance tab, set the Java Installation to a 64 bit **Java 17** Installation (javaw.exe), easily done using Auto Detect. If **Java 17** is not installed, you may install it from [Oracle](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) or [Adoptium](https://adoptium.net/temurin/releases/?version=17). One may work better than the other.
5. Allocate RAM to the modpack. Users with **16+ GB** of RAM should allocate a **minimum of 4GB (4096MB)** and a **maximum of 8GB (8192MB) or 10GB (10240MB)** of RAM. Allocating more than 8 GB of RAM may actually lower performance. Users with **8 GB of RAM** should allocate a **minimum of 2GB (2049MB)** and a **maximum of 4GB (4096MB)** of RAM. Users with less RAM than that probably cannot run the pack at all.
6. Add the following to the JVM Arguments section to make Java run better:
>-XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1
7. Click Launch to finish installation and to open the modpack.
8. If you have any trouble installing the modpack, contact Kenny for assistance.


## Server
The **League of Mango Minecraft Server** will host this modpack 24/7 once it is in an acceptable state.

Information about the League of Mango can be found here:

[https://leagueofmango.xyz](https://leagueofmango.xyz)


# Modlist Table of Contents
- [Current Mods Implemented](#current-mods-implemented)
  * [Large Content Mods](#large-content-mods)
  * [Utility and Supplementary Mods](#utility-and-supplementary-mods)
  * [Gameplay and World Generation Changing Mods](#gameplay-and-world-generation-changing-mods)
  * [Flavor Mods](#flavor-mods)
  * [Quality of Life Mods](#quality-of-life-mods)
  * [Additional Settings Mods](#additional-settings-mods)
  * [Performance Enhancing Mods and Bug Fixes](#performance-enhancing-mods-and-bug-fixes)
  * [Modpack Utility Mods](#modpack-utility-mods)
  * [Mod Libraries](#mod-libraries)
- [Mods to be Added](#mods-to-be-added)
- [Potential Additions](#potential-additions)


# Current Mods Implemented
Mod Count: 162

Mods in _italics_ are completely optional and may be safely disabled for performance.

They are removed from the lite version of the modpack.


## Large Content Mods
(14)


### [Botania](https://www.curseforge.com/minecraft/mc-mods/botania)
* Harness the power of natural magic using plants that generate mana. Some engineering is required to get the most value from the plants. Also contains various useful magical artifacts.

[MythicBotany](https://www.curseforge.com/minecraft/mc-mods/mythicbotany)
* Addon mod for Botania that adds additional endgame content.


### [Create](https://www.curseforge.com/minecraft/mc-mods/create)
* Mod that allows for large mechanical contraptions to be made that can do almost anything including farming, mining, crafting, and transportation.

### [Farmer's Delight](https://www.curseforge.com/minecraft/mc-mods/farmers-delight)
* Adds new crops, new foods, and new ways to farm and cook.

[Brewin' And Chewin'](https://www.curseforge.com/minecraft/mc-mods/brewin-and-chewin)
* Adds a keg to Farmer's Delight which allows foods to be fermented and alcoholic beverages to be brewed. Also adds new foods and recipes to Farmer's Delight.

[Cultural Delights](https://www.curseforge.com/minecraft/mc-mods/cultural-delights)
* Adds new ingredients and foods based on cuisine from around the world. This mod features sushi crafting, calamari, and corn-based foods.

[Farmer's Respite](https://www.curseforge.com/minecraft/mc-mods/farmers-respite)
* Adds tea and brewing mechanics to Farmer's Delight.

[Abnormals Delight](https://www.curseforge.com/minecraft/mc-mods/abnormals-delight) _(Disabled due to bug)_
* Adds new foods and recipes involving ingredients from Team Abnormals Mods.

[Alex's Delight](https://www.curseforge.com/minecraft/mc-mods/alexs-delight)
* Adds new foods and recipes involving ingredients from Alex's Mobs.


### [Dark Utilities](https://www.curseforge.com/minecraft/mc-mods/dark-utilities)
* Adds new tools and blocks such as vector plates and mob filters which can be very useful in many situations.

### [Tinker's Construct](https://www.curseforge.com/minecraft/mc-mods/tinkers-construct)
* A revamped system for creating tools and weapons. Tools and weapons can now crafted from individual parts which have various modifiers and different stats based on the material used. Also adds new alloys, slimes, and tools.

### [Quark](https://www.curseforge.com/minecraft/mc-mods/quark)
* Adds many additions,features, and quality of life changes that would fit in with Vanilla Minecraft.

[Quark Oddities](https://www.curseforge.com/minecraft/mc-mods/quark-oddities)
* Additional features to Quark that may not necessarily fit Vanilla Minecraft. Includes copper pipes, magnets, Quark crate, and matrix enchanting.


### [Supplementaries](https://www.curseforge.com/minecraft/mc-mods/supplementaries)
* Adds some new functional and decorative blocks that would fit with Vanilla Minecraft.


## Utility and Supplementary Mods
(15)


### [Akashic Tome](https://www.curseforge.com/minecraft/mc-mods/akashic-tome)
* A magical book that can hold multiple instruction booklets for other mods.

### [Morph-o-Tool](https://www.curseforge.com/minecraft/mc-mods/morph-o-tool)
* A magical tool that can transform into the appropriate wrenches for other mods.

### [Carry On](https://www.curseforge.com/minecraft/mc-mods/carry-on)
* Allows for tile entities and small mobs to be picked up with empty hands.

### [Corpse](https://www.curseforge.com/minecraft/mc-mods/corpse)
* When players die, their corpse is left on the ground. Players can pick up their lost items from the corpse. The corpse will decompose after an hour which allows any player to loot the remains.

### [Dual Riders](https://www.curseforge.com/minecraft/mc-mods/dual-riders)
* Enables two players to ride on the same horse at a time.

### [Horse Combat Controls](https://www.curseforge.com/minecraft/mc-mods/horse-combat-controls)
* Adds Mount and Blade style controls for horses, making combat on horseback better and easier.

### [MmmMmmMmmMmm](https://www.curseforge.com/minecraft/mc-mods/mmmmmmmmmmmm)
* Adds a target dummy that lets you test out the damage and dps of your weapons.

### [Iron Chests](https://www.curseforge.com/minecraft/mc-mods/iron-chests)
* Adds new, higher level upgrades for chests.

### [Nature's Compass](https://www.curseforge.com/minecraft/mc-mods/natures-compass)
* Adds a compass that points to a selected biome.

### [Neapolitan](https://www.curseforge.com/minecraft/mc-mods/neapolitan)
* Adds chocolate, vanilla, strawberry, bananas, adzuki beans, and mint to add more food options.

### [Paragliders](https://www.curseforge.com/minecraft/mc-mods/paragliders)
* Adds Breath of the Wild-like paragliders.

### [Small Ships](https://www.curseforge.com/minecraft/mc-mods/small-ships)
* Adds functional ships with sails that can carry cargo and cannons.

### [Storage Drawers](https://www.curseforge.com/minecraft/mc-mods/storage-drawers)
* Containers that specialize in storing a large quantity of a single item. Exceptionally useful and aesthethically pleasing.

[Framed Compacting Drawers](https://www.curseforge.com/minecraft/mc-mods/framed-compacting-drawers)
* Allows for compacting drawers to be framed with other blocks.

### [Traveler's Backpack](https://www.curseforge.com/minecraft/mc-mods/travelers-backpack)
* Adds a backpack that comes with a crafting table, a sleeping bag, two tanks for fluids, and a hose to fill or empty the tanks. They are able to be placed on the ground or equipped in either a chestplate slot or a Curios slot. They can even interface with other machines.


## Gameplay and World Generation Changing Mods
(9)


### [Champions](https://www.curseforge.com/minecraft/mc-mods/champions)
* Some mobs become elite mobs that are extra strong but drop better loot.

### [Diet](https://www.curseforge.com/minecraft/mc-mods/diet)
* Every food item in the game will give different nutrients. These nutrients are divided into separate groups. By maintaning a healthy balance of nutrients, players will receive many benefits while being malnourished will incur negative effects.

### [Valhelsia Structures](https://www.curseforge.com/minecraft/mc-mods/valhelsia-structures)
* Adds new structures to the world.

### Yung's Better Mods
A collection of mods that improve vanilla structure generation.
* [Yung's Better Desert Temples](https://www.curseforge.com/minecraft/mc-mods/yungs-better-desert-temples)
* [Yung's Better Desert Temples](https://www.curseforge.com/minecraft/mc-mods/yungs-better-dungeons)
* [Yung's Better Mineshafts](https://www.curseforge.com/minecraft/mc-mods/yungs-better-mineshafts-forge)
* [Yung's Better Strongholds](https://www.curseforge.com/minecraft/mc-mods/yungs-better-strongholds)
* [Yung's Better Witch Huts](https://www.curseforge.com/minecraft/mc-mods/yungs-better-witch-huts)
* [Yung's Extras](https://www.curseforge.com/minecraft/mc-mods/yungs-extras)


## Flavor Mods
(16)


### [Additional Banners](https://www.curseforge.com/minecraft/mc-mods/additional-banners)
* Adds new banner patterns.

### [Alex's Mobs](https://www.curseforge.com/minecraft/mc-mods/alexs-mobs)
* Adds many new mobs including those based on real life creatures and Minecraft fantasy. Every mob added has unique drops, mechanics, or functions so no mob is purely aesthetic.

### [Creeper Confetti](https://www.curseforge.com/minecraft/mc-mods/creeper-confetti)
* Creepers now have a 25% chance to explode into harmless confetti.

### [Customizable Elytra](https://www.curseforge.com/minecraft/mc-mods/customizable-elytra)
* Elytras can now be dyed and banners can be placed on them.

### _[Damage Tilt](https://www.curseforge.com/minecraft/mc-mods/damage-tilt)_
* Re-adds a feature that makes the screen tilt after taking damage in the direction of the damage source.

### [Dark Paintings](https://www.curseforge.com/minecraft/mc-mods/dark-paintings)
* Adds extra paintings.

### [Giants Spawn](https://www.curseforge.com/minecraft/mc-mods/giant-spawn)
* Giants will now rarely spawn on the surface of the overworld.

### [Goblin Traders](https://www.curseforge.com/minecraft/mc-mods/goblin-traders)
* Adds goblins that trade with players underground.

### [Instrumental Mobs](https://www.curseforge.com/minecraft/mc-mods/instrumental-mobs)
* Some mobs now spawn with instruments and will attempt to kill you with vibes.

### [Joy of Painting](https://www.curseforge.com/minecraft/mc-mods/joy-of-painting)
* Paint your own pictures in Minecraft and proudly display them.

### [Local Looks](https://www.curseforge.com/minecraft/mc-mods/local-looks)
* Adds an item which allows a player to change their skin in game.

### [Macaw's Paintings](https://www.curseforge.com/minecraft/mc-mods/macaws-paintings)
* Adds extra paintings.

### [Music Maker Mod](https://www.curseforge.com/minecraft/mc-mods/music-maker-mod)
* Adds playable instruments and music sheets. Create, play, and perform custom-made music alone or with friends.

### _[Seamless Loading Screen](https://www.curseforge.com/minecraft/mc-mods/seamless-loading-screen-forge)_
* Loading a world now displays a snapshot of the last position you were previously in.

### [Skinned Lanterns](https://www.curseforge.com/minecraft/mc-mods/skinned-lanterns)
* Adds many new types of lanterns.

### _[Villager Names](https://www.curseforge.com/minecraft/mc-mods/villager-names)_
* Villagers now spawn with actual names.


## Quality of Life Mods
(34)


### [AppleSkin](https://www.curseforge.com/minecraft/mc-mods/appleskin)
* Displays detailed information about food and their nutrition values.

### [Bigger Sponge Absorption Radius](https://www.curseforge.com/minecraft/mc-mods/bigger-sponge-absorption-radius)
* Placing multiple sponges next to each other extends the radius of absorption.

### [CleanCut](https://www.curseforge.com/minecraft/mc-mods/cleancut)
* Allows for mobs to be attacked through blocks like tall grass and vines.

### [Crafting Tweaks](https://www.curseforge.com/minecraft/mc-mods/crafting-tweaks)
* Adds buttons and shortcuts that make crafting easier.

### [Curious Elytra](https://www.curseforge.com/minecraft/mc-mods/curious-elytra)
* Allows for Elytras to be placed in a Curios back slot.

### [Cycle Paintings](https://www.curseforge.com/minecraft/mc-mods/cycle-paintings)
* Allows for players to cycle through pictures in paintings.

### [Dismount Entity](https://www.curseforge.com/minecraft/mc-mods/dismount-entity)
* Crouch+Right-click mobs in boats or minecarts to dismount them.

### [Farsight](https://www.curseforge.com/minecraft/mc-mods/farsight)
* Allows for players to see chunks beyond the server view distance if they were loaded already in the client.

### [Fast Leaf Decay](https://www.curseforge.com/minecraft/mc-mods/fast-leaf-decay)
* Makes leaves decay faster.

### [Fixed Anvil Repair Cost](https://www.curseforge.com/minecraft/mc-mods/fixed-anvil-repair-cost)
* Repairing items in an anvil no longer scales level costs beyond player capability.

### [FlickerFix](https://www.curseforge.com/minecraft/mc-mods/flickerfix)
* Makes the flickering effect when the night vision effect is about to expire less annoying.

### [Friendly Fire](https://www.curseforge.com/minecraft/mc-mods/friendly-fire)
* Prevents you from accidently killing your pets. You can sneak to attack them if you are a monster.

### _[Item Zoom](https://www.curseforge.com/minecraft/mc-mods/itemzoom)_
* Hovering over a block or item in JEI displays a larger, zoomed-in version of it.

### [Just Enough Items](https://www.curseforge.com/minecraft/mc-mods/jei)
* Displays the crafting recipes and possible processes of every block, item, and material. Also displays every block and item that exists.

[Just Enough Resources](https://www.curseforge.com/minecraft/mc-mods/just-enough-resources-jer)
* Displays information about world drops and ore generation.

[Just Enough Effect Descriptions](https://www.curseforge.com/minecraft/mc-mods/just-enough-effect-descriptions-jeed)
* Displays information about potion effects and their sources.

[Just Enough Painting Previews](https://www.curseforge.com/minecraft/mc-mods/jepp)
* Displays all available paintings.

[Just Enough Profressions](https://www.curseforge.com/minecraft/mc-mods/just-enough-professions-jep)
* Displays which workstations are required for different villagers.


### [JourneyMap](https://www.curseforge.com/minecraft/mc-mods/journeymap)
* Adds a large, automatically updating map, markable waypoints, and a minimap.

[JourneyMap Integration](https://www.curseforge.com/minecraft/mc-mods/journeymap-integration)
* Allow for chunks to be claimed via FTB Chunks inside the JourneyMap.

[Map Frontiers](https://www.curseforge.com/minecraft/mc-mods/mapfrontiers)
* Allows for large regions on the map to be marked and labeled.


###[Just Zoom](https://www.curseforge.com/minecraft/mc-mods/just-zoom-forge)
* Adds a keybind to zoom in like in Optifine. The level of zoom can be adjusted using the scroll wheel.

### [Klee Slabs](https://www.curseforge.com/minecraft/mc-mods/kleeslabs)
* Allows for half of a double slab to be broken.

### [Mod Name Tooltip](https://www.curseforge.com/minecraft/mc-mods/mod-name-tooltip)
* Displays the name of the mod an item originates from.

### [More Overlays Updated](https://www.curseforge.com/minecraft/mc-mods/more-overlays-updated)
* Adds overlays for light levels (F7) and chunk boundaries (F9) in the F3 debug menu.

### [Mounted Pearl](https://www.curseforge.com/minecraft/mc-mods/mounted-pearl-bring-your-mount-along-when-you)
* Using an Ender Pearl brings a player's mount if they are riding it.

### [Mouse Tweaks](https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks)
* Adds new mouse dragging mechanics that make moving items from inventories easier.

### [Neat](https://www.curseforge.com/minecraft/mc-mods/neat)
* Adds an HP bar above every mob.

### [Not Enough Crashes](https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes-forge)
* In-game crashes now take the user back to the main menu. Displays more detailed crash logs.

### [Notes](https://www.curseforge.com/minecraft/mc-mods/notes)
* Adds an in-game notepad.

### [Smarter Farmers](https://www.curseforge.com/minecraft/mc-mods/smarter-farmers-farmers-replant)
* Farmer Villagers can now interact, plant, and replant modded crops and will overall be less dumb.

### [Stack Refill](https://www.curseforge.com/minecraft/mc-mods/stack-refill)
* Automatically refills items and stacks in a player's hands if that item or block exists in the player's inventory.

### [The One Probe](https://www.curseforge.com/minecraft/mc-mods/the-one-probe)
* Shows information about the block or entity you are viewing.

### [Torch Slabs Mod](https://www.curseforge.com/minecraft/mc-mods/torchslabs-mod)
* Allows for torches and lanterns to be placed on slabs.


## Additional Settings Mods
(16)
All of these mods are optional, but are highly recommended.

### [BetterF3](https://www.curseforge.com/minecraft/mc-mods/betterf3)
* Adds more visual clarity to the F3 debug HUD.

### [Better Third Person](https://www.curseforge.com/minecraft/mc-mods/better-third-person)
* Allows for free camera rotation in third-person view.

### [Borderless Window](https://www.curseforge.com/minecraft/mc-mods/borderless)
* Replaces Minecraft's default fullscreen mode with a custom borderless fullscreen if it would be faster.

### [Compact Help Command](https://www.curseforge.com/minecraft/mc-mods/compact-help-command)
* Improves the /help command.

### [Extended Creative Inventory](https://www.curseforge.com/minecraft/mc-mods/extended-creative-inventory)
* Adds a tab to the Creative Mode inventory that contains command-only items like command blocks and barriers.

### [Catalogue](https://www.curseforge.com/minecraft/mc-mods/catalogue)
* Updates Forge's mod list menu.

### _[Configured](https://www.curseforge.com/minecraft/mc-mods/configured)_
* Creates a configuration menu for each mod.

### [Controlling](https://www.curseforge.com/minecraft/mc-mods/controlling)
* Allows for you to search the controls menu.

### _[Chunk Pregenerator](https://www.curseforge.com/minecraft/mc-mods/chunkpregenerator)_
* Allows for world chunks to be generated before a world is actually loaded.

### [Drippy Loading Screen](https://www.curseforge.com/minecraft/mc-mods/drippy-loading-screen)
* Allows for the initial loading screen to be customized.

### [FancyMenu](https://www.curseforge.com/minecraft/mc-mods/fancymenu)
* Allows for the menus GUIs to be customized and animated.

[Audio Extension for FancyMenu](https://www.curseforge.com/minecraft/mc-mods/audio-extension-for-fancymenu-forge)
* Allows for audio elements to be added to FancyMenu GUIs.


### [ModernWorldCreation](https://www.curseforge.com/minecraft/mc-mods/modernworldcreation)
* Changes the world creation menu to make it look nicer.

### _[Oculus](https://www.curseforge.com/minecraft/mc-mods/oculus)_
* Allows for Optifine Shaders to be used.
* The modpack comes shipped with [Complementary Shaders](https://www.complementary.dev), which are designed to be as compatible as possible with modded minecraft.

### [ReAuth](https://www.curseforge.com/minecraft/mc-mods/reauth)
* Adds tools to help login.

### _[Shoulder Surfing Reloaded](https://www.curseforge.com/minecraft/mc-mods/shoulder-surfing-reloaded)_
* Enables a over-the-shoulder third-person view mode.


## Performance Enhancing Mods and Bug Fixes
(21)


### [AttributeFix](https://www.curseforge.com/minecraft/mc-mods/attributefix)
* Significantly increases caps for attributes to fix stats from mods.

### [Bad Wither No Cookie - Reloaded](https://www.curseforge.com/minecraft/mc-mods/bad-wither-no-cookie-reloaded)
* Silences global broadcast sounds for withers.

### [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps)
* Makes XP orbs clump up into a single entity.

### [Connectivity](https://www.curseforge.com/minecraft/mc-mods/connectivity)
* Fixes some problems involving server connection.

### [Debugify](https://www.curseforge.com/minecraft/mc-mods/debugify)
* Fixes many bugs in Vanilla Minecraft.

### [Dynamic View](https://www.curseforge.com/minecraft/mc-mods/dynamic-view)
* Dynamically adjusts server chunk view distance based on server lag.

### [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entityculling)
* Skips rendering entities that are not visible.

### [FastFurnace](https://www.curseforge.com/minecraft/mc-mods/fastfurnace)
* Optimizes furnace performance.

### [FastWorkbench](https://www.curseforge.com/minecraft/mc-mods/fastworkbench)
* Optimizes crafting table performance.

### [FastSuite](https://www.curseforge.com/minecraft/mc-mods/fastsuite)
* Optimizes everything that uses recipes.

### [Feature NBT Deadlock Be Gone](https://www.curseforge.com/minecraft/mc-mods/feature-nbt-deadlock-be-gone)
* Fixes a bug where generating structures with NBT data would freeze the game.

### [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore)
* Reduced the memory usage of Minecraft.

### [FPS Reducer](https://www.curseforge.com/minecraft/mc-mods/fps-reducer)
* Lowers FPS while AFK or tabbed out to reduce unecessary CPU and GPU load.

### [Kyrpton Reforged](https://www.curseforge.com/minecraft/mc-mods/krypton-reforged)
* Optimizes Minecraft's networking stack.

### [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazydfu)
* Makes initializing the game faster.

### [NetherPortalFix](https://www.curseforge.com/minecraft/mc-mods/netherportalfix)
* Makes players return to the same portal they entered the nether from if they return through the same nether portal.

### [Overloaded Armor Bar](https://www.curseforge.com/minecraft/mc-mods/overloaded-armor-bar-updated)
* Displays armor values beyond diamond armor.

### [Potion ID Packet Fixer](https://www.curseforge.com/minecraft/mc-mods/potion-id-packet-fixer)
* Fixes issues that would occur if more than 255 potion effects were registered.

### [Radium](https://www.curseforge.com/minecraft/mc-mods/radium-reforged)
* Forge port of Lithium. Optimizes game events such as physics, mob AI, and more.

### [Radon](https://www.curseforge.com/minecraft/mc-mods/radon)
* Forge port of Phosphor. Optimizes Minecraft's lighting engine.

### [Rubidium](https://www.curseforge.com/minecraft/mc-mods/rubidium)
* Forge port of Sodium. Optimizes Minecraft's rendering engine. Better than Optifine.


## Modpack Utility Mods
(3)


### [CraftTweaker](https://www.curseforge.com/minecraft/mc-mods/crafttweaker)
* Allows for recipes to be added and edited.

[JEITweaker](https://www.curseforge.com/minecraft/mc-mods/jeitweaker)
* Allows for what JEI displays to be configured.


### [Default Options](https://www.curseforge.com/minecraft/mc-mods/default-options)
* Allows for modpacks to ship with default keybindings without resetting user changes upon updating.


### FTB Mods
(6)
A collection of mods which improve the multiplayer experience.
* [FTB Backups](https://www.curseforge.com/minecraft/mc-mods/ftb-backups-2)
	* Makes backups of the world at a specified time. Set to 5:00 AM by default.

* [FTB Chunks](https://www.curseforge.com/minecraft/mc-mods/ftb-chunks)
	* Allows for players or teams to claim chunks as their own, preventing other players from destroying terrain in these chunks. Also allows for these chunks to be constantly loaded.

* [FTB Quests](https://www.curseforge.com/minecraft/mc-mods/ftb-quests)
	* Enables quests and questlines to be added.
	* [Quests Additions](https://www.curseforge.com/minecraft/mc-mods/quests-additions)
		* Addon mod for FTB Quests that adds additional quest objective and rewards parameters.


* [FTB Teams](https://www.curseforge.com/minecraft/mc-mods/ftb-teams)
	* Enables players to form teams and share chunks and quests.

* [FTB Ultimine](https://www.curseforge.com/minecraft/mc-mods/ftb-ultimine-forge)
	* Mine multiple blocks of the same kind at a time.


## Mod Libraries
(28)


### [Architectury API](https://www.curseforge.com/minecraft/mc-mods/architectury-api)
* Library for many mods, notably FTB mods.

### [AutoRegLib](https://www.curseforge.com/minecraft/mc-mods/autoreglib)
* Library for Akashic Tome, Morph-o-Tool, and Quark.

### [Auudio](https://www.curseforge.com/minecraft/mc-mods/auudio-forge)
* Library for adding sounds to menus and worlds, used in FancyMenu.

### [Balm](https://www.curseforge.com/minecraft/mc-mods/balm)
* Library for Crafting Tweaks, Default Options, KleeSlabs, and NetherPortalFix.

### [Blueprint](https://www.curseforge.com/minecraft/mc-mods/blueprint)
* Library for Team Abnormals mods.

### [Bookshelf](https://www.curseforge.com/minecraft/mc-mods/bookshelf)
* Library for Additional Bannners, Dark Paintings, Dark Utilities, and FriendlyFire.

### [Caelus API](https://www.curseforge.com/minecraft/mc-mods/caelus)
* API for elytra based mods, used in Curious Elytra.

### [Citadel](https://www.curseforge.com/minecraft/mc-mods/citadel)
* Library mod for Alex's Mobs, Alex's Delight, and Local Looks.

### [Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config)
* Config screen API.

### [Collective](https://www.curseforge.com/minecraft/mc-mods/collective)
* Library for Serilum's mods, which include many Vanilla+ mods like Bigger Sponge Absorption Radius, Compact Help Command, Cycle Paintings, Dismount Entity, Extended Creative Inventory, Fixed Anvil Repair Cost, Giant Spawn, Path Under Gates, Stack Refill, and Villager Names.

### [ConnectedTexturesMod](https://www.curseforge.com/minecraft/mc-mods/ctm)
* Allows for resource packs/mods to add connected textures.

### [Curios](https://www.curseforge.com/minecraft/mc-mods/curios)
* Enables additional slots for equipment.

### [FlytreLib](https://www.curseforge.com/minecraft/mc-mods/lib)
* Library mod for Dual Riders.

### [FlyWheel](https://www.curseforge.com/minecraft/mc-mods/flywheel)
* Rendering engine for Create.

### [FTB Library](https://www.curseforge.com/minecraft/mc-mods/ftb-library-forge)
* Library for GUIs in FTB mods.

### [Item Filters](https://www.curseforge.com/minecraft/mc-mods/item-filters)
* Library for FTB Quests.

### [Konkrete](https://www.curseforge.com/minecraft/mc-mods/konkrete)
* Library for FancyMenu, Drippy Loading Screen, Modern World Creation, and their extensions.

### [LibX](https://www.curseforge.com/minecraft/mc-mods/libx)
* Library for MythicBotany

### [Load My Resources](https://www.curseforge.com/minecraft/mc-mods/load-my-resources-forge)
* Library for FancyMenu and Drippy Loading Screen which allows for resources to be loaded on game start.

### [Mantle](https://www.curseforge.com/minecraft/mc-mods/mantle)
* Library for Tinker's Construct.

### [Structure Gel API](https://www.curseforge.com/minecraft/mc-mods/structure-gel-api)
* API to generate structures. Used in The Conjurer.

### [Patchouli](https://www.curseforge.com/minecraft/mc-mods/patchouli)
* API for in-game documentation books for mods. Used in many mods.

### [Pig Pen Cipher](https://www.curseforge.com/minecraft/mc-mods/pig-pen-cipher)
* Adds the Pig Pen Cipher as a font.

### [Placebo](https://www.curseforge.com/minecraft/mc-mods/placebo)
* Library for FastFurnace, FastWorkbench, FastSuite.

### [Runelic](https://www.curseforge.com/minecraft/mc-mods/runelic)
* Adds the Runelic font.

### [Selene](https://www.curseforge.com/minecraft/mc-mods/selene)
* Library for Supplementaries, MmmMmmMmmMmm, Smarter Farmers, Just Enough Effect Descriptions, and Just Enough Painting Previews.

### [Valhelsia Core](https://www.curseforge.com/minecraft/mc-mods/valhelsia-core)
* Core mod for Valhelsia Structures.

### [Yung's API]((https://www.curseforge.com/minecraft/mc-mods/yungs-api))
* API for the Yung's Better mod series.


# Mods to be Added


## Content Mods


### Thermal Suite
A collection of various technological additions that pair fantastically with other mods .
The Thermal Suite includes:
* [Thermal Foundation](https://www.curseforge.com/minecraft/mc-mods/thermal-foundation)
	* Provides many new ores, metals, alloys, materials, and mobs. Also provides various processed forms of these resources.

* [Thermal Expansion](https://www.curseforge.com/minecraft/mc-mods/thermal-expansion)
	* One-block machines that perform specific tasks and are highly configurable and upgradable.

* [Thermal Dynamics](https://www.curseforge.com/minecraft/mc-mods/thermal-dynamics) _(not updated yet)_
	* Various levels of aesthetically pleasing tubes that transport items, fluids, and RF between locations.

* [Thermal Innovation](https://www.curseforge.com/minecraft/mc-mods/thermal-innovation)
	* Various supplementary tools that use Thermal Foundation's parts.

* [Thermal Locomotion](https://www.curseforge.com/minecraft/mc-mods/thermal-locomotion)
	* Adds new types of minecarts and rails.

### [CoFH Core](https://www.curseforge.com/minecraft/mc-mods/cofh-core)
* Library for CoFH mods, including Archer's Paradox, Ensorcellation, and the Thermal Suite.


### [Immersive Engineering](https://www.curseforge.com/minecraft/mc-mods/immersive-engineering)
* A realistic tech mod with a rustic feel. It features multi-block machines which are both functional and fashionabl. It also features electrical wires which can be strewn over long distances and carry RF and redstone signals. Various additional cosmetic blocks and lighting fixtures are present to help create an aesthetic base. Finally, various weapons such as revolvers and railguns are present.

[Immersive Petroleum](https://www.curseforge.com/minecraft/mc-mods/immersive-petroleum) _(not updated yet)_
* An addon for Immersive Engineering which adds oil generation and oil processing.


### [Ars Nouveau](https://www.curseforge.com/minecraft/mc-mods/ars-nouveau)
* Magic mod that involves custom spell creation, magical artifacts, rituals, and familiars.

### [Eidolon](https://www.curseforge.com/minecraft/mc-mods/eidolon) _(not updated yet)_
* Magic mod featuring alchemy, rituals, and theurgy.

### [Hexerei](https://www.curseforge.com/minecraft/mc-mods/hexerei)
* Magic mod that involves creating mystical items with black magic and cauldrons. Features witch-based magical items like flying brooms.

### [Astral Sorcery](https://www.curseforge.com/minecraft/mc-mods/astral-sorcery) _(not updated yet)_
* Starlight and constellation based magic.

### [The Twilight Forest](https://www.curseforge.com/minecraft/mc-mods/the-twilight-forest)
* Fantasy dimension with many areas to explore and bosses to take on.

### [Team Abnormal Mods] _(not updated yet)_
A collection of various additions that match vanilla Minecraft, most notably new mobs and biomes.

* [Atmospheric](https://www.curseforge.com/minecraft/mc-mods/atmospheric)
	* Adds rainforest and dunes biomes.

* [Autumnnity](https://www.curseforge.com/minecraft/mc-mods/autumnity)
	* Adds autumn based biomes and other content.

* [Bamboo Blocks](https://www.curseforge.com/minecraft/mc-mods/bamboo-blocks)
	* Adds more blocks that use bamboo.

* [The Endergetic Expansion](https://www.curseforge.com/minecraft/mc-mods/endergetic)
	* Adds some new additions to The End.

* [Environmental](https://www.curseforge.com/minecraft/mc-mods/environmental)
	* Adds some new biomes and adds many new additions to existing biomes, including new trees, flowers, mobs, items, and equipment.


### [RFTools Pack](https://www.curseforge.com/minecraft/mc-mods/mcjtylib)
A collection of machines powered by RF that can perform many different actions.
The Thermal Suite includes:
* [RFTools Base](https://www.curseforge.com/minecraft/mc-mods/rftools-base)
	* Base mod for RFTools. Includes materials and a wrench used in the other mods.

* [RFTools Builder](https://www.curseforge.com/minecraft/mc-mods/rftools-builder) _(to potentially add)_
	* A single block that can build, destroy, or mine a specified area.

* [RFTools Control](https://www.curseforge.com/minecraft/mc-mods/rftools-control) _(to potentially add)_
	* Adds a visual programming interface to help control automation.

* [RFTools Dimensions](https://www.curseforge.com/minecraft/mc-mods/rftools-dimensions) _(to potentially add)_
	* Use RF to generate dimensions.

* [RFTools Power](https://www.curseforge.com/minecraft/mc-mods/rftools-power)
	* Adds ways to generate and store power.

* [RFTools Storage](https://www.curseforge.com/minecraft/mc-mods/rftools-storage) _(to potentially add)_
	* Adds a way to store items digitally using RF powered networks.

* [RFTools Utility](https://www.curseforge.com/minecraft/mc-mods/rftools-utility)
	* Various machines that are very useful. Includes a teleporter and automatic crafter.

* [XNet](https://www.curseforge.com/minecraft/mc-mods/xnet)
	* Adds a way to network inventories together to transport items, fluids, energy, and information instantly with precise control.
	* [XNet Gases](https://www.curseforge.com/minecraft/mc-mods/xnet-gases)
		* Adds support for Mekanism gases.


### [Pneumaticraft: Repressurized](https://www.curseforge.com/minecraft/mc-mods/pneumaticcraft-repressurized)
* Machines, drones, and weapons powered by compressed air.

### [Applied Energistics 2](https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2)
* Build a complex network that can store many items and fluids as well as automate crafting processes.

### [Mekanism](https://www.curseforge.com/minecraft/mc-mods/mekanism)
* Powerful and badass machinery.

[Mekanism Generators](https://www.curseforge.com/minecraft/mc-mods/mekanism-generators)
* Adds new generators for Mekanism. _(could be too OP unless tweaked heavily)_


### [Productive Bees](https://www.curseforge.com/minecraft/mc-mods/productivebees)
* Bees that generate resources.

### [Advanced Rocketry](https://www.curseforge.com/minecraft/mc-mods/advanced-rocketry)
* Build custom rockets to go to the moon. You can also build a space station.


## Utility and Supplementary Mods


### [AstikorCarts](https://www.curseforge.com/minecraft/mc-mods/astikorcarts) _(not updated yet)_
* Adds various carts that horses can pull.

### [Archer's Paradox](https://www.curseforge.com/minecraft/mc-mods/archers-paradox)
* Adds new types of arrows.

### [Ensorcellation](https://www.curseforge.com/minecraft/mc-mods/ensorcellation)
* Adds new enchantments.


## Gameplay and World Generation Changing Mods


### [The Conjurer](https://www.curseforge.com/minecraft/mc-mods/the-conjurer)
* Adds an illager mini-boss found in a special structure in a dark forest biome.


## Flavor Mods


### _[Dynamic Surroundings](https://www.curseforge.com/minecraft/mc-mods/dynamic-surroundings)_ _(not updated yet)_
* Makes the world's sounds more immersive.

### [Trumpet Skeletons](https://www.curseforge.com/minecraft/mc-mods/doot) _(not updated yet)_
* Skeletons will occasionally go doot.


## Quality of Life Mods


### [Path Under Gates](https://www.curseforge.com/minecraft/mc-mods/path-under-gates)
* Allows for grass path blocks to exist under fence gates.


# Potential Additions


### [AmbientSounds 3](https://www.curseforge.com/minecraft/mc-mods/ambientsounds)
* Adds more ambient sounds.

### [Ambience](https://www.curseforge.com/minecraft/mc-mods/ambience-extras)
* Plays sounds and animations when a player does something notable.

### [Dungeon Crawl](https://www.curseforge.com/minecraft/mc-mods/dungeon-crawl)
* Generates large, underground roguelike structures.

### [Engineer's Decor](https://www.curseforge.com/minecraft/mc-mods/engineers-decor)
* Adds new blocks that match Immmersive Engineering's aesthetic.

### [Redstone Gauges and Switches](https://www.curseforge.com/minecraft/mc-mods/redstone-gauges-and-switches)
* Adds various aesthetic redstone components.

### [Farming for Blockheads](https://www.curseforge.com/minecraft/mc-mods/farming-for-blockheads)
* Adds a marketplace block where people can trade for certain crops. _(replace with Amadron?)_

### [Macaw's Bridges](https://www.curseforge.com/minecraft/mc-mods/macaws-bridges)
* Adds cool-looking bridges.

### [Macaw's Doors](https://www.curseforge.com/minecraft/mc-mods/macaws-doors)
* Adds cool, new doors.

### [Macaw's Furniture](https://www.curseforge.com/minecraft/mc-mods/macaws-furniture)
* Adds aesthetic and functional furniture.

### [Macaw's Windows](https://www.curseforge.com/minecraft/mc-mods/macaws-windows)
* Adds aesthetic and functional windows.

### [Miner's Helmet](https://www.curseforge.com/minecraft/mc-mods/miners-helmet)
* Adds a helmet that provides light around the wearer.

### [Scuba Gear](https://www.curseforge.com/minecraft/mc-mods/scuba-gear)
* Adds a set of armor that allows for you to breathe underwater and move underwater faster.

### [Hats](https://www.curseforge.com/minecraft/mc-mods/hats)
* Adds wearable hats.

### [Aquaculture](https://www.curseforge.com/minecraft/mc-mods/aquaculture)
* Expands on fishing by adding many new types of fish and rods.

### [Plato's Transporters](https://www.curseforge.com/minecraft/mc-mods/platos-transporters)
* Create custom boats and aircraft to travel around the world.

### [Mowzie's Mobs](https://www.curseforge.com/minecraft/mc-mods/mowzies-mobs)
* Adds new, challenging boss mobs.

### [Rats](https://www.curseforge.com/minecraft/mc-mods/rats)
* haha funny rat mod.

### [Spiders 2.0](https://www.curseforge.com/minecraft/mc-mods/spiders-2-0)
* Spiders can now walk on walls and ceilings and have improved AI to navigate around obstacles.

### [Doggy Talents](https://www.curseforge.com/minecraft/mc-mods/doggy-talents)
* Train your wolves to become stronger companions.

### [Psi](https://www.curseforge.com/minecraft/mc-mods/psi)
* Programmable magic.

### [Good Night's Sleep](https://www.curseforge.com/minecraft/mc-mods/good-nights-sleep)
* Adds two new dimensions: the dream world and the nightmare dimension. These can be accessed by sleeping in a special bed.

### [The Abyss](https://www.curseforge.com/minecraft/mc-mods/the-abyss)
* Adds a new dimension with dark dangers.

### [Tumbleweed](https://www.curseforge.com/minecraft/mc-mods/tumbleweed)
* Rolling plants that may have loot.

### [Just Another Void Dimension](https://www.curseforge.com/minecraft/mc-mods/just-another-void-dimension)
* Void dimension

### [Nature's Aura](https://www.curseforge.com/minecraft/mc-mods/natures-aura)
* Magic mod that uses surrounding nature.

### [Simply Jetpacks 2](https://www.curseforge.com/minecraft/mc-mods/simply-jetpacks-2)
* Adds tiered RF-powered jetpacks.

### [Advanced Hook Launchers](https://www.curseforge.com/minecraft/mc-mods/advanced-hook-launchers)
* Adds various kinds of grappling hooks.

### [Off Hand Combat](https://www.curseforge.com/minecraft/mc-mods/off-hand-combat)
* Enables dual-wielding weapons.

### [Explorer's Compass](https://www.curseforge.com/minecraft/mc-mods/explorers-compass)
* Compass that locates structures.

### [Waddles](https://www.curseforge.com/minecraft/mc-mods/waddles)
* Adds penguins.

### [Infernal Expansion](https://www.curseforge.com/minecraft/mc-mods/infernal-expansion)
* Adds more mobs to the Nether.

### [Untamed Wilds](https://www.curseforge.com/minecraft/mc-mods/untamedwilds)
* Adds new mobs to the overworld.

### [Netherite Firework](https://www.curseforge.com/minecraft/mc-mods/netherite-firework)
* Reusable Firework

### [Abundance](https://www.curseforge.com/minecraft/mc-mods/abundance)
* Adds flower biomes.

### [Bayou Blues](https://www.curseforge.com/minecraft/mc-mods/bayou-blues)
* Adds a bayou biome.

### [Ars Creo](https://www.curseforge.com/minecraft/mc-mods/ars-creo)
* Create addon that adds interaction with Ars Nouveau.

### [Compressed Creativity](https://www.curseforge.com/minecraft/mc-mods/compressedcreativity)
* Create addon that adds interaction with Pneumatricraft: Repressurized.

### [Create Confectionery](https://www.curseforge.com/minecraft/mc-mods/create-confectionery)
* Create addon that adds sweets.

### [Little Logistics](https://www.curseforge.com/minecraft/mc-mods/little-logistics)
* Adds small trains and boats that automatically transfer items over distances.
