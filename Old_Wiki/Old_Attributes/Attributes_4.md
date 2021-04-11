---
title: Attributes 4
permalink: Attributes_4/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Attributes](/keeperrl_wiki/Old_Attributes "wikilink")

__NOTOC__
== Ranged Damage ==
''Defines the chance of a successful ranged attack and dodging.''
* Is equal to intrinsic ranged damage + ranged training + (weapon) ranged damage.

== Spell Damage ==
''Defines the chance of a successful magic attack and dodging.''
* Is equal to intrinsic spell damage + spell training + (weapon) spell damage.

== Melee Damage ==
''Affects if and how much damage is dealt in combat.''
* Is equal to intrinsic damage + melee training + (weapon) damage.

== Defense ==
''Affects if and how much damage is taken in combat.''
* Is equal to intrinsic defence + melee training + armor value.

== Inventory Limit ==
''The maxiumum amount of weight you can carry.''

== Size ==
''Affects which body parts are hit in combat.''

== Speed ==
''Affects how much time every action takes.''

== Unarmed damage ==
''Damage bonus if not wearing any weapon''

== Weight ==
''The weight of creatures dead body''

== Calculation of actual combat damage ==

 Def = targets def * ( 0.95 ^ TimesHitThisTurn ) #the stuff in parenthesis = 1 If this is the first time this target has been hit this turn
 Attack = attackers strength 
 Ratio = Attack / Def
 if Ratio &lt;= 0.6:
    No damage Delt
  if Ratio &gt;= 2.2:
    Insta-kill
  otherwise:
    if Ratio &lt;= 1 then:
        Damage = 0.3 * (Ratio - 0.6)
    if not:
        Damage = 0.733 * (Ratio - 1.0)
  #Please note that damage is a percentage

[[Category:Creature Guide]]

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Attributes](/keeperrl_wiki/Old_Attributes "wikilink")

Other items in this section
-    [Attributes 0](/keeperrl_wiki/Attributes_0 "wikilink")
-    [Attributes 1](/keeperrl_wiki/Attributes_1 "wikilink")
-    [Attributes 2](/keeperrl_wiki/Attributes_2 "wikilink")
-    [Attributes 3](/keeperrl_wiki/Attributes_3 "wikilink")
