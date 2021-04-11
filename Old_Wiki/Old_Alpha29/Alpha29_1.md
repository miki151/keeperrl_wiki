---
title: Alpha29 1
permalink: Alpha29_1/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Alpha29](/keeperrl_wiki/Old_Alpha29 "wikilink")

Gameplay
*Mods and retired dungeons are shared on Steam Workshop.
*Contagious plague effect.
*Z-level enemies can attack upon being discovered.
*Enemy aggression can be tweaked in settings.
*Spying effect, which allows infiltrating enemy territory.
*Equipped shield prevents equipping bows and two-handed weapons.
*New “parry” attribute, which prevents de-buffs when surrounded by enemies.
*Temporarily insane creatures won’t make allies hostile forever.
*All consumable items are automatically picked up by minions.
*Creatures with 0 ranged damage can’t equip bows.
*Poetry writing.
*Creatures can’t cast spells at enemies that they can’t see.
*Bodies of water can become bloody after a large battle.
*Items can have randomized modifiers.
*Walking into the map border opens the travel menu.
*Other furniture can be built on top of prison floor.

Content
*Special item ingredients: hydra tongue, cyclops brain, dragon scales, and more.
*Iron and adamantine shields.
*Wizard hats a’ka Cornuthaums.
*Underground treeshrooms for players who always run out of wood.
*Desert biome with thieves castle and a djinn in a dungeon.
*Snow biome with Eskimos and a white dragon.
*Totems that have a permanent area effect: healing, blindness, bleeding.
*Evil God Adoxie is in vanilla game with his own secret level!
*Double trouble unique ability.
*Black rats infected with plague z-level.
*Group healing spell affects only allies.

Modding
Items are moddable.
BuildingInfo is moddable.
Z-level width is moddable.
Items can grant a custom ability.
Creature first names are moddable.
More than 10 keeper/adventurer avatars are allowed
Game doesn’t crash when mod specifies skill level outside of [0;1] range.
New effect types: Chance, Message, Enhance, Wish, Filter, Ice, IMMOBILE, FROZEN, COLD_RESISTANCE
Creatures can drop custom items (body parts).

UI
Improved mod menu.
Added “locate” button to minion page.
Rectangle selection on the map shows rectangle dimensions.
Uploaded dungeons include a screenshot of an area chosen by the dungeon’s author.
Main menu and loading bar visual changes.
Added warning when online features are disabled and trying to download maps/mods.
Main menu can display personal messages from the developer.
Added item effect description to item’s tooltip.
Added some handy links to the main menu.
Return key closes text windows.

Fixes
Gameplay loop optimizations.
Fixed spell schools of legendary humanoids.
Limited immigrant spawning to the ground level if possible.
Fixed issue with placing the smaller castle in bad position on the map.
Fixed rare crash when removing nonexistent team member in control mode.
Added diagnostics for a rare fire wall processing crash.
Fixed crash when using PlaceMinion order and creature can’t be placed at position.
Fixed scrolling to the end of message history window.
Fixed crash when multiple special attack effects kill a creature.
Fixed friendly fire issue when casting ranged spells.
Fixed issue with first name input field in the keeper menu.
Fixed verification of ViewIds in mods.
AI won’t throw items other than potion for their effect.
Flying over pits is possible.
Forbidden zone doesn’t block spells.
Fixed AI throwing logic.
Fixed special intrinsic attacks of some creatures.

KeeperRL
248
KeeperRL Alpha 29 is available for testing
1 Oct
An unofficial Alpha 29 build is out on the BETA branch. Check it out if you're an experienced player and want an early glimpse of all the new stuff!

Please post your feedback in this thread or in the comments below.

Please don't opt in if you are new to the game, as this build is very unstable, and the tutorial doesn't work at the moment.

To opt into the build, please go into the game's properties, BETA tab, and choose the &quot;dev&quot; branch.

KeeperRL
1221
New content in KeeperRL Alpha 29
3 Sep
Besides Steam Workshop support, Alpha 29 is going to bring a large amount of new content and mechanics for your enjoyment!

New biomes

KeeperRL will receive two new enemies with their own biomes and even dedicated soundtracks! They are: thieves in the desert, and a white dragon in an arctic setting. Both environments come with new mechanics and some juicy surprises! You can't build in different biomes yet, but it's something that will definitely happen at some point.

Totems

Totems are structures that place a certain buff or debuff on all friendly or hostile creatures in a given radius. The player has a healing totem available to build, and some locations feature other totems, like bleeding or blindness. They will mix up the combat mechanics in the game quite a bit. This is a feature that was suggested by player Amaze, if I'm not mistaken. Thanks!

Special item ingredients

Some (mostly major) enemies will drop body parts that can be used as ingredients to craft special items. This is in line with my efforts to give the player more rewards for exploration. Some of these crafted items will be very interesting :). The mechanic is fully moddable, of course.

Freezing mechanics

Along the new arctic biome and the white dragon enemy comes the effect of freezing, which interacts with water and other creatures. The reverse is also true - you can melt snowmen and igloos using fireballs :)

Spying

Originally intended for a new type of demon, this skill allows you to infiltrate the enemy lines. Great for gathering intel or stealing stuff! It's not clear to me yet whether it will be activated by a ring or by some other means, and I have to make sure it can't be used to evade attacking enemies forever as the Keeper.

Shields and the parry mechanic

Shields have been present in the game for a few updates, but they needed an overhaul. Thanks to some helpful input from players, I've added a new combat mechanic that makes them more relevant. If a creature is attacked multiple times within one turn, its defense stat gets a penalty for each attack. This makes it easier to take down very strong enemies if you have a large team of average creatures. Shields counteract this effect, for example an adamantine shield will let you take on four enemies at once before your defense is lowered.

Plague effect

Plague is a similar effect to poison, but it won't kill most creatures (and some are totally immune). It's also highly contagious. Have fun with it :).

Enemy aggression setting

You can now switch between three enemy aggression levels, with the lowest one completely turning off enemy attacks. The medium level will keep the normal aggression, and the extreme level will cause every active enemy to attack within a few thousand turns, provided that their population is high enough.

KeeperRL
658
KeeperRL will feature Steam Workshop integration in the next update!
8 Aug
The last few KeeperRL patches improved modding support to the point where you can change or replace the majority of the game’s content. I’m very happy that a few hardcore fans jumped at the opportunity and published some really cool things, and the most popular mod is played nearly as much as the vanilla game!

The game features a very simple interface for downloading mods, but a far better framework made for mod sharing is the Steam Workshop, which supports commenting, ranking, subscribing, searching and all the other things necessary for a great sharing experience. And thus I brought the coding guru Krzysiek onboard again, to integrate it into KeeperRL. Once at it, we also plan to support sharing of retired maps through the Steam Workshop.

I hope to release a testing build integrated with Steam Workshop in late August/early September, so we can work with mod creators and players to make sure the experience of content exchange is as perfect as possible.

For players that don’t use Steam, all content will also be hosted on the keeperrl.com server, as usual, but without the extra functionality that Steam Workshop supports. I feel bad about creating this inequality, but since more than 95% of players play on Steam, it would be a mistake not to make use of the extra free features that it provides.

KeeperRL
962
KeeperRL Alpha 28 hotfix 1 is out
4 Jul
This is a bug fixing patch that gets rid of some common issues found in Alpha 28.

Please note that the first three items take effect only in newly started games.

Fixed dark elf ally recruitment.
Removed temples from the home map (priest was too dangerous).
Fixed ghost spawning in ruins.
Fixed issue with removing some tree trunks.
Fixed flickering immigrant button glitch.
Fixed a crash caused by non-humanoid creatures trying to drop items.
Fixed a typo in the gloves item plural name and one in the build menu.
Vanilla mod files were converted to DOS line endings.

KeeperRL
238
KeeperRL Alpha 28 is released!
26 Jun
KeeperRL Alpha 28 is out! This update focuses on modding support, and also features new content and many quality-of-life improvements.

At this point most of KeeperRL's content has been exported to data files and can be modded. Mods can be shared at keeperrl.com and downloaded directly from the game! A few veteran players have already published a mod with massive amounts of new content.

I'd like to thank everyone involved in crash testing this patch, sending bug reports and suggestions. Your help was invaluable!

Scroll down for a detailed change log.
If you would like to continue your saved game from Alpha 27, you can opt-in into the &quot;Alpha 27 save compatibility&quot; BETA branch under the game's properties in Library. Make sure to opt-out of the branch to go back to Alpha 28 when you're done!

Gameplay
Merged &quot;campaign&quot;, &quot;free play&quot; and &quot;endless&quot; modes. Endless enemy waves can be set to attack after winning the game or from the start.
Improved the spell system, with multiple spell schools and many added spells.
Demon rituals are now performed by regular minions in order to attract demons and to heal them.
Improved AI for spell casting and potion throwing.
Spirit/ghost creatures have a separate health type, called materialization, with dedicated health potions and can be healed using demon rituals.
Healer team member AI does a better job at not engaging in fights.
Added rare spawning of the village guardian aka &quot;witchman&quot;.
Content
Black dragon enemy.
Gates/double doors.
Fire trap.
Orc healer minion
Orc shaman renamed to orc mage.
Battle mage and fire mage minions for the White Keeper.
Fighter abilities: &quot;swap positions&quot; and &quot;shove&quot;.
Reworked &quot;summon spirit&quot; spell of the shaman and unicorns to summon ghosts of actual creatures.
Healing and Heal other spells have been merged into a single spell with two upgrades.
Group healing spell.
Cure blindness spell.
Magic missile spell upgrades.
Teleport spell.
Pacify spell.
Magic cancellation spell and effect, preventing another creature from casting spells.
Pull spell.
Firewall spell.
Magical damage ring, which transforms melee damage of a creature into magical damage during a fight.
Modding
Added a new mod menu that allows downloading mods from the server.
Added support for adding new sprites in mods.
Campaign and endless enemies are now moddable.
All furniture, traps and other constructions are moddable.
Better support for creative or &quot;cheating&quot; modes: placing minions, and items, and immediate digging in the building menu.
Improved reporting errors in mods.
Retired dungeons contain information on which mods are required to load them.
Some sprites, such as all of the keeper sprites, support color variants without having to modify the sprite itself.
Added support for &quot;magical floors&quot; that cause a &quot;LastingEffect&quot; on the creature standing on them.
UI
Added a search box and other improvements to the list of retired dungeons.
Improved player name entry text field.
Fixes
Multiple optimizations for larger dungeons.
Online highscores are not downloaded anymore at the start of the game to improve startup time.
Made White Keeper animals visible in minions tab and obey quarters.
Fixed splitting team if undead team members can't travel due to daylight.
Fixed a bug that caused traveling team members to be transferred back to base randomly.
Fixed base retirement crashes.
Fixed showing gender names in character menu.
Fixed issue with increasing adventurer training levels beyond limits.
Fixed gas emitting in poison gas trap.


KeeperRL
751
Alpha 28 is available for testing
5 Jun
I've uploaded a pre-release build of Alpha 28 for all three platforms. I invite all seasoned players to take a look and post their feedback in this thread or in the comments below.

Please don't opt in if you are new to the game, as this build is very unstable, and the tutorial doesn't work at the moment.

To opt-in into the build, please go into the game's properties, BETA tab, and choose the &quot;dev&quot; branch.

KeeperRL
535
New stuff coming in Alpha 28
21 May
It's been almost two months since the last patch came out, and during that time I've been working full time on bringing you Alpha 28. At this point I'm done with adding major new features, and will work on finishing everything up and turning it into something that can be released. Here's a rundown of what you can expect. Tighten your seat belts!
New, fully modable, spells[github.com] and spell schools[github.com]. You can add new spells using the same effect system that is used for potions, special weapons, etc. Spells are grouped together into spell schools, and every creature can have a custom set of schools that they study in the library. Alpha 28 will likely feature the following spell schools to start with: evocation, shaman, healing, fire, illusion, and possibly necromancy. In addition, the same system is used to give abilities to fighter classes, such as shoving, swapping positions, intimidation, etc. I've also added more effects, for example custom area effects, fire, and teleportation.

New, general spell/effect AI, which works with custom effects. For example, knowing that blindness is a good offensive effect, it will try to cast any spell or throw any potion that causes it at an enemy. If a mod adds an area blindness spell, for whatever reason, the AI will try to cast it in such a way that only enemies are harmed by it. Similarly, area healing would only be cast at wounded allies. My aim is that the AI knows how to use most effects in the game, even ones added in mods.
Furniture modding[github.com]. This includes all static objects that are found on maps or can be built in dungeons. I was able to add double-tile gates using just mods, so it works pretty well. I also added the possibility of adding custom effects to floors, eg. floor of magic cancellation or insanity (every creature that stands on the floor gets the effect). The result is a bit crazy and OP, but I'm sure modders will find some good use for them. You can also add new traps.
Custom sprites[github.com]. Finally you can add your own sprites to the game! They can be used for both furniture and creatures. I've also added custom color variants for existing sprites, which lets you recolor them without having to edit the sprites themselves.

Modding has caused some issues with the dungeon retiring system, but I've made it so that any mods that don't add new sprites are contained in the dungeon file itself, so the only time you need to share your mod is when you've added custom sprites. The retired dungeons list will warn about requiring mods to load a dungeon. In the future mod sharing will be built into the game, so you won't have to worry about all of this.
Some of the current game modes will be merged. I noticed that very few players play the free play and endless modes, admittedly because they are pretty hidden in the menus. This is very bad, because sharing retired dungeons is a major feature of KeeperRL. Because of this, I will merge the main campaign mode with free play and endless modes, and this will become the main mode that everyone will play. I also want to improve the experience of downloading retired dungeons by adding ratings and better search. This may be added in later patches though.

KeeperRL
1356
KeeperRL Alpha 27 is released!
27 Mar
KeeperRL Alpha 27 is out! This is another big gameplay update, introducing many improvements in playability and AI.

You can now build your dungeons across multiple Z-levels, and digging downwards gives you access to extra resources, enemies and other surprises. Check below for the full change log.

I'd like to thank everyone involved in crash testing this patch, sending bug reports and suggestions. Your help was invaluable!

If you would like to continue your saved game from Alpha 26, you can opt-in into the &quot;Alpha 26 save compatibility&quot; BETA branch under the game's properties in Library. Make sure to opt-out of the branch to go back to Alpha 27 when you're done!

Gameplay
Z-levels!
Items can be upgraded using glyphs.
New random location: temples.
New random location: ruins.
Dragon AI learns how to breathe fire.
Added leisure zone, where minions go when idle.
Throwing items, firing ranged weapons and casting ranged spells have free instead of directional aim.
AI tries to create formations when fighting in open areas.
Healers and archer AI try to avoid melee combat.
Healers make more effort to heal wounded allies.
Tree spirits can be set on fire, and will actively seek out water to put it out.
Added &quot;entertainer&quot; and &quot;bad breath&quot; immigrant traits, which influence minion morale.
Increased spell and ranged max training of adventurers.
Traveling between sites is restricted during combat and when poisoned.
Creature AI knows how to use all resistance and vulnerability potions. (quaffing and throwing)
Insane minions of retired keepers won't be used in raids.
Minions won't go to sleep if they're poisoned.
Added healing starting spell to white knight keepers.
Creatures teleported by the throne get woken up.
Insane minions won't attack the keeper.
Insane immigrants get much higher damage bonuses.
Knights, dragons and dwarves in the main dwarf villain are much stronger.
Legendary minions are much stronger.
Added rat people
Adamantium golems are removed from the top level and exist only deep underground.
Prisoners are no longer granted poison resistance.
Combat experience bonus is reduced to the current level of given training type instead of the max level.
Lizardmen are hostile to lawful adventurers.
Added a basic wooden shield.
AI won't enter tiles adjacent to fire when pathfinding to avoid fire damage.
Corpses decrease morale instead of emitting poison gas.
Switching between real-time and turn-based modes doesn't advance the game clock.
Minions with night vision won't equip torches.
Immigrants can come with extra wings or heads, the latter allowing equipping multiple helmets and amulets.
Hydra has 7 heads which need to be cut off to kill it.
The demon villain top level is a ruined castle.
AI will try to go indoors at night.

Mods
Mods can be switched in settings.
Mineral patch numbers can be modded (per given z-level depth).
Creatures and their inventories can be modded. New creatures can be added and used in immigration and as player characters.
NegateRequirement immigrant requirement which lets you require that a requirement is not fulfilled.

Interface
Improved character creation menu.
Darkness and night is rendered directly on sprites to avoid ugly graphical glitches with lighting.
When the player is killed, the notification is displayed below the center of the map so it doesn't obscure the view of what happened.
Improved button visuals.
Improved the lava animation.
Added succubi lovemaking animation.
Direct spell attacks have a magic animation.
Immigrant legendary crafting skill is displayed explicitly.

Fixes
Multiple optimizations.
Reduced RAM usage per level, to accommodate Z-levels.
Fixed worker AI getting stuck when idle.
Control mode sidebar scrolling includes team member list. Fix
Fixed eating task AI to not get stuck.
Increased server connection timeouts.
Fixed doppelganger consumption menu.
Fixed issues with clicking on the game speed dialog.
Keeper level button is not highlighted if there is nothing more to research
Fixed bug in calculating visibility which showed itself in wrongly lit tiles after a forest fire.
Fixed spell icon tooltips in control mode.
Fixed AI crash when killing enemy using a projectile.
Fixed a bug where a minion paces back and forth between two pigsties.
Fixed UI buttons accuracy.
Fixed AI issue with workers trying to drop items on inaccessible storage tiles.
Fixed giant spider AI.
Equipment storage located outside of territory is taken into account when

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Alpha29](/keeperrl_wiki/Old_Alpha29 "wikilink")

Other items in this section
-    [Alpha29 0](/keeperrl_wiki/Alpha29_0 "wikilink")
-    [Alpha29 2](/keeperrl_wiki/Alpha29_2 "wikilink")
-    [Alpha29 3](/keeperrl_wiki/Alpha29_3 "wikilink")
