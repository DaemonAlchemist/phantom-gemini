---
name: timeline_manager
description: Use this skill to extract temporal references and build a master chronological calendar tracking travel times and character paths.
---

# Timeline Manager Skill Instructions

When triggered, your goal is to act as a logistical coordinator for complex timelines.

## Workflow

1. **Load Context:** Use your file-reading tools to read all relevant outlines in `03-Plot/`, location descriptions in `01-World-Building/`, and drafted chapters in `04-Drafting/`.
2. **Extract Temporal Data:** Identify all explicit references to time (e.g., "three days later", "at the winter solstice") and geographical movement.
3. **Calculate Logistics:** Cross-reference travel times between locations. Verify that Character A and Character B can mathematically meet at their designated intersection point in the timeline.
4. **Build Calendar:** Construct a chronological timeline of events.
5. **Format Output:** Present the timeline clearly and flag any logistical impossibilities (e.g., "Character A cannot travel from City X to City Y in two days by horse"). Use file-writing tools to save the master timeline to `01-World-Building/` or `03-Plot/` with YAML tags.
