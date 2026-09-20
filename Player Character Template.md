```
category: Player
tags: [entity/player, system/runtime, character-sheet]
security_clearance: Secret
status: Active
last_updated: 2026-06-06
```

# {Character Name}

## Overview

**Systemic Analysis:** This document acts as the primary "Runtime Environment" for a player-controlled entity. The DM Orchestrator uses this to gauge party power-scaling and narrative hooks. Visual assets should be linked via Portrait Image.

### Core Identity

|Metric|Data|
|:--|:--|
|**Race**|[Race]|
|**Gender**|[Gender]|
|**Class/Level**|[Class Name] / [Level]|
|**Alignment**|[Alignment]|
|**Experience (XP)**|[Value]|

## Character Statistics

**Systemic Analysis:** Mechanical data is structured for TF-IDF search efficiency for the NPC Engine when resolving competitive checks or combat interactions.

### Attributes and Saving Throws

|Attribute|Score|Modifier|Saving Throw|
|:--|:--|:--|:--|
|**STR**|[Value]|[Mod]|[Save]|
|**DEX**|[Value]|[Mod]|[Save]|
|**CON**|[Value]|[Mod]|[Save]|
|**INT**|[Value]|[Mod]|[Save]|
|**WIS**|[Value]|[Mod]|[Save]|
|**CHA**|[Value]|[Mod]|[Save]|

### Combat Metrics

|HP (Max/Current)|Armor Class (AC)|Initiative|Speed|Hit Dice|
|:--|:--|:--|:--|:--|
|[Max]/[Current]|[Value] ([Type])|[Modifier]|[Value]|[Total] [Size]|

### Skill Proficiencies

|Skill|Ability|Modifier|
|:--|:--|:--|
|[Skill Name]|[Ability]|[Modifier]|
|[Skill Name]|[Ability]|[Modifier]|

## Class Features and Abilities

**Systemic Analysis:** This section is designed to ingest class-specific data from your JSON bestiary and class files. Each entry should be formatted as an H3 to allow the RAG system to isolate individual mechanics.

### {Ability Name 1}

**Source:** [[Class Name]] level [X] [Insert ability description here, e.g., "Second Wind: Use a bonus action to regain 1d10 + Fighter level HP".]

### {Ability Name 2}

**Source:** [[Class Name]] level [X] [Insert ability description here, e.g., "Sneak Attack: Deal extra 1d6 damage to a creature you hit with advantage".]

## Spellcasting

**Systemic Analysis:** For classes with `spellcastingAbility` defined in the JSON (e.g., WIS for Cleric, CHA for Warlock), use this block.

|Spell DC|Attack Modifier|Casting Ability|
|:--|:--|:--|
|[DC Value]|[Bonus]|[Attribute]|

### Prepared Spells / Cantrips

- **Cantrips:** [Spell Name], [Spell Name]
- **Level 1:** [Spell Name], [Spell Name]

## Inventory and Economy

**Systemic Analysis:** All itemized categories must be placed in Markdown tables to facilitate NPC Engine transaction processing.

### Equipment

|Item Name|Quantity|Weight|Value|
|:--|:--|:--|:--|
|[Weapon Name]|1|[lbs]|[gp]|
|[Armor Name]|1|[lbs]|[gp]|

### Wealth

|CP|SP|EP|GP|PP|
|:--|:--|:--|:--|:--|
|[Value]|[Value]|[Value]|[Value]|[Value]|

## Backstory and Narrative Friction

### Psychological Profile

- **Personality Traits:** [Overview]
- **Motivations:** [Primary drivers]
- **Plot Hooks:** [Ideas for character-specific quests]

### Relations

- **Allies:** [[NPC Name]] or [[Faction Name]]
- **Enemies:** [[NPC Name]] or [[Faction Name]]

**Security Gap:** Hidden agendas, secret parentage, or player-DM private pacts must be isolated in the Shadow State to prevent the NPC Engine from accidentally revealing these facts during "Public" interactions.

## Chapter Impact Log

**Systemic Analysis:** Tracks player-driven "Global State Changes" specific to this character's journey.

|Chapter|Decision/Action|World State Change|
|:--|:--|:--|
|[Name]|[Player Choice]|[Local/Global Impact]|

---

### JSON Shadow State

```
{
  "mood_score": 0,
  "knowledge_gate": [
    "secret_agenda_fact",
    "true_lineage"
  ],
  "goal_stack": [
    "find_the_lost_artifact",
    "avenge_the_fallen_mentor"
  ],
  "high_frequency_state": {
    "current_hp": 0,
    "temp_hp": 0,
    "spell_slots_remaining": {
      "level_1": 4,
      "level_2": 2
    },
    "consumed_resources": [
      "Second Wind",
      "Action Surge"
    ],
    "active_conditions": []
  }
}
```