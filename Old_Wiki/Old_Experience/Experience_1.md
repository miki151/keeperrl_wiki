== Creature Level ==
A creatures level is calculated from its strength and dexterity.

 Level = max[1.0, 10 * ((STRENGTH / 12) - 1) + 10 * ((DEXTERITY / 12) - 1)]

== Attribute Gains ==
A creature can get attribute gains by training or killing an enemy.

Possible attribute gains are:
* Strenght bonus
* Dexterity bonus
* Speed bonus

The displayed value of an attribute is the sum of its ''baseValue'', its ''bonusValue'' and ''item/spell bonuses''.
* ''baseVale'' is the one from the minions [[:Orc#Attributes|base values]].
* ''bonusValue'' is the bonus from training and fighting.


=== Training ===
----
title: Experience 1
permalink: Experience_1/
layout: wiki
----
When a creature kills an enemy, the creatures level is increased based on the level difference to the victim and its attributes are raised accordingly.

'''Level bonus'''
{| class=&quot;wikitable&quot;
|- align=&quot;center&quot;
|align=&quot;left&quot;|Level difference
|MIN||-7||-6||-5||-4||-3||-2||-1||0||1||2||3||4||5||6||7||8||MAX
|- align=&quot;center&quot;
|align=&quot;left&quot;|Level bonus
|0.05||0.05||0.13||0.27||0.40||0.54||0.67||0.81||0.94||1.08||1.21||1.35||1.48||1.62||1.75||1.89||2.00||2.00
|}

'''Attribute bonus'''

After calculating the level difference the following happens:
# remember the current level as ''oldLevel''
# a random attribute [[:Experience#Attribute_Gains|bonusValue]] (either strength, dexterity or speed with equal chances) is increased by a certain amount
# calculate the value of the ''newLevel'' based on the new attribute value(s) 
# check if the ''newLevel'' is equal or larger then the ''oldLevel'' plus the ''level bonus''.
# if the ''newLevel'' is not equal or larger start again with step 2.

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Experience](/keeperrl_wiki/Old_Experience "wikilink")

Other items in this section
-    [Experience 0](/keeperrl_wiki/Experience_0 "wikilink")
-    [Experience 10](/keeperrl_wiki/Experience_10 "wikilink")
-    [Experience 11](/keeperrl_wiki/Experience_11 "wikilink")
-    [Experience 12](/keeperrl_wiki/Experience_12 "wikilink")
-    [Experience 13](/keeperrl_wiki/Experience_13 "wikilink")
-    [Experience 14](/keeperrl_wiki/Experience_14 "wikilink")
-    [Experience 15](/keeperrl_wiki/Experience_15 "wikilink")
-    [Experience 16](/keeperrl_wiki/Experience_16 "wikilink")
-    [Experience 2](/keeperrl_wiki/Experience_2 "wikilink")
-    [Experience 3](/keeperrl_wiki/Experience_3 "wikilink")
-    [Experience 4](/keeperrl_wiki/Experience_4 "wikilink")
-    [Experience 5](/keeperrl_wiki/Experience_5 "wikilink")
-    [Experience 6](/keeperrl_wiki/Experience_6 "wikilink")
-    [Experience 7](/keeperrl_wiki/Experience_7 "wikilink")
-    [Experience 8](/keeperrl_wiki/Experience_8 "wikilink")
-    [Experience 9](/keeperrl_wiki/Experience_9 "wikilink")
