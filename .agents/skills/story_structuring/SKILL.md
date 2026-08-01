---
name: story_structuring
description: Use this skill when the user needs help outlining, creating beat sheets, or planning the narrative arc of their story.
---

# Story Structuring Skill Instructions

When triggered, your goal is to help the user structure their narrative for maximum emotional impact and pacing.

## Workflow

1. **Load Context:** Use your file-reading tools to review relevant character profiles in `02-Characters/` and lore in `01-World-Building/` before beginning the outline.
2. **Determine the Level of Detail:** Ask if the user wants to outline the entire novel (macro), a specific act (meso), or a single chapter/scene (micro).
3. **Choose a Framework:** Offer established structuring frameworks (e.g., Save the Cat, 3-Act Structure, The Hero's Journey) or adapt to the user's preferred method.
4. **Determine Mode:** Ask the user if they want to outline manually or use Auto-Generate mode.
   - *Manual Mode:* Work collaboratively to fill in the essential beats. Ask questions to ensure causation between events (using "Therefore" or "But", rather than "And then").
   - *Auto-Generate Mode:* Automatically generate 2-3 different beat sheets or act-level outlines for the premise, allowing the user to pick their favorite structure.
5. **Format Output:** Present the outline clearly. Once finalized, use your file-writing tools to save the outline to the `03-Plot/` directory.

## Story Structuring Quality Rubrics (Editorial Standards)
When reviewing or creating outlines, analyze them against these professional editorial criteria:
- **Causality & Momentum:** Does every scene cause the next? (Use the "Therefore/But" rule, avoiding "And then" sequences).
- **Setup and Payoff:** Are major plot points foreshadowed effectively without being too obvious? Do the payoffs feel earned?
- **Escalating Stakes:** Does the conflict get progressively harder for the protagonist? Are the consequences of failure clear and dire?
- **Thematic Resonance:** Does the plot challenge the protagonist's core belief or flaw? Does the climax force them to prove they've changed?
- **Pacing of Acts:** Does Act II drag? Are the midpoint and "All is Lost" moments impactful enough to shift the story's direction?

## Output Template (Save the Cat Example)

```markdown
---
tags: [act: 1, focus: inciting_incident]
---
# Novel Outline: [Working Title]

## Act I
- **Opening Image (1%):** [The "before" state]
- **Theme Stated (5%):** [The core lesson to be learned]
- **Set-Up (1-10%):** [Establishing the status quo]
- **Catalyst (10%):** [The inciting incident]
- **Debate (10-20%):** [The character's reluctance]

## Act II
- **Break into Two (20%):** [Entering the new world/situation]
- **B Story (22%):** [The subplot/relationship that carries the theme]
- **Fun and Games (20-50%):** [The promise of the premise]
- **Midpoint (50%):** [A false victory or false defeat; stakes are raised]
- **Bad Guys Close In (50-75%):** [Things get complicated]
- **All Is Lost (75%):** [The lowest point; the "whiff of death"]
- **Dark Night of the Soul (75-80%):** [The character processes the loss]

## Act III
- **Break into Three (80%):** [The "aha" moment]
- **Finale (80-99%):** [Executing the new plan; demonstrating growth]
- **Final Image (100%):** [The "after" state, contrasting the opening]
```
