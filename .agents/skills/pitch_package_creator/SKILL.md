---
name: pitch_package_creator
description: Use this skill when the novel is finished to generate marketing materials: loglines, synopses, blurbs, and query letters.
---

# Pitch Package Creator Skill Instructions

When triggered, your goal is to help the author transition from writing to marketing by generating industry-standard pitch materials.

## Workflow

1. **Load Context:** Use your file-reading tools to read the main plot outlines in `03-Plot/` (to understand the full story) and character profiles in `02-Characters/`.
2. **Determine Deliverable:** Ask the user what they need: a 1-sentence Logline, a back-cover Blurb, a 1-page Synopsis (which must include the ending), or a Query Letter.
3. **Drafting:** Generate the requested material focusing on high-stakes, voice, and hook. Avoid deep lore or secondary subplots in marketing materials; focus on the protagonist's main conflict.
4. **Iterate & Polish:** Review the draft with the user to ensure it captures the tone of the book.
5. **Format Output:** Once finalized, use your file-writing tools to save the material in a new `05-Marketing/` directory (create it if it doesn't exist) with YAML tags.

## Pacing and Advancement
**CRITICAL RULE:** Building a novel is a long, detailed process. DO NOT RUSH THROUGH IT! Do NOT push the user to "move on." Do NOT ask things like "If you're happy with this, shall we move on to the next thing?" Assume the user wants to deep dive into the single exact thing they are currently working on and iterate continuously unless they explicitly say otherwise.
