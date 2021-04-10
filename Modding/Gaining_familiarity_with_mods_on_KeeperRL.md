---
title: Gaining_Familiarity_With_Mods_On_KeeperRL
permalink: Gaining_Familiarity_With_Mods_On_KeeperRL/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Modding](/keeperrl_wiki/Modding_Guide "wikilink")

Recommended method
------------------

-   The first recommendation is to get familiar with the existing
    modding system on KeeperRL
-   Read the [Download\_Mods](/keeperrl_wiki/Download_Mods "wikilink") wiki page
-   Install some existing mods
-   Test them
-   Make some simple changes to the mod files (Try some of the
    suggestions below) and test the changes.

Suggestions for simple changes to workshops\_menu.txt
-----------------------------------------------------

### Remove wooden staffs from the workshop

Delete the line containing:

`WoodenStaff`

under the

`# Workshop`

section.

### Reduce the cost of golden staffs

In the line containing

`GoldenStaff`

on the

“`#`` ``Forge`”

section change the numbers in that line.

### Sell rings of invisibility instead of wakefulness

Change the line containing

“`RESTED`”

in the

`# Jeweller section.`

Change it to

“`INVISIBLE`”

### Change an exchange rate for resources

In the

“`#`` ``Lab`` ``section`”`.`

experiment with changing the numbers.

Suggestions for simple changes to technology.txt
------------------------------------------------

### Include a mention of heavy wooden clubs considering two-handed weapon tech

Change the line containing

`two-handed weapons`

and edit the description text.

### Remove the requirement for researching advanced sorcery before demonology

Change the line containing:

`DEMONOLOGY`

and delete this:

`\{`“`advanced`` ``sorcery`”`\}`

Suggestions for simple changes to player\_creatures.txt
-------------------------------------------------------

### Make it impossible for mages to get the archery technology

Change line 9 containing:

“`archery`”

Remove the text

“`archery`”

### Remove female adventurers

In the

`# Adventures`

section at the bottom delete this text:

`ADVENTURER_F`

Suggestions for simple changes to immigration.txt
-------------------------------------------------

### Allow recruitment of gnomes

Find the

`# Dark Keeeper`

section. Look at the block where:

`ids = \{ GOBLIN \}`

Change it to:

`ids = \{ GOBLIN GNOME \}`

### Recruiting all goblins without any insanity

On lines 54 and 55 in that section, remove the text:

`LastingEffect INSANITY`

Suggestions for simple changes to campaign\_villains.txt
--------------------------------------------------------

### Remove green dragons from keeper campaigns

Delete the whole of Line 10 containing the text:

`GREEN_DRAGON`

### Remove red dragons from keeper campaigns

1.  Delete the whole of Line 8 containing the text:

`RED_DRAGON`

Suggestions for simple changes build\_menu.txt
----------------------------------------------

### Make it free to fill in stone blocks

On line 10 change the text:

`STONE 5`

to

`STONE 0`

### Allow building of iron training rooms without the iron working tech

On line 155 remove the text:

`TechId `“`iron`` ``working`”

[MainPage](/keeperrl_wiki/ "wikilink")>>[Modding](/keeperrl_wiki/Modding_Guide "wikilink")

