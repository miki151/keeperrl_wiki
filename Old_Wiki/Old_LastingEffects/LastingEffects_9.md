---
title: LastingEffects 9
permalink: LastingEffects_9/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_LastingEffects](/keeperrl_wiki/Old_LastingEffects "wikilink")

=Usage=
#Used with [[ItemTypes]] to specify variations of those items
#Used to define special traits for immigrants.

=Example from workshops_menu.txt=
From: [[Workshops_Menu.txt]]
 {{Potion Lasting '''SLOWED'''}               2        GOLD 2}
 {{Potion Lasting '''SLEEP'''}                2        GOLD 2}
 {{Potion Lasting '''POISON_RESISTANT'''}     4        GOLD 6}
 {{Potion Lasting '''SPEED'''}                4        GOLD 6}
 {{Potion Lasting '''TELEPATHY'''}            4        GOLD 6}
 {{Potion Lasting '''REGENERATION'''}         4        GOLD 8}
 {{Potion Lasting '''POISON'''}               4        GOLD 8}
 {{Potion Lasting '''FLYING'''}               4        GOLD 8}

=Example from immigration.txt=
From: [[Immigration.txt]]
 specialTraits = {
 { 0.03 { AttrBonus SPELL_DAMAGE 7 LastingEffect '''INSANITY'''}}
 { 0.10 { ExtraTraining SPELL 4}}
 { 0.05 { SkillId LABORATORY }}
 { 0.10 { LastingEffect '''MAGIC_RESISTANCE''' }}
 { 0.02 { LastingEffect '''HATE_ELVES''' }}
 { 0.02 { LastingEffect '''HATE_HUMANS''' }}

=Valid values=
*SLEEP
*PANIC
*RAGE
*SLOWED
*SPEED
*DAM_BONUS
*DEF_BONUS
*BLEEDING
*HALLU
*BLIND
*INVISIBLE
*POISON
*ENTANGLED
*TIED_UP
*STUNNED
*POISON_RESISTANT
*FIRE_RESISTANT
*FLYING
*COLLAPSED
*INSANITY
*PEACEFULNESS
*LIGHT_SOURCE
*DARKNESS_SOURCE
*PREGNANT
*SLEEP_RESISTANT
*MAGIC_RESISTANCE
*MELEE_RESISTANCE
*RANGED_RESISTANCE
*MAGIC_VULNERABILITY
*MELEE_VULNERABILITY
*RANGED_VULNERABILITY
*ELF_VISION
*NIGHT_VISION
*REGENERATION
*WARNING
*TELEPATHY
*SUNLIGHT_VULNERABLE
*SATIATED
*RESTED
*SUMMONED
*HATE_DWARVES
*HATE_UNDEAD
*HATE_HUMANS
*HATE_GREENSKINS
*HATE_ELVES
*FAST_CRAFTING
*FAST_TRAINING
*SLOW_CRAFTING
*SLOW_TRAINING

[[Category: Modding Reference Data]]

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_LastingEffects](/keeperrl_wiki/Old_LastingEffects "wikilink")

Other items in this section
-    [LastingEffects 0](/keeperrl_wiki/LastingEffects_0 "wikilink")
-    [LastingEffects 1](/keeperrl_wiki/LastingEffects_1 "wikilink")
-    [LastingEffects 2](/keeperrl_wiki/LastingEffects_2 "wikilink")
-    [LastingEffects 3](/keeperrl_wiki/LastingEffects_3 "wikilink")
-    [LastingEffects 4](/keeperrl_wiki/LastingEffects_4 "wikilink")
-    [LastingEffects 5](/keeperrl_wiki/LastingEffects_5 "wikilink")
-    [LastingEffects 6](/keeperrl_wiki/LastingEffects_6 "wikilink")
-    [LastingEffects 7](/keeperrl_wiki/LastingEffects_7 "wikilink")
-    [LastingEffects 8](/keeperrl_wiki/LastingEffects_8 "wikilink")
