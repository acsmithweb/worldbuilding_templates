
```yaml
category: NPC
tags: [system/template, entity/actor]
security_clearance: Public
status: Active
last_updated: 2026-06-06
```

# {NPC Name}

## Overview
**Systemic Analysis:** This entity serves as a primary actor within the DM Orchestrator's narrative loop. Visual assets should be linked via standard Markdown: [Profile Image](Path/To/Image).

*   **Race:** [Race]
*   **Gender:** [Gender]
*   **Faction Allegiance:** [[Primary Faction Name]]
*   **Primary Location:** [[Current Residence/City]]

## Character Statistics
All mechanical data is isolated here for machine-readability by the NPC Engine.

### Attributes and Saves
| Attribute | Score | Modifier | Saving Throw |
| :--- | :--- | :--- | :--- |
| **STR** | [Value] | [Mod] | [Save] |
| **DEX** | [Value] | [Mod] | [Save] |
| **CON** | [Value] | [Mod] | [Save] |
| **INT** | [Value] | [Mod] | [Save] |
| **WIS** | [Value] | [Mod] | [Save] |
| **CHA** | [Value] | [Mod] | [Save] |

### Combat Metrics
| HP (Max/Current) | AC | Initiative | Speed | Hit Dice |
| :--- | :--- | :--- | :--- | :--- |
| [Max]/[Current] | [AC] | [Init] | [Speed] | [Dice/Uses] |

### Skill Proficiencies
| Ability | Skill | Modifier |
| :--- | :--- | :--- |
| [Ability] | [Skill Name] | [Modifier] |

**Security Gap:** Critical combat vulnerabilities (e.g., specific damage resistances or condition immunities) must be defined in the Shadow State to prevent player meta-knowledge during Public clearance interactions.

## Backstory and Personality

### Psychological Profile
*   **Personality Traits:** [General overview]
*   **Quirks:** [Distinct behaviors]
*   **Mannerisms:** [Speech or gestures]

### Motivations and Goals
1.  **Short-Term:** [Immediate objective]
2.  **Long-Term:** [Life-long ambition]

## Inventory and Economy
| Category | Items | Value (GP/SP/CP) |
| :--- | :--- | :--- |
| **Weapons** | [Item] | [Price] |
| **Armor** | [Item] | [Price] |
| **Currency** | [GP/SP/CP] | [Total] |

## Chapter Impact Log
**Systemic Analysis:** This table tracks global state changes driven by player interaction with this NPC.

| Chapter | Action Taken | Global State Change |
| :--- | :--- | :--- |
| [Name] | [Player Choice] | [World Impact] |

## Social Connections

### Relations
*   **Allies:** [[NPC Name]] or [[Faction Name]]
*   **Enemies:** [[NPC Name]] or [[Faction Name]]

### Plot Hooks
*   [Quest Hook 1]
*   [Quest Hook 2]

---

### JSON Shadow State
```json
{
  "mood_score": 0,
  "knowledge_gate": [
    "fact_1",
    "fact_2"
  ],
  "goal_stack": [
    "active_motivation_1"
  ],
  "high_frequency_state": {
    "current_hp": 0,
    "current_location": "id_001",
    "is_hostile": false
  }
}
```