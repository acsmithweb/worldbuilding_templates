
```
category: Companion
tags: [entity/actor, sidekick, progression/scaling]
security_clearance: Secret
status: Active
last_updated: 2026-06-06
```

# {Companion Name}

## Overview

**Systemic Analysis:** This entity acts as a secondary narrative actor managed by the DM Orchestrator but often controlled tactically by players. It utilizes a streamlined version of the Player Character Template while maintaining the tactical modularity of a Statblock. Visual assets should be linked via standard Markdown: Portrait Image.

- **Race/Type:** [Race] ([Type])
- **Role:** [e.g., Healer, Attacker, Defender]
- **Primary PC Link:** [[Character Name]]
- **Current Allegiance:** [[Faction Name]]

## Core Statistics

**Systemic Analysis:** All mechanical data follows the **Statistical Data Governance** protocol to ensure machine readability and TF-IDF search efficiency for competitive checks.

### Attributes and Saves

|Attribute|Score|Modifier|Saving Throw|
|:--|:--|:--|:--|
|**STR**|[Value]|[Mod]|[Save]|
|**DEX**|[Value]|[Mod]|[Save]|
|**CON**|[Value]|[Mod]|[Save]|
|**INT**|[Value]|[Mod]|[Save]|
|**WIS**|[Value]|[Mod]|[Save]|
|**CHA**|[Value]|[Mod]|[Save]|

### Combat Metrics

|HP (Max/Current)|AC|Initiative|Speed|Hit Dice|
|:--|:--|:--|:--|:--|
|[Max]/[Current]|[Value]|[Modifier]|[Value]|[Total] [Size]|

### Skill Proficiencies

|Ability|Skill|Modifier|
|:--|:--|:--|
|[Ability]|[Skill Name]|[Modifier]|

## Combat Actions and Signature Abilities

**Systemic Analysis:** Companion abilities are limited to "Signature Actions" to reduce cognitive load while allowing for the "Power Hook" escalation found in the Saga Framework.

### Actions

|Action Name|Type|Attack Bonus|Damage Formula|Damage Type|
|:--|:--|:--|:--|:--|
|[Attack Name]|[Melee/Ranged]|[to Hit]|[Formula]|[Type]|
|[Signature Move]|[Utility/AOE]|[DC]|[Effect]|[Type]|

### Bonus Actions and Reactions

- **{Ability Name}:** [Brief mechanical description].
- **{Ability Name}:** [Brief mechanical description].

## Progression and Legacy

**Systemic Analysis:** This section tracks "Legacy Items" or latent abilities that evolve as the campaign moves through the **Saga Escalation Phases**.

- **Current Phase:** [e.g., Phase I: Local Catalyst]
- **Power Hook:** [Unique trait or latent ability discovered at levels 1–4].
- **Legacy Item:** [[Item Name]] — [A unique item that differentiates the companion from standard entities].

## Psychological Profile and Bond

**Security Gap:** Latent betrayal triggers or "Revelation 2" level moral compromises (e.g., the companion is actually a double agent for a "stronger boss") must be isolated in the JSON Shadow State.

### Personality and Mannerisms

- **Personality Traits:** [Overview].
- **Mannerisms/Quirks:** [Speech patterns or distinct behaviors].
- **Bond Status:** [e.g., Loyal, Wavering, Hostile].

### Motivations and Goals

1. **Short-Term:** [Immediate objective].
2. **Long-Term:** [Ambition aligned with or contrary to the party].

## Chapter Impact Log

**Systemic Analysis:** Tracks player-driven "Global State Changes" specific to the companion's loyalty or survival.

|Chapter|Player Interaction|Companion State Change|
|:--|:--|:--|
|[Name]|[e.g., Saved from Orcs]|[e.g., Loyalty +2, Unlocked Signature Move]|

---

### JSON Shadow State

```
{
  "mood_score": 0,
  "loyalty_index": 5,
  "knowledge_gate": [
    "secret_origin_fact",
    "hidden_fear_of_fire"
  ],
  "goal_stack": [
    "protect_primary_pc",
    "reclaim_stolen_heirloom"
  ],
  "high_frequency_state": {
    "current_hp": 0,
    "latent_ability_unlocked": false,
    "is_disguised": false,
    "active_conditions": []
  }
}
```