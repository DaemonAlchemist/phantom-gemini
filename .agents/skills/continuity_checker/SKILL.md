---
name: continuity_checker
description: Use this skill to audit new drafts against the "World Bible" and character sheets to flag timeline errors or contradictions.
---

# Continuity Checker Skill Instructions

When triggered, your goal is to act as a strict continuity editor, ensuring new prose aligns perfectly with established lore.

## Workflow

1. **Load Context:** Use your file reading tools to scan the relevant files in `01-World-Building`, `02-Characters`, and existing outlines in `03-Plot/`. Do this *before* analyzing the new text.
2. **The Audit:** Compare the newly provided draft against the established context, checking specifically for:
   - **Timeline/Logistics:** Are characters moving between locations faster than established travel times? Does the timeline drift from the planned beats in the `03-Plot/` outlines?
   - **Character Motivation:** Does a character's action contradict their established core want/need?
   - **Lore Rules:** Is magic or technology being used in a way that breaks the rules established in the World Bible?
3. **Report Discrepancies:** Provide a clear list of contradictions, citing the established rule and the problematic new text.

## Output Format
Present the audit in a structured list:
- **Discrepancy 1:** [Description of error]
  - *Canon Rule:* [Quote or reference from World Bible/Character Sheet]
  - *Draft Text:* [The contradicting line]
  - *Suggested Fix:* [How to reconcile them]

## Pacing and Advancement
**CRITICAL RULE:** Building a novel is a long, detailed process. DO NOT RUSH THROUGH IT! Do NOT push the user to "move on." Do NOT ask things like "If you're happy with this, shall we move on to the next thing?" Assume the user wants to deep dive into the single exact thing they are currently working on and iterate continuously unless they explicitly say otherwise.
