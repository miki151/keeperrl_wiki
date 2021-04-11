---
title: Modding Guide 29
permalink: Modding_Guide_29/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Modding_Guide](/keeperrl_wiki/Old_Modding_Guide "wikilink")

=Gaining familiarity with mods on KeeperRL=
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

==Suggestions for simple changes technology.txt==

===Include a mention of heavy wooden clubs considering two-handed weapon tech===
Change the line containing
 two-handed weapons
and edit the description text.

===Remove the requirement for researching advanced sorcery before demonology===
Change the line containing:
 DEMONOLOGY
and delete this:
 {&quot;advanced sorcery&quot;}

==Suggestions for simple changes player_creatures.txt==

===Make it impossible for mages to get the archery technology===
Change line 9 containing
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

==Suggestions for simple changes campaign_villains.txt==

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

=Understanding the file formats for Alpha 26=
#Not written yet. Check back later.#

=Available reference data for modding in Alpha 26=
#Not written yet. Check back later.

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Modding_Guide](/keeperrl_wiki/Old_Modding_Guide "wikilink")

Other items in this section
-    [Modding Guide 0](/keeperrl_wiki/Modding_Guide_0 "wikilink")
-    [Modding Guide 1](/keeperrl_wiki/Modding_Guide_1 "wikilink")
-    [Modding Guide 10](/keeperrl_wiki/Modding_Guide_10 "wikilink")
-    [Modding Guide 11](/keeperrl_wiki/Modding_Guide_11 "wikilink")
-    [Modding Guide 12](/keeperrl_wiki/Modding_Guide_12 "wikilink")
-    [Modding Guide 13](/keeperrl_wiki/Modding_Guide_13 "wikilink")
-    [Modding Guide 14](/keeperrl_wiki/Modding_Guide_14 "wikilink")
-    [Modding Guide 15](/keeperrl_wiki/Modding_Guide_15 "wikilink")
-    [Modding Guide 16](/keeperrl_wiki/Modding_Guide_16 "wikilink")
-    [Modding Guide 17](/keeperrl_wiki/Modding_Guide_17 "wikilink")
-    [Modding Guide 18](/keeperrl_wiki/Modding_Guide_18 "wikilink")
-    [Modding Guide 19](/keeperrl_wiki/Modding_Guide_19 "wikilink")
-    [Modding Guide 2](/keeperrl_wiki/Modding_Guide_2 "wikilink")
-    [Modding Guide 20](/keeperrl_wiki/Modding_Guide_20 "wikilink")
-    [Modding Guide 21](/keeperrl_wiki/Modding_Guide_21 "wikilink")
-    [Modding Guide 22](/keeperrl_wiki/Modding_Guide_22 "wikilink")
-    [Modding Guide 23](/keeperrl_wiki/Modding_Guide_23 "wikilink")
-    [Modding Guide 24](/keeperrl_wiki/Modding_Guide_24 "wikilink")
-    [Modding Guide 25](/keeperrl_wiki/Modding_Guide_25 "wikilink")
-    [Modding Guide 26](/keeperrl_wiki/Modding_Guide_26 "wikilink")
-    [Modding Guide 27](/keeperrl_wiki/Modding_Guide_27 "wikilink")
-    [Modding Guide 28](/keeperrl_wiki/Modding_Guide_28 "wikilink")
-    [Modding Guide 3](/keeperrl_wiki/Modding_Guide_3 "wikilink")
-    [Modding Guide 30](/keeperrl_wiki/Modding_Guide_30 "wikilink")
-    [Modding Guide 31](/keeperrl_wiki/Modding_Guide_31 "wikilink")
-    [Modding Guide 32](/keeperrl_wiki/Modding_Guide_32 "wikilink")
-    [Modding Guide 33](/keeperrl_wiki/Modding_Guide_33 "wikilink")
-    [Modding Guide 34](/keeperrl_wiki/Modding_Guide_34 "wikilink")
-    [Modding Guide 35](/keeperrl_wiki/Modding_Guide_35 "wikilink")
-    [Modding Guide 36](/keeperrl_wiki/Modding_Guide_36 "wikilink")
-    [Modding Guide 37](/keeperrl_wiki/Modding_Guide_37 "wikilink")
-    [Modding Guide 38](/keeperrl_wiki/Modding_Guide_38 "wikilink")
-    [Modding Guide 39](/keeperrl_wiki/Modding_Guide_39 "wikilink")
-    [Modding Guide 4](/keeperrl_wiki/Modding_Guide_4 "wikilink")
-    [Modding Guide 40](/keeperrl_wiki/Modding_Guide_40 "wikilink")
-    [Modding Guide 41](/keeperrl_wiki/Modding_Guide_41 "wikilink")
-    [Modding Guide 42](/keeperrl_wiki/Modding_Guide_42 "wikilink")
-    [Modding Guide 5](/keeperrl_wiki/Modding_Guide_5 "wikilink")
-    [Modding Guide 6](/keeperrl_wiki/Modding_Guide_6 "wikilink")
-    [Modding Guide 7](/keeperrl_wiki/Modding_Guide_7 "wikilink")
-    [Modding Guide 8](/keeperrl_wiki/Modding_Guide_8 "wikilink")
-    [Modding Guide 9](/keeperrl_wiki/Modding_Guide_9 "wikilink")
