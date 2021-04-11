---
title: Minions 55
permalink: Minions_55/
layout: wiki
---

= Base Stats =

{| class=&quot;wikitable sortable&quot; border=&quot;1&quot;
|-
! scope=&quot;col&quot; | Creature
! scope=&quot;col&quot; | Strength
! scope=&quot;col&quot; | Dexterity
! scope=&quot;col&quot; | Speed
! scope=&quot;col&quot; | Salary
! scope=&quot;col&quot; | Unarmed&lt;br&gt;Damage
! scope=&quot;col&quot; | Can wear&lt;br&gt;Equipment
! scope=&quot;col&quot; | Weight
! scope=&quot;col&quot; | Size
! scope=&quot;col&quot; | [[Immigration|Immigrant&lt;br&gt;Frequency]]
|-
| [[Keeper]]
| 15
| 15
| 100
| -
| 5
| YES
| 90
| LARGE
| -
|-
| [[Imp]]
| 8
| 15
| 200
| -
| 3
| NO
| 30
| SMALL
| -
|-
| [[Goblin]]
| 12
| 13
| 80
| 10
| 3
| NO
| 45
| MEDIUM
| 1.0

|-
| [[Orc]]
| 16
| 14
| 100
| 20
| 3
| YES
| 100
| LARGE
| 0.7

|-
| [[Orc Shaman]]
| 13
| 11
| 100
| 20
| 3
| YES
| 100
| LARGE
| 0.15
|-
| [[Ogre]]
| 20
| 17
| 80
| 40
| 6
| YES
| 140
| LARGE
| 0.3
|-
| [[Harpy]]
| 13
| 16
| 120
| 40
| 3
| YES
| 70
| LARGE
| 0.3
|-
| [[Zombie]]
| 14
| 13
| 60
| 10
| 13
| YES
| 100
| LARGE
| 0.5
|-
| [[Vampire]]
| 17
| 17
| 100
| 40
| 2
| YES
| 70
| LARGE
| 0.3
|-
| [[Ghost]]
| 5
| 35
| 80
| -
| 3
| NO
| 10
| LARGE
| 0.3
|-
| [[Succubus]]
| 5
| 15
| 80
| -
| 3
| NO
| 10
| LARGE
| 0.3
|-
| [[Doppleganger|Doppelganger]]
| 14
| 15
| 80
| -
| 3
| ?
| 10
| LARGE
| 0.2
|-
| [[Raven]]
| 2
| 12
| 250
| -
| 0
| NO
| 0.5
| SMALL
| 1.0
|-
| [[Bat]]
| 3
| 16
| 150
| -
| 2
| NO
| 0.5
| SMALL
| 1.0

|-
| [[Wolf]]
| 18
| 17
| 160
| -
| 12
| NO
| 35
| MEDIUM
| 0.15
|-
| [[Cave Bear]]
| 23
| 18
| 120
| -
| 11
| NO
| 250
| MEDIUM
| 0.1
|-
| [[Werewolf]]
| 18
| 17
| 100
| -
| 12
| YES
| 0.5
| LARGE
| 0.1
|-
| [[Legendary Humanoid]]
| 20-26
| 20-26
| 70-150
| 40
| 5-15
| YES
| 5-120
| S / M / L
| 0.2
|-
| [[Legendary Beast]]
| 15-26
| 20-36
| 70-150
| 40
| 5-25
| YES
| 5-120
| S / M / L
| 0.2
|}

source: creature_factory.cpp, model_builder.cpp

= Level =

A creatures level[https://github.com/miki151/keeperrl/blob/master/creature.cpp#L2113] is:

 max[1.0, 10 * ((STRENGTH / 12) - 1) + 10 * ((DEXTERITY / 12) - 1)]

Decimal places are not displayed.

= Experience =

'''Leveled Stats:'''
* Strength
* Dexterity
* Speed

 stat[Str|Dex|Spd] = statBase[Str|Dex|Spd] + statIncrease[Str|Dex|Spd]

 
'''Training Room:'''

Each time training is applied, choose and increase one random Stat [Str|Dex|Spd][https://github.com/miki151/keeperrl/blob/master/creature.cpp#L2135]

 statIncrease[RND] += ( statBase[RND] - statIncrease[RND] ) * 0.001 * roomTileEfficiency[0.x-1.0]

Ticks needed until training applied ?(2-3)? (depends on speed)

This translates to following increase per Stat:

{| class=&quot;wikitable&quot; border=&quot;1&quot;
|-
|'''Training units per Stat'''
|110
|225
|360
|510
|690
|925
|1200
|1600
|2300
|8800
|-
|'''Stat increase'''
|10%
|20%
|30%
|40%
|50%
|60%
|70%
|80%
|90%
|99,99%
|}

'''Kill Experience:'''

 levelGain[https://github.com/miki151/keeperrl/blob/master/creature.cpp#L942] = max[0.05, min[2.0, 1.9 * ((Level[victim] - Level[killer]) + 7) / (2.0 * 7) + 0.1]]

 oldExpLevel = max[1.0, 10 * ((STRENGTH / 12) - 1) + 10 * ((DEXTERITY / 12) - 1)]

 do 100000 times:[https://github.com/miki151/keeperrl/blob/master/creature.cpp#L2135]
    Rnd = random Stat [Str|Dex|Spd]
    statIncrease[Rnd] += ( statBase[Rnd] - statIncrease[Rnd] ) * 0.001 * 0.05
    if ( max[1.0, 10 * ((Strength / 12) - 1) + 10 * ((Dexterity / 12) - 1)] &gt;= oldExpLevel + levelGain )
       break

= Salary =

A creature only costs gold when training or working in a room.

The payout for each creature is:

 SALARY * 3 * workAmount / 500

workAmount is roughly:

 (2 * SPEED) * [TIME on training/working TILE] / 500

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Minions](/keeperrl_wiki/Old_Minions "wikilink")

Other items in this section
-    [Minions 0](/keeperrl_wiki/Minions_0 "wikilink")
-    [Minions 1](/keeperrl_wiki/Minions_1 "wikilink")
-    [Minions 10](/keeperrl_wiki/Minions_10 "wikilink")
-    [Minions 11](/keeperrl_wiki/Minions_11 "wikilink")
-    [Minions 12](/keeperrl_wiki/Minions_12 "wikilink")
-    [Minions 13](/keeperrl_wiki/Minions_13 "wikilink")
-    [Minions 14](/keeperrl_wiki/Minions_14 "wikilink")
-    [Minions 15](/keeperrl_wiki/Minions_15 "wikilink")
-    [Minions 16](/keeperrl_wiki/Minions_16 "wikilink")
-    [Minions 17](/keeperrl_wiki/Minions_17 "wikilink")
-    [Minions 18](/keeperrl_wiki/Minions_18 "wikilink")
-    [Minions 19](/keeperrl_wiki/Minions_19 "wikilink")
-    [Minions 2](/keeperrl_wiki/Minions_2 "wikilink")
-    [Minions 20](/keeperrl_wiki/Minions_20 "wikilink")
-    [Minions 21](/keeperrl_wiki/Minions_21 "wikilink")
-    [Minions 22](/keeperrl_wiki/Minions_22 "wikilink")
-    [Minions 23](/keeperrl_wiki/Minions_23 "wikilink")
-    [Minions 24](/keeperrl_wiki/Minions_24 "wikilink")
-    [Minions 25](/keeperrl_wiki/Minions_25 "wikilink")
-    [Minions 26](/keeperrl_wiki/Minions_26 "wikilink")
-    [Minions 27](/keeperrl_wiki/Minions_27 "wikilink")
-    [Minions 28](/keeperrl_wiki/Minions_28 "wikilink")
-    [Minions 29](/keeperrl_wiki/Minions_29 "wikilink")
-    [Minions 3](/keeperrl_wiki/Minions_3 "wikilink")
-    [Minions 30](/keeperrl_wiki/Minions_30 "wikilink")
-    [Minions 31](/keeperrl_wiki/Minions_31 "wikilink")
-    [Minions 32](/keeperrl_wiki/Minions_32 "wikilink")
-    [Minions 33](/keeperrl_wiki/Minions_33 "wikilink")
-    [Minions 34](/keeperrl_wiki/Minions_34 "wikilink")
-    [Minions 35](/keeperrl_wiki/Minions_35 "wikilink")
-    [Minions 36](/keeperrl_wiki/Minions_36 "wikilink")
-    [Minions 37](/keeperrl_wiki/Minions_37 "wikilink")
-    [Minions 38](/keeperrl_wiki/Minions_38 "wikilink")
-    [Minions 39](/keeperrl_wiki/Minions_39 "wikilink")
-    [Minions 4](/keeperrl_wiki/Minions_4 "wikilink")
-    [Minions 40](/keeperrl_wiki/Minions_40 "wikilink")
-    [Minions 41](/keeperrl_wiki/Minions_41 "wikilink")
-    [Minions 42](/keeperrl_wiki/Minions_42 "wikilink")
-    [Minions 43](/keeperrl_wiki/Minions_43 "wikilink")
-    [Minions 44](/keeperrl_wiki/Minions_44 "wikilink")
-    [Minions 45](/keeperrl_wiki/Minions_45 "wikilink")
-    [Minions 46](/keeperrl_wiki/Minions_46 "wikilink")
-    [Minions 47](/keeperrl_wiki/Minions_47 "wikilink")
-    [Minions 48](/keeperrl_wiki/Minions_48 "wikilink")
-    [Minions 49](/keeperrl_wiki/Minions_49 "wikilink")
-    [Minions 5](/keeperrl_wiki/Minions_5 "wikilink")
-    [Minions 50](/keeperrl_wiki/Minions_50 "wikilink")
-    [Minions 51](/keeperrl_wiki/Minions_51 "wikilink")
-    [Minions 52](/keeperrl_wiki/Minions_52 "wikilink")
-    [Minions 53](/keeperrl_wiki/Minions_53 "wikilink")
-    [Minions 54](/keeperrl_wiki/Minions_54 "wikilink")
-    [Minions 56](/keeperrl_wiki/Minions_56 "wikilink")
-    [Minions 57](/keeperrl_wiki/Minions_57 "wikilink")
-    [Minions 58](/keeperrl_wiki/Minions_58 "wikilink")
-    [Minions 59](/keeperrl_wiki/Minions_59 "wikilink")
-    [Minions 6](/keeperrl_wiki/Minions_6 "wikilink")
-    [Minions 60](/keeperrl_wiki/Minions_60 "wikilink")
-    [Minions 7](/keeperrl_wiki/Minions_7 "wikilink")
-    [Minions 8](/keeperrl_wiki/Minions_8 "wikilink")
-    [Minions 9](/keeperrl_wiki/Minions_9 "wikilink")
