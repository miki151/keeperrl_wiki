---
title: Alpha28Spells 4
permalink: Alpha28Spells_4/
layout: wiki
---

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Alpha28Spells](/keeperrl_wiki/Old_Alpha28Spells "wikilink")

This is a spells.txt for Alpha28. Feel free to add your own spells. The symbols are Unicode.

 {
  &quot;heal self&quot;
  {
    symbol = &quot;❤️&quot;
    effect = Effect Heal
    cooldown = 30
    sound = SPELL_HEALING
  }
  &quot;summon flies&quot;
  {
    symbol = &quot;🐝🐝&quot;
    effect = Effect Summon &quot;FLY&quot; {3 7}
    cooldown = 40
    sound = SPELL_SUMMON_INSECTS
  }
  &quot;heal other&quot;
  {
    symbol = &quot;✚&quot;
    effect = DirEffectType { range = 1 effect = Effect Heal}
    cooldown = 15
    sound = SPELL_HEALING
  }
  &quot;magic missile&quot;
  {
    symbol = &quot;⥇&quot;
    effect = DirEffectType { range = 4 effect = Effect Damage SPELL_DAMAGE SPELL}
    cooldown = 20
    sound = SPELL_BLAST
  }
  &quot;deception&quot;
  {
    symbol = &quot;🎭&quot;
    effect = Effect Deception
    cooldown = 60
    sound = SPELL_DECEPTION
  }
  &quot;escape&quot;
  {
    symbol = &quot;↑↑&quot;
    effect = Effect Teleport
    cooldown = 80
    sound = SPELL_TELEPORT
  }
  &quot;haste self&quot;
  {
    symbol = &quot;🏃&quot;
    effect = Effect Lasting SPEED
    cooldown = 60
    sound = SPELL_SPEED_SELF
  }
  &quot;cure poison&quot;
  {
    symbol = &quot;⚕&quot;
    effect = Effect CurePoison
    cooldown = 50
    sound = SPELL_CURE_POISON
  }
  &quot;directed blast&quot;
  {
    symbol = &quot;💨&quot;
    effect = DirEffectType { range = 4 effect = BlastDirEffect}
    cooldown = 30
    sound = SPELL_BLAST
  }
  &quot;circular blast&quot;
  {
    symbol = &quot;💥&quot;
    effect = Effect CircularBlast
    cooldown = 50
    sound = SPELL_AIR_BLAST
    castMessageType = AIR_BLAST
  }
  &quot;fireball&quot;
  {
    symbol = &quot;⮜🔥&quot;
    effect = DirEffectType { range = 4 effect = Effect Fire fx = FIREBALL}
    cooldown = 30
    sound = SPELL_BLAST
  }
  &quot;defense bonus&quot;
  {
    symbol = &quot;🛡&quot;
    effect = Effect Lasting DEF_BONUS
    cooldown = 50
    sound = SPELL_DEX_BONUS
  }
  &quot;summon element&quot;
  {
    symbol = &quot;👾&quot;
    effect = Effect SummonElement
    cooldown = 100
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;damage bonus&quot;
  {
    symbol = &quot;⚔&quot;
    effect = Effect Lasting DAM_BONUS
    cooldown = 50
    sound = SPELL_STR_BONUS
  }
  &quot;meteor shower&quot;
  {
    symbol = &quot;/☄&quot;
    effect = Effect PlaceFurniture METEOR_SHOWER
    cooldown = 150
    sound = SPELL_METEOR_SHOWER
  }
  &quot;invisibility&quot;
  {
    symbol = &quot;🕵️&quot;
    effect = Effect Lasting INVISIBLE
    cooldown = 150
    sound = SPELL_INVISIBILITY
  }
  &quot;fire breath&quot;
  {
    symbol = &quot;🔥&quot;
    effect = DirEffectType { range = 4 effect = Effect Fire fx = FLAMETHROWER}
    cooldown = 30
    sound = SPELL_BLAST
    castMessageType = BREATHE_FIRE
  }
  &quot;summon spirit&quot;
  {
    symbol = &quot;👻&quot;
    effect = Effect Summon &quot;SPIRIT&quot; { 3 5}
    cooldown = 100
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;fire wall&quot;
  {
    symbol = &quot;🔥🔥&quot;
    effect = DirEffectType { range = 2 effect = Effect CustomArea PlaceFurniture FIRE_WALL { 0 -2 0 -1 0 0 0 1 0 2 } endOnly = true }
    cooldown = 30
    sound = SPELL_BLAST
    castMessageType = BREATHE_FIRE
  }
  &quot;stone golem&quot;
  {
    symbol = &quot;👤&quot;
    effect = Effect Summon &quot;STONE_GOLEM&quot; { 1 2}
    cooldown = 100
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;snakes&quot;
  {
    symbol = &quot;🐍&quot;
    effect = Effect Summon &quot;SNAKE&quot; { 7 8 }
    cooldown = 100
    sound = SPELL_SUMMON_SPIRIT 
  }
  &quot;spiders&quot;
  {
    symbol = &quot;🕷&quot;
    effect = Effect Summon &quot;SPIDER&quot; { 2 3 }
    cooldown = 100
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;fumes&quot;
  {
    symbol = &quot;☠&quot;
    effect = DirEffectType { range = 4 effect = Effect EmitPoisonGas 4 }
    cooldown = 50
    sound = SPELL_AIR_BLAST
  }
  &quot;curse&quot;
  {
    symbol = &quot;☛&quot;
    effect = DirEffectType { range = 10 effect = Effect Lasting BLEEDING }
    cooldown = 150
    sound = SPELL_BLAST
  }  
  &quot;stone to mud&quot;
  {
    #cheese wood in other map section?
    symbol = &quot;🕳&quot;
    effect = Effect DestroyWalls
    cooldown = 1000
    sound = SPELL_AIR_BLAST
  } 
  &quot;entangling vines&quot;
  {
    symbol = &quot;🙙&quot;
    effect = DirEffectType { range = 10 effect = Effect Lasting TIED_UP }
    cooldown = 70
    sound = SPELL_STR_BONUS
  }
  &quot;resist magic&quot;
  {
    symbol = &quot;O&quot;
    effect = Effect Lasting MAGIC_RESISTANCE
    cooldown = 80
    sound = SPELL_DEX_BONUS
  }
  &quot;light&quot;
  {
    symbol = &quot;🕯&quot;
    effect = Effect Lasting LIGHT_SOURCE
    cooldown = 80
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;darkness&quot;
  {
    symbol = &quot;☁&quot;
    effect = Effect Lasting DARKNESS_SOURCE
    cooldown = 14
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;teleport other&quot; 
  {
    symbol = &quot;⬸&quot;
    effect = DirEffectType { range = 1 effect = Effect Teleport }
    cooldown = 200
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;wolves&quot;
  {
    symbol = &quot;🐺&quot;
    effect = Effect Summon &quot;WOLF&quot; { 3 4 }
    cooldown = 150
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;bear&quot;
  {
    symbol = &quot;🐻&quot;
    effect = Effect Summon &quot;CAVE_BEAR&quot; { 1 2 }
    cooldown = 80
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;boar&quot;
  {
    symbol = &quot;🐖&quot;
    effect = Effect Summon &quot;BOAR&quot; { 1 2 }
    cooldown = 50
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;raven&quot;
  {
    symbol = &quot;🐦&quot;
    effect = Effect Summon &quot;RAVEN&quot; { 1 2 }
    cooldown = 20
    sound = SPELL_SUMMON_SPIRIT
  }
  &quot;levitate&quot;
  {
    symbol = &quot;^&quot;
    effect = Effect Lasting FLYING
    cooldown = 175
    sound = SPELL_SPEED_SELF
  }
  &quot;fire shield&quot;
  {
    symbol = &quot;🌣&quot;
    effect = Effect Lasting FIRE_RESISTANT
    cooldown = 150
    sound = SPELL_INVISIBILITY
  }
  &quot;telepathy&quot;
  {
    symbol = &quot;💭&quot;
    effect = Effect Lasting TELEPATHY
    cooldown = 175
    sound = SPELL_INVISIBILITY
  }
  &quot;elf vision&quot;
  {
    symbol = &quot;👁&quot;
    effect = Effect Lasting ELF_VISION
    cooldown = 90
    sound = SPELL_SPEED_SELF
  }
  &quot;weapon dodge&quot;
  {
    symbol = &quot;⇠⇢&quot;
    effect = Effect Lasting MELEE_RESISTANCE
    cooldown = 90
    sound = SPELL_DEX_BONUS
  }
  &quot;arrow shield&quot;
  {
    symbol = &quot;→◌&quot;
    effect = Effect Lasting RANGED_RESISTANCE
    cooldown = 50
    sound = SPELL_DEX_BONUS
  }
  &quot;sleep&quot;
  {
    symbol = &quot;Z💤&quot;
    effect = DirEffectType { range = 1 effect = Effect Lasting SLEEP }
    cooldown = 30
    sound = SPELL_HEALING
  }
  &quot;slow other&quot;
  {
    symbol = &quot;⏲&quot;
    effect = DirEffectType { range = 1 effect = Effect Lasting SLOWED }
    cooldown = 120
    sound = SPELL_DECEPTION
  }
  &quot;cause blindness&quot;
  {
    symbol = &quot;👀&quot;
    effect = DirEffectType { range = 5 effect = Effect Lasting BLIND }
    cooldown = 100
    sound = SPELL_DECEPTION
  }
  &quot;cripple&quot;
  {
    symbol = &quot;X&quot;
    effect = DirEffectType { range = 5 effect = Effect Lasting COLLAPSED }
    cooldown = 120
    sound = SPELL_BLAST
  }
  &quot;mind bolt&quot;
  {
    symbol = &quot;⇝&quot;
    effect = DirEffectType { range = 5 effect = Effect Lasting INSANITY }
    cooldown = 180
    sound = SPELL_BLAST
  }
  &quot;charm&quot;
  {
    symbol = &quot;😍&quot;
    effect = DirEffectType { range = 5 effect = Effect Lasting PEACEFULNESS }
    cooldown = 95
    sound = SPELL_HEALING
  }
  &quot;arrow attraction&quot;
  {
    symbol = &quot;↶&quot;
    effect = DirEffectType { range = 5 effect = Effect Lasting RANGED_VULNERABILITY }
    cooldown = 60
    sound = SPELL_BLAST
  }
  &quot;mana curse&quot;
  {
    symbol = &quot;☞&quot;
    effect = DirEffectType { range = 5 effect = Effect Lasting MAGIC_VULNERABILITY }
    cooldown = 60
    sound = SPELL_BLAST
  }
  &quot;regrow body parts&quot;
  {
    symbol = &quot;⨢&quot;
    effect = Effect RegrowBodyPart
    cooldown = 3000
    sound = SPELL_BLAST
  }
 }

[MainPage](/keeperrl_wiki/ "wikilink")>>[Old_Wiki](/keeperrl_wiki/Old_Wiki "wikilink")>>[Old_Alpha28Spells](/keeperrl_wiki/Old_Alpha28Spells "wikilink")

Other items in this section
-    [Alpha28Spells 0](/keeperrl_wiki/Alpha28Spells_0 "wikilink")
-    [Alpha28Spells 1](/keeperrl_wiki/Alpha28Spells_1 "wikilink")
-    [Alpha28Spells 2](/keeperrl_wiki/Alpha28Spells_2 "wikilink")
-    [Alpha28Spells 3](/keeperrl_wiki/Alpha28Spells_3 "wikilink")
-    [Alpha28Spells 5](/keeperrl_wiki/Alpha28Spells_5 "wikilink")
-    [Alpha28Spells 6](/keeperrl_wiki/Alpha28Spells_6 "wikilink")
-    [Alpha28Spells 7](/keeperrl_wiki/Alpha28Spells_7 "wikilink")
