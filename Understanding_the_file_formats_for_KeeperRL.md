---
title: Understanding the file formats for KeeperRL
permalink: wiki/Understanding_the_file_formats_for_KeeperRL/
layout: wiki
---

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
`  creatureId = \{ `[`CreatureIDMale`](/keeperrl_wiki/CreatureIDs "wikilink")` `[`CreatureIDFemale`](CreatureIDs "wikilink")` \}`  
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

`\{ `[`CreatureIDMale`](/keeperrl_wiki/CreatureIDs "wikilink")` `[`CreatureIDFemale`](CreatureIDs "wikilink")` \} `[`TribeAlignment`](/keeperrl_wiki/TribeAlignments "wikilink")` `“**`HelpText`**”

Example:

`\{ ADVENTURER ADVENTURER_F \} LAWFUL `“`Roam`` ``the`` ``land`` ``in`` ``search`` ``of`` ``adventures`` ``and`` ``loot!`”

### End the file

The file always begins like this:

`\}`
