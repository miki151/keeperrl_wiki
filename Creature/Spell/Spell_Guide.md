---
title: Spell Guide
permalink: Spell_Guide/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Creature](/keeperrl_wiki/Creature "wikilink")>>[Spell](/keeperrl_wiki/Spell "wikilink")

**Spells** are active abilities with cooldown between uses that can be
learned by your [Keeper](/keeperrl_wiki/Keeper "wikilink") and some of your
[Minions](/keeperrl_wiki/Minions "wikilink").

Creatures who immigrate to your dungeon generally don't have any spells, though those eligible can learn the spells from their [spell school](/keeperrl_wiki/Spells "wikilink") through training.
Spells known are based on your Magic Damage training, with each level of
training generally providing a new spell or improving a previous one (removing the previous spell, for better or worse).
This also means that you will need [Sorcery
techs](/keeperrl_wiki/Sorcery "wikilink") to train the spells of your
minions in your dungeon, as wooden, iron and golden bookcases cap at +3,
+7 and +99 Magic Damage training, respectively. While no creature in vanilla KeeperRL can train more than 12 levels in Magic Damage, mod content can and does go higher.

In KeeperRL 1.0, it's entirely possible to improve your Magic Damage through practical combat experience.  This will make your magic missiles and staff swings hit harder, but will NOT add to your spell selection.

Cooldown of spell uses is affected by your spell-speed statistic, which can generally decrease cooldowns to 50% of their original value (though some spells may be capped at longer cooldown times).

Spells by School
============

Healer
-------

### Healing

-   Keepers and Goblin Priests start with this.  Mage school level 4, Dwarf school level 2.
-   Cooldown: 31 base, 10 minimum.

Restores the caster to full hit points, but does not restore damaged or destroyed limbs.

### Advanced Healing

-   Healer school level 1, Dwarf school level 4.
-   Supplants (basic) Healing.
-   Cooldown: 31 base, 10 minimum.

Restores the caster or an adjacent target to full hit points, but does not restore damaged or destroyed limbs.

### Expert Healing

-   Healer school level 2.
-   Supplants Advanced Healing.
-   Cooldown: 31 base, 10 minimum.

Restores the caster or *all* targets in a line up to 4 tiles from the caster (including hostile targets! aim carefully) to full hit points, but does not restore damaged or destroyed limbs.

### Group Healing

-   Healer school level 7.
-   Cooldown: 51 base, 25 minimum.

Restores the caster and all friendly creatures in a 2-tile radius to full hit points, but does not restore damaged or destroyed limbs.

### Cure Poison

-   Healer school level 3, Mage school level 6.
-   Cooldown: 51 base, 25 minimum.

Removes the POISON status from the caster. Does not restore lost hit points or prevent re-poisoning.

### Advanced Cure Poison

-   Healer school level 4.
-   Supplants Cure Poison.
-   Cooldown: 51 base, 25 minimum.

Removes the POISON status from the caster or an adjacent target. Does not restore lost hit points or prevent re-poisoning.

### Cure Blindness

-   Healer school level 5.
-   Cooldown: 51 base, 25 minimum.

Removes the BLIND status from the caster or an adjacent target. Does not restore lost or damaged heads or eyes.

### Poison Resistance

-   Healer school level 6.
-   Cooldown: 101 base, 50 minimum.

Grants the caster or an adjacent target the POISON_RESISTANT status for approximately 30 turns, removing POISON status should it be present and preventing re-poisoning for the duration.  Does not restore hit points lost to any poisoning cured, though.


Mage
====

### Directed Blast

-   Mage level 1.
-   Cooldown: 21 base, 5 minimum.

Knocks back *everyone* in a line from the caster, knocking them down for 1-2 turns, but not damaging their hitpoints. If there are any
items on the ground, they will also be knocked back and into the creatures knocked back. This flung-item effect can do damage, but generally does not and should not be relied upon.

Creatures knocked back will NOT be knocked into hazardous terrain such as water or lava, instead stopping at the edge.  This is working as intended.

### Escape

-   Mage level 2.
-   Cooldown: 101 base, 50 minimum.

Teleports 6 tiles away from known enemies.  Does NOT check whether the destination is "safe" from other enemies or would be bottlenecked by the known enemies, though, so use with caution...

### Haste Self

-   Mage level 8.
-   Cooldown: 61 base, 30 minimum.

Grants SPEED_BONUS status, granting an additional movement-only action every time the creature acts.  (Once Hasted creatures use their movement-only move, they must finish their turn.  You may not have a Hasted creature move and then have another creature act, intending to finish the Hasted creature's turn later in the round.)  Does NOT counteract Slow.

### Magic Missile

-   Mage level 3.
-   Cooldown: 21 base, 5 minimum.

Shoots a ray causing Magic Damage (based on the caster's stat) up to 4 tiles from the caster, penetrating through all creatures in the way.  Mages with this will NOT have learned to avoid friendly fire, so shooting through friendlies may be expected to hit, hurt, and Hostile them.  (You will be warned of this fact and given the option to abort should you tell a creature to so cast.)

### Advanced Magic Missile

-   Mage level 7.
-   Supplants (basic) Magic Missile.
-   Cooldown: 21 base, 5 minimum.

Shoots a ray causing Magic Damage (based on the caster's stat) up to 8 tiles from the caster, penetrating through all creatures in the way.  Mages with this will have learned to avoid friendly fire, so shooting through friendlies will safely bypass them.  (Downed folks tagged for capture are still vulnerable, though!)

### Expert Magic Missile

-   Mage level 11.
-   Supplants Advanced Magic Missile.
-   Cooldown: 21 base, 5 minimum.

Shoots a ray causing Magic Damage (based on the caster's stat) up to 12 tiles from the caster, penetrating through all creatures in the way.  Mages with this will have learned to avoid friendly fire, so shooting through friendlies will safely bypass them.  (Downed folks tagged for capture are still vulnerable, though!)

### Teleport

- Mage level 5.
- Cooldown: 201 base, 50 minimum.

Teleports the caster to a chosen tile up to 3 tiles away.  You don't need to have sight to the tile, but you need to know that the terrain is safe.

### Advanced Teleport

- Mage level 10.
- Supplants (basic) Teleport.
- Cooldown: 201 base, 50 minimum.

Teleports the caster to a chosen tile up to 8 tiles away.  You don't need to have sight to the tile, but you need to know that the terrain is safe.

### Defense

-   Mage level 9, Dwarf level 1.
-   Cooldown: 81 base, 30 minimum.

Grants the caster +3 Defense for 40 turns.  Does not stack with Defense-boosting gear, but will stack with Thick Skin.

### Invisibility

-   Mage level 12, Illusion level 4.
-   Cooldown: 301 base, 100 minimum.

Turn invisible for 15 ticks.


### Summon Insects

-   Requires +2 Magic Damage training.
-   Cooldown: 30

Summons 3 - 6 [flies](/keeperrl_wiki/Fly "wikilink") for 100 ticks.



Advanced Spells
===============

Unlocked by [advanced sorcery
tech](/keeperrl_wiki/Advanced_Sorcery "wikilink") and trained at an iron
bookcase.



### Deception

-   Requires +4 Magic Damage training.
-   Cooldown: 60

Summons 3 - 7 [Illusions](/keeperrl_wiki/Illusion "wikilink") for 5 - 10 ticks.



### Circular Blast

-   Requires +7 Magic Damage training.
-   Cooldown: ?

Knocks back enemies around the caster, without damaging them. If there
are any items on the ground, they are also thrown back and will hit any
enemies in their path.

Master Spells
=============

Unlocked by [master sorcery
tech](/keeperrl_wiki/Master_Sorcery "wikilink") and trained at a golden
bookcase.



### Summon Elemental

-   Requires +8 Magic Damage training.
-   Cooldown: ?

Summons a random elemental:

-   air elemental
-   earth elemental
-   fire elemental
-   water elemental
-   tree spirit

### Damage

-   Requires +9 Magic Damage training.
-   Cooldown: ?

Buffs Melee Damage.

### Fire Sphere

-   Requires +10 Magic Damage training.
-   Cooldown: 20

Summons a [Fire Sphere](/keeperrl_wiki/Fire_Sphere "wikilink").

### Meteor Shower

-   Requires +11 Magic Damage training.
-   Cooldown: 150

Meteors rain from the sky around the caster. Each tick a random tile
near the caster is hit by either a rock or a piece of iron ore, damaging
any creature that stand there in the process. Rocks and iron ore left
behind by this spell can then be gathered for your resource stockpile.



Disabled Spells
===============

These spells are still in the game, but cannot be learned right now.

### Stun Ray

-   Cooldown: 60

Stuns target for 7 ticks.

[MainPage](/keeperrl_wiki/ "wikilink")>>[Creature](/keeperrl_wiki/Creature "wikilink")>>[Spell](/keeperrl_wiki/Spell "wikilink")

Other items in this section
-    [Category Spells](/keeperrl_wiki/Category_Spells "wikilink")
-    [Cure Poisoning](/keeperrl_wiki/Cure_Poisoning "wikilink")
-    [Force Bolt](/keeperrl_wiki/Force_Bolt "wikilink")
-    [Haste Self](/keeperrl_wiki/Haste_Self "wikilink")
-    [Healing](/keeperrl_wiki/Healing "wikilink")
-    [Illusion](/keeperrl_wiki/Illusion "wikilink")
-    [Magic Shield](/keeperrl_wiki/Magic_Shield "wikilink")
-    [Spell](/keeperrl_wiki/Spell "wikilink")
-    [Spells](/keeperrl_wiki/Spells "wikilink")
-    [Stun Ray](/keeperrl_wiki/Stun_Ray "wikilink")
-    [Summon Insects](/keeperrl_wiki/Summon_Insects "wikilink")
-    [Summon Spirit](/keeperrl_wiki/Summon_Spirit "wikilink")
-    [Word of Power](/keeperrl_wiki/Word_Of_Power "wikilink")
