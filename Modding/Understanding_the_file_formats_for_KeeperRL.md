---
title: Understanding The File Formats For KeeperRL
permalink: Understanding_The_File_Formats_For_KeeperRL/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")

general rules
=============

-   The text files are editable in a text editor
-   Each text file is a set of tables containing a list of available
    game content
-   Multiple spaces and new lines between entries in the table are read
    as a single space
-   Lines starting in a \# are ignored and may contain useful comments

technology.txt
==============

### Begin the file

The file always begins like this:

`\{`  
`\{`

### The table of technologies in the game

-   Each entry adds a new technology to the game.
-   The entry has two possible formats

1) “**TechId**” \{**Description**\} Example:

“`alchemy`”` \{ `“`Build`` ``a`` ``laboratory`` ``and`` ``produce`` ``basic`` ``potions.`”` \}`

2) “**TechId1**” \{ “**Description**” \{“**TechId2**”\} \}

Where TechID1 is the new technology and TechId2 must be researched first
to unlock it. Example:

“`alchemical`` ``conversion`”` \{ `“`Convert`` ``resources`` ``to`` ``and`` ``from`` ``gold.`”` \{`“`alchemy`”`\} \}`

### End the file

The file always begins like this:

`\}`  
`\}`

workshops\_menu.txt
===================

### Begin the file

The file always begins like this:

`\{`  

-   The format is constructed of sections, sub-sections and entries

### Sections and subsections

-   There can be as many sections as you want and later on any section
    can be assigned to player\_characters.txt to give those characters
    the build menu sections they need.
-   There are 4 sub-sections below each section. These subsections are
    respectively for:

1.  Workshop
2.  Forge
3.  Lab
4.  Jeweller

-   Each subsection has as many entries as you want.

Example of an empty section with all 4 subsections but no actual
entries:

“`DwarvenCrafting`”  
`# Workshop`  
`\{`  
`\}`  
  
`# Forge`  
`\{`  
`\}`  
  
`# Lab`  
`\{`  
`\}`  
  
`# Jeweller`  
  
`\{`  
`\}`

### Entries

-   Each entry enables an item to be built in that workshop, forge,
    jewellers or lab.
-   The entry has two possible formats

1) \{\{[ItemType](/keeperrl_wiki/ItemTypes "wikilink")\} **Speed**
[ResourceID](/keeperrl_wiki/ResourceIDs "wikilink") **Amount**\}

Example:

  
` \{ 0.03 \{ SkillId FORGE LastingEffect INSANITY \}\}\}`

-   Each entry ends with

`\}`

-   Each section ends with

`\}`

### End the file

The file always ends like this:

`\}`

player\_creatures.txt
=====================

### Begin the file

The file always begins like this:

`\{`

-   The format is constructed of 2 sections (keepers and adventures) and
    entries in both sections.
-   Each section begins with

`\{`

-   Each section ends with

`\}`

### Keeper Entries

-   Entries in the keeper section enable a new type of **Keeper Class**
-   The immigrants available from immigration.txt are specified
-   The technologies available from technology.txt are specified
-   The game menus available to the keeper class from build\_menus.txt
    are specified
-   The items buildable in workshops from workshops\_menu.txt are
    specified.
-   The format for an entry is as follows:

`\{`  
`  creatureId = \{ `[`CreatureIDMale`](/keeperrl_wiki/CreatureIDs "wikilink")` `[`CreatureIDFemale`](/keeperrl_wiki/CreatureIDs "wikilink")` \}`  
`  tribeAlignment = `[`TribeAlignment`](/keeperrl_wiki/TribeAlignments "wikilink")  
`  immigrantGroups = \{`“**`ImmigrantSection1`**”` `“**`ImmigrantSection2`**”`...\}`  
`  technology = \{`  
`    `“**`TechID1`**”` `“**`TechID2`**”`...`  
`    \}`  
`  intialTech = \{`  
`    `“**`TechID1`**”` `“**`TechID2`**”`...`  
`    \}`  
`  buildingGroups = \{`  
`    \{`“**`BuildMenuSection1`**”` `“**`BuildMenuSection2`**”`...\}`  
`  \}`  
`  workshopGroups = \{`  
`    \{`“**`WorkshopMenuSection1`**”` `“**`WorkshopMenuSection2`**”`...\}`  
`  \}`  
`  description = `“**`HelpText`**”  
`\}`

Example:

`\{`  
`  creatureId = \{ KEEPER_MAGE KEEPER_MAGE_F \}`  
`  tribeAlignment = EVIL`  
`  immigrantGroups = \{`“`imps`”` `“`dark_keeper`”`\}`  
`  technology = \{`  
`    `“`alchemy`”` `“`advanced`` ``alchemy`”` `“`alchemical`` ``conversion`”` `“`humanoid`` ``mutation`”` `“`beast`` ``mutation`”  
`    `“`pig`` ``breeding`”` `“`iron`` ``working`”` `“`jewellery`”` `“`two-handed`` ``weapons`”` `“`traps`”` `“`archery`”` `“`sorcery`”  
`    `“`advanced`` ``sorcery`”` `“`magical`` ``weapons`”` `“`master`` ``sorcery`”` `“`demonology`”  
`    \}`  
`  initialTech = \{ `“`sorcery`”` \}`  
`  buildingGroups = \{`  
`    `“`structure`”` `“`doors`”` `“`floors`”` `“`storage`”` `“`quarters`”` `“`library`”` `“`throne`”` `“`beds`”` `“`beast_cage`”` `“`pigsty`”` `“`coffins`”  
`    `“`training`”` `“`crafting`”` `“`demon_shrine`”` `“`prison`”` `“`orders`”` `“`installations`”` `“`magical_installations`”` `“`traps`”  
`  \}`  
`  workshopGroups = \{ `“`basic`”` `“`traps`”` \}`  
`  description = `“`Build`` ``and`` ``manage`` ``your`` ``dream`` ``dungeon,`` ``defend`` ``against`` ``raids,`` ``and`` ``attack`` ``your`` ``enemies!`”  
`\}`

### Adventurers Entries

-   Entries in the adventurer section enable a new type of **Adventurer
    Class**

`\{ `[`CreatureIDMale`](/keeperrl_wiki/CreatureIDs "wikilink")` `[`CreatureIDFemale`](/keeperrl_wiki/CreatureIDs "wikilink")` \} `[`TribeAlignment`](/keeperrl_wiki/TribeAlignments "wikilink")` `“**`HelpText`**”

Example:

`\{ ADVENTURER ADVENTURER_F \} LAWFUL `“`Roam`` ``the`` ``land`` ``in`` ``search`` ``of`` ``adventures`` ``and`` ``loot!`”

### End the file

The file always begins like this:

`\}`

[MainPage](/keeperrl_wiki/ "wikilink")

Other items in this section
-    [Available reference data for modding KeeperRL](/keeperrl_wiki/Available_Reference_Data_For_Modding_KeeperRL "wikilink")
-    [Build Menu.txt](/keeperrl_wiki/Build_Menu.txt "wikilink")
-    [Build Requirements](/keeperrl_wiki/Build_Requirements "wikilink")
-    [Category Modding Reference Data](/keeperrl_wiki/Category_Modding_Reference_Data "wikilink")
-    [CreatureIDs](/keeperrl_wiki/CreatureIDs "wikilink")
-    [Download Mods](/keeperrl_wiki/Download_Mods "wikilink")
-    [Fixed Spawn Locations](/keeperrl_wiki/Fixed_Spawn_Locations "wikilink")
-    [Gaining familiarity with mods on KeeperRL](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL "wikilink")
-    [Immigration Options](/keeperrl_wiki/Immigration_Options "wikilink")
-    [Modding](/keeperrl_wiki/Modding "wikilink")
-    [Modding Creatures](/keeperrl_wiki/Modding_Creatures "wikilink")
-    [Modding Effect Types](/keeperrl_wiki/Modding_Effect_Types "wikilink")
-    [Modding Effects](/keeperrl_wiki/Modding_Effects "wikilink")
-    [Modding Enemies](/keeperrl_wiki/Modding_Enemies "wikilink")
-    [Modding guide](/keeperrl_wiki/Modding_Guide "wikilink")
-    [Modding Immigration](/keeperrl_wiki/Modding_Immigration "wikilink")
-    [Modding Reference Data Guide](/keeperrl_wiki/Modding_Reference_Data_Guide "wikilink")
-    [Modding Technology](/keeperrl_wiki/Modding_Technology "wikilink")
-    [Modding Traits](/keeperrl_wiki/Modding_Traits "wikilink")
-    [Modding Views](/keeperrl_wiki/Modding_Views "wikilink")
-    [Modding Zones](/keeperrl_wiki/Modding_Zones "wikilink")
-    [Player Creatures.txt](/keeperrl_wiki/Player_Creatures.txt "wikilink")
-    [ResourceIDs](/keeperrl_wiki/ResourceIDs "wikilink")
