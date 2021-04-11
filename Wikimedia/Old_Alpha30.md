---
title: Old Alpha30
permalink: Old_Alpha30/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Previous_Wiki](/keeperrl_wiki/Previous_Wiki "wikilink")

=Big features=
*Playable Gnomes faction
*The modding system has been reworked to allow turning on all your favorite mods at the same time. Go crazy!

=Gameplay=
*Creatures can fight with multiple weapons if they have the “multi-weapon” skill.
*Some enemies will be retired when they kill the player, and the player’s base will be used as that enemy’s lair in future games.
*The player can choose any of the 5 existing biomes to build their base.
*Creatures get “slayer” titles and stat bonuses for killing tribe leaders.
*Keepers make paintings and write poems inspired by real game events.
*Guard zone designation that minions will take turns guarding.
*Zombies have a special “Swarmer” trait, which increases their damage and defense for every other zombie nearby.
*Writing a poem or making a painting has a very small chance of summoning a demon.
*Shamans and other creatures with the “shamanism” skill surround themselves by combat-worthy spirits.
*Keepers abuse their minions to make them work faster.
*Hostility between creatures of the same tribe times out after 50 turns.
*Vampires will sometimes regenerate lost or injured body parts after biting an enemy.
*Minions eat at dining tables instead of killing pigs directly.
*Certain creatures and weapons get special attack and defense bonuses based on the enemy’s race, being indoors, only at night, etc.
*Bandits are less aggressive and the minimum gold amount that triggers them is increased.
*Insane minions with the absorption skill are still allowed to absorb.
*Non-prisoner workers can be assigned quarters.
*Ranged damage is taken into account when evaluating how dangerous a creature is.
*Prisoners go back to prison when idle.
*Removed peacefulness and invisibility permanent effects from altar destruction.
*Minions can create moonshine from rats and get drunk.
*Creatures made of fire emit light.
*Added amulets of life saving.
*Brainless creatures don’t have morale.
*Undead get brains.
*Friendly creatures don’t get angry if attacked by an effect that doesn’t hurt them (for example by fire if fire resistant).
*Discovered allies that auto-join don’t use up population slots.
*Traveling to other maps is not prevented if enemies are fleeing from the player.
*The game considers an enemy conquered by the player only if he/she killed at least one creature from that enemy.
*Added “Fire trap” spell used by red dragons and other creatures.
*A spying creature’s identity is uncovered if items are looted.
*An allied tribe will get angry if items are stolen.
*Some villains, like ants and dwarves will only defend their mineral patches instead of attacking the player, if their minerals are breached.
*Dwarves receive an “unstable” status, which can cause them to become insane if they witness the death of an ally.
*Travel to other maps is not possible when carrying unpaid items.

=Content=
*New “Hell” hidden dungeon of end-game difficulty with new enemies, special items and other surprises.
*“Black market” hidden level with special equipment.
*“Adoxie Vault” special level.
*New minions of the “less evil” Keeper: angels, galeams, cherubs, cleric, artisan, and recruitable Teutonic Knights.
*Blacksmith location with an artisan of legendary crafting skills.
*The Dwarf Baron enemy contains a blacksmith of legendary crafting skills.
*Wizard tower location.
*Ghost ruins are less common.
*Added random corpses with loot on some maps.
*“Animate weapons” spell added to some enemies.
*Scrolls of Audience, which work similarly to sitting on thrones.
*Added stone bridges, wooden bridges now burn if placed on lava.
*Added an “Ice demon” minion.
*Added a “weaker” dwarf creature that replaces the dwarf fighter everywhere except in the Dwarf Baron settlement.
*Added a yellow dragon enemy with an acid attack.
*Added Naga creatures of various colors and abilities.
*Removed insane orc healer immigrant.
*Added flowers to ground levels.
*Added trees to the arctic biome.

=Modding=
*Loading multiple mods at the same time is now possible.
*All graphics in the game can be reloaded by pressing F8 while playing.
*The size of the campaign map and enemy limits can be increased in mods.
*Creature inventories are moved to creatures.txt.
*Allowed defining custom biomes.
*Allowed defining custom workshops.
*Allowed defining custom resources.
*Enemy dungeons may have branches.
*Mods are moved to the “mods” folder.
*Existing mod or vanilla game elements can be modified or appended to.
*New Effects: TakeItems, RemoveFurniture, ChainUntilFail, AddMinionTrait, ChooseRandom, FirstSuccessful, IncreaseSkill, IncreaseWorkshopSkill, Psychiatry, AIBelowHealth, Name, Description, FixedDamage, ColorVariant, Audience, GrantAbility, TriggerTrap.
*DestroyWalls effect can work with Area and directional spells.
*Filter Effect for applying effects conditionally: depending on creatures’s health, enemy/allied status, body material, being hidden, being a prisoner/civilian, being an automaton, being indoors/outdoors, at night/day, creature’s race, holding a special item, checking for global game flags, and more.
*Stairs can have custom effects, including Filter, which lets you require certain things before a creature can pass through.
*Custom Effect triggered when chatting with a creature.
*Custom Effect for creature’s death.
*Custom Effect for furniture “entry”.
*Custom Effect for furniture “tick”.
*Custom Effect for furniture usage.
*Summon and SummonEnemy effects have a tweak-able timer for creature to disappear.
*World generation can be tested by running “keeper.exe –worldgen_test” in command line.
*Overriding endless enemies or specifying custom enemies per keeper is possible.
*Can define separate orders for digging and cutting trees.
*Immigrant special traits can include timed LastingEffects.
*Added “gold” body material.
*Enemy dungeons can have custom level names.

=UI=
*Activities can be disabled for an entire minion group.
*A list of kills can be inspected for every minion.
*When a sprite file is not found, the game will render a random sprite, instead of crashing.
*Poison gas gets a nice particle effect animation.
*When dragging creatures, their shortest path to the target is displayed.
*Whole creature groups can be dragged from the menu to workshops and other furniture.
*Constructions and workshop items that can’t be afforded are colored red.
*New Keeperopedia UI with bestiary, items and spells.
*New “keeper in danger” warning UI with options to disable or turn off auto-pause.
*The “keeper in danger” pop-up only warns about recent wounds.
*New glyph sprites.
*New trap sprites.
*Potion sprites have different colors depending on the potion’s effect.
*Company logo splash screen while the game is starting.
*Game initialization takes place during the loading screen to avoid lag when game begins.
*Added commas to spell school list in minion menu.
*Forbidden zone is rendered on top of objects if it otherwise wouldn’t have been visible beneath.
*Moved the [new team] button to above the team list.
*Time interval between autosaves can be changed.
*Added a mini-menu for scrolling directly to chosen z-level.
*Current z-level depth is shown in control mode.
*Removed “visible enemies” and some mostly unused settings from the minions tab.
*Minion menu shows body description and intrinsic attacks.
*Mod descriptions can be scrolled in mod menu.
*The game asks if you want to start with a tutorial the first time you play.
*Added “cancel” buttons to mod and dungeon downloading progress bars.

=Fixes=
*Massive reduction in RAM usage.
*Optimized particle effects animations.
*Building bridges on z-levels is now possible without having first to descend manually.
*Fixed bug involving inability to place structures in some visible areas.
*Fixed mixing messages from different games in message boards.
*Fixed music playback restarting on some computers.
*Fixed wrong cursor position glitch in full screen.
*Ranged attacks don’t abuse the “parry” ability.
*Illusions are ignored when AI forms formations.
*Fixed endless enemies saving issue which led to attacks being cancelled after saving and loading.
*Reduced VRAM usage by sprites loaded in mods.
*Wishing for Suicide, stunned, summoned, invulnerable and “turned off” effects is disabled.
*Increased cool down of “ice cone” to avoid infinite freezing loop.
*Removed sprite limit per mod.
*Fixed a rare crash when the wish spell is granted by a piece of equipment.
*Traveling by bumping into the level border is only allowed on the ground level.
*Fixed UI crash when alt-tabbing out of full screen.
*Fixed a rare crash in graphics likely caused by changed system clock.
*Fixed issue with rebuilding triggered traps.
*Fixed crash in direction choice UI.
*Made it impossible to place a trap on up stairs after claiming the tile.
*Items that are already in storage can’t be pillaged.
*The “Zoom in UI” is available only if resolution is 1600×1200 or higher.
*Fixed crash when trying to teleport outside of map bounds.

[[Category : Game versions]]

[MainPage](/keeperrl_wiki/ "wikilink")>>[Previous_Wiki](/keeperrl_wiki/Previous_Wiki "wikilink")

Other items in this section
-    [Old 5 Reasons For Using Customized Lapel Pins](/keeperrl_wiki/Old_5_Reasons_For_Using_Customized_Lapel_Pins "wikilink")
-    [Old Abomination](/keeperrl_wiki/Old_Abomination "wikilink")
-    [Old Absorbtion](/keeperrl_wiki/Old_Absorbtion "wikilink")
-    [Old Adamantium Golem](/keeperrl_wiki/Old_Adamantium_Golem "wikilink")
-    [Old Adamantium Golems](/keeperrl_wiki/Old_Adamantium_Golems "wikilink")
-    [Old Adoxie's Entrance](/keeperrl_wiki/Old_Adoxie's_Entrance "wikilink")
-    [Old Adoxie Foot Left](/keeperrl_wiki/Old_Adoxie_Foot_Left "wikilink")
-    [Old Adoxie Foot Right](/keeperrl_wiki/Old_Adoxie_Foot_Right "wikilink")
-    [Old Adoxie Hand Left](/keeperrl_wiki/Old_Adoxie_Hand_Left "wikilink")
-    [Old Adoxie Hand Right](/keeperrl_wiki/Old_Adoxie_Hand_Right "wikilink")
-    [Old Adoxie Head](/keeperrl_wiki/Old_Adoxie_Head "wikilink")
-    [Old Adoxie Priest](/keeperrl_wiki/Old_Adoxie_Priest "wikilink")
-    [Old Adoxie Temple](/keeperrl_wiki/Old_Adoxie_Temple "wikilink")
-    [Old Advances](/keeperrl_wiki/Old_Advances "wikilink")
-    [Old Adventurer](/keeperrl_wiki/Old_Adventurer "wikilink")
-    [Old Aggressive Bandits](/keeperrl_wiki/Old_Aggressive_Bandits "wikilink")
-    [Old Aimed Spells](/keeperrl_wiki/Old_Aimed_Spells "wikilink")
-    [Old Air Elemental](/keeperrl_wiki/Old_Air_Elemental "wikilink")
-    [Old Alpha15](/keeperrl_wiki/Old_Alpha15 "wikilink")
-    [Old Alpha15 Changelog](/keeperrl_wiki/Old_Alpha15_Changelog "wikilink")
-    [Old Alpha16](/keeperrl_wiki/Old_Alpha16 "wikilink")
-    [Old Alpha17](/keeperrl_wiki/Old_Alpha17 "wikilink")
-    [Old Alpha18](/keeperrl_wiki/Old_Alpha18 "wikilink")
-    [Old Alpha19](/keeperrl_wiki/Old_Alpha19 "wikilink")
-    [Old Alpha20](/keeperrl_wiki/Old_Alpha20 "wikilink")
-    [Old Alpha21](/keeperrl_wiki/Old_Alpha21 "wikilink")
-    [Old Alpha22](/keeperrl_wiki/Old_Alpha22 "wikilink")
-    [Old Alpha23](/keeperrl_wiki/Old_Alpha23 "wikilink")
-    [Old Alpha24](/keeperrl_wiki/Old_Alpha24 "wikilink")
-    [Old Alpha25](/keeperrl_wiki/Old_Alpha25 "wikilink")
-    [Old Alpha26](/keeperrl_wiki/Old_Alpha26 "wikilink")
-    [Old Alpha27](/keeperrl_wiki/Old_Alpha27 "wikilink")
-    [Old Alpha27BonusFeaturesMod](/keeperrl_wiki/Old_Alpha27BonusFeaturesMod "wikilink")
-    [Old Alpha28](/keeperrl_wiki/Old_Alpha28 "wikilink")
-    [Old Alpha28Spells](/keeperrl_wiki/Old_Alpha28Spells "wikilink")
-    [Old Alpha29](/keeperrl_wiki/Old_Alpha29 "wikilink")
-    [Old Alpha31](/keeperrl_wiki/Old_Alpha31 "wikilink")
-    [Old Alpha 26 Mods](/keeperrl_wiki/Old_Alpha_26_Mods "wikilink")
-    [Old Alpha 27 Mods](/keeperrl_wiki/Old_Alpha_27_Mods "wikilink")
-    [Old Alpha 28 Mods](/keeperrl_wiki/Old_Alpha_28_Mods "wikilink")
-    [Old Alternative Keeper Characters](/keeperrl_wiki/Old_Alternative_Keeper_Characters "wikilink")
-    [Old Ambush](/keeperrl_wiki/Old_Ambush "wikilink")
-    [Old Angel](/keeperrl_wiki/Old_Angel "wikilink")
-    [Old Ant Queen](/keeperrl_wiki/Old_Ant_Queen "wikilink")
-    [Old Ant Worker](/keeperrl_wiki/Old_Ant_Worker "wikilink")
-    [Old Archer](/keeperrl_wiki/Old_Archer "wikilink")
-    [Old Archery](/keeperrl_wiki/Old_Archery "wikilink")
-    [Old Armless](/keeperrl_wiki/Old_Armless "wikilink")
-    [Old Armor](/keeperrl_wiki/Old_Armor "wikilink")
-    [Old Artisan](/keeperrl_wiki/Old_Artisan "wikilink")
-    [Old AttrBonuses](/keeperrl_wiki/Old_AttrBonuses "wikilink")
-    [Old Attributes](/keeperrl_wiki/Old_Attributes "wikilink")
-    [Old Automaton](/keeperrl_wiki/Old_Automaton "wikilink")
-    [Old Available Reference Data For Modding KeeperRL](/keeperrl_wiki/Old_Available_Reference_Data_For_Modding_KeeperRL "wikilink")
-    [Old Bandit](/keeperrl_wiki/Old_Bandit "wikilink")
-    [Old Bat](/keeperrl_wiki/Old_Bat "wikilink")
-    [Old Beasts](/keeperrl_wiki/Old_Beasts "wikilink")
-    [Old Beast Cage](/keeperrl_wiki/Old_Beast_Cage "wikilink")
-    [Old Beast Lair](/keeperrl_wiki/Old_Beast_Lair "wikilink")
-    [Old Bed](/keeperrl_wiki/Old_Bed "wikilink")
-    [Old Blacksmith](/keeperrl_wiki/Old_Blacksmith "wikilink")
-    [Old Black Dragon](/keeperrl_wiki/Old_Black_Dragon "wikilink")
-    [Old Black Market](/keeperrl_wiki/Old_Black_Market "wikilink")
-    [Old Black Market Entry](/keeperrl_wiki/Old_Black_Market_Entry "wikilink")
-    [Old Black Market Guard](/keeperrl_wiki/Old_Black_Market_Guard "wikilink")
-    [Old Black Rat](/keeperrl_wiki/Old_Black_Rat "wikilink")
-    [Old Black Rats](/keeperrl_wiki/Old_Black_Rats "wikilink")
-    [Old Boar](/keeperrl_wiki/Old_Boar "wikilink")
-    [Old BuildRequirements](/keeperrl_wiki/Old_BuildRequirements "wikilink")
-    [Old Build Menu.txt](/keeperrl_wiki/Old_Build_Menu.txt "wikilink")
-    [Old BuiltinLayoutIDs](/keeperrl_wiki/Old_BuiltinLayoutIDs "wikilink")
-    [Old Builtin Layout Ids](/keeperrl_wiki/Old_Builtin_Layout_Ids "wikilink")
-    [Old Camel](/keeperrl_wiki/Old_Camel "wikilink")
-    [Old Campaign Mode](/keeperrl_wiki/Old_Campaign_Mode "wikilink")
-    [Old Campaign Villain.txt](/keeperrl_wiki/Old_Campaign_Villain.txt "wikilink")
-    [Old Campaign Villains.txt](/keeperrl_wiki/Old_Campaign_Villains.txt "wikilink")
-    [Old Cave Bear](/keeperrl_wiki/Old_Cave_Bear "wikilink")
-    [Old Cemetery](/keeperrl_wiki/Old_Cemetery "wikilink")
-    [Old Cemetery Entrance](/keeperrl_wiki/Old_Cemetery_Entrance "wikilink")
-    [Old Characteristics](/keeperrl_wiki/Old_Characteristics "wikilink")
-    [Old Cherub](/keeperrl_wiki/Old_Cherub "wikilink")
-    [Old Chicken](/keeperrl_wiki/Old_Chicken "wikilink")
-    [Old Child](/keeperrl_wiki/Old_Child "wikilink")
-    [Old Child (Spider Food)](/keeperrl_wiki/Old_Child_(Spider_Food) "wikilink")
-    [Old Child ](/keeperrl_wiki/Old_Child_ "wikilink")
-    [Old Clay Golem](/keeperrl_wiki/Old_Clay_Golem "wikilink")
-    [Old Cleric](/keeperrl_wiki/Old_Cleric "wikilink")
-    [Old Construction](/keeperrl_wiki/Old_Construction "wikilink")
-    [Old Constructions](/keeperrl_wiki/Old_Constructions "wikilink")
-    [Old Consumables](/keeperrl_wiki/Old_Consumables "wikilink")
-    [Old Copulate](/keeperrl_wiki/Old_Copulate "wikilink")
-    [Old Cottage Bandits](/keeperrl_wiki/Old_Cottage_Bandits "wikilink")
-    [Old Cottage Orcs](/keeperrl_wiki/Old_Cottage_Orcs "wikilink")
-    [Old Cow](/keeperrl_wiki/Old_Cow "wikilink")
-    [Old Crafting](/keeperrl_wiki/Old_Crafting "wikilink")
-    [Old CreatureIDs](/keeperrl_wiki/Old_CreatureIDs "wikilink")
-    [Old Creatures](/keeperrl_wiki/Old_Creatures "wikilink")
-    [Old Creature Guide](/keeperrl_wiki/Old_Creature_Guide "wikilink")
-    [Old Cure Poisoning](/keeperrl_wiki/Old_Cure_Poisoning "wikilink")
-    [Old Cyclops](/keeperrl_wiki/Old_Cyclops "wikilink")
-    [Old Dark Elf](/keeperrl_wiki/Old_Dark_Elf "wikilink")
-    [Old Dark Elf Cave](/keeperrl_wiki/Old_Dark_Elf_Cave "wikilink")
-    [Old Dark Elf Child](/keeperrl_wiki/Old_Dark_Elf_Child "wikilink")
-    [Old Dark Elf Dungeon Entrance](/keeperrl_wiki/Old_Dark_Elf_Dungeon_Entrance "wikilink")
-    [Old Dark Elf Lord](/keeperrl_wiki/Old_Dark_Elf_Lord "wikilink")
-    [Old Dark Elf Warrior](/keeperrl_wiki/Old_Dark_Elf_Warrior "wikilink")
-    [Old Dark Elves](/keeperrl_wiki/Old_Dark_Elves "wikilink")
-    [Old Dark Elves Enemy](/keeperrl_wiki/Old_Dark_Elves_Enemy "wikilink")
-    [Old Dark Mage](/keeperrl_wiki/Old_Dark_Mage "wikilink")
-    [Old Death](/keeperrl_wiki/Old_Death "wikilink")
-    [Old Deep Dungeon Floor](/keeperrl_wiki/Old_Deep_Dungeon_Floor "wikilink")
-    [Old Deer](/keeperrl_wiki/Old_Deer "wikilink")
-    [Old Demon Den Overground](/keeperrl_wiki/Old_Demon_Den_Overground "wikilink")
-    [Old Demon Den Underground](/keeperrl_wiki/Old_Demon_Den_Underground "wikilink")
-    [Old Demon Dweller](/keeperrl_wiki/Old_Demon_Dweller "wikilink")
-    [Old Demon Lord](/keeperrl_wiki/Old_Demon_Lord "wikilink")
-    [Old Disarm Traps](/keeperrl_wiki/Old_Disarm_Traps "wikilink")
-    [Old Djinn](/keeperrl_wiki/Old_Djinn "wikilink")
-    [Old Djinn Empty Maze](/keeperrl_wiki/Old_Djinn_Empty_Maze "wikilink")
-    [Old Djinn Entrance](/keeperrl_wiki/Old_Djinn_Entrance "wikilink")
-    [Old Dog](/keeperrl_wiki/Old_Dog "wikilink")
-    [Old Donkey](/keeperrl_wiki/Old_Donkey "wikilink")
-    [Old Doppleganger](/keeperrl_wiki/Old_Doppleganger "wikilink")
-    [Old Dormitory](/keeperrl_wiki/Old_Dormitory "wikilink")
-    [Old Download Mods](/keeperrl_wiki/Old_Download_Mods "wikilink")
-    [Old Dragon](/keeperrl_wiki/Old_Dragon "wikilink")
-    [Old Driad](/keeperrl_wiki/Old_Driad "wikilink")
-    [Old Driads](/keeperrl_wiki/Old_Driads "wikilink")
-    [Old Duke](/keeperrl_wiki/Old_Duke "wikilink")
-    [Old Dungeon Guide](/keeperrl_wiki/Old_Dungeon_Guide "wikilink")
-    [Old Dwarf](/keeperrl_wiki/Old_Dwarf "wikilink")
-    [Old Dwarf Baron](/keeperrl_wiki/Old_Dwarf_Baron "wikilink")
-    [Old Dwarf Blacksmith](/keeperrl_wiki/Old_Dwarf_Blacksmith "wikilink")
-    [Old Dwarf Cave](/keeperrl_wiki/Old_Dwarf_Cave "wikilink")
-    [Old Dwarf Female](/keeperrl_wiki/Old_Dwarf_Female "wikilink")
-    [Old Dwarves](/keeperrl_wiki/Old_Dwarves "wikilink")
-    [Old Earth Elemental](/keeperrl_wiki/Old_Earth_Elemental "wikilink")
-    [Old Effects](/keeperrl_wiki/Old_Effects "wikilink")
-    [Old EffectTypeIDs](/keeperrl_wiki/Old_EffectTypeIDs "wikilink")
-    [Old Elementalist](/keeperrl_wiki/Old_Elementalist "wikilink")
-    [Old Elementalist Entrance](/keeperrl_wiki/Old_Elementalist_Entrance "wikilink")
-    [Old Elementalist Floor](/keeperrl_wiki/Old_Elementalist_Floor "wikilink")
-    [Old Elf](/keeperrl_wiki/Old_Elf "wikilink")
-    [Old Elf Archer](/keeperrl_wiki/Old_Elf_Archer "wikilink")
-    [Old Elf Child](/keeperrl_wiki/Old_Elf_Child "wikilink")
-    [Old Elf Lord](/keeperrl_wiki/Old_Elf_Lord "wikilink")
-    [Old Elf Vision](/keeperrl_wiki/Old_Elf_Vision "wikilink")
-    [Old Elven Archer](/keeperrl_wiki/Old_Elven_Archer "wikilink")
-    [Old Elven Cottage](/keeperrl_wiki/Old_Elven_Cottage "wikilink")
-    [Old Elves](/keeperrl_wiki/Old_Elves "wikilink")
-    [Old Endless Mode](/keeperrl_wiki/Old_Endless_Mode "wikilink")
-    [Old Endless Waves Of Invaders](/keeperrl_wiki/Old_Endless_Waves_Of_Invaders "wikilink")
-    [Old Enemies](/keeperrl_wiki/Old_Enemies "wikilink")
-    [Old EnemyIDs](/keeperrl_wiki/Old_EnemyIDs "wikilink")
-    [Old Ent](/keeperrl_wiki/Old_Ent "wikilink")
-    [Old Ents](/keeperrl_wiki/Old_Ents "wikilink")
-    [Old Eskimo](/keeperrl_wiki/Old_Eskimo "wikilink")
-    [Old Eskimo Child](/keeperrl_wiki/Old_Eskimo_Child "wikilink")
-    [Old Eskimo Cottage](/keeperrl_wiki/Old_Eskimo_Cottage "wikilink")
-    [Old Eskimo Village](/keeperrl_wiki/Old_Eskimo_Village "wikilink")
-    [Old Evil Temple](/keeperrl_wiki/Old_Evil_Temple "wikilink")
-    [Old Experience](/keeperrl_wiki/Old_Experience "wikilink")
-    [Old ExtraTrainingIDs](/keeperrl_wiki/Old_ExtraTrainingIDs "wikilink")
-    [Old Fallen Corpses](/keeperrl_wiki/Old_Fallen_Corpses "wikilink")
-    [Old FAQ](/keeperrl_wiki/Old_FAQ "wikilink")
-    [Old Father Oblivion](/keeperrl_wiki/Old_Father_Oblivion "wikilink")
-    [Old Female Adventurer](/keeperrl_wiki/Old_Female_Adventurer "wikilink")
-    [Old Female Keeper](/keeperrl_wiki/Old_Female_Keeper "wikilink")
-    [Old File Keeper East.png](/keeperrl_wiki/Old_File_Keeper_East.png "wikilink")
-    [Old File Keeper Female West.png](/keeperrl_wiki/Old_File_Keeper_Female_West.png "wikilink")
-    [Old File Keeper Knight East.png](/keeperrl_wiki/Old_File_Keeper_Knight_East.png "wikilink")
-    [Old File Keeper Knight Female West.png](/keeperrl_wiki/Old_File_Keeper_Knight_Female_West.png "wikilink")
-    [Old File Keeper Knight West.png](/keeperrl_wiki/Old_File_Keeper_Knight_West.png "wikilink")
-    [Old File Keeper West.png](/keeperrl_wiki/Old_File_Keeper_West.png "wikilink")
-    [Old Fire Elemental](/keeperrl_wiki/Old_Fire_Elemental "wikilink")
-    [Old Fire Mage](/keeperrl_wiki/Old_Fire_Mage "wikilink")
-    [Old Fire Sphere](/keeperrl_wiki/Old_Fire_Sphere "wikilink")
-    [Old FixedSpawnLocations](/keeperrl_wiki/Old_FixedSpawnLocations "wikilink")
-    [Old Fly](/keeperrl_wiki/Old_Fly "wikilink")
-    [Old Flying](/keeperrl_wiki/Old_Flying "wikilink")
-    [Old Force Bolt](/keeperrl_wiki/Old_Force_Bolt "wikilink")
-    [Old Fox](/keeperrl_wiki/Old_Fox "wikilink")
-    [Old Friar](/keeperrl_wiki/Old_Friar "wikilink")
-    [Old FurnitureLayers](/keeperrl_wiki/Old_FurnitureLayers "wikilink")
-    [Old FurnitureTypes](/keeperrl_wiki/Old_FurnitureTypes "wikilink")
-    [Old Gaining Familiarity With Mods On KeeperRL](/keeperrl_wiki/Old_Gaining_Familiarity_With_Mods_On_KeeperRL "wikilink")
-    [Old Galeam](/keeperrl_wiki/Old_Galeam "wikilink")
-    [Old Gameplay](/keeperrl_wiki/Old_Gameplay "wikilink")
-    [Old Game Versions](/keeperrl_wiki/Old_Game_Versions "wikilink")
-    [Old Get All Nutrients And Minerals By Cooking Food In Rice Cooker](/keeperrl_wiki/Old_Get_All_Nutrients_And_Minerals_By_Cooking_Food_In_Rice_Cooker "wikilink")
-    [Old Ghost](/keeperrl_wiki/Old_Ghost "wikilink")
-    [Old Gnome](/keeperrl_wiki/Old_Gnome "wikilink")
-    [Old Gnomes](/keeperrl_wiki/Old_Gnomes "wikilink")
-    [Old Gnome Chief](/keeperrl_wiki/Old_Gnome_Chief "wikilink")
-    [Old Gnome Entrance](/keeperrl_wiki/Old_Gnome_Entrance "wikilink")
-    [Old Goat](/keeperrl_wiki/Old_Goat "wikilink")
-    [Old Goblin](/keeperrl_wiki/Old_Goblin "wikilink")
-    [Old Graveyard](/keeperrl_wiki/Old_Graveyard "wikilink")
-    [Old Green Dragon](/keeperrl_wiki/Old_Green_Dragon "wikilink")
-    [Old Guide For Adventurer Mode](/keeperrl_wiki/Old_Guide_For_Adventurer_Mode "wikilink")
-    [Old Halloween Kid](/keeperrl_wiki/Old_Halloween_Kid "wikilink")
-    [Old Harpy](/keeperrl_wiki/Old_Harpy "wikilink")
-    [Old Harpy Cave](/keeperrl_wiki/Old_Harpy_Cave "wikilink")
-    [Old Haste Self](/keeperrl_wiki/Old_Haste_Self "wikilink")
-    [Old Healing](/keeperrl_wiki/Old_Healing "wikilink")
-    [Old Horse](/keeperrl_wiki/Old_Horse "wikilink")
-    [Old How To Win As An Adventurer!!!](/keeperrl_wiki/Old_How_To_Win_As_An_Adventurer!!! "wikilink")
-    [Old Human Cottage](/keeperrl_wiki/Old_Human_Cottage "wikilink")
-    [Old Husky](/keeperrl_wiki/Old_Husky "wikilink")
-    [Old Hydra](/keeperrl_wiki/Old_Hydra "wikilink")
-    [Old Illusion](/keeperrl_wiki/Old_Illusion "wikilink")
-    [Old Immigration](/keeperrl_wiki/Old_Immigration "wikilink")
-    [Old Immigration.txt](/keeperrl_wiki/Old_Immigration.txt "wikilink")
-    [Old ImmigrationOptions](/keeperrl_wiki/Old_ImmigrationOptions "wikilink")
-    [Old ImmigrationRequirements](/keeperrl_wiki/Old_ImmigrationRequirements "wikilink")
-    [Old Imp](/keeperrl_wiki/Old_Imp "wikilink")
-    [Old Imps](/keeperrl_wiki/Old_Imps "wikilink")
-    [Old Installations](/keeperrl_wiki/Old_Installations "wikilink")
-    [Old Iron Golem](/keeperrl_wiki/Old_Iron_Golem "wikilink")
-    [Old Items](/keeperrl_wiki/Old_Items "wikilink")
-    [Old ItemTypes](/keeperrl_wiki/Old_ItemTypes "wikilink")
-    [Old Jackal](/keeperrl_wiki/Old_Jackal "wikilink")
-    [Old Jester](/keeperrl_wiki/Old_Jester "wikilink")
-    [Old Jewelry](/keeperrl_wiki/Old_Jewelry "wikilink")
-    [Old Keeper](/keeperrl_wiki/Old_Keeper "wikilink")
-    [Old Keeper Mode](/keeperrl_wiki/Old_Keeper_Mode "wikilink")
-    [Old Knife Throwing](/keeperrl_wiki/Old_Knife_Throwing "wikilink")
-    [Old Knight](/keeperrl_wiki/Old_Knight "wikilink")
-    [Old Knights](/keeperrl_wiki/Old_Knights "wikilink")
-    [Old Kobold](/keeperrl_wiki/Old_Kobold "wikilink")
-    [Old Kobold Cave](/keeperrl_wiki/Old_Kobold_Cave "wikilink")
-    [Old Kraken](/keeperrl_wiki/Old_Kraken "wikilink")
-    [Old Laboratory](/keeperrl_wiki/Old_Laboratory "wikilink")
-    [Old LastingEffects](/keeperrl_wiki/Old_LastingEffects "wikilink")
-    [Old Lava Golem](/keeperrl_wiki/Old_Lava_Golem "wikilink")
-    [Old Lawful Keepers](/keeperrl_wiki/Old_Lawful_Keepers "wikilink")
-    [Old Legendary Beast](/keeperrl_wiki/Old_Legendary_Beast "wikilink")
-    [Old Legendary Humanoid](/keeperrl_wiki/Old_Legendary_Humanoid "wikilink")
-    [Old Legless](/keeperrl_wiki/Old_Legless "wikilink")
-    [Old LeisureZone](/keeperrl_wiki/Old_LeisureZone "wikilink")
-    [Old Library](/keeperrl_wiki/Old_Library "wikilink")
-    [Old Lizardman](/keeperrl_wiki/Old_Lizardman "wikilink")
-    [Old Lizardman Chief](/keeperrl_wiki/Old_Lizardman_Chief "wikilink")
-    [Old Lizardman Cottage](/keeperrl_wiki/Old_Lizardman_Cottage "wikilink")
-    [Old Lizardman Lord](/keeperrl_wiki/Old_Lizardman_Lord "wikilink")
-    [Old Lost Soul](/keeperrl_wiki/Old_Lost_Soul "wikilink")
-    [Old Magic Shield](/keeperrl_wiki/Old_Magic_Shield "wikilink")
-    [Old Main Lizardmen](/keeperrl_wiki/Old_Main_Lizardmen "wikilink")
-    [Old Main Page](/keeperrl_wiki/Old_Main_Page "wikilink")
-    [Old Manufactories](/keeperrl_wiki/Old_Manufactories "wikilink")
-    [Old Map Editor Ideas](/keeperrl_wiki/Old_Map_Editor_Ideas "wikilink")
-    [Old Minions](/keeperrl_wiki/Old_Minions "wikilink")
-    [Old Mini Lizardmen](/keeperrl_wiki/Old_Mini_Lizardmen "wikilink")
-    [Old Minotaur](/keeperrl_wiki/Old_Minotaur "wikilink")
-    [Old Miscellaneous Items](/keeperrl_wiki/Old_Miscellaneous_Items "wikilink")
-    [Old Modding Guide](/keeperrl_wiki/Old_Modding_Guide "wikilink")
-    [Old Modding Reference Data](/keeperrl_wiki/Old_Modding_Reference_Data "wikilink")
-    [Old Morale](/keeperrl_wiki/Old_Morale "wikilink")
-    [Old Mummy](/keeperrl_wiki/Old_Mummy "wikilink")
-    [Old Night Vision](/keeperrl_wiki/Old_Night_Vision "wikilink")
-    [Old Nomad](/keeperrl_wiki/Old_Nomad "wikilink")
-    [Old Nomad Child](/keeperrl_wiki/Old_Nomad_Child "wikilink")
-    [Old Nomad Cottage](/keeperrl_wiki/Old_Nomad_Cottage "wikilink")
-    [Old Nomad Village](/keeperrl_wiki/Old_Nomad_Village "wikilink")
-    [Old Non Aggressive Bandits](/keeperrl_wiki/Old_Non_Aggressive_Bandits "wikilink")
-    [Old OfficialAlpha26GameConfigs](/keeperrl_wiki/Old_OfficialAlpha26GameConfigs "wikilink")
-    [Old Official Game Configs](/keeperrl_wiki/Old_Official_Game_Configs "wikilink")
-    [Old Ogre](/keeperrl_wiki/Old_Ogre "wikilink")
-    [Old Ogre Cave](/keeperrl_wiki/Old_Ogre_Cave "wikilink")
-    [Old Open Ant Nest](/keeperrl_wiki/Old_Open_Ant_Nest "wikilink")
-    [Old Orc](/keeperrl_wiki/Old_Orc "wikilink")
-    [Old Orc Cave](/keeperrl_wiki/Old_Orc_Cave "wikilink")
-    [Old Orc Healer](/keeperrl_wiki/Old_Orc_Healer "wikilink")
-    [Old Orc Mage](/keeperrl_wiki/Old_Orc_Mage "wikilink")
-    [Old Orc Shaman](/keeperrl_wiki/Old_Orc_Shaman "wikilink")
-    [Old Orc Village](/keeperrl_wiki/Old_Orc_Village "wikilink")
-    [Old Orders](/keeperrl_wiki/Old_Orders "wikilink")
-    [Old Peasant](/keeperrl_wiki/Old_Peasant "wikilink")
-    [Old Peseant](/keeperrl_wiki/Old_Peseant "wikilink")
-    [Old Pig](/keeperrl_wiki/Old_Pig "wikilink")
-    [Old Pigsty](/keeperrl_wiki/Old_Pigsty "wikilink")
-    [Old Player Characters](/keeperrl_wiki/Old_Player_Characters "wikilink")
-    [Old Player Contributed Sprites](/keeperrl_wiki/Old_Player_Contributed_Sprites "wikilink")
-    [Old Player Creatures.txt](/keeperrl_wiki/Old_Player_Creatures.txt "wikilink")
-    [Old Player Ideas, Requests And Contributions](/keeperrl_wiki/Old_Player_Ideas,_Requests_And_Contributions "wikilink")
-    [Old Player Requests For New Content](/keeperrl_wiki/Old_Player_Requests_For_New_Content "wikilink")
-    [Old Player Requests For New Game Mechanics](/keeperrl_wiki/Old_Player_Requests_For_New_Game_Mechanics "wikilink")
-    [Old Polar Bear](/keeperrl_wiki/Old_Polar_Bear "wikilink")
-    [Old Polar Fox](/keeperrl_wiki/Old_Polar_Fox "wikilink")
-    [Old Potions](/keeperrl_wiki/Old_Potions "wikilink")
-    [Old Pre-fix Ideas](/keeperrl_wiki/Old_Pre-fix_Ideas "wikilink")
-    [Old Priest](/keeperrl_wiki/Old_Priest "wikilink")
-    [Old Prison](/keeperrl_wiki/Old_Prison "wikilink")
-    [Old Prisoner](/keeperrl_wiki/Old_Prisoner "wikilink")
-    [Old Prisoner Guide](/keeperrl_wiki/Old_Prisoner_Guide "wikilink")
-    [Old Quarters](/keeperrl_wiki/Old_Quarters "wikilink")
-    [Old Quick Start Walkthrough](/keeperrl_wiki/Old_Quick_Start_Walkthrough "wikilink")
-    [Old Rat](/keeperrl_wiki/Old_Rat "wikilink")
-    [Old Rat Cave](/keeperrl_wiki/Old_Rat_Cave "wikilink")
-    [Old Rat King](/keeperrl_wiki/Old_Rat_King "wikilink")
-    [Old Rat Lady](/keeperrl_wiki/Old_Rat_Lady "wikilink")
-    [Old Rat People Cave](/keeperrl_wiki/Old_Rat_People_Cave "wikilink")
-    [Old Rat Soldier](/keeperrl_wiki/Old_Rat_Soldier "wikilink")
-    [Old Raven](/keeperrl_wiki/Old_Raven "wikilink")
-    [Old Recruits](/keeperrl_wiki/Old_Recruits "wikilink")
-    [Old Red Dragon](/keeperrl_wiki/Old_Red_Dragon "wikilink")
-    [Old Requests For Game Messages](/keeperrl_wiki/Old_Requests_For_Game_Messages "wikilink")
-    [Old Requests For Graphics](/keeperrl_wiki/Old_Requests_For_Graphics "wikilink")
-    [Old Requests For Immigration Mechanics](/keeperrl_wiki/Old_Requests_For_Immigration_Mechanics "wikilink")
-    [Old Requests For Keys, Buttons, Menus](/keeperrl_wiki/Old_Requests_For_Keys,_Buttons,_Menus "wikilink")
-    [Old Requests For New Allies](/keeperrl_wiki/Old_Requests_For_New_Allies "wikilink")
-    [Old Requests For New Armour](/keeperrl_wiki/Old_Requests_For_New_Armour "wikilink")
-    [Old Requests For New Biomes](/keeperrl_wiki/Old_Requests_For_New_Biomes "wikilink")
-    [Old Requests For New Configurations](/keeperrl_wiki/Old_Requests_For_New_Configurations "wikilink")
-    [Old Requests For New Damage Spells](/keeperrl_wiki/Old_Requests_For_New_Damage_Spells "wikilink")
-    [Old Requests For New Installations](/keeperrl_wiki/Old_Requests_For_New_Installations "wikilink")
-    [Old Requests For New Jewellery](/keeperrl_wiki/Old_Requests_For_New_Jewellery "wikilink")
-    [Old Requests For New Minions](/keeperrl_wiki/Old_Requests_For_New_Minions "wikilink")
-    [Old Requests For New Rooms](/keeperrl_wiki/Old_Requests_For_New_Rooms "wikilink")
-    [Old Requests For New Spells](/keeperrl_wiki/Old_Requests_For_New_Spells "wikilink")
-    [Old Requests For New Tasks And Skills](/keeperrl_wiki/Old_Requests_For_New_Tasks_And_Skills "wikilink")
-    [Old Requests For New Technology](/keeperrl_wiki/Old_Requests_For_New_Technology "wikilink")
-    [Old Requests For New Traits](/keeperrl_wiki/Old_Requests_For_New_Traits "wikilink")
-    [Old Requests For New Traps](/keeperrl_wiki/Old_Requests_For_New_Traps "wikilink")
-    [Old Requests For New Triggers](/keeperrl_wiki/Old_Requests_For_New_Triggers "wikilink")
-    [Old Requests For New Unequipped Items](/keeperrl_wiki/Old_Requests_For_New_Unequipped_Items "wikilink")
-    [Old Requests For New Villains](/keeperrl_wiki/Old_Requests_For_New_Villains "wikilink")
-    [Old Requests For New Weapons](/keeperrl_wiki/Old_Requests_For_New_Weapons "wikilink")
-    [Old Requests For New Wildlife](/keeperrl_wiki/Old_Requests_For_New_Wildlife "wikilink")
-    [Old Requests For Resource Collection Mechanics](/keeperrl_wiki/Old_Requests_For_Resource_Collection_Mechanics "wikilink")
-    [Old Requests For Screen Layout](/keeperrl_wiki/Old_Requests_For_Screen_Layout "wikilink")
-    [Old Requests For Sound](/keeperrl_wiki/Old_Requests_For_Sound "wikilink")
-    [Old Requests For World Map Mechanics](/keeperrl_wiki/Old_Requests_For_World_Map_Mechanics "wikilink")
-    [Old ResourceIDs](/keeperrl_wiki/Old_ResourceIDs "wikilink")
-    [Old Resources](/keeperrl_wiki/Old_Resources "wikilink")
-    [Old Ritual Room](/keeperrl_wiki/Old_Ritual_Room "wikilink")
-    [Old Roguelike Realtime Strategy Concept](/keeperrl_wiki/Old_Roguelike_Realtime_Strategy_Concept "wikilink")
-    [Old Rooms](/keeperrl_wiki/Old_Rooms "wikilink")
-    [Old Room Layouts](/keeperrl_wiki/Old_Room_Layouts "wikilink")
-    [Old Ruins](/keeperrl_wiki/Old_Ruins "wikilink")
-    [Old Scorpion](/keeperrl_wiki/Old_Scorpion "wikilink")
-    [Old Sealed Ant Nest](/keeperrl_wiki/Old_Sealed_Ant_Nest "wikilink")
-    [Old Shallow Dungeon Floor](/keeperrl_wiki/Old_Shallow_Dungeon_Floor "wikilink")
-    [Old Shaman](/keeperrl_wiki/Old_Shaman "wikilink")
-    [Old Shelob](/keeperrl_wiki/Old_Shelob "wikilink")
-    [Old Shopkeeper](/keeperrl_wiki/Old_Shopkeeper "wikilink")
-    [Old Shortcut Keys](/keeperrl_wiki/Old_Shortcut_Keys "wikilink")
-    [Old Skeleton](/keeperrl_wiki/Old_Skeleton "wikilink")
-    [Old SkillIDs](/keeperrl_wiki/Old_SkillIDs "wikilink")
-    [Old Skills](/keeperrl_wiki/Old_Skills "wikilink")
-    [Old Small Sealed Ant Nest](/keeperrl_wiki/Old_Small_Sealed_Ant_Nest "wikilink")
-    [Old Snake](/keeperrl_wiki/Old_Snake "wikilink")
-    [Old Soft Monster](/keeperrl_wiki/Old_Soft_Monster "wikilink")
-    [Old Sokoban Entry](/keeperrl_wiki/Old_Sokoban_Entry "wikilink")
-    [Old Sokoban Reward](/keeperrl_wiki/Old_Sokoban_Reward "wikilink")
-    [Old Soldier Ant](/keeperrl_wiki/Old_Soldier_Ant "wikilink")
-    [Old Sorcerer](/keeperrl_wiki/Old_Sorcerer "wikilink")
-    [Old Sorcery](/keeperrl_wiki/Old_Sorcery "wikilink")
-    [Old SpecialTraitTypes](/keeperrl_wiki/Old_SpecialTraitTypes "wikilink")
-    [Old Spells](/keeperrl_wiki/Old_Spells "wikilink")
-    [Old Spider](/keeperrl_wiki/Old_Spider "wikilink")
-    [Old Spirit](/keeperrl_wiki/Old_Spirit "wikilink")
-    [Old Statue](/keeperrl_wiki/Old_Statue "wikilink")
-    [Old Stealing](/keeperrl_wiki/Old_Stealing "wikilink")
-    [Old Storage](/keeperrl_wiki/Old_Storage "wikilink")
-    [Old Structures And Installations](/keeperrl_wiki/Old_Structures_And_Installations "wikilink")
-    [Old Stun Ray](/keeperrl_wiki/Old_Stun_Ray "wikilink")
-    [Old Succubus](/keeperrl_wiki/Old_Succubus "wikilink")
-    [Old Swimming](/keeperrl_wiki/Old_Swimming "wikilink")
-    [Old Talk Imp](/keeperrl_wiki/Old_Talk_Imp "wikilink")
-    [Old Talk Main Page](/keeperrl_wiki/Old_Talk_Main_Page "wikilink")
-    [Old Talk Requests For New Villains](/keeperrl_wiki/Old_Talk_Requests_For_New_Villains "wikilink")
-    [Old Team Strategy](/keeperrl_wiki/Old_Team_Strategy "wikilink")
-    [Old TechIDs](/keeperrl_wiki/Old_TechIDs "wikilink")
-    [Old Technologies](/keeperrl_wiki/Old_Technologies "wikilink")
-    [Old Technology.txt](/keeperrl_wiki/Old_Technology.txt "wikilink")
-    [Old Temple](/keeperrl_wiki/Old_Temple "wikilink")
-    [Old Teuton](/keeperrl_wiki/Old_Teuton "wikilink")
-    [Old Teutonic Grandmaster](/keeperrl_wiki/Old_Teutonic_Grandmaster "wikilink")
-    [Old Teutons](/keeperrl_wiki/Old_Teutons "wikilink")
-    [Old The Duke](/keeperrl_wiki/Old_The_Duke "wikilink")
-    [Old Thief](/keeperrl_wiki/Old_Thief "wikilink")
-    [Old Thief Leader](/keeperrl_wiki/Old_Thief_Leader "wikilink")
-    [Old Thieves](/keeperrl_wiki/Old_Thieves "wikilink")
-    [Old Throne](/keeperrl_wiki/Old_Throne "wikilink")
-    [Old Torture Room](/keeperrl_wiki/Old_Torture_Room "wikilink")
-    [Old Training](/keeperrl_wiki/Old_Training "wikilink")
-    [Old Training Room](/keeperrl_wiki/Old_Training_Room "wikilink")
-    [Old TraitIDs](/keeperrl_wiki/Old_TraitIDs "wikilink")
-    [Old Traits](/keeperrl_wiki/Old_Traits "wikilink")
-    [Old Traps](/keeperrl_wiki/Old_Traps "wikilink")
-    [Old Treasure Chest](/keeperrl_wiki/Old_Treasure_Chest "wikilink")
-    [Old Treasure Room](/keeperrl_wiki/Old_Treasure_Room "wikilink")
-    [Old Tree Spirit](/keeperrl_wiki/Old_Tree_Spirit "wikilink")
-    [Old TribeAlignments](/keeperrl_wiki/Old_TribeAlignments "wikilink")
-    [Old Tribes](/keeperrl_wiki/Old_Tribes "wikilink")
-    [Old Tutorial Village](/keeperrl_wiki/Old_Tutorial_Village "wikilink")
-    [Old Unarmed Melee](/keeperrl_wiki/Old_Unarmed_Melee "wikilink")
-    [Old Understanding The File Formats For KeeperRL](/keeperrl_wiki/Old_Understanding_The_File_Formats_For_KeeperRL "wikilink")
-    [Old Unicorn](/keeperrl_wiki/Old_Unicorn "wikilink")
-    [Old Unicorn Herd](/keeperrl_wiki/Old_Unicorn_Herd "wikilink")
-    [Old User Icezander](/keeperrl_wiki/Old_User_Icezander "wikilink")
-    [Old User Keeperman](/keeperrl_wiki/Old_User_Keeperman "wikilink")
-    [Old User Owen](/keeperrl_wiki/Old_User_Owen "wikilink")
-    [Old User Taxibutler](/keeperrl_wiki/Old_User_Taxibutler "wikilink")
-    [Old Vampire](/keeperrl_wiki/Old_Vampire "wikilink")
-    [Old Vampire Lord](/keeperrl_wiki/Old_Vampire_Lord "wikilink")
-    [Old Very Deep Dungeon Floor](/keeperrl_wiki/Old_Very_Deep_Dungeon_Floor "wikilink")
-    [Old Video Tutorials From Nat20](/keeperrl_wiki/Old_Video_Tutorials_From_Nat20 "wikilink")
-    [Old ViewIDs](/keeperrl_wiki/Old_ViewIDs "wikilink")
-    [Old Village](/keeperrl_wiki/Old_Village "wikilink")
-    [Old VillainTypes](/keeperrl_wiki/Old_VillainTypes "wikilink")
-    [Old Vulture](/keeperrl_wiki/Old_Vulture "wikilink")
-    [Old Warrior](/keeperrl_wiki/Old_Warrior "wikilink")
-    [Old Warriors](/keeperrl_wiki/Old_Warriors "wikilink")
-    [Old Water Elemental](/keeperrl_wiki/Old_Water_Elemental "wikilink")
-    [Old Weapons](/keeperrl_wiki/Old_Weapons "wikilink")
-    [Old Weapon Melee](/keeperrl_wiki/Old_Weapon_Melee "wikilink")
-    [Old Werewolf](/keeperrl_wiki/Old_Werewolf "wikilink")
-    [Old White Dragon](/keeperrl_wiki/Old_White_Dragon "wikilink")
-    [Old White Dragon Dungeon Floor](/keeperrl_wiki/Old_White_Dragon_Dungeon_Floor "wikilink")
-    [Old White Dragon Entrance](/keeperrl_wiki/Old_White_Dragon_Entrance "wikilink")
-    [Old White Wizard](/keeperrl_wiki/Old_White_Wizard "wikilink")
-    [Old Witch](/keeperrl_wiki/Old_Witch "wikilink")
-    [Old Witchman](/keeperrl_wiki/Old_Witchman "wikilink")
-    [Old Wizard Tower](/keeperrl_wiki/Old_Wizard_Tower "wikilink")
-    [Old Wizard Tower Entrance](/keeperrl_wiki/Old_Wizard_Tower_Entrance "wikilink")
-    [Old Wolf](/keeperrl_wiki/Old_Wolf "wikilink")
-    [Old Word Of Power](/keeperrl_wiki/Old_Word_Of_Power "wikilink")
-    [Old WorkshopsMenu.txt](/keeperrl_wiki/Old_WorkshopsMenu.txt "wikilink")
-    [Old Workshops Menu.txt](/keeperrl_wiki/Old_Workshops_Menu.txt "wikilink")
-    [Old Yellow Dragon](/keeperrl_wiki/Old_Yellow_Dragon "wikilink")
-    [Old Yeti](/keeperrl_wiki/Old_Yeti "wikilink")
-    [Old YouTube Videos](/keeperrl_wiki/Old_YouTube_Videos "wikilink")
-    [Old Z-Level Guide](/keeperrl_wiki/Old_Z-Level_Guide "wikilink")
-    [Old Zombie](/keeperrl_wiki/Old_Zombie "wikilink")
-    [Old ZoneIds](/keeperrl_wiki/Old_ZoneIds "wikilink")
-    [Previous Wiki](/keeperrl_wiki/Previous_Wiki "wikilink")
