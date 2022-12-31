---
title: Alpha35
permalink: Alpha35
layout: wiki
---


Gameplay

Decreased minimum damage/defense ratio required to reduce health in combat.
New “spell speed” attribute, which influences spell cooldowns, and is acquired in training and from various equipment.
Workshop and other skills such as multi-weapon have been replaced with attributes.
Stealing items from allies will make them hostile.
Enemies may ambush you after you travel to their site.
Infernite weapons will cause actual fire damage.
Made it impossible to craft automaton corpuses without adding any upgrades.
Rat corpses can no longer be used to craft undead.
Peacefulness debuff duration reduced to 5 turns.
Removed unnecessary “nothing happens” message when healing didn’t have any effect.

Content

New attributes/damage types: cold damage, acid damage, fire damage.
Added immunity buffs for all types of damage.
Added adoxium and infernite corpuses and arms for automatons.
New weapons: Infernite trident, elves staves, King’s Sceptre.
Added automaton “kaboom” head.
Disallowed crafting bone dragons from ki-rin corpses.
Allowed prisoner heads to be built outside.

UI

Wielded weapons are rendered together with creature sprites.
Customizable keybindings for most keyboard controls.
Made it possible to scroll freely in the turn-based mode.
Torches are rendered above other symbols in the ASCII mode.

Modding

Attributes are moddable.
Buffs / lasting effects are moddable.
Body materials are moddable.
Added OnTheGround predicate for checking if a certain ingredient is laying on the ground.
Spell cooldowns should now be assigned a range, with exact value calculated based on creature’s spell speed.
Arithmetic expressions can be used wherever the game expects numbers in the game files.
All furniture with BedType set to PRISON can be used as prison.
Persistent immigrant teams (ex. wolf packs) have been removed.

Fixes

Fixed pathfinding issues caused by removing portals.
Disallowed capturing companion creatures.
Spirit summons won’t be counted as unique for the purpose of calculating combat experience.
Clicking on portals in the real-time mode scrolls to the correct other portal position.
Removed bogus message about portal being inactive.
Using the stairs defocuses the item pick-up menu.
Enemy minions will not dig in their own territory in order to get somewhere.
Removed bogus blue dot from the minimap in the real-time mode.
Added an icon to the game window on Linux and Mac.
