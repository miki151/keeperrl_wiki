---
title: Alpha32
permalink: Alpha32/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Releases](/keeperrl_wiki/Releases "wikilink")

<hr>
Released in April 2021
<hr>


Gameplay
--------

-	Improved combat formations AI, including keeping spellcasters and healers behind the front lines.
-	The type of AI can be switched between 'melee' and 'ranged' for every creature.
-	The game has the concept of polymorph, with multiple new polymorph spells and abilities of various kind.
-	Archer and mage classes receive the ability to have projectiles bypass allies with training.
-	Spellcasting AI will try to maximize the effect of projectile and area spells.
-	The speed and slowness effects apply only to movement and not other actions, ex. fighting, digging, etc.
-	Guarding activity and guard zones are split into three groups, and the activity is disabled by default.
-	Artifact potions with permanent effects are available as consumables in the minion menu, and minions will automatically consume them when ordered to pick them up.
-	The speed and slowness effects are allowed to coexist and cancel each other out.
-	The Keeper will also abuse workers, not only fighters.
-	The ring of spying will get destroyed if the spy attacks anyone.
-	The Keeper is allowed to copulate.
-	Peacefulness prevents creatures from using hostile spells and abilities.
-	Removed tech books.


Content
-------

-	Goblin faction adapted from the Bonus Mod.
-	Special z-level for the Goblin faction.
-	Orcs and ogres are replaced by goblins and trolls.
-	Vampires are granted the 'lord' status when reaching their max training level.
-	Added a 'blink' spell to vampires.
-	Shaman summons have been reworked as a generic companion system, with other creatures that have companions and pieces of equipment that can grant them. -	Companions always respawn up to a certain limit, and their stats may depend on their owner's stats.
-	Added setting to unlock all locked content.
-	Swords are swapped for clubs in bandits and rat people.
-	Green dragon has a 'poison breath' attack.
-	New red dragon lair.

Modding
-------

-	Prisoners can be converted using the Effect system, so you can add other ways of conversion other than the torture table.
-	The type of AI can be defined as 'melee' and 'ranged' for every creature.
-	Added a Flag requirement to immigration.
-	Added the ability to add flags to chosen keepers.
-	'InTerritory', 'Humanoid', and 'Spellcaster' creature filters.
-	'SpecialAttr' effect, which adds attribute bonuses that depend on chosen filters applied to the enemy.
-	Added an 'eyeball' property to furniture, so that new eyeball types can be modded.
-	Particle effects, such as glitter can be added to custom furniture.
-	Added 'SetCreatureName' and 'SetViewId' effects (see the ennoblement spell).
-	Reimplemented 'AITarget', 'AIDistance' and 'AIBelowHealth' with a generic AI effect which uses creature predicates.
-	Ranged weapon logic is removed from the game. Ranged weapons instead grant spells/abilities that shoot the missile.
-	Ranged spells have a 'maxHits' attribute, which defines the max number of creatures that are hit by the spell.


UI
--

-	Drag-and-dropping team members on the map in the turn-based mode causes them to receive go-to orders.
-	Improved the order of sprite rendering, getting a more natural '3d' look.
-	Creature sprites are flipped horizontally based on their movement.
-	Reworked settings and 'load game' menus.
-	Added a message when content gets unlocked.
-	Improved workshop menu, including a 'change count' button.
-	Glyphs can be mass-applied to a stack of crafted items.
-	Added a 'choose all' button in the pillage menu.
-	Visual warning when torture is unavailable due to reached population limit.
-	Added a warning when spell or ability might harm an ally.
-	Question marks drawn in place of locked keeper and adventurer characters.
-	Started using short versions of very long workshop item names.
-	Creature description includes info on multiple heads.
-	Added a steam animation to automaton engines.
-	Added a 'peacefulness' effect animation.
-	Magic missile can be invoked using the 'f' key.


Fixes
-----

-	Prevented the leader from running after minions outside his base to abuse them.
-	Fixed a crash caused by casting a firewall or related spell on a candelabrum.
-	Added rendering optimizations.
-	Fixed storage warnings referencing a wrong storage type.
-	Workers won't drink all the booze that they were to haul to storage.
-	Potions of booze won't have an effect when thrown.
-	Glyphs can no longer be 'applied' in control mode, which did nothing and used up the glyph.
-	Fixed drawing bogus particle effects generated on different z-levels.
-	Fixed some enemy AI not returning to their territory at night.
-	The game considers peacefulness a negative effect so that AI uses it offensively.
-	Sleeping creatures will wake up when attacked by fire or acid.
-	Stopped Adventurer from sleeping multiple times if player keeps clicking the sleep order.
-	Fixed names of intrinsic items with prefixes, ex. fangs of poison, etc.
-	Shopkeeper debt is not shown if shopkeeper is dead or not nearby.
-	Fixed crash caused by recruiting allies that were stunned.
-	Fixed gnome traps requirements.
-	Fixed save incompatibility between the Linux and Windows platforms.
-	Fixed item tooltips in the pillage and trade menus.
-	Prevented creature attributes from going below 0.
-	Fixed crash caused by an applied item killing the creature.
-	Fixed mouse click glitch involving the mini map.
-	Fixed 'RemovePermanent' effect 

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
-    [Alpha30](/keeperrl_wiki/Alpha30 "wikilink")
-    [Alpha31](/keeperrl_wiki/Alpha31 "wikilink")
