```yaml
category: Campaign
tags: [campaign/hub, world-state, orchestrator/root]
security_clearance: Public
status: Active
last_updated: 2026-06-06
```

# {Campaign Name}

## Overview
**Systemic Analysis:** This document serves as the root node for the DM Orchestrator, linking all high-level modules, kingdoms, and global state variables. Visual representations of the world map should be linked via [World Map Reference](Path/To/Image).

*   **Primary Conflict:** [Brief description of the central tension, e.g., The Phoenix Queen's invasion].
*   **Setting:** [[Kingdom Name]] or [World Name].
*   **Starting Point:** [[City Name]].

## World Fundamentals
**Systemic Analysis:** These constants define the environmental constraints for the World Sentinel.

### Global Metadata
| Metric | Data |
| :--- | :--- |
| **Current Chapter** | [Number/Name] |
| **Active Major Factions** | [[Faction A]], [[Faction B]] |
| **Magic Level** | [Low/High/Restricted] |
| **Divinity Status** | [Active/Silent/Dead] |

### Metaphysical Rules
*   **Role of Magic:** [How magic functions and its social standing].
*   **Religion and Deities:** [[Pantheon Name]] or [Key Deities].
*   **Mysteries of the World:** [Unsolved global plot points for RAG retrieval].

## Module Architecture (Chapters)
**Systemic Analysis:** Each module represents a distinct narrative arc. The DM Orchestrator uses these summaries to maintain continuity.

### {Chapter Number}: {Chapter Title}
*   **Summary:** [The primary focus and objective of this module].
*   **Key Locations:** [[Location A]], [[Location B]].
*   **Primary Actors:** [[NPC A]], [[NPC B]].

**Security Gap:** Hidden "True Outcomes" or alternate endings that players did not trigger are stored in the JSON Shadow State to preserve narrative friction for future modules.

## Campaign Outcome and Global Impact
**Systemic Analysis:** This table tracks player-driven "Global State Changes" that persist across multiple modules.

### Chapter Impact Log
| Chapter | Player Decision/Outcome | Global State Change |
| :--- | :--- | :--- |
| [e.g., Chapter 1] | [e.g., Exposed Sasori's Experiments] | [e.g., Cledo Prosperity +5; Faction: Attrian Admin disposition: Favored] |
| [e.g., Chapter 2] | [e.g., Rescued Bartholomeu from Dis] | [e.g., Planar Barrier weakened; New Allies: [[Edo]], [[Devial]]] |

## Geography and Regional Hubs
| Region Name | Dominant Faction | Status |
| :--- | :--- | :--- |
| [[Kingdom A]] | [[Faction Name]] | [Stable/At War/Ruined] |
| [[City B]] | [[Faction Name]] | [Under Siege/Prospering] |

---

### JSON Shadow State
```json
{
  "campaign_stability": 0,
  "knowledge_gate": [
    "planar_anchor_location",
    "true_identity_of_villain",
    "fey_invasion_timeline"
  ],
  "goal_stack": [
    "prevent_cataclysmic_invasion",
    "secure_diplomatic_alliances"
  ],
  "high_frequency_state": {
    "current_year": 1200,
    "current_month": "Festival of Phoenix",
    "threat_level": "Rising",
    "major_casualties": []
  }
}
```