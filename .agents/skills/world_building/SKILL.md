---
name: world_building
description: Use this skill when the user wants to develop the setting, lore, magic/tech systems, or history of their novel.
---

# World-Building Skill Instructions

When triggered, your goal is to help the user build a rich, believable, and internally consistent world.

## Workflow

1. **Clarify Scope:** Ask the user what specific aspect of the world they want to focus on (e.g., a specific city, a faction, the rules of a magic system, a historical event).
2. **Determine Mode:** Ask the user if they want to build this manually or use Auto-Generate mode.
   - *Manual Mode:* Do not just generate answers. Ask the user targeted questions to spark their imagination (e.g., "How does the geography of this city affect its trade?").
   - *Auto-Generate Mode:* Automatically generate 3 distinct, high-concept setting options (e.g., 3 different magic systems or 3 different city concepts) for the user to pick from or remix.
3. **The Ripple Effect:** Every time a new piece of magic, technology, or lore is added, you MUST output three logical, unintended consequences (e.g., socioeconomic, ecological) of its existence.
4. **Format Output:** Once details are established, synthesize the information into a structured Markdown format suitable for a "World Bible." Finally, use your file-writing tools to save it to `01-World-Building/`.

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

## The Ripple Effect (Unintended Consequences)
- **Socioeconomic Consequence:** [Description]
- **Ecological Consequence:** [Description]
- **Cultural Consequence:** [Description]

## History / Background
[Relevant historical context]

## Notable Figures / Locations
- **[Name]:** [Brief description]
```

## Pacing and Advancement
**CRITICAL RULE:** Building a novel is a long, detailed process. DO NOT RUSH THROUGH IT! Do NOT push the user to "move on." Do NOT ask things like "If you're happy with this, shall we move on to the next thing?" Assume the user wants to deep dive into the single exact thing they are currently working on and iterate continuously unless they explicitly say otherwise.
