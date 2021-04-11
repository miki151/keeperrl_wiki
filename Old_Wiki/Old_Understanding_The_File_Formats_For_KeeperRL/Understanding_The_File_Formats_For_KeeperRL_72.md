---
title: Understanding The File Formats For KeeperRL 72
permalink: Understanding_The_File_Formats_For_KeeperRL_72/
layout: wiki
---
=general rules=
*The text files are editable in a text editor
*Each text file is a set of tables containing a list of available game content
*Multiple spaces and new lines between entries in the table are read as a single space
*Lines starting in a # are ignored and may contain useful comments

=technology.txt=
*Locate technology.txt on your computer. It should look like this [[Technology.txt]]

===Begin the file===
The file always begins like this:
 {
 {

===The table of technologies in the game===
*Each entry adds a new technology to the game.
*The entry has two possible formats
1) &quot;'''TechId'''&quot; {'''Description'''}
Example:
 &quot;alchemy&quot; { &quot;Build a laboratory and produce basic potions.&quot; }
2) &quot;'''TechId1'''&quot; { &quot;'''Description'''&quot; {&quot;'''TechId2'''&quot;} }

Where TechID1 is the new technology and TechId2 must be researched first to unlock it.
Example:
 &quot;alchemical conversion&quot; { &quot;Convert resources to and from gold.&quot; {&quot;alchemy&quot;} }

===End the file===
The file always ends like this:
 }
 }

=workshops_menu.txt=
*Locate workshops_menu.txt on your computer. It should look like this [[Workshops_Menu.txt]]

===Begin the file===
The file always begins like this:
 {
 
*The format is constructed of sections, sub-sections and entries
===Sections and subsections===
*There can be as many sections as you want and later on any section can be assigned to player_characters.txt to give those characters the build menu sections they need.
*There are 4 sub-sections below each section. These subsections are respectively for:
#Workshop
#Forge
#Lab
#Jeweller
*Each subsection has as many entries as you want.

Example of an empty section with all 4 subsections but no actual entries:
 &quot;DwarvenCrafting&quot;
 # Workshop
 {
 }
 
 # Forge
 {
 }
 
 # Lab
 {
 }
 
 # Jeweller
 
 {
 }

===Entries===
*Each entry enables an item to be built in that workshop, forge, jewellers or lab.
*The entry has two possible formats
1) {{[[ItemTypes|ItemType]]} '''BuildSpeed''' [[ResourceIDs|ResourceID]] '''Amount'''}

Example:
 {{LeatherGloves} 1 WOOD 2}

2) {{[[ItemTypes|ItemType]]} '''BuildSpeed''' [[ResourceIDs|ResourceID]] '''Amount''' &quot;'''TechID'''&quot;}

Example:
 {{HeavyClub} 5 WOOD 20 &quot;two-handed weapons&quot;}

?..so, the tech Id for two handed weapons is a requirement before you can craft heavy clubs.

===End the file===
The file always ends like this:
 }

=build_menu.txt=
*Locate build_menu.txt on your computer. It should look like this [[Build_Menu.txt]]

===Begin the file===
The file always begins like this:
 {
 
*The format is constructed of sections and entries

===Sections===
*The sections can be assigned later on in player_characters.txt to give any character the entries in that section, on their build menu
*Each section begins with
 {
 &quot;'''SectionName'''&quot;
*Each section ends with
 }

===Entries===
*Each entry inside the section adds a menu item to a player's build menu
*Each entry inside the section has a number of possible formats.
*In brief the different formats are '''Dig''', '''Zone''', '''Furniture''', '''ClaimTile''', '''Dispatch''', '''Trap'''
*There are two variants of the '''Furniture''' format, which are the most useful for modding.

1) 
 { Furniture {{ [[FurnitureTypes|FurnitureType]] } [[ResourceIDs|ResourceID]] '''amount'''   
   &quot;'''MenuName'''&quot; &quot;'''MenuItem'''&quot; &quot;'''HelpTextHint'''&quot; }
Example: 
 { Furniture {{ BRIDGE } WOOD 5 } &quot;Bridge&quot; &quot;Structure&quot; &quot;Build to pass over water of lava.&quot; }

2)
 { Furniture {{ [[FurnitureTypes|FurnitureType]] } [[ResourceIDs|ResourceID]] '''amount''' }
   &quot;'''MenuName'''&quot; &quot;'''MenuItem'''&quot; &quot;'''HelpTextHint'''&quot; 0
   { TechId &quot;'''TechID'''&quot; } }
Example:
 { Furniture {{ TRAINING_IRON } IRON 12 }
   &quot;Iron dummy&quot; &quot;Training room&quot; &quot;Train your minions' melee skills here.&quot; 0
   { TechId &quot;iron working&quot; } }

===End the file===
The file always begins like this:
 }

=campaign_villains.txt=
*Locate campaign_villains.txt on your computer. It should look like this [[Campaign_Villains.txt]]

===Begin the file===
The file always begins like this:
 {
 
*The format is constructed of sections and entries

===Sections===
*Each section begins with
 {
*Each section ends with
 }
*There are 4 sections in the file. These sections are respectively for:
#Evil keeper villains
#Lawful keeper villains
#Evil adventurer villains
#Lawful adventurer villains
*Section has as many entries as you want.

Example of an empty file with all 4 sections but no actual entries:
 #Evil keeper campaign
 {
 }
 
 #Lawful keeper campaign
 {
 }
 
 #Evil adventurer campaign
 {
 }
 
 #Lawful adventurer campaign
 {
 }

===Entries===
*Each entry inside the section adds a possible villain or ally for a type of campaign  
*Each entry inside the section has any number of entries in this format:
 [[ViewIDs|ViewId]] [[EnemyIDs|EnemyID]] &quot;'''VillainName'''&quot; [[VillainTypes|VillainType]]
Example:
 DUKE4 KNIGHTS &quot;Knights&quot; MAIN

===End the file===
The file always begins like this:
 }

=immigration.txt=
*Locate immigration.txt on your computer. It should look like this [[Immigration.txt]]

===Begin the file===
The file always begins like this:
 {
 
*The format is constructed of sections and entries

===Sections===
*The sections can be assigned later on in player_characters.txt to give any character the immigrants in that sections
*Each section begins with
 {
 &quot;'''SectionName'''&quot;
*Each section ends with
 }

===Entries===
*Each entry inside the section adds a new type of immigrant
*Each entry begins with
 {
*Each entry must specify the creature ID(s) for the immigrant(s):
 ids = { [[CreatureIDs|CreatureId]] }
Or:
 ids = { [[CreatureIDs|CreatureId]] [[CreatureIDs|CreatureId]] }
Or:
 ids = { [[CreatureIDs|CreatureId]] [[CreatureIDs|CreatureId]] [[CreatureIDs|CreatureId]] }
etc.
Example:
 ids = { IMP }
*Each entry can specify any of the following:
1)
 traits = { [[TraitIDs|TraidID]] }
Or:
 traits = { [[TraitIDs|TraidID]] [[TraitIDs|TraidID]]}
etc. Example:
 traits = { WORKER NO_LIMIT NO_EQUIPMENT }
2)
 spawnLocation = [[FixedSpawnLocations|SpawnLocation]]
etc. Example:
 spawnLocation = NearLeader
3) [[ImmigrationOptions|ImmigrationOption]]=='''Value'''

Example:
 noAuto = true
4)
 requirements = {[[ImmigrationRequirements|ImmigrationRequirent(s)]]}
Example:
 requirements = {{
 0.1 AttractionInfo 1 {FurnitureType FORGE FurnitureType WORKSHOP FurnitureType JEWELLER}}}
5)
 specialTraits = {[[specialTraitTypes|specialTrait(s)]]}

Example:
 specialTraits = {
  { 0.03 { SkillId WORKSHOP LastingEffect INSANITY }}
  { 0.03 { SkillId FORGE LastingEffect INSANITY }}}
*Each entry ends with
 }
*Each section ends with
 }

===End the file===
The file always ends like this:
 }

=player_creatures.txt=
*Locate player_creatures.txt on your computer. It should look like this [[Player_Creatures.txt]]

===Begin the file===
The file always begins like this:
 {
*The format is constructed of 2 sections (keepers and adventures) and entries in both sections.
*Each section begins with
 {
*Each section ends with
 }

===Keeper Entries===
*Entries in the keeper section enable a new type of '''Keeper Class'''
*The immigrants available from immigration.txt are specified
*The technologies available from technology.txt are specified
*The game menus available to the keeper class from build_menus.txt are specified
*The items buildable in workshops from workshops_menu.txt are specified. 
*The format for an entry is as follows:
 {
   creatureId = { [[CreatureIDs|CreatureIDMale]] [[CreatureIDs|CreatureIDFemale]] }
   tribeAlignment = [[TribeAlignments|TribeAlignment]]
   immigrantGroups = {&quot;'''ImmigrantSection1'''&quot; &quot;'''ImmigrantSection2'''&quot;...}
   technology = {
     &quot;'''TechID1'''&quot; &quot;'''TechID2'''&quot;...
     }
   intialTech = {
     &quot;'''TechID1'''&quot; &quot;'''TechID2'''&quot;...
     }
   buildingGroups = {
     {&quot;'''BuildMenuSection1'''&quot; &quot;'''BuildMenuSection2'''&quot;...}
   }
   workshopGroups = {
     {&quot;'''WorkshopMenuSection1'''&quot; &quot;'''WorkshopMenuSection2'''&quot;...}
   }
   description = &quot;'''HelpText'''&quot;
 }

Example:
 {
   creatureId = { KEEPER_MAGE KEEPER_MAGE_F }
   tribeAlignment = EVIL
   immigrantGroups = {&quot;imps&quot; &quot;dark_keeper&quot;}
   technology = {
     &quot;alchemy&quot; &quot;advanced alchemy&quot; &quot;alchemical conversion&quot; &quot;humanoid mutation&quot; &quot;beast mutation&quot;
     &quot;pig breeding&quot; &quot;iron working&quot; &quot;jewellery&quot; &quot;two-handed weapons&quot; &quot;traps&quot; &quot;archery&quot; &quot;sorcery&quot;
     &quot;advanced sorcery&quot; &quot;magical weapons&quot; &quot;master sorcery&quot; &quot;demonology&quot;
     }
   initialTech = { &quot;sorcery&quot; }
   buildingGroups = {
     &quot;structure&quot; &quot;doors&quot; &quot;floors&quot; &quot;storage&quot; &quot;quarters&quot; &quot;library&quot; &quot;throne&quot; &quot;beds&quot; &quot;beast_cage&quot; &quot;pigsty&quot; &quot;coffins&quot;
     &quot;training&quot; &quot;crafting&quot; &quot;demon_shrine&quot; &quot;prison&quot; &quot;orders&quot; &quot;installations&quot; &quot;magical_installations&quot; &quot;traps&quot;
   }
   workshopGroups = { &quot;basic&quot; &quot;traps&quot; }
   description = &quot;Build and manage your dream dungeon, defend against raids, and attack your enemies!&quot;
 }

===Adventurers Entries===
*Entries in the adventurer section enable a new type of '''Adventurer Class'''
 { [[CreatureIDs|CreatureIDMale]] [[CreatureIDs|CreatureIDFemale]] } [[TribeAlignments|TribeAlignment]] &quot;'''HelpText'''&quot;

Example:
 { ADVENTURER ADVENTURER_F } LAWFUL &quot;Roam the land in search of adventures and loot!&quot;

===End the file===
The file always ends like this:
 }

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Understanding_The_File_Formats_For_KeeperRL](/keeperrl_wiki/Old_Understanding_The_File_Formats_For_KeeperRL "wikilink")

Other items in this section
-    [Understanding The File Formats For KeeperRL 0](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_0 "wikilink")
-    [Understanding The File Formats For KeeperRL 1](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_1 "wikilink")
-    [Understanding The File Formats For KeeperRL 10](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_10 "wikilink")
-    [Understanding The File Formats For KeeperRL 11](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_11 "wikilink")
-    [Understanding The File Formats For KeeperRL 12](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_12 "wikilink")
-    [Understanding The File Formats For KeeperRL 13](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_13 "wikilink")
-    [Understanding The File Formats For KeeperRL 14](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_14 "wikilink")
-    [Understanding The File Formats For KeeperRL 15](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_15 "wikilink")
-    [Understanding The File Formats For KeeperRL 16](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_16 "wikilink")
-    [Understanding The File Formats For KeeperRL 17](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_17 "wikilink")
-    [Understanding The File Formats For KeeperRL 18](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_18 "wikilink")
-    [Understanding The File Formats For KeeperRL 19](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_19 "wikilink")
-    [Understanding The File Formats For KeeperRL 2](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_2 "wikilink")
-    [Understanding The File Formats For KeeperRL 20](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_20 "wikilink")
-    [Understanding The File Formats For KeeperRL 21](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_21 "wikilink")
-    [Understanding The File Formats For KeeperRL 22](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_22 "wikilink")
-    [Understanding The File Formats For KeeperRL 23](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_23 "wikilink")
-    [Understanding The File Formats For KeeperRL 24](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_24 "wikilink")
-    [Understanding The File Formats For KeeperRL 25](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_25 "wikilink")
-    [Understanding The File Formats For KeeperRL 26](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_26 "wikilink")
-    [Understanding The File Formats For KeeperRL 27](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_27 "wikilink")
-    [Understanding The File Formats For KeeperRL 28](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_28 "wikilink")
-    [Understanding The File Formats For KeeperRL 29](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_29 "wikilink")
-    [Understanding The File Formats For KeeperRL 3](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_3 "wikilink")
-    [Understanding The File Formats For KeeperRL 30](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_30 "wikilink")
-    [Understanding The File Formats For KeeperRL 31](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_31 "wikilink")
-    [Understanding The File Formats For KeeperRL 32](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_32 "wikilink")
-    [Understanding The File Formats For KeeperRL 33](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_33 "wikilink")
-    [Understanding The File Formats For KeeperRL 34](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_34 "wikilink")
-    [Understanding The File Formats For KeeperRL 35](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_35 "wikilink")
-    [Understanding The File Formats For KeeperRL 36](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_36 "wikilink")
-    [Understanding The File Formats For KeeperRL 37](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_37 "wikilink")
-    [Understanding The File Formats For KeeperRL 38](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_38 "wikilink")
-    [Understanding The File Formats For KeeperRL 39](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_39 "wikilink")
-    [Understanding The File Formats For KeeperRL 4](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_4 "wikilink")
-    [Understanding The File Formats For KeeperRL 40](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_40 "wikilink")
-    [Understanding The File Formats For KeeperRL 41](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_41 "wikilink")
-    [Understanding The File Formats For KeeperRL 42](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_42 "wikilink")
-    [Understanding The File Formats For KeeperRL 43](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_43 "wikilink")
-    [Understanding The File Formats For KeeperRL 44](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_44 "wikilink")
-    [Understanding The File Formats For KeeperRL 45](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_45 "wikilink")
-    [Understanding The File Formats For KeeperRL 46](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_46 "wikilink")
-    [Understanding The File Formats For KeeperRL 47](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_47 "wikilink")
-    [Understanding The File Formats For KeeperRL 48](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_48 "wikilink")
-    [Understanding The File Formats For KeeperRL 49](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_49 "wikilink")
-    [Understanding The File Formats For KeeperRL 5](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_5 "wikilink")
-    [Understanding The File Formats For KeeperRL 50](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_50 "wikilink")
-    [Understanding The File Formats For KeeperRL 51](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_51 "wikilink")
-    [Understanding The File Formats For KeeperRL 52](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_52 "wikilink")
-    [Understanding The File Formats For KeeperRL 53](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_53 "wikilink")
-    [Understanding The File Formats For KeeperRL 54](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_54 "wikilink")
-    [Understanding The File Formats For KeeperRL 55](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_55 "wikilink")
-    [Understanding The File Formats For KeeperRL 56](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_56 "wikilink")
-    [Understanding The File Formats For KeeperRL 57](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_57 "wikilink")
-    [Understanding The File Formats For KeeperRL 58](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_58 "wikilink")
-    [Understanding The File Formats For KeeperRL 59](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_59 "wikilink")
-    [Understanding The File Formats For KeeperRL 6](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_6 "wikilink")
-    [Understanding The File Formats For KeeperRL 60](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_60 "wikilink")
-    [Understanding The File Formats For KeeperRL 61](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_61 "wikilink")
-    [Understanding The File Formats For KeeperRL 62](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_62 "wikilink")
-    [Understanding The File Formats For KeeperRL 63](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_63 "wikilink")
-    [Understanding The File Formats For KeeperRL 64](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_64 "wikilink")
-    [Understanding The File Formats For KeeperRL 65](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_65 "wikilink")
-    [Understanding The File Formats For KeeperRL 66](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_66 "wikilink")
-    [Understanding The File Formats For KeeperRL 67](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_67 "wikilink")
-    [Understanding The File Formats For KeeperRL 68](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_68 "wikilink")
-    [Understanding The File Formats For KeeperRL 69](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_69 "wikilink")
-    [Understanding The File Formats For KeeperRL 7](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_7 "wikilink")
-    [Understanding The File Formats For KeeperRL 70](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_70 "wikilink")
-    [Understanding The File Formats For KeeperRL 71](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_71 "wikilink")
-    [Understanding The File Formats For KeeperRL 73](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_73 "wikilink")
-    [Understanding The File Formats For KeeperRL 74](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_74 "wikilink")
-    [Understanding The File Formats For KeeperRL 75](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_75 "wikilink")
-    [Understanding The File Formats For KeeperRL 76](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_76 "wikilink")
-    [Understanding The File Formats For KeeperRL 77](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_77 "wikilink")
-    [Understanding The File Formats For KeeperRL 78](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_78 "wikilink")
-    [Understanding The File Formats For KeeperRL 79](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_79 "wikilink")
-    [Understanding The File Formats For KeeperRL 8](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_8 "wikilink")
-    [Understanding The File Formats For KeeperRL 80](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_80 "wikilink")
-    [Understanding The File Formats For KeeperRL 9](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_9 "wikilink")
