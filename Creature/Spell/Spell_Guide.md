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

-   Keepers and Goblin Priests start with this.  Mage school 4, Dwarf level 2.
-   Cooldown: 31 base, 10 minimum.

Restores the caster to full hit points, but does not restore damaged or destroyed limbs.

### Advanced Healing

-   Healer level 1, Dwarf school level 4.
-   Supplants (basic) Healing.
-   Cooldown: 31 base, 10 minimum.

Restores the caster or an adjacent target to full hit points, but does not restore damaged or destroyed limbs.  Does not affect Materialization.

### Expert Healing

-   Healer school level 2.
-   Supplants Advanced Healing.
-   Cooldown: 31 base, 10 minimum.

Restores the caster or *all* targets in a line up to 4 tiles from the caster (including hostile targets! aim carefully) to full hit points, but does not restore damaged or destroyed limbs.  Does not affect Materialization.

### Group Healing

-   Healer level 7, Dwarf level 12.
-   Cooldown: 51 base, 25 minimum.

Restores the caster and all friendly creatures in a 2-tile radius to full hit points, but does not restore damaged or destroyed limbs. Does not affect Materialization.

### Cure Poison

-   Healer level 3, Mage school level 6.
-   Cooldown: 51 base, 25 minimum.

Removes the POISON status from the caster. Does not restore lost hit points or prevent re-poisoning.

### Advanced Cure Poison

-   Healer level 4.
-   Supplants Cure Poison.
-   Cooldown: 51 base, 25 minimum.

Removes the POISON status from the caster or an adjacent target. Does not restore lost hit points or prevent re-poisoning.

### Cure Blindness

-   Healer level 5.
-   Cooldown: 51 base, 25 minimum.

Removes the BLIND status from the caster or an adjacent target. Does not restore lost or damaged heads or eyes.

### Poison Resistance

-   Healer level 6.
-   Cooldown: 101 base, 50 minimum.

Grants the caster or an adjacent target the POISON_RESISTANT status for approximately 30 turns, removing POISON status should it be present and preventing re-poisoning for the duration.  Does not restore hit points lost to any poisoning cured, though.

Mage
----

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

Shoots a ray causing Magic Damage (based on the caster's stat) up to 4 tiles from the caster, penetrating through all creatures in the way.  Mages with this will NOT have learned to avoid friendly fire, so shooting through friendlies may be expected to hit, hurt, and Hostile them.  (You will be warned of this fact, and given the option to abort, should you tell a creature to so cast.)

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

### Defense Bonus

-   Mage level 9, Dwarf level 1.
-   Cooldown: 81 base, 30 minimum.

Grants the caster +3 Defense for 40 turns.  Does not stack with Defense-boosting gear, but will stack with Thick Skin.

### Invisibility

-   Mage level 12, Illusion level 4.
-   Cooldown: 301 base, 100 minimum.

Turn invisible for 15 ticks.


Spiritualist
------------

### Heal Spirit

-   Spiritualist level 1.
-   Cooldown: 31 base, 10 minimum.

Restores the caster or an adjacent target to full Materialization.  Does not affect hit points.

### Advanced Heal Spirit

-   Spiritualist level 4.
-   Supplants (basic) Heal Spirit.
-   Cooldown: 31 base, 10 minimum.

Restores the caster or *all* spirits in a line up to 4 tiles long to full Materialization.  Does not affect hit points.

### Heal Spirit Group

  - Spiritualist level 7.
  - Cooldown: 51 base, 25 minimum.

Restores all friendlies in radius 2 to full Materialization.  Does not affect hit points.

Illusion
--------

### Deception

-   Illusion level 1.
-   Cooldown: 61 base, 30 minimum.

Summons 3 - 7 [Illusions](/keeperrl_wiki/Illusion "wikilink") for 5 - 10 ticks.

### Panic

-   Illusion level 2.
-   Cooldown: 51 base, 25 minimum.

Inflicts the PANIC status on a target (or line of targets) up to 5 tiles away, debuffing their attack but raising their defense.

### Fog Cloud

-   Illusion level 3.
-   Cooldown: 61 base, 30 minimum.

Creates (temporary) fog tiles in a 4-tile radius, which block vision and ranged attacks, but not movement.

### Pacify

-   Illusion level 5.
-   Cooldown: 61 base, 20 minimum.

Inflicts the Peaceful status on a single target up to 2 tiles away.  Peaceful creatures are considered "friendly" to everyone and cannot attack or cast offensive magic, but can be manually attacked (right-click menu), will freely swap places if moved into, and will not resist absorbption attempts.

### Advanced Invisibility

-   Illusion level 6.
-   Supplants (basic) invisibility.
-   Cooldown: 301 base, 100 minimum.

Turn invisible; per code, no difference between this and (basic) invisibility.

### Blink

-   Illusion level 8.
-   Cooldown: 1.

Triggers the "Escape" effect similar to the spell of that name, but only looks 2 tiles away.  Given the non-cooldown, this is probably better than Escape.


Chickenmancy
------------

### Summon Chicken

-   Chickenmancy level 1.
-   Cooldown: 5.

Summons a Chicken for 15 turns.

### Summon More Chickens

-   Chickenmancy level 2.
-   Cooldown: 10 base, 3 minimum.

Summons 3 to 5 Chickens, for 15 turns.

### Chickenmorph

-   Chickenmancy level 5.
-   Cooldown: 101 base, 30 minimum.

Polymorphs the caster into a Chicken for 10 turns, during which time the chicken is Invulnerable.

### Advanced Chickenmorph

-   Chickenmancy level 7.
-   Supplants (basic) Chickenmorph.
-   Cooldown: 101 base, 30 minimum.

Polymorphs the caster, or a single target up to 5 tiles away, into a Chicken for 10 turns, during which time the chicken is Invulnerable.

### Chickengeddon

-   Chickenmancy level 7.
-   Cooldown: 301 base, 150 minimum.

Polymorphs *everyone* in a 20-tile radius into a chicken for 10 turns.  During this time, all such chickens are Invulnerable.

Dwarf
-----

### Damage Bonus

-   Dwarf level 3.
-   Cooldown: 81 base, 30 minimum.

Buffs melee damage for 40 turns.

### Advanced Defense Bonus

-   Dwarf level 5, Zombie Mage 2.
-   Supplants (basic) Defense Bonus.
-   Cooldown: 81 base, 30 minimum.

Buffs the caster or an adjacent target's Defense for 40 turns.

### Dig

-   Dwarf level 6.
-   Cooldown: 10.

Destroys all walls in a line up to 7 tiles long.

### Advanced Damage Bonus

-   Dwarf level 7, Zombie Mage 3.
-   Supplants (basic) Damage Bonus.
-   Cooldown: 81 base, 30 minimum.

Buffs the caster or an adjacent target's melee Damage for 40 turns.

### Earth Elemental

-   Dwarf level 8.
-   Cooldown: 81 base, 30 minimum.

Summons an earth elemental for 100 turns.

### Mass Defense Bonus

-   Dwarf level 9, Zombie Mage 6.
-   Supplants Advanced Defense Bonus.
-   Cooldown: 81 base, 30 minimum.

Buffs the Defense of all friendly creatures in a 10-tile radius, for 40 turns.

### Advanced Earth Elemental

-   Dwarf level 10.
-   Supplants (basic) Earth Elemental.
-   Cooldown: 81 base, 30 minimum.

Summons 2-4 earth elementals, for 100 turns.

### Mass Damage Bonus

-   Dwarf level 11, Zombie Mage 7.
-   Supplants Advanced Damage Bonus.
-   Cooldown: 81 base, 30 minimum.

Buffs the melee Damage of all friendly creatures in a 10-tile radius, for 40 turns.

Zombie Mage
-----------

### Summon Flies

-   Zombie Mage level 1.
-   Cooldown: 61 base, 30 minimum.

Summons 3 - 7 [flies](/keeperrl_wiki/Fly "wikilink") for 100 ticks.

### Animate Corpses

-   Zombie Mage level 4.
-   Cooldown: 201 base, 50 minimum.

Causes 3-5 corpses to float on their own and attack hostiles, for 10-20 turns.  (This is more along the lines of telekinetically picking up the dead body and whacking folks with it, rather than creating more undead.)

### Blindness

-   Zombie Mage level 5.
-   Cooldown: 21 turns base, 10 turns minimum.

Inflicts the BLIND status on a line of targets, up to 5 tiles long, for 5 turns.

### Advanced Animate Corpses

-   Zombie Mage level 8.
-   Supplants (basic) Animate Corpses.
-   Cooldown: 201 base, 50 minimum.

Causes 6-5 (_sic_) corpses to float on their own and attack hostiles, for 30-50 turns.  (This is more along the lines of telekinetically picking up the dead body and whacking folks with it, rather than creating more undead.)

[MainPage](/keeperrl_wiki/ "wikilink")>>[Creature](/keeperrl_wiki/Creature "wikilink")>>[Spell](/keeperrl_wiki/Spell "wikilink")
