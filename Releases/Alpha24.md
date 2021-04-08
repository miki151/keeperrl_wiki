---
title: Alpha24
permalink: Alpha24/
layout: wiki
---

The full change log
===================

Gameplay
--------

-   Prisoners retain their identity and can join your side if tortured.
-   Prisoners can be captured outside of player's dungeon.
-   Player must tag specific enemies that are to be captured.
-   Prisoners can perform work like crafting, if they have appropriate
    skills.
-   Prisoners can escape if there are too many compared to fighter
    units.
-   Most mineral veins are guarded by enemies like ants, dwarves and
    golems, who will attack when the player tries to mine the vein.
-   As most minerals are guarded, geology tech is removed.
-   Changed steel to adamantium, which is mined and not smelted from
    iron.
-   Added 'quarters', which can be used to create mini-dungeons for
    selected minions.
-   Added 'hard rock' tiles, which take longer to dig out, deeper in the
    mountain.
-   Added iron and adamantine doors.
-   Creatures have explicit intrinsic attacks, like fangs or fists that
    can be chosen via UI when attacking.
-   Time system is changed to explicit turns and 'half-turns' for easier
    control during battle.
-   Creatures only have 3 speed options: half-speed, normal, and
    double-speed. (speed attribute is removed)
-   Creatures with double-speed perform their second move immediately
    after the first.
-   Boulders don't wound huge creatures like dragons.
-   Some villages have a chance to be generated on the 'bones' of
    others.
-   Healer AI prioritizes healing creatures that stand directly next to
    an enemy.
-   Increased spell damage of legendary minions.
-   Added maximum range for bows.
-   Decreased mana regeneration rate in free mode when mana regeneration
    option is turned on.
-   Kobolds are stronger and have spears.
-   Improved eating AI, minions will try to leave the pigsty after
    having eaten.
-   Changed AI code involving swapping positions, creature's won't get
    in each other's way so much anymore.
-   Made cooperative AI assign better positions when mining close to
    each other.
-   Removed tech number limit based on library size.
-   Minions respond immediately to the player manually changing their
    activity (including waking up).
-   Minion wakes up when it is assigned new equipment.
-   Added hand torches.
-   Burning objects emit light!
-   Improved logic of injuring non-living creatures, which fixes the
    problem of killing them taking too long.
-   Added caps to how much of the basic stats dopplegangers can inherit.
-   Added minimum turn requirement to some higher level immigrants,
    which causes more low level immigrants to be presented early in the
    game.
-   'Prioritize task' order makes an imp drop their current task
    immediately.
-   Decreased the 'unavailable zone' width on the map border to reduce
    memory usage.
-   Reduced amount of stone dropped by boulder to avoid generating free
    stone.
-   Reduced amount of gold dropped by demon dwellers.
-   Made minions do other tasks when there is nothing to craft.
-   Statues cost gold instead of mana.
-   Creatures and items are teleported out of inaccessible tiles.
-   Added the ability to push away smaller creatures.
-   Removed the 'stun ray' spell.
-   Added 'demonology' tech that unlocks demon shrines.
-   Hallucination effect also grants telepathy.
-   Added baby spiders and blind children to giant spider's den.
-   Vampire lord drops a scroll of darkness, which causes a creature to
    become permanently immune to sunlight.
-   Ghost gets a 'touch of insanity' attack, which causes creatures to
    be hostile to everyone.
-   Succubus gets a 'touch of love' attack, which causes creatures to
    become peaceful.
-   Robe gives spell resistance.
-   Added invisible alarm trap to castle.
-   Added priest to castle.
-   Pig corpses don't emit gas.
-   All enemy creatures heal slowly over time.

Interface
---------

-   New UI for managing team members: adding and removing from team,
    changing move order.
-   New UI for interacting with other creatures, like attacking,
    chatting, etc.
-   Added creature status (leader/fighter/civilian) highlights and
    descriptions.
-   Added tabs to view team members.
-   Added new buttons for toggling and exiting control mode.
-   Attribute bonuses from equipment and buffs are visible in the UI.
-   Added a simple animation for when creatures are wounded or tortured.
-   Limb losses are represented on HP bar for non-living creatures,
    which don't have health and have to be chopped into pieces.
-   New sprites for the demon tribe.
-   New buttons under the minimap to open world map or scroll to
    keeper's location.
-   Boulders can be pushed using the mouse.
-   Summoned creatures remaining 'time to live' is explicitly shown in
    the UI.
-   Total inventory weight and maximum capacity is displayed in control
    mode.

Fixes
-----

-   Endless mode highscore takes into account only time spent defending
    the base, and not wandering around.
-   Optimized and fixed various issues with creature pathfinding.
-   Optimized field-of-view calculations, which speeds up the game
    considerably.
-   Optimized world generation.
-   Stopped doppleganger from being able to consume itself.
-   Doppleganger doesn't inherit effects granted by rings and other
    equipment.
-   Fixed ancient spirit's spell attack.
-   Minions pick up potions of melee, spell and ranged resistance.
-   Chests and coffins spawn creatures further away if adjacent tiles
    are blocked.
-   Reinforce wall order is removed when wall is marked to be dug out.
-   Disallowed destroying bridges.
-   Fixed digging orders persisting when tile was destroyed by someone
    else.
-   Fixed trap removal and building floors under traps.
-   Fixed 'sleep on torch' UI bug.
-   Fixed level generation crashed caused by trying to place a blind
    creature.
-   Fixed marking campaign base map as conquered when village is
    destroyed.
-   Fixed drawing question marks on the main map.
-   Fixed red dragon appearing on green dragon's place in the campaign.
-   Increased female keeper spell damage to match the male version.
-   Fixed issue with calculating influence area in campaign map.

