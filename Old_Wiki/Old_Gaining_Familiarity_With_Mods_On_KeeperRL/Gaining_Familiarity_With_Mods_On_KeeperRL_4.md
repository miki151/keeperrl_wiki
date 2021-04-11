---
title: Gaining Familiarity With Mods On KeeperRL 4
permalink: Gaining_Familiarity_With_Mods_On_KeeperRL_4/
layout: wiki
---
==Recommended method==
*The first recommendation is to get familiar with the existing modding system on KeeperRL
*Read the [[Download_Mods]] wiki page
*Install some existing mods
*Test them
*Make some simple changes to the mod files (Try some of the suggestions below) and test the changes.

==Suggestions for simple changes to workshops_menu.txt==
===Remove wooden staffs from the workshop===
Delete the line containing:
 WoodenStaff
under the 
 # Workshop
section.

===Reduce the cost of golden staffs===
In the line containing
 GoldenStaff
on the
 &quot;# Forge&quot;
section change the numbers in that line.


===Sell rings of invisibility instead of wakefulness===
Change the line containing
 &quot;RESTED&quot;
in the
 # Jeweller section.
Change it to
 &quot;INVISIBLE&quot;

===Change an exchange rate for resources===
In the
 &quot;# Lab section&quot;.
experiment with changing the numbers.

==Suggestions for simple changes to technology.txt==

===Include a mention of heavy wooden clubs considering two-handed weapon tech===
Change the line containing
 two-handed weapons
and edit the description text.

===Remove the requirement for researching advanced sorcery before demonology===
Change the line containing:
 DEMONOLOGY
and delete this:
 {&quot;advanced sorcery&quot;}

==Suggestions for simple changes to player_creatures.txt==

===Make it impossible for mages to get the archery technology===
Change line 9 containing:
 &quot;archery&quot;
Remove the text
 &quot;archery&quot;


===Remove female adventurers===
In the
 # Adventures
section at the bottom delete this text:
 ADVENTURER_F

==Suggestions for simple changes immigration.txt==

===Allow recruitment of gnomes===
Find the
 # Dark Keeeper
section. Look at the block where:
 ids = { GOBLIN }
Change it to:
 ids = { GOBLIN GNOME }


===Recruiting all goblins without any insanity===
On lines 54 and 55 in that section, remove the text:
 LastingEffect INSANITY

==Suggestions for simple changes to campaign_villains.txt==

===Remove green dragons from keeper campaigns===
Delete the whole of Line 10 containing the text:
 GREEN_DRAGON


===Remove red dragons from keeper campaigns===
#Delete the whole of Line 8 containing the text:
 RED_DRAGON

==Suggestions for simple changes build_menu.txt==
===Make it free to fill in stone blocks===
On line 10 change the text:
 STONE 5
to
 STONE 0

===Allow building of iron training rooms without the iron working tech===
On line 155 remove the text:
 TechId &quot;iron working&quot;

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Gaining_Familiarity_With_Mods_On_KeeperRL](/keeperrl_wiki/Old_Gaining_Familiarity_With_Mods_On_KeeperRL "wikilink")

Other items in this section
-    [Gaining Familiarity With Mods On KeeperRL 0](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_0 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 1](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_1 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 10](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_10 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 11](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_11 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 12](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_12 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 13](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_13 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 14](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_14 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 15](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_15 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 16](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_16 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 17](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_17 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 18](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_18 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 19](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_19 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 2](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_2 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 20](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_20 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 21](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_21 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 22](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_22 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 23](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_23 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 24](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_24 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 25](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_25 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 26](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_26 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 27](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_27 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 28](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_28 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 29](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_29 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 3](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_3 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 30](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_30 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 31](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_31 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 32](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_32 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 33](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_33 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 34](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_34 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 35](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_35 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 36](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_36 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 37](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_37 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 38](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_38 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 39](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_39 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 40](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_40 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 41](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_41 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 42](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_42 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 43](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_43 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 44](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_44 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 45](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_45 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 46](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_46 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 47](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_47 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 48](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_48 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 49](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_49 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 5](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_5 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 50](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_50 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 51](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_51 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 52](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_52 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 53](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_53 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 54](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_54 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 55](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_55 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 56](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_56 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 57](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_57 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 58](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_58 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 59](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_59 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 6](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_6 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 60](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_60 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 61](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_61 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 62](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_62 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 63](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_63 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 64](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_64 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 65](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_65 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 66](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_66 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 67](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_67 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 68](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_68 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 69](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_69 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 7](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_7 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 70](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_70 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 71](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_71 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 72](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_72 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 8](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_8 "wikilink")
-    [Gaining Familiarity With Mods On KeeperRL 9](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL_9 "wikilink")
