---
title: Understanding The File Formats For KeeperRL 20
permalink: Understanding_The_File_Formats_For_KeeperRL_20/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Understanding_The_File_Formats_For_KeeperRL](/keeperrl_wiki/Old_Understanding_The_File_Formats_For_KeeperRL "wikilink")

=general rules=
*The text files are editable in a text editor
*Each text file is a set of tables containing a list of available game content
*Multiple spaces and new lines between entries in the table are read as a single space

=technology.txt=

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
The file always begins like this:
 }
 }

=workshops_menu.txt=
*The format is constructed of sections, sub-sections and entries
*There can be as many sections as you want and later on, each section can be used in player_characters.txt to give those characters the build menu sections they need.
*There are 4 sub-sections below each section. These subsections are respectively for:
##Workshop
##Forge
##Lab
##Jeweller
*Each subsection has as many entries as you want.
*Each entry enables an item to be built in that workshop, forge, jewellers or lab.
*The entry has two possible formats
1) {{[[ItemTypes|ItemType]]} '''Speed''' [[ResourceIDs|ResourceID]] '''Amount'''}

Example:
 {{LeatherGloves} 1 WOOD 2}

2) {{[[ItemTypes|ItemType]]} '''Speed''' [[ResourceIDs|ResourceID]] '''Amount''' &quot;'''TechID'''&quot;}

Example:
 {{HeavyClub} 5 WOOD 20 &quot;two-handed weapons&quot;}

=build_menu.txt=

=campaign_villains.txt=

=immigration,txt=

=player_creatures.txt=

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
-    [Understanding The File Formats For KeeperRL 72](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL_72 "wikilink")
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
