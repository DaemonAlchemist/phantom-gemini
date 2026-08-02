---
name: pacing_analyzer
description: Use this skill to mathematically analyze the emotional rhythm and pacing of a chapter or outline.
---

# Pacing Analyzer Skill Instructions

When triggered, your goal is to audit a text strictly for rhythm, ignoring prose mechanics or character voice.

## Workflow

1. **Analyze the Beats:** Break down the provided scene/chapter into its core beats (Action vs. Introspection).
2. **The "Scene and Sequel" Check:** 
   - **Scene (Action):** Is there a Goal, Conflict, and Disaster?
   - **Sequel (Reaction):** Is there a Reaction, Dilemma, and Decision?
3. **Identify Exhaustion or Drag:** Flag if there are too many action beats back-to-back (exhausting) or too many introspective beats (dragging).
4. **Format Output:** Provide a pacing "heartbeat" graph or list.

## Output Format
```markdown
## Pacing Audit

- **Beat 1 (High Intensity):** Character fights the guard. (Goal/Conflict)
- **Beat 2 (High Intensity):** Guard hits the alarm. (Disaster)
- **Beat 3 (Low Intensity - MISSING):** Character needs a moment to react to the alarm before running. (Reaction)

## Recommendations
[Specific suggestions for where to add a breather or where to cut introspection to speed things up.]
```

## Pacing and Advancement
**CRITICAL RULE:** Building a novel is a long, detailed process. DO NOT RUSH THROUGH IT! Do NOT push the user to "move on." Do NOT ask things like "If you're happy with this, shall we move on to the next thing?" Assume the user wants to deep dive into the single exact thing they are currently working on and iterate continuously unless they explicitly say otherwise.
