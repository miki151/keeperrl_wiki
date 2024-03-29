---
title: Alpha30
permalink: Alpha30/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Releases](/keeperrl_wiki/Releases "wikilink")

Full change log
===============

Gnomes
------


-   New mechanic involving assembling automaton minions from different body parts.
-   4 types of corpuses: light, normal, heavy, and helicopterum. Made from wood, iron or adamantine.
-   Humanoid, fire breathing, acid spitting and archer heads.
-   Melee, drill, crafting, and repair arms.
-   No single Keeper creature, all gnomes need to be killed in order to lose the game.
-   New traps: "destroy walls" and "trap trigger".


Gameplay
--------
-   Some enemies will be retired when they kill the player, and the player's base will be used as that enemy's lair in future games.
-   The player can choose any of the 5 existing biomes to build their base.
-   Creatures get "slayer" titles and stat bonuses for killing tribe leaders.
-   Keepers make paintings and write poems inspired by real game events.
-   Guard zone designation that minions will take turns guarding.
-   Creatures can fight with multiple weapons if they have the "multi-weapon" skill.
-   Zombies have a special "Swarmer" trait, which increases their damage and defense for every other zombie nearby.
-   Writing a poem or making a painting has a very small chance of summoning a demon.
-   Shamans and other creatures with the "shamanism" skill surround themselves by combat-worthy spirits.
-   Keepers abuse their minions to make them work faster.
-   Hostility between creatures of the same tribe times out after 50 turns.
-   Vampires will sometimes regenerate lost or injured body parts after biting an enemy.
-   Minions eat at dining tables instead of killing pigs directly.
-   Certain creatures and weapons get special attack and defense bonuses based on the enemy's race, being indoors, only at night, etc.
-   Bandits are less aggressive and the minimum gold amount that triggers them is increased.
-   Insane minions with the absorption skill are still allowed to absorb.
-   Non-prisoner workers can be assigned quarters.
-   Ranged damage is taken into account when evaluating how dangerous a creature is.
-   Prisoners go back to prison when idle.
-   Removed peacefulness and invisibility permanent effects from altar destruction.
-   Minions can create moonshine from rats and get drunk.
-   Creatures made of fire emit light.
-   Added amulets of life saving.
-   Brainless creatures don't have morale.
-   Undead get brains.
-   Friendly creatures don't get angry if attacked by an effect that doesn't hurt them (for example by fire if fire resistant).
-   Discovered allies that auto-join don't use up population slots.
-   Traveling to other maps is not prevented if enemies are fleeing from the player.
-   The game considers an enemy conquered by the player only if he/she killed at least one creature from that enemy.
-   Added "Fire trap" spell used by red dragons and other creatures.
-   A spying creature's identity is uncovered if items are looted.
-   An allied tribe will get angry if items are stolen.
-   Some villains, like ants and dwarves will only defend their mineral patches instead of attacking the player, if their minerals are breached.
-   Dwarves receive an "unstable" status, which can cause them to become insane if they witness the death of an ally.
-   Travel to other maps is not possible when carrying unpaid items.


Content
-------

-   New "Hell" hidden dungeon of end-game difficulty with new enemies, special items and other surprises.
-   "Black market" hidden level with special equipment.
-   "Adoxie Vault" special level.
-   New minions of the "less evil" Keeper: angels, galeams, cherubs, cleric, artisan, and recruitable Teutonic Knights.
-   Blacksmith location with an artisan of legendary crafting skills.
-   The Dwarf Baron enemy contains a blacksmith of legendary crafting skills.
-   Wizard tower location.
-   Ghost ruins are less common.
-   Added random corpses with loot on some maps.
-   "Animate weapons" spell added to some enemies.
-   Scrolls of Audience, which work similarly to sitting on thrones.
-   Added stone bridges, wooden bridges now burn if placed on lava.
-   Added an "Ice demon" minion.
-   Added a "weaker" dwarf creature that replaces the dwarf fighter everywhere except in the Dwarf Baron settlement.
-   Added a yellow dragon enemy with an acid attack.
-   Added Naga creatures of various colors and abilities.
-   Removed insane orc healer immigrant.
-   Added flowers to ground levels.
-   Added trees to the arctic biome.


Modding
-------

-   Loading multiple mods at the same time is now possible.
-   All graphics in the game can be reloaded by pressing F8 while playing.
-   The size of the campaign map and enemy limits can be increased in mods.
-   Creature inventories are moved to creatures.txt.
-   Allowed defining custom biomes.
-   Allowed defining custom workshops.
-   Allowed defining custom resources.
-   Enemy dungeons may have branches.
-   Mods are moved to the "mods" folder.
-   Existing mod or vanilla game elements can be modified or appended to.
-   New Effects: TakeItems, RemoveFurniture, ChainUntilFail, AddMinionTrait, ChooseRandom, FirstSuccessful, IncreaseSkill, IncreaseWorkshopSkill,
-   Psychiatry, AIBelowHealth, Name, Description, FixedDamage, ColorVariant, Audience, GrantAbility, TriggerTrap.
-   DestroyWalls effect can work with Area and directional spells.
-   Filter Effect for applying effects conditionally: depending on creatures's health, enemy/allied status, body material, being hidden, being a
-   prisoner/civilian, being an automaton, being indoors/outdoors, at night/day, creature's race, holding a special item, checking for global game -   flags, and more.
-   Stairs can have custom effects, including Filter, which lets you require certain things before a creature can pass through.
-   Custom Effect triggered when chatting with a creature.
-   Custom Effect for creature's death.
-   Custom Effect for furniture "entry".
-   Custom Effect for furniture "tick".
-   Custom Effect for furniture usage.
-   Summon and SummonEnemy effects have a tweak-able timer for creature to disappear.
-   World generation can be tested by running "keeper.exe --worldgen_test" in command line.
-   Overriding endless enemies or specifying custom enemies per keeper is possible.
-   Can define separate orders for digging and cutting trees.
-   Immigrant special traits can include timed LastingEffects.
-   Added "gold" body material.
-   Enemy dungeons can have custom level names.


UI
--

-   Activities can be disabled for an entire minion group.
-   A list of kills can be inspected for every minion.
-   When a sprite file is not found, the game will render a random sprite, instead of crashing.
-   Poison gas gets a nice particle effect animation.
-   When dragging creatures, their shortest path to the target is displayed.
-   Whole creature groups can be dragged from the menu to workshops and other furniture.
-   Constructions and workshop items that can't be afforded are colored red.
-   New Keeperopedia UI with bestiary, items and spells.
-   New "keeper in danger" warning UI with options to disable or turn off auto-pause.
-   The "keeper in danger" pop-up only warns about recent wounds.
-   New glyph sprites.
-   New trap sprites.
-   Potion sprites have different colors depending on the potion's effect.
-   Company logo splash screen while the game is starting.
-   Game initialization takes place during the loading screen to avoid lag when game begins.
-   Added commas to spell school list in minion menu.
-   Forbidden zone is rendered on top of objects if it otherwise wouldn't have been visible beneath.
-   Moved the [new team] button to above the team list.
-   Time interval between autosaves can be changed.
-   Added a mini-menu for scrolling directly to chosen z-level.
-   Current z-level depth is shown in control mode.
-   Removed "visible enemies" and some mostly unused settings from the minions tab.
-   Minion menu shows body description and intrinsic attacks.
-   Mod descriptions can be scrolled in mod menu.
-   The game asks if you want to start with a tutorial the first time you play.
-   Added "cancel" buttons to mod and dungeon downloading progress bars.


Fixes
-----

-   Massive reduction in RAM usage.
-   Optimized particle effects animations.
-   Building bridges on z-levels is now possible without having first to descend manually.
-   Fixed bug involving inability to place structures in some visible areas.
-   Fixed mixing messages from different games in message boards.
-   Fixed music playback restarting on some computers.
-   Fixed wrong cursor position glitch in full screen.
-   Ranged attacks don't abuse the "parry" ability.
-   Illusions are ignored when AI forms formations.
-   Fixed endless enemies saving issue which led to attacks being cancelled after saving and loading.
-   Reduced VRAM usage by sprites loaded in mods.
-   Wishing for Suicide, stunned, summoned, invulnerable and "turned off" effects is disabled.
-   Increased cool down of "ice cone" to avoid infinite freezing loop.
-   Removed sprite limit per mod.
-   Fixed a rare crash when the wish spell is granted by a piece of equipment.
-   Traveling by bumping into the level border is only allowed on the ground level.
-   Fixed UI crash when alt-tabbing out of full screen.
-   Fixed a rare crash in graphics likely caused by changed system clock.
-   Fixed issue with rebuilding triggered traps.
-   Fixed crash in direction choice UI.
-   Made it impossible to place a trap on up stairs after claiming the tile.
-   Items that are already in storage can't be pillaged.
-   The "Zoom in UI" is available only if resolution is 1600x1200 or higher.
-   Fixed crash when trying to teleport outside of map bounds.

[MainPage](/keeperrl_wiki/ "wikilink")>>[Releases](/keeperrl_wiki/Releases "wikilink")

Other items in this section
-    [Alpha15](/keeperrl_wiki/Alpha15 "wikilink")
-    [Alpha16](/keeperrl_wiki/Alpha16 "wikilink")
-    [Alpha17](/keeperrl_wiki/Alpha17 "wikilink")
-    [Alpha18](/keeperrl_wiki/Alpha18 "wikilink")
-    [Alpha19](/keeperrl_wiki/Alpha19 "wikilink")
-    [Alpha20](/keeperrl_wiki/Alpha20 "wikilink")
-    [Alpha21](/keeperrl_wiki/Alpha21 "wikilink")
-    [Alpha22](/keeperrl_wiki/Alpha22 "wikilink")
-    [Alpha23](/keeperrl_wiki/Alpha23 "wikilink")
-    [Alpha24](/keeperrl_wiki/Alpha24 "wikilink")
-    [Alpha25](/keeperrl_wiki/Alpha25 "wikilink")
-    [Alpha26](/keeperrl_wiki/Alpha26 "wikilink")
-    [Alpha27](/keeperrl_wiki/Alpha27 "wikilink")
-    [Alpha28](/keeperrl_wiki/Alpha28 "wikilink")
-    [Alpha29](/keeperrl_wiki/Alpha29 "wikilink")
-    [Alpha31](/keeperrl_wiki/Alpha31 "wikilink")
-    [Alpha32](/keeperrl_wiki/Alpha32 "wikilink")
-    [Alpha33](/keeperrl_wiki/Alpha33 "wikilink")
-    [Alpha34](/keeperrl_wiki/Alpha34 "wikilink")
-    [Alpha35](/keeperrl_wiki/Alpha35 "wikilink")
-    [Alpha36](/keeperrl_wiki/Alpha36 "wikilink")
-    [Historical Mythos](/keeperrl_wiki/Historical_Mythos "wikilink")
