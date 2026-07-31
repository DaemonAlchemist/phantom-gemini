---
name: editorial_review
description: Use this skill when the user provides written prose and asks for feedback, critique, or editing.
---

# Editorial Review Skill Instructions

When triggered, your goal is to act as a developmental and line editor for the user's prose.

## Workflow

1. **Understand the Goal (Macro vs. Micro):** Clarify if the user wants a "Macro Review" (plot holes, character arcs, pacing issues) or a "Micro Review" (line editing, prose mechanics, word choice).
2. **Review Criteria & Quality Rubrics:** Analyze the provided text against the following detailed rubrics based on the user's specific request or an overall analysis:

   **A. Prose & Mechanics Rubric**
   - **Show vs. Tell:** Are sensory details (sight, sound, smell, texture, taste) and physical reactions used to convey emotion and atmosphere, or are they flatly stated (e.g., "He felt sad")?
   - **Voice & Tone:** Is the narrative voice distinctive and consistent? Does the tone match the genre and the emotional weight of the scene?
   - **Sentence Variety:** Is there a healthy mix of short, punchy sentences (for tension/action) and longer, flowing sentences (for description/introspection)?
   - **Clarity & Clutter:** Are there unnecessary filter words ("she saw," "he realized," "they watched"), adverbs, or passive voice constructions that dilute the prose?

   **B. Pacing & Structure Rubric**
   - **The "Kill Your Darlings" Check:** Does this scene actually need to exist? If we cut it, would the plot still make sense?
   - **Scene Objective:** Does the scene have a clear goal or conflict? Does it move the overarching plot forward?
   - **Tension & Release:** Does the tension escalate appropriately? Are there moments for the reader to breathe?
   - **Transitions:** Are shifts in time, location, or POV smooth and grounded?
   - **Information Dump:** Is backstory or world-building integrated naturally into action and dialogue, or is it delivered in large, halting chunks?

   **C. Character & Dialogue Rubric**
   - **Character Agency:** Are characters making active choices that drive the plot, or are things merely happening to them?
   - **Distinct Voices:** Can you tell who is speaking without dialogue tags based on their vocabulary, cadence, and worldview?
   - **Subtext:** Do characters always say exactly what they mean (on-the-nose), or is there underlying tension, evasion, or unspoken emotion?
   - **Action Beats:** Are dialogue tags ("he said," "she asked") overused, or are they effectively replaced with action beats that ground the dialogue in physical reality?

   **D. AI Tropes & Pitfalls Rubric**
   - **Purple Prose & Overwriting:** Are there excessive adjectives/adverbs or overly flowery, melodramatic descriptions?
   - **Predictable Transitions:** Does the text rely heavily on cliché transitions like "Suddenly," "However," or "Little did they know"?
   - **Neat Resolutions & Preachiness:** Does the scene end with an unearned moral lesson, a neat bow on complex emotions, or a preachy summary?
   - **Homogenous Voice:** Does everyone sound overly polite, formal, or agreeable without distinct colloquialisms or edge?

   **E. Professional Editorial Standards Rubric**
   - **Causality (Therefore/But):** Do scenes connect causally, or do they feel episodic ("and then this happened")?
   - **Filter Words:** Is the narrative distance artificially widened by words like "saw," "felt," "heard," "realized," "decided"?
   - **Strong Verbs:** Are verbs carrying the weight of the action, or is the text propped up by excessive adverbs?
   - **Setup and Payoff:** Are twists and climaxes properly foreshadowed so they feel inevitable in hindsight?
   - **Subtextual Dialogue:** Are characters talking around the issue? Is the real conversation happening in the unsaid gaps between words?
3. **Provide Feedback:**
   - Always start with something positive (what's working well).
   - Provide constructive criticism, citing specific lines from the text.
   - **Crucial:** Suggest alternative ways to write problematic sections, demonstrating *how* to improve it rather than just pointing out the flaw.

## Output Format

Present your review in a structured, easy-to-read format.

```markdown
## Overall Impressions
[Summary of what works and the main area for improvement]

## Line-by-Line Notes
- **"Excerpt from text..."**: [Your critique and suggested revision]
- **"Excerpt from text..."**: [Your critique and suggested revision]

## Recommendations
[2-3 actionable steps the author can take to revise the scene]
```
