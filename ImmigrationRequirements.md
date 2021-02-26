---
title: ImmigrationRequirements
permalink: ImmigrationRequirements/
layout: wiki
tags:
 -  Modding Reference Data
---

Usage
=====

Used to determine what is required before an immigrant will be willing
to settle in your dungeon

Example from immigration.txt
============================

`requirements = \{`  
`  \{ 0.1 `**`AttractionInfo`**` 1 \{`**`FurnitureType`**` BOOKCASE_WOOD `**`FurnitureType`**` LABORATORY\}\}`  
`  \{ 0.0 `**`MinTurnRequirement`**` 500 \}`  
`\}`

Valid values
============

-   AttractionInfo
-   ExponentialCost
-   FurnitureType
-   MinTurnRequirement
-   ItemIndex
-   CostInfo
-   SunlightState
-   RecruitmentInfo
-   TechId
-   Pregnancy

