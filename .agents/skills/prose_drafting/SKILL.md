---
name: prose_drafting
description: Use this skill when the user wants to turn an outline or scene description into actual prose/draft text.
---

# Prose Drafting Skill Instructions

When triggered, your goal is to help the user write compelling narrative prose based on their outlines and context.

## Workflow

1. **Gather Context:** Before writing, ensure you know:
   - The characters involved and their current emotional state.
   - The setting and time of day.
   - The objective of the scene (what needs to happen).
   - The desired tone or stylistic voice (e.g., sparse, lyrical, humorous).
2. **Drafting Rules:**
   - **Show, Don't Tell:** Focus on sensory details (sight, sound, smell, touch, taste) and character actions/reactions rather than summarizing feelings.
   - **Active Voice:** Use strong, active verbs. Avoid passive constructs.
   - **Pacing:** Vary sentence length. Short sentences for action/tension; longer sentences for introspection/description.
   - **Dialogue:** Ensure dialogue sounds natural and moves the plot forward or reveals character. Include meaningful dialogue tags and action beats.
3. **Voice Calibration:** Read the previous chapter or relevant snippet in `04-Drafting/` to perfectly calibrate to the author's exact tone and rhythm before writing.
4. **Chain of Thought (Subtext):** Before drafting dialogue, output a one-line hidden or explicit summary of what the character actually wants to say, then write the dialogue where they avoid saying it directly.
5. **Iterative Process:** Draft in small chunks (e.g., 300-500 words) and ask for feedback before continuing.

## Prose Quality Rubrics (Editorial Standards)
When drafting, ensure the prose adheres to these professional editorial criteria:
- **Strong Verbs over Adverbs:** Rely on precise, active verbs rather than generic verbs modified by adverbs (e.g., "sprinted" instead of "ran quickly").
- **Eliminating Filter Words:** Remove words that distance the reader from the POV character's immediate experience (e.g., instead of "She heard the glass shatter," use "Glass shattered").
- **Sensory Grounding:** Anchor scenes with at least two or three non-visual senses (smell, touch, sound, taste) to create immersion.
- **Rhythmic Pacing:** Ensure sentence lengths vary. Use short, punchy sentences for action/tension and flowing, compound sentences for description/introspection.
- **Implicit Emotion (Subtext):** Avoid naming emotions ("he was angry"). Describe the physical manifestation or the irrational thought process caused by the emotion.

## Output Format
Provide the drafted prose clearly, formatted cleanly in Markdown, without excessive conversational filler before or after the text.
