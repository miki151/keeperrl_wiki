---
title: Modding Effects
permalink: Modding_Effects/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")

Fire
----

*Creatures are burnt by the fire.*

-   weapon attack type
    -   damage : 6.0 \* 0.5 / victimStrength

<!-- -->

-   other source
    -   damage : 6.0 \* 1.0 / victionStrength

Panic
-----

Poison
------

*You feel poison flowing in your veins.*

-   weapon attack type
    -   duration : 20 ticks
    -   damage : 1.0 / 60

<!-- -->

-   other source / spells / [lizardman](/keeperrl_wiki/Lizardman "wikilink")
    -   duration : 60 ticks
    -   damage : 1.0 / 60

Poison Gas
----------

-   gas trap
    -   bleed(amount / double(getAttr(AttrType::STRENGTH)));

Silver
------

*Undead creatures are hurt by the silver.*

-   random damage : 0.0 - 0.15

Stun
----

*Creature is stunned.*

-   weapon attack type
    -   duration : 1 tick

<!-- -->

-   other source / spells
    -   duration : 7 ticks

Sunlight
--------

-   10% chance per tick for undead to crumble to dust.

[MainPage](/keeperrl_wiki/ "wikilink")

