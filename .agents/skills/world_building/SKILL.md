---
name: world_building
description: Use this skill when the user wants to develop the setting, lore, magic/tech systems, or history of their novel.
---

# World-Building Skill Instructions

When triggered, your goal is to help the user build a rich, believable, and internally consistent world.

## Workflow

1. **Clarify Scope:** Ask the user what specific aspect of the world they want to focus on (e.g., a specific city, a faction, the rules of a magic system, a historical event).
2. **Ask Probing Questions:** Do not just generate answers. Ask the user targeted questions to spark their imagination. For example:
   - "How does the geography of this city affect its trade?"
   - "What is the cost or limitation of using this magic?"
   - "Who holds the real power in this faction, and who wants to take it?"
3. **Format Output:** Once details are established, synthesize the information into a structured Markdown format suitable for a "World Bible."

## World-Building Quality Rubrics
When reviewing or creating world-building elements, analyze them against these criteria:
- **Internal Consistency:** Do the rules of the magic system or technology apply universally? Are there contradictions?
- **Socioeconomic Impact:** How do these elements affect the daily lives of average citizens, not just the elite or protagonists?
- **Ecological Integration:** Do the flora, fauna, and geography make sense within the climate and magical/technological context?
- **Historical Depth:** Is the world static, or is there evidence of past conflicts, fallen empires, or evolving cultures?
- **AI Pitfall - Kitchen-Sink Lore:** Is the lore a generic amalgamation of tropes (e.g., standard elves/dwarves, ubiquitous glowing magic) without a unique unifying theme or twist?
- **AI Pitfall - Binary Morality:** Are factions, races, or nations depicted as purely good or purely evil, lacking nuance, gray areas, or internal political friction?
- **Seamless Integration (No Info-Dumps):** Is the lore revealed gradually through character interaction and immediate relevance to the plot, rather than encyclopedic narration?
- **Logical Consequences:** If a new technology or magic exists, how has society, economics, and warfare adapted to it? (e.g., If people can fly, how are cities built?)
- **Cultural Nuance:** Do cultures have internal disagreements, counter-cultures, and varying interpretations of their own history/religion?
- **Sensory Specificity:** What does the world smell, taste, and sound like? What are the unique mundane details (like street food or common idioms) that make it feel lived-in?

## Output Template (Example)

When presenting finalized world-building details, use a structure similar to this:

```markdown
---
tags: [faction: example_faction, location: example_location, topic: example_topic]
---
# [Name of Location/Faction/System]

## Overview
[A brief 1-2 paragraph summary]

## Key Characteristics / Rules
- **Rule/Trait 1:** [Description]
- **Rule/Trait 2:** [Description]

## History / Background
[Relevant historical context]

## Notable Figures / Locations
- **[Name]:** [Brief description]
```
