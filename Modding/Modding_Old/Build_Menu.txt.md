---
title: Build Menu.txt
permalink: Build_Menu.txt/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")

`# `“`structure`”`, `“`doors`”`, etc are groups that are then used in the last column in player_creatures.txt.`  
`# (they do not necessarily correspond to how menu items are grouped into submenus, you can join several`  
`# groups into a submenu, like beds, cages, pigsty and coffins are in the `“`living`”` submenu)`

`\{`  
`  `“`structure`”  
`  \{`  
` \{ Dig                                                      `“`Dig`` ``or`` ``cut`` ``tree`”`   `“`Structure`”`  `  
`   "" d \{\} true DIG_OR_CUT_TREES\}`  
` \{ Furniture \{\{ MOUNTAIN \}                   STONE 5 \}      `“`Soft`` ``rock`”`         `“`Structure`”` \}`  
` \{ Furniture \{\{ MOUNTAIN2 \}                  STONE 10 \}     `“`Hard`` ``rock`”`         `“`Structure`”` \}`  
  
` \{ Furniture \{\{ DUNGEON_WALL DUNGEON_WALL2 \} STONE 3\}       `“`Reinforce`` ``wall`”`    `“`Structure`”  
`   `“`Reinforced`` ``walls`` ``are`` ``better`` ``at`` ``stopping`` ``enemies`` ``from`` ``digging`` ``into`` ``your`` ``dungeon.`”`\}`  
  
` \{ Furniture \{\{ PIT \}                        STONE 0 \}      `“`Dig`` ``a`` ``pit`”`         `“`Structure`”  
`   `“`Dig`` ``a`` ``pit`` ``in`` ``the`` ``ground.`` ``Building`` ``next`` ``to`` ``water`` ``or`` ``lava`` ``will`` ``cause`` ``it`` ``to`` ``fill`` ``up.`”` \}`  
  
` \{ Furniture \{\{ WOOD_WALL \}                  WOOD 5 \}       `“`Wooden`` ``building`”`   `“`Structure`”  
`   `“`Outdoor`` ``building.`` ``Tiles`` ``covered`` ``by`` ``the`` ``roof`` ``are`` ``considered`` ``territory`` ``and`` ``can`` ``be`` ``built`` ``on.`”` \}`  
  
` \{ Furniture \{\{ CASTLE_WALL \}                STONE 5 \}      `“`Stone`` ``building`”`    `“`Structure`”  
`   `“`Outdoor`` ``building.`` ``Tiles`` ``covered`` ``by`` ``the`` ``roof`` ``are`` ``considered`` ``territory`` ``and`` ``can`` ``be`` ``built`` ``on.`”` \}`  
  
` \{ Furniture \{\{ BRIDGE \}                     WOOD 5 \}       `“`Bridge`”`            `“`Structure`”  
`   `“`Build`` ``to`` ``pass`` ``over`` ``water`` ``of`` ``lava.`”` \}`  
`  \}`

`  `“`doors`”  
`  \{`  
` \{ Furniture \{\{ WOOD_DOOR \}                  WOOD 5 \}       `“`Wooden`` ``door`”`       `“`Doors`”  
`   `“`Stops`` ``enemies.`` ``Your`` ``minions`` ``can`` ``pass`` ``freely`` ``unless`` ``you`` ``lock`` ``it.`”`  o \{\} true BUILD_DOOR\}`  
  
` \{ Furniture \{\{ IRON_DOOR \}                  IRON 5 \}       `“`Iron`` ``door`”`         `“`Doors`”  
`   `“`Stops`` ``enemies.`` ``Your`` ``minions`` ``can`` ``pass`` ``freely`` ``unless`` ``you`` ``lock`` ``it.`”` \}`  
  
` \{ Furniture \{\{ ADA_DOOR \}                   ADA 5 \}        `“`Adamantine`` ``door`”`   `“`Doors`”  
`   `“`Stops`` ``enemies.`` ``Your`` ``minions`` ``can`` ``pass`` ``freely`` ``unless`` ``you`` ``lock`` ``it.`”`\}`  
`  \}`

`  `“`floors`”  
`  \{`  
` \{ Furniture \{\{ FLOOR_WOOD1 \}                WOOD 2 \}       `“`Wooden`”`            `“`Floors`”  
`  "" f \{\} true BUILD_FLOOR\}`  
` \{ Furniture \{\{ FLOOR_WOOD2 \}                WOOD 2 \}       `“`Wooden`”`            `“`Floors`”  
`  "" 0 \{\} true BUILD_FLOOR\}`  
` \{ Furniture \{\{ FLOOR_STONE1 \}               STONE 2 \}      `“`Stone`”`             `“`Floors`”` \}`  
` \{ Furniture \{\{ FLOOR_STONE2 \}               STONE 2 \}      `“`Stone`”`             `“`Floors`”` \}`  
` \{ Furniture \{\{ FLOOR_CARPET1 \}              GOLD 2 \}       `“`Carpet`”`            `“`Floors`”` \}`  
` \{ Furniture \{\{ FLOOR_CARPET2 \}              GOLD 2 \}       `“`Carpet`”`            `“`Floors`”` \}`  
` \{ DestroyLayers \{FLOOR\}                                    `“`Remove`` ``floor`”`      `“`Floors`”` \}`  
`  \}`

`  `“`storage`”  
`  \{`  
` \{ Zone STORAGE_RESOURCES                                   `“`Resources`”`         `“`Storage`”` `  
`  `“`Only`` ``wood,`` ``iron,`` ``granite,`` ``and`` ``adamantium`` ``can`` ``be`` ``stored`` ``here.`”` s \{\} true RESOURCE_STORAGE\}`  
  
` \{ Zone STORAGE_EQUIPMENT                                   `“`Equipment`”`         `“`Storage`”  
`  `“`All`` ``equipment`` ``for`` ``your`` ``minions`` ``can`` ``be`` ``stored`` ``here.`”` 0 \{\} false EQUIPMENT_STORAGE \}`  
  
` \{ Furniture \{\{ TREASURE_CHEST \}             WOOD 5  \}      `“`Treasure`` ``chest`”`    `“`Storage`”  
`  `“`All`` ``your`` ``gold`` ``is`` ``stored`` ``here.`”` \}`  
  
` \{ Furniture \{\{ GRAVE \}                      STONE 5 \}      `“`Grave`”`             `“`Storage`”  
`  `“`All`` ``corpses`` ``are`` ``stored`` ``here.`”`\}`  
`  \}`

`  `“`quarters`”  
`  \{`  
` \{ Zone QUARTERS1                                           `“`Quarters`` ``1`”`        `“`Quarters`”  
`  `“`Designate`` ``separate`` ``quarters`` ``for`` ``chosen`` ``minions.`”` q \{\} true\}`  
  
` \{ Zone QUARTERS2                                           `“`Quarters`` ``2`”`        `“`Quarters`”  
`  `“`Designate`` ``separate`` ``quarters`` ``for`` ``chosen`` ``minions.`”`\}`  
  
` \{ Zone QUARTERS3                                           `“`Quarters`` ``3`”`        `“`Quarters`”  
`  `“`Designate`` ``separate`` ``quarters`` ``for`` ``chosen`` ``minions.`”`\}`  
`  \}`

`  `“`library`”  
`  \{`  
` \{ Furniture \{\{ BOOKCASE_WOOD \}   WOOD 15 \}                 `“`Wooden`` ``bookcase`”`   `“`Library`”`  `  
`  `“`Train`` ``your`` ``minions'`` ``magical`` ``powers`` ``here.`”` y          \{TechId `“`sorcery`”`\} true BUILD_LIBRARY \}`  
` `  
` \{ Furniture \{\{ BOOKCASE_IRON \}   IRON 15 \}                 `“`Iron`` ``bookcase`”`     `“`Library`”  
`  `“`Train`` ``your`` ``minions'`` ``magical`` ``powers`` ``here.`”` 0          \{TechId `“`advanced`` ``sorcery`”`\} \}`  
` `  
` \{ Furniture \{\{ BOOKCASE_GOLD \}   GOLD 15 \}                 `“`Golden`` ``bookcase`”`   `“`Library`”  
`  `“`Train`` ``your`` ``minions'`` ``magical`` ``powers`` ``here.`”`0           \{TechId `“`master`` ``sorcery`”`\}\}`  
`  \}`

`  `“`throne`”  
`  \{`  
` \{ Furniture \{ types = \{ THRONE \} cost = GOLD 500 limit = 1\} `“`Throne`”` "" ""  0   \{DungeonLevel 10\} \}`  
`  \}`

`  `“`beds`”  
`  \{`  
` \{ Furniture \{\{ BED1 \}       WOOD 12 \}                      `“`Basic`` ``bed`”`         `“`Living`”  
`  `“`Humanoid`` ``minions`` ``sleep`` ``here.`”` v \{\} true  BUILD_BED \}`  
` `  
` \{ Furniture \{\{ BED2 \}       IRON 12 \}                      `“`Fine`` ``bed`”`          `“`Living`”  
`  `“`Humanoid`` ``minions`` ``sleep`` ``here.`”` \}`  
  
` \{ Furniture \{\{ BED3 \}       GOLD 12 \}                      `“`Luxurious`` ``bed`”`     `“`Living`”  
`  `“`Humanoid`` ``minions`` ``sleep`` ``here.`”`\}`  
`  \}`

`  `“`beast_cage`”  
`  \{`  
` \{ Furniture \{\{ BEAST_CAGE \} WOOD 8 \}                       `“`Beast`` ``cage`”`        `“`Living`”  
`  `“`Beasts`` ``sleep`` ``here.`”`\}`  
`  \}`  
` `  
`  `“`pigsty`”  
`  \{`  
` \{ Furniture \{\{ PIGSTY \}     WOOD 5 \}                       `“`Pigsty`”`            `“`Living`”`\}`  
`  \}`

`  `“`coffins`”  
`  \{`  
` \{ Furniture \{\{ COFFIN1 \}    WOOD 15 \}                      `“`Basic`` ``coffin`”`      `“`Living`”  
`  `“`Undead`` ``creatures`` ``sleep`` ``here.`”`\}`  
  
` \{ Furniture \{\{ COFFIN2 \}    STONE 15 \}                     `“`Fine`` ``coffin`”`       `“`Living`”  
`  `“`Undead`` ``creatures`` ``sleep`` ``here.`”`\}`  
  
` \{ Furniture \{\{ COFFIN3 \}    GOLD 15 \}                      `“`Luxurious`` ``coffin`”`  `“`Living`”  
`  `“`Undead`` ``creatures`` ``sleep`` ``here.`”`\}`  
`  \}`

`  `“`training`”  
`  \{`  
` \{ Furniture \{\{ TRAINING_WOOD \} WOOD 12 \}                   `“`Wooden`` ``dummy`”`      `“`Training`` ``room`”  
`  `“`Train`` ``your`` ``minions'`` ``melee`` ``skills`` ``here.`”` r \{\} true  TRAINING_ROOM\}`  
  
` \{ Furniture \{\{ TRAINING_IRON \} IRON 12 \}                   `“`Iron`` ``dummy`”`        `“`Training`` ``room`”  
`  `“`Train`` ``your`` ``minions'`` ``melee`` ``skills`` ``here.`”`   0 \{ TechId `“`iron`` ``working`”` \} \}`  
  
` \{ Furniture \{\{ TRAINING_ADA \}  ADA  12 \}                   `“`Adamantine`` ``dummy`”`  `“`Training`` ``room`”  
`  `“`Train`` ``your`` ``minions'`` ``melee`` ``skills`` ``here.`”`   0 \{ TechId `“`iron`` ``working`”` \}\}`  
  
` \{ Furniture \{\{ ARCHERY_RANGE \} WOOD 12 \}                   `“`Archery`` ``target`”`    `“`Training`` ``room`”  
`  `“`Train`` ``your`` ``minions'`` ``archery`` ``skills`` ``here.`”` 0 \{ TechId `“`archery`”` \}\}`  
`  \}`

`  `“`crafting`”  
`  \{`  
` \{ Furniture \{\{ WORKSHOP \}   WOOD 15 \}                      `“`Workshop`”`          `“`Crafting`”  
`  `“`Produces`` ``leather`` ``equipment,`` ``traps,`` ``first-aid`` ``kits`` ``and`` ``other.`”` m \{\} true  BUILD_WORKSHOP\}`  
  
` \{ Furniture \{\{ FORGE \}      IRON 20 \}                      `“`Forge`”`             `“`Crafting`”  
`  `“`Produces`` ``metal`` ``weapons`` ``and`` ``armor.`”`    0 \{ TechId `“`iron`` ``working`”` \}\}`  
  
` \{ Furniture \{\{ LABORATORY \} STONE 10 \}                     `“`Laboratory`”`        `“`Crafting`”  
`  `“`Produces`` ``magical`` ``potions.`”`            0 \{ TechId `“`alchemy`”` \}\}`  
  
` \{ Furniture \{\{ JEWELLER \}   WOOD 12 \}                      `“`Jeweller`”`          `“`Crafting`”  
`  `“`Produces`` ``magical`` ``rings`` ``and`` ``amulets.`”`  0 \{ TechId `“`jewellery`”` \}\}`  
`  \}`

`  `“`demon_shrine`”  
`  \{`  
` \{ Furniture \{\{ DEMON_SHRINE \} GOLD 30 \}                    `“`Demon`` ``shrine`”`      ""`  
`  `“`Undead`` ``creatures`` ``sleep`` ``here.`”` 0 \{ TechId `“`demonology`”` \}\}`  
`  \}`

`  `“`prison`”  
`  \{`  
` \{ Furniture \{\{ PRISON \}        IRON 15 \}                   `“`Prison`”`            `“`Prison`”  
`  `“`Required`` ``to`` ``capture`` ``enemies.`”` p \{\} true\}`  
  
` \{ Furniture \{\{ TORTURE_TABLE \} IRON 15 \}                   `“`Torture`` ``table`”`     `“`Prison`”  
`  `“`Can`` ``be`` ``used`` ``to`` ``torture`` ``prisoners.`` ``Free`` ``population`` ``slot`` ``required`` ``for`` ``torturing.`”`\}`  
`  \}`

`  `“`orders`”  
`  \{`  
` \{ ClaimTile                                                `“`Claim`` ``tile`”`        `“`Orders`”  
`  `“`Claim`` ``a`` ``dungeon`` ``tile`` ``as`` ``your`` ``own.`` ``Building`` ``anything`` ``on`` ``it`` ``has`` ``the`` ``same`` ``effect.`”` \}`  
  
` \{ Zone FETCH_ITEMS                                         `“`Fetch`` ``items`”`       `“`Orders`”  
`  `“`Order`` ``imps`` ``to`` ``fetch`` ``items`` ``from`` ``locations`` ``outside`` ``the`` ``dungeon.`` ``This`` ``is`` ``a`` ``one-time`` ``order.`”`\}`  
  
` \{ Zone PERMANENT_FETCH_ITEMS                               `“`Fetch`` ``items`` ``persistently`”` `“`Orders`”  
`  `“`Order`` ``imps`` ``to`` ``fetch`` ``items`` ``from`` ``locations`` ``outside`` ``the`` ``dungeon.`` ``This`` ``is`` ``a`` ``persistent`` ``order.`”`\}`  
  
` \{ Dispatch                                                 `“`Prioritize`` ``task`”`   `“`Orders`”  
`  `“`Click`` ``on`` ``an`` ``existing`` ``task`` ``to`` ``give`` ``it`` ``a`` ``high`` ``priority.`”` a \}`  
  
` \{ DestroyLayers \{CEILING MIDDLE\}                           `“`Remove`` ``construction`”` `“`Orders`”  
`  "" e \{\} false REMOVE_CONSTRUCTION \}`  
` `  
` \{ ForbidZone                                               `“`Forbind`` ``zone`”`      `“`Orders`”  
`  `“`Mark`` ``tiles`` ``to`` ``keep`` ``minions`` ``from`` ``entering.`”`\}`  
`  \}`

`  `“`installations`”  
`  \{`  
` \{ Furniture \{\{ BARRICADE \}     WOOD 5 \}                    `“`Barricade`”`         `“`Installations`”  
`  `“`Blocks`` ``enemy`` ``movement,`` ``but`` ``projectiles`` ``and`` ``spells`` ``can`` ``pass`` ``over`` ``it.`”` \}`  
  
` \{ Furniture \{\{ TORCH_N TORCH_E TORCH_S TORCH_W \}\}          `“`Torch`”`             `“`Installations`”  
`  `“`Place`` ``it`` ``on`` ``tiles`` ``next`` ``to`` ``a`` ``wall.`”` c \{\} false BUILD_TORCH\}`  
  
` \{ Furniture \{\{ CANDELABRUM_N CANDELABRUM_E CANDELABRUM_S CANDELABRUM_W \} GOLD 5 \}`  
`  `“`Candelabrum`”`             `“`Installations`”`       `“`Place`` ``it`` ``on`` ``tiles`` ``next`` ``to`` ``a`` ``wall.`”` \}`  
  
` \{ Furniture \{\{ GROUND_TORCH \}  WOOD 10  \}                  `“`Standing`` ``torch`”`    `“`Installations`”  
`  "" 0 \{\} false BUILD_TORCH \}`  
  
` \{ Furniture \{\{ KEEPER_BOARD \}  WOOD 15 \}                   `“`Message`` ``board`”`     `“`Installations`”  
`  `“`A`` ``board`` ``where`` ``you`` ``can`` ``leave`` ``a`` ``message`` ``for`` ``other`` ``players.`”` \}`  
  
` \{ Furniture \{\{ FOUNTAIN \}      STONE 30 \}                  `“`Fountain`”`          `“`Installations`”` \}`  
  
` \{ Furniture \{\{ WHIPPING_POST \} WOOD  20 \}                  `“`Whipping`` ``post`”`     `“`Installations`”  
`  `“`A`` ``place`` ``to`` ``whip`` ``your`` ``minions`` ``if`` ``they`` ``need`` ``a`` ``morale`` ``boost.`”` \}`  
  
` \{ Furniture \{\{ GALLOWS \}       WOOD  20 \}                  `“`Gallows`”`           `“`Installations`”  
`  `“`For`` ``hanging`` ``prisoners.`”`\}`  
  
` \{ Furniture \{\{ IMPALED_HEAD \}  PRISONER_HEAD 1 true\}       `“`Prisoner`` ``head`”`     `“`Installations`”  
`  `“`Impaled`` ``head`` ``of`` ``an`` ``executed`` ``prisoner.`` ``Aggravates`` ``enemies.`”`\}`  
`  \}`

`  `“`magical_installations`”  
`  \{`  
` \{ Furniture \{\{ EYEBALL \}              WOOD   30 \}                   `“`Eyeball`”`           `“`Installations`”  
`  `“`Makes`` ``the`` ``area`` ``around`` ``it`` ``visible.`”`\}`  
  
` \{ Furniture \{\{ MINION_STATUE \}        GOLD   50  \}                  `“`Golden`` ``statue`”`     `“`Installations`”` ""\}`  
` \{ Furniture \{\{ STONE_MINION_STATUE \}  STONE  250 \}                  `“`Stone`` ``statue`”`      `“`Installations`”` ""\}`  
` \{ Furniture \{\{ PORTAL \}               STONE  60 \}                   `“`Portal`”`            `“`Installations`”  
`  `“`Opens`` ``a`` ``connection`` ``if`` ``another`` ``portal`` ``is`` ``present.`”`\}`  
`  \}`

`  `“`tutorial`”  
`  \{`  
` \{ Furniture \{\{ TUTORIAL_ENTRANCE \} \}                  `“`Tutorial`` ``Entrance`”`           `“`Installations`”`\}`  
`  \}`

`  `“`traps`”  
`  \{`  
` \{ Trap TERROR TERROR_TRAP                                  `“`Terror`` ``trap`”`       `“`Traps`”  
`  `“`Causes`` ``the`` ``trespasser`` ``to`` ``panic.`”` 0                   \{ TechId `“`traps`”` \}\}`  
  
` \{ Trap POISON_GAS GAS_TRAP                                 `“`Gas`` ``trap`”`          `“`Traps`”  
`  `“`Releases`` ``a`` ``cloud`` ``of`` ``poisonous`` ``gas.`”` 0                \{ TechId `“`traps`”` \}\}`  
  
` \{ Trap ALARM ALARM_TRAP                                    `“`Alarm`` ``trap`”`        `“`Traps`”  
`  `“`Summons`` ``all`` ``minions`”` 0                               \{ TechId `“`traps`”` \}\}`  
  
` \{ Trap WEB WEB_TRAP                                        `“`Web`` ``trap`”`          `“`Traps`”  
`  `“`Immobilises`` ``the`` ``trespasser`` ``for`` ``some`` ``time.`”` 0         \{ TechId `“`traps`”` \}\}`  
  
` \{ Trap BOULDER BOULDER                                     `“`Boulder`` ``trap`”`      `“`Traps`”  
`  `“`Causes`` ``a`` ``huge`` ``boulder`` ``to`` ``roll`` ``towards`` ``the`` ``enemy.`”` 0  \{ TechId `“`traps`”` \}\}`  
  
` \{ Trap SURPRISE SURPRISE_TRAP                              `“`Surprise`` ``trap`”`     `“`Traps`”  
`  `“`Teleports`` ``nearby`` ``minions`` ``to`` ``deal`` ``with`` ``the`` ``trespasser.`”` 0 \{ TechId `“`traps`”` \}\}`  
`  \}`  
`\}`

[MainPage](/keeperrl_wiki/ "wikilink")

