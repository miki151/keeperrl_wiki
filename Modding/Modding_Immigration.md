---
title: Modding Immigration
permalink: Modding_Immigration/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")

`\{`  
` `“`imps`”  
` \{`  
`  \{`  
`    ids = \{ IMP \}`  
`    traits = \{ WORKER NO_LIMIT NO_EQUIPMENT \}`  
`    spawnLocation = NearLeader`  
`    keybinding = CREATE_IMP`  
`    sound = CREATE_IMP 2`  
`    noAuto = true`  
`    initialRecruitment = 4`  
`    requirements = \{`  
`   \{ 1 ExponentialCost GOLD 30 5 4 \}`  
`    \}`  
`  \}`  
` \}`

` `“`peseant_prisoners`”  
` \{`  
`  \{`  
`    ids = \{ PESEANT_PRISONER \}`  
`    traits = \{ WORKER NO_LIMIT NO_EQUIPMENT \}`  
`    spawnLocation = NearLeader`  
`    noAuto = true`  
`    invisible = true`  
`    initialRecruitment = 4`  
`  \}`  
` \}`

` `“`peseants`”  
` \{`  
`  \{`  
`    ids = \{ PESEANT_PLAYER \}`  
`    traits = \{ WORKER NO_LIMIT NO_EQUIPMENT \}`  
`    keybinding = CREATE_IMP`  
`    noAuto = true`  
`    initialRecruitment = 4`  
`    requirements = \{`  
`   \{ 1 ExponentialCost GOLD 30 5 4 \}`  
`    \}`  
`  \}`  
` \}`

` `“`dark_keeper`”  
` \{`  
`  \{`  
`    ids = \{ GOBLIN \}`  
`    traits = \{ FIGHTER NO_AUTO_EQUIPMENT \}`  
`    frequency = 0.7`  
`    requirements = \{`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType FORGE FurnitureType WORKSHOP FurnitureType JEWELLER\}\}`  
`    \}`  
`    specialTraits = \{`  
`   \{ 0.03 \{ SkillId WORKSHOP LastingEffect INSANITY \}\}`  
`   \{ 0.03 \{ SkillId FORGE LastingEffect INSANITY \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ ORC \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.7`  
`    requirements = \{`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType TRAINING_WOOD\}\}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.05 \{ ExtraTraining ARCHERY 2\}\}`  
`    \{ 0.05 \{ ExtraTraining MELEE 2\}\}`  
`    \{ 0.03 \{ AttrBonus DAMAGE 7 LastingEffect INSANITY\}\}`  
`    \{ 0.05 \{ LastingEffect NIGHT_VISION \}\}`  
`    \{ 0.05 \{ SkillId DISARM_TRAPS \}\}`  
`    \{ 0.05 \{ SkillId SWIMMING \}\}`  
`    \{ 0.05 \{ LastingEffect MAGIC_VULNERABILITY \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_ELVES \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_HUMANS \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ ORC_SHAMAN \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.6`  
`    requirements = \{`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType BOOKCASE_WOOD FurnitureType LABORATORY\}\}`  
`   \{ 0.0 MinTurnRequirement 500 \}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.03 \{ AttrBonus SPELL_DAMAGE 7 LastingEffect INSANITY\}\}`  
`    \{ 0.10 \{ ExtraTraining SPELL 4\}\}`  
`    \{ 0.05 \{ SkillId LABORATORY \}\}`  
`    \{ 0.10 \{ LastingEffect MAGIC_RESISTANCE \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_ELVES \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_HUMANS \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ OGRE \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.3`  
`    requirements = \{`  
`   \{ 0.0 MinTurnRequirement 2000 \}`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType TRAINING_IRON\}\}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.03 \{ AttrBonus DAMAGE 5 LastingEffect INSANITY\}\}`  
`    \{ 0.03 \{ AttrBonus DEFENSE 5 LastingEffect SLOWED\}\}`  
`    \{ 0.05 \{ LastingEffect RANGED_VULNERABILITY \}\}`  
`    \{ 0.05 \{ SkillId DISARM_TRAPS \}\}`  
`    \{ 0.05 \{ SkillId SWIMMING \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_ELVES \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_HUMANS \}\}`  
`    \{ 0.05 \{ ExtraTraining ARCHERY 2\}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ HARPY \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.3`  
`    requirements = \{`  
`   \{ 0.0 MinTurnRequirement 2000 \}`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType TRAINING_IRON\}\}`  
`   \{ 0.3 AttractionInfo 1 \{ItemIndex RANGED_WEAPON\}\}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.03 \{ AttrBonus DAMAGE 5 LastingEffect INSANITY\}\}`  
`    \{ 0.03 \{ AttrBonus DEFENSE 5 LastingEffect SLOWED\}\}`  
`    \{ 0.05 \{ LastingEffect RANGED_VULNERABILITY \}\}`  
`    \{ 0.05 \{ SkillId DISARM_TRAPS \}\}`  
`    \{ 0.05 \{ SkillId SWIMMING \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_ELVES \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_HUMANS \}\}`  
`    \{ 0.05 \{ ExtraTraining ARCHERY 2\}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ ZOMBIE \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.5`  
`    spawnLocation = FurnitureType GRAVE`  
`    requirements = \{`  
`   \{ 0.0 MinTurnRequirement 1000 \}`  
`   \{ 0.0 CostInfo CORPSE 1\}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.3 \{ LastingEffect BLIND \}\}`  
`    \{ 0.3 \{ LastingEffect COLLAPSED \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ SKELETON \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.5`  
`    spawnLocation = FurnitureType GRAVE`  
`    requirements = \{`  
`   \{ 0.0 MinTurnRequirement 1000 \}`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType ARCHERY_RANGE\}\}`  
`   \{ 0.0 CostInfo CORPSE 1\}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.3 \{ LastingEffect SLOWED \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ VAMPIRE \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.2`  
`    spawnLocation = FurnitureType GRAVE`  
`    requirements = \{`  
`   \{ 0.0 MinTurnRequirement 1000 \}`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType TRAINING_IRON\}\}`  
`   \{ 0.0 CostInfo CORPSE 1\}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.3 \{ LastingEffect TELEPATHY \}\}`  
`    \{ 0.3 \{ LastingEffect FIRE_RESISTANT \}\}`  
`    \{ 0.05 \{ LastingEffect HATE_GREENSKINS \}\}`  
`    \{ 0.3 \{ LastingEffect FLYING \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ MUMMY \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.1`  
`    spawnLocation = FurnitureType GRAVE`  
`    requirements = \{`  
`   \{ 0.0 MinTurnRequirement 1000 \}`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType TRAINING_IRON\}\}`  
`   \{ 0.0 CostInfo CORPSE 1\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ LOST_SOUL \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.3`  
`    spawnLocation = FurnitureType DEMON_SHRINE`  
`    requirements = \{`  
`   \{ 0.3 AttractionInfo 1 \{FurnitureType DEMON_SHRINE\}\}`  
`   \{ 0.0 FurnitureType DEMON_SHRINE \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ SUCCUBUS \}`  
`    traits = \{ FIGHTER NO_EQUIPMENT \}`  
`    frequency = 0.3`  
`    spawnLocation = FurnitureType DEMON_SHRINE`  
`    requirements = \{`  
`   \{ 0.3 AttractionInfo 2 \{FurnitureType DEMON_SHRINE\}\}`  
`   \{ 0.0 FurnitureType DEMON_SHRINE \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ DOPPLEGANGER \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.3`  
`    spawnLocation = FurnitureType DEMON_SHRINE`  
`    requirements = \{`  
`   \{ 0.3 AttractionInfo 3 \{FurnitureType DEMON_SHRINE\}\}`  
`   \{ 0.0 FurnitureType DEMON_SHRINE \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ RAVEN \}`  
`    traits = \{ FIGHTER DOESNT_TRIGGER \}`  
`    frequency = 0.5`  
`    requirements = \{`  
`   \{ 0.0 SunlightState DAY \}`  
`   \{ 0.0 FurnitureType BEAST_CAGE \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ BAT \}`  
`    traits = \{ FIGHTER DOESNT_TRIGGER \}`  
`    frequency = 0.5`  
`    requirements = \{`  
`   \{ 0.0 SunlightState NIGHT \}`  
`   \{ 0.0 FurnitureType BEAST_CAGE \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ WOLF \}`  
`    traits = \{ FIGHTER DOESNT_TRIGGER \}`  
`    frequency = 0.15`  
`    groupSize = \{3 9\}`  
`    autoTeam = true`  
`    requirements = \{`  
`   \{ 0.0 SunlightState NIGHT \}`  
`   \{ 0.0 FurnitureType BEAST_CAGE \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ CAVE_BEAR \}`  
`    traits = \{ FIGHTER DOESNT_TRIGGER \}`  
`    frequency = 0.1`  
`    requirements = \{`  
`   \{ 0.0 FurnitureType BEAST_CAGE \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ WEREWOLF \}`  
`    traits = \{ FIGHTER DOESNT_TRIGGER \}`  
`    frequency = 0.1`  
`    requirements = \{`  
`   \{ 0.0 MinTurnRequirement 2000 \}`  
`   \{ 0.0 FurnitureType BEAST_CAGE \}`  
`   \{ 0.3 AttractionInfo 2 \{FurnitureType TRAINING_IRON\}\}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.1 \{ AttrBonus DAMAGE 5 LastingEffect INSANITY\}\}`  
`    \{ 0.03 \{ LastingEffect INSANITY\}\}`  
`    \{ 0.1 \{ LastingEffect HATE_UNDEAD\}\}`  
`    \{ 0.3 \{ SkillId AMBUSH \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ DARK_ELF_WARRIOR \}`  
`    traits = \{ FIGHTER \}`  
`    requirements = \{`  
`   \{ 0.0 RecruitmentInfo \{ORC_VILLAGE\} 3 FIGHTER \}`  
`   \{ 1.0 CostInfo GOLD 20 \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ ORC \}`  
`    traits = \{ FIGHTER \}`  
`    requirements = \{`  
`   \{ 0.0 RecruitmentInfo \{ORC_VILLAGE\} 3 FIGHTER \}`  
`   \{ 1.0 CostInfo GOLD 5 \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ HARPY \}`  
`    traits = \{ FIGHTER \}`  
`    requirements = \{`  
`   \{ 0.0 RecruitmentInfo \{HARPY_CAVE\} 3 FIGHTER \}`  
`   \{ 1.0 CostInfo GOLD 12 \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ OGRE \}`  
`    traits = \{ FIGHTER \}`  
`    requirements = \{`  
`   \{ 0.0 RecruitmentInfo \{OGRE_CAVE ORC_VILLAGE\} 3 FIGHTER \}`  
`   \{ 1.0 CostInfo GOLD 12 \}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ SPECIAL_HMBN SPECIAL_HMBW SPECIAL_HMGN SPECIAL_HMGW \}`  
`    traits = \{ FIGHTER \}`  
`    consumeIds = true`  
`    spawnLocation = Pregnancy`  
`    requirements = \{`  
`   \{ 0.0 TechId `“`humanoid`` ``mutation`”` \}`  
`   \{ 0.0 Pregnancy \}`  
`   \{ 1.0 CostInfo GOLD 100 \}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.1 \{ LastingEffect INSANITY\}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ SPECIAL_BMBN SPECIAL_BMBW SPECIAL_BMGN SPECIAL_BMGW \}`  
`    traits = \{ FIGHTER DOESNT_TRIGGER \}`  
`    consumeIds = true`  
`    spawnLocation = Pregnancy`  
`    requirements = \{`  
`   \{ 0.0 TechId `“`beast`` ``mutation`”` \}`  
`   \{ 0.0 Pregnancy \}`  
`   \{ 1.0 CostInfo GOLD 100 \}`  
`    \}`  
`  \}`  
` \}`

` `“`white_keeper`”  
` \{`  
`  \{`  
`    ids = \{ GNOME_PLAYER \}`  
`    traits = \{ FIGHTER NO_AUTO_EQUIPMENT \}`  
`    frequency = 0.7`  
`    requirements = \{`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType FORGE FurnitureType WORKSHOP FurnitureType JEWELLER\}\}`  
`    \}`  
`    specialTraits = \{`  
`   \{ 0.05 \{ OneOfTraits \{ LastingEffect FAST_CRAFTING LastingEffect SLOW_CRAFTING \} \}\}`  
`   \{ 0.03 \{ SkillId WORKSHOP LastingEffect INSANITY \}\}`  
`   \{ 0.03 \{ SkillId FORGE LastingEffect INSANITY \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ KNIGHT_PLAYER \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.7`  
`    requirements = \{`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType TRAINING_IRON\}\}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.05 \{ ExtraTraining ARCHERY 2\}\}`  
`    \{ 0.05 \{ ExtraTraining MELEE 2\}\}`  
`    \{ 0.05 \{ OneOfTraits \{ LastingEffect FAST_TRAINING LastingEffect SLOW_TRAINING \} \}\}`  
`    \{ 0.05 \{ LastingEffect HATE_ELVES \}\}`  
`    \{ 0.05 \{ LastingEffect HATE_DWARVES \}\}`  
`    \{ 0.05 \{ LastingEffect HATE_GREENSKINS \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ PRIEST_PLAYER \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.3`  
`    requirements = \{`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType BOOKCASE_WOOD\}\}`  
`   \{ 0.0 MinTurnRequirement 500 \}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.03 \{ AttrBonus SPELL_DAMAGE 4 AttrBonus DEFENSE -4\}\}`  
`    \{ 0.05 \{ ExtraTraining SPELL 2\}\}`  
`    \{ 0.02 \{ LastingEffect HATE_UNDEAD \}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ ARCHER_PLAYER \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.3`  
`    requirements = \{`  
`   \{ 0.0 MinTurnRequirement 2000 \}`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType TRAINING_WOOD\}\}`  
`   \{ 0.1 AttractionInfo 1 \{FurnitureType ARCHERY_RANGE\}\}`  
`    \}`  
`    specialTraits = \{`  
`    \{ 0.03 \{ AttrBonus DAMAGE 5 LastingEffect INSANITY\}\}`  
`    \{ 0.03 \{ AttrBonus DEFENSE 5 LastingEffect SLOWED\}\}`  
`    \{ 0.05 \{ LastingEffect RANGED_VULNERABILITY \}\}`  
`    \{ 0.05 \{ SkillId DISARM_TRAPS \}\}`  
`    \{ 0.05 \{ SkillId SWIMMING \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_ELVES \}\}`  
`    \{ 0.02 \{ LastingEffect HATE_HUMANS \}\}`  
`    \{ 0.05 \{ ExtraTraining ARCHERY 2\}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ JESTER_PLAYER \}`  
`    traits = \{ FIGHTER \}`  
`    frequency = 0.1`  
`    requirements = \{`  
`   \{ 0.0 AttractionInfo 1 \{FurnitureType THRONE\}\}`  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ DOG \}`  
`    traits = \{ FIGHTER DOESNT_TRIGGER NO_LIMIT \}`  
`    frequency = 0.1`  
`  \}`  
`  \{`  
`    ids = \{ DONKEY COW HORSE GOAT \}`  
`    traits = \{ NO_LIMIT INCREASE_POPULATION \}`  
`    requirements = \{`  
`   \{ 1.0 CostInfo GOLD 50 \}`  
`    \}`  
`  \}`

` \}`

` `“`tutorial`”

` \{`  
`  \{`  
`    ids = \{ ORC \}`  
`    traits = \{ FIGHTER NO_AUTO_EQUIPMENT \}`  
`    tutorialHighlight = ACCEPT_IMMIGRANT`  
`    hiddenInHelp = true`  
`    consumeIds = true`  
`    requirements = \{`  
`   \{ 1.0 AttractionInfo 1 \{ FurnitureType TRAINING_WOOD \} \} `  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ ORC \}`  
`    frequency = 0.5`  
`    traits = \{ FIGHTER NO_AUTO_EQUIPMENT \}`  
`#          hiddenInHelp = true`  
`    requirements = \{`  
`   \{ 0.0 TutorialRequirement ACCEPT_IMMIGRANT \}`  
`   \{ 1.0 AttractionInfo 1 \{ FurnitureType TRAINING_WOOD \} \} `  
`    \}`  
`  \}`  
`  \{`  
`    ids = \{ GOBLIN \}`  
`    frequency = 0.1`  
`    traits = \{ FIGHTER NO_AUTO_EQUIPMENT \}`  
`#          hiddenInHelp = true`  
`    requirements = \{`  
`   \{ 0.0 TutorialRequirement ACCEPT_MORE_IMMIGRANTS\}`  
`   \{ 1.0 AttractionInfo 1 \{ FurnitureType WORKSHOP \} \} `  
`    \}`  
`  \}`  
` \}`  
`\}`

[MainPage](/keeperrl_wiki/ "wikilink")

Other items in this section
-    [Available reference data for modding KeeperRL](/keeperrl_wiki/Available_Reference_Data_For_Modding_KeeperRL "wikilink")
-    [Build Menu.txt](/keeperrl_wiki/Build_Menu.txt "wikilink")
-    [Build Requirements](/keeperrl_wiki/Build_Requirements "wikilink")
-    [Category Modding Reference Data](/keeperrl_wiki/Category_Modding_Reference_Data "wikilink")
-    [Download Mods](/keeperrl_wiki/Download_Mods "wikilink")
-    [Fixed Spawn Locations](/keeperrl_wiki/Fixed_Spawn_Locations "wikilink")
-    [Gaining familiarity with mods on KeeperRL](/keeperrl_wiki/Gaining_Familiarity_With_Mods_On_KeeperRL "wikilink")
-    [Immigration Options](/keeperrl_wiki/Immigration_Options "wikilink")
-    [Modding](/keeperrl_wiki/Modding "wikilink")
-    [Modding Creatures](/keeperrl_wiki/Modding_Creatures "wikilink")
-    [Modding Effects](/keeperrl_wiki/Modding_Effects "wikilink")
-    [Modding Effect Types](/keeperrl_wiki/Modding_Effect_Types "wikilink")
-    [Modding Enemies](/keeperrl_wiki/Modding_Enemies "wikilink")
-    [Modding guide](/keeperrl_wiki/Modding_Guide "wikilink")
-    [Modding Technology](/keeperrl_wiki/Modding_Technology "wikilink")
-    [Modding Traits](/keeperrl_wiki/Modding_Traits "wikilink")
-    [Modding Views](/keeperrl_wiki/Modding_Views "wikilink")
-    [Modding Zones](/keeperrl_wiki/Modding_Zones "wikilink")
-    [Player Creatures.txt](/keeperrl_wiki/Player_Creatures.txt "wikilink")
-    [Understanding the file formats for KeeperRL](/keeperrl_wiki/Understanding_The_File_Formats_For_KeeperRL "wikilink")
