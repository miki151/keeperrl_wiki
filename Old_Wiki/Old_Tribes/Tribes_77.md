---
title: Tribes 77
permalink: Tribes_77/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Tribes](/keeperrl_wiki/Old_Tribes "wikilink")

Tribes faced by players can sometimes have &quot;triggers&quot; which mean they are planning to attack the player's dungeon or castle. Types of triggers include greed for gold, excessive hostility, revenge for stealing from or killing tribe members, the population of your dungeon being threatening or seen as an easy target, provocation by hanging up executed prisoner heads and some other reasons.

=Campaign configuration=

The tribes faced in campaigns are configurable in campaign_villains.txt. The file looks like this:

 [[https://github.com/miki151/keeperrl/blob/master/data_free/game_config/campaign_villains.txt campaign_villains.txt]]

The standard version of Keeper is configured like this:

=Villains faced by evil keepers=

==Main Villains faced by evil keepers==
*[[Knights]]
*[[Elves]]
*[[Dwarves]]
*[[Red dragon]]
*[[Elementalist]]
*[[Green dragon]]
*[[Black Dragon]]
*[[White Dragon]]
*[[Main Lizardmen]]
*[[Warriors]]
*[[Demon den underground]]
*[[Thieves]]
*Other enemy keepers and dungeons of other players that have been uploaded

==Lesser Villains faced by evil keepers==
*[[Ents]]
*[[Driads]]
*[[Cyclops]]
*[[Shelob]]
*[[Hydra]]
*[[Unicorn Herd]]
*[[Open ant nest]]
*[[Cemetery]]

==Tribes allied to evil keepers==
*[[Ogre cave]]
*[[Harpy cave]]
*[[Sokoban reward]]
*[[Dark Elves]]
*[[Gnomes]]
*[[Orc village]]

=Villains faced by lawful keepers=

==Major lawful enemies==
*[[Red dragon]]
*[[Green dragon]]
*[[Black Dragon]]
*[[White Dragon]]
*[[Open ant nest]]
*[[Dark Elves Enemy]]
*[[Orc village]]
*[[Demon den underground]]
*[[Main Lizardmen]]
*Other enemy keepers and dungeons of other players that have been uploaded

==Minor lawful enemies==
*[[Shelob]]
*[[Cyclops]]
*[[Hydra]]
*[[Cemetery]]
*[[Ogre cave]]
*[[Open ant nest]]
*[[Harpy cave]]

==Lawful Allies==
*[[Dwarves]]
*[[Teutons]]

=Some note worthy Mini tribes=
*[[Aggressive Bandits]]
*[[Temple]]
*[[Ruins]]
*[[Dark Elves]]
*[[Lizardman cottage]]
*[[Kobold cave]]
*[[Rat people cave]]
*[[Human cottage]]
*[[Elven Cottage]]
*[[Dwarf cave]]
*[[Sealed ant nest]]
*[[Adamantium golems]]
*[[Rat cave]]

= Tribal loyalties =

Each tribe has a tribal loyalty. The tribal loyalty determines which tribes are friendly to which. This matters most in single map games, where you can coax monsters into attacking each other (eg. get the red dragon to chase you past a castle full of knights). In campaign maps, there is also some possible in-fighting between the tribes on each map sector. When tribes that are hostile to each other attack you at the same time, they may kill each other instead of you.

Note that tribal loyalties are static and do not evolve within a game. However, tribes that would normally be friendly because of their tribal loyalty can become enemies if one tribe accidentally, insanely or deliberately kills a tribe member. 

Players can be loyal to &quot;Evil&quot; or &quot;Lawful&quot;. Retired keepers are loyal to &quot;Retired&quot;. 

Tribal loyalties are found in the source code here:

[ https://github.com/miki151/keeperrl/blob/master/tribe.cpp]

This is a grid showing friendships between tribes marked with an X.

{| class=&quot;wikitable sortable&quot;
|-
!Tribal Loyalty||Monster||Lizard||Pest||Wildlife||Elf||DarkElf||Human||Dwarf||Gnome||Lawful||Evil||Retired||Greenskin||Ant||Bandit||Hostile||Peaceful||Spider
|- align=&quot;right&quot;
|'''Monster'''    ||X||.||X||.||X||X||.||X||X||.||.||X||X||X||.||.||X||.
|- align=&quot;right&quot;
|'''Lizard'''     ||.||X||X||X||X||X||.||X||X||.||.||X||X||X||X||.||X||.
|- align=&quot;right&quot;
|'''Pest'''       ||X||X||X||X||X||X||X||X||X||.||.||X||X||X||X||.||X||.
|- align=&quot;right&quot;
|'''Wildlife'''   ||.||X||X||X||X||X||X||X||X||X||X||X||X||X||X||.||X||.
|- align=&quot;right&quot;
|'''Elf'''        ||X||X||X||X||X||X||X||.||X||X||.||X||X||X||.||.||X||.
|- align=&quot;right&quot;
|'''DarkElf'''    ||X||X||X||X||X||X||.||.||X||.||X||X||X||X||.||.||X||.
|- align=&quot;right&quot;
|'''Human'''      ||.||.||X||X||X||.||X||X||X||X||.||X||X||.||.||.||X||.
|- align=&quot;right&quot;
|'''Dwarf'''      ||X||X||X||X||.||.||X||X||X||X||.||X||X||X||.||.||X||.
|- align=&quot;right&quot;
|'''Gnome'''      ||X||X||X||X||X||X||X||X||X||X||X||X||X||X||.||.||X||.
|- align=&quot;right&quot;
|'''Lawful'''    ||.||.||.||X||X||.||X||X||X||X||.||.||.||.||.||.||X||.
|- align=&quot;right&quot;
|'''Evil'''      ||.||.||.||X||.||X||.||.||X||.||X||.||X||.||X||.||X||.
|- align=&quot;right&quot;
|'''Retired'''   ||X||X||X||X||X||X||X||X||X||.||.||X||X||X||X||.||X||.
|- align=&quot;right&quot;
|'''Greenskin''' ||X||X||X||X||X||X||X||X||X||.||X||X||X||X||X||.||X||.
|- align=&quot;right&quot;
|'''Ant'''       ||X||X||X||X||X||X||.||X||X||.||.||X||X||X||X||.||X||.
|- align=&quot;right&quot;
|'''Bandit'''    ||.||X||X||X||.||.||.||.||.||.||X||X||X||X||X||.||X||.
|- align=&quot;right&quot;
|'''Hostile'''   ||.||.||.||.||.||.||.||.||.||.||.||.||.||.||.||.||.||.
|- align=&quot;right&quot;
|'''Peaceful'''  ||X||X||X||X||X||X||X||X||X||X||X||X||X||X||X||.||X||.
|- align=&quot;right&quot;
|'''Spider'''    ||.||.||.||.||.||.||.||.||.||.||.||.||.||.||.||.||.||X
|- align=&quot;right&quot;
|}

= Tribe configuration =

The tribe data is configurable and can be modded. The official configs are here:

 [[https://github.com/miki151/keeperrl/blob/master/data_free/game_config/enemies.txt enemies.txt]]

If you are going to mod the tribes data, you may need to work out the tribal loyalty for a new tribe you made. Use the grid above to select a tribal loyalty. Note that &quot;hostile&quot; is the only tribe hostile to itself. Hostile monsters of the same tribe will fight each other!

[[Category:Creature Guide]]

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Tribes](/keeperrl_wiki/Old_Tribes "wikilink")

Other items in this section
-    [Tribes 0](/keeperrl_wiki/Tribes_0 "wikilink")
-    [Tribes 1](/keeperrl_wiki/Tribes_1 "wikilink")
-    [Tribes 10](/keeperrl_wiki/Tribes_10 "wikilink")
-    [Tribes 11](/keeperrl_wiki/Tribes_11 "wikilink")
-    [Tribes 12](/keeperrl_wiki/Tribes_12 "wikilink")
-    [Tribes 13](/keeperrl_wiki/Tribes_13 "wikilink")
-    [Tribes 14](/keeperrl_wiki/Tribes_14 "wikilink")
-    [Tribes 15](/keeperrl_wiki/Tribes_15 "wikilink")
-    [Tribes 16](/keeperrl_wiki/Tribes_16 "wikilink")
-    [Tribes 17](/keeperrl_wiki/Tribes_17 "wikilink")
-    [Tribes 18](/keeperrl_wiki/Tribes_18 "wikilink")
-    [Tribes 19](/keeperrl_wiki/Tribes_19 "wikilink")
-    [Tribes 2](/keeperrl_wiki/Tribes_2 "wikilink")
-    [Tribes 20](/keeperrl_wiki/Tribes_20 "wikilink")
-    [Tribes 21](/keeperrl_wiki/Tribes_21 "wikilink")
-    [Tribes 22](/keeperrl_wiki/Tribes_22 "wikilink")
-    [Tribes 23](/keeperrl_wiki/Tribes_23 "wikilink")
-    [Tribes 24](/keeperrl_wiki/Tribes_24 "wikilink")
-    [Tribes 25](/keeperrl_wiki/Tribes_25 "wikilink")
-    [Tribes 26](/keeperrl_wiki/Tribes_26 "wikilink")
-    [Tribes 27](/keeperrl_wiki/Tribes_27 "wikilink")
-    [Tribes 28](/keeperrl_wiki/Tribes_28 "wikilink")
-    [Tribes 29](/keeperrl_wiki/Tribes_29 "wikilink")
-    [Tribes 3](/keeperrl_wiki/Tribes_3 "wikilink")
-    [Tribes 30](/keeperrl_wiki/Tribes_30 "wikilink")
-    [Tribes 31](/keeperrl_wiki/Tribes_31 "wikilink")
-    [Tribes 32](/keeperrl_wiki/Tribes_32 "wikilink")
-    [Tribes 33](/keeperrl_wiki/Tribes_33 "wikilink")
-    [Tribes 34](/keeperrl_wiki/Tribes_34 "wikilink")
-    [Tribes 35](/keeperrl_wiki/Tribes_35 "wikilink")
-    [Tribes 36](/keeperrl_wiki/Tribes_36 "wikilink")
-    [Tribes 37](/keeperrl_wiki/Tribes_37 "wikilink")
-    [Tribes 38](/keeperrl_wiki/Tribes_38 "wikilink")
-    [Tribes 39](/keeperrl_wiki/Tribes_39 "wikilink")
-    [Tribes 4](/keeperrl_wiki/Tribes_4 "wikilink")
-    [Tribes 40](/keeperrl_wiki/Tribes_40 "wikilink")
-    [Tribes 41](/keeperrl_wiki/Tribes_41 "wikilink")
-    [Tribes 42](/keeperrl_wiki/Tribes_42 "wikilink")
-    [Tribes 43](/keeperrl_wiki/Tribes_43 "wikilink")
-    [Tribes 44](/keeperrl_wiki/Tribes_44 "wikilink")
-    [Tribes 45](/keeperrl_wiki/Tribes_45 "wikilink")
-    [Tribes 46](/keeperrl_wiki/Tribes_46 "wikilink")
-    [Tribes 47](/keeperrl_wiki/Tribes_47 "wikilink")
-    [Tribes 48](/keeperrl_wiki/Tribes_48 "wikilink")
-    [Tribes 49](/keeperrl_wiki/Tribes_49 "wikilink")
-    [Tribes 5](/keeperrl_wiki/Tribes_5 "wikilink")
-    [Tribes 50](/keeperrl_wiki/Tribes_50 "wikilink")
-    [Tribes 51](/keeperrl_wiki/Tribes_51 "wikilink")
-    [Tribes 52](/keeperrl_wiki/Tribes_52 "wikilink")
-    [Tribes 53](/keeperrl_wiki/Tribes_53 "wikilink")
-    [Tribes 54](/keeperrl_wiki/Tribes_54 "wikilink")
-    [Tribes 55](/keeperrl_wiki/Tribes_55 "wikilink")
-    [Tribes 56](/keeperrl_wiki/Tribes_56 "wikilink")
-    [Tribes 57](/keeperrl_wiki/Tribes_57 "wikilink")
-    [Tribes 58](/keeperrl_wiki/Tribes_58 "wikilink")
-    [Tribes 59](/keeperrl_wiki/Tribes_59 "wikilink")
-    [Tribes 6](/keeperrl_wiki/Tribes_6 "wikilink")
-    [Tribes 60](/keeperrl_wiki/Tribes_60 "wikilink")
-    [Tribes 61](/keeperrl_wiki/Tribes_61 "wikilink")
-    [Tribes 62](/keeperrl_wiki/Tribes_62 "wikilink")
-    [Tribes 63](/keeperrl_wiki/Tribes_63 "wikilink")
-    [Tribes 64](/keeperrl_wiki/Tribes_64 "wikilink")
-    [Tribes 65](/keeperrl_wiki/Tribes_65 "wikilink")
-    [Tribes 66](/keeperrl_wiki/Tribes_66 "wikilink")
-    [Tribes 67](/keeperrl_wiki/Tribes_67 "wikilink")
-    [Tribes 68](/keeperrl_wiki/Tribes_68 "wikilink")
-    [Tribes 69](/keeperrl_wiki/Tribes_69 "wikilink")
-    [Tribes 7](/keeperrl_wiki/Tribes_7 "wikilink")
-    [Tribes 70](/keeperrl_wiki/Tribes_70 "wikilink")
-    [Tribes 71](/keeperrl_wiki/Tribes_71 "wikilink")
-    [Tribes 72](/keeperrl_wiki/Tribes_72 "wikilink")
-    [Tribes 73](/keeperrl_wiki/Tribes_73 "wikilink")
-    [Tribes 74](/keeperrl_wiki/Tribes_74 "wikilink")
-    [Tribes 75](/keeperrl_wiki/Tribes_75 "wikilink")
-    [Tribes 76](/keeperrl_wiki/Tribes_76 "wikilink")
-    [Tribes 78](/keeperrl_wiki/Tribes_78 "wikilink")
-    [Tribes 79](/keeperrl_wiki/Tribes_79 "wikilink")
-    [Tribes 8](/keeperrl_wiki/Tribes_8 "wikilink")
-    [Tribes 80](/keeperrl_wiki/Tribes_80 "wikilink")
-    [Tribes 81](/keeperrl_wiki/Tribes_81 "wikilink")
-    [Tribes 9](/keeperrl_wiki/Tribes_9 "wikilink")
