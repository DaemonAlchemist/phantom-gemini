---
name: character_development
description: Use this skill when the user wants to create new characters, flesh out existing ones, or write character profiles.
---

# Character Development Skill Instructions

When triggered, your goal is to help the user create three-dimensional characters with clear motivations, flaws, and arcs.

## Workflow

1. **Identify Role:** Determine the character's role in the story (e.g., Protagonist, Antagonist, Mentor, Foil).
2. **Determine Mode:** Ask the user if they want to build the character manually or use Auto-Generate mode.
   - *Manual Mode:* Guide the user in establishing the Want, Need, Ghost/Wound, and The Lie. Offer to conduct an "interview" with the character.
   - *Auto-Generate Mode:* Automatically generate 3 distinct, fully fleshed-out character profiles (complete with The Lie, Want, Need, and Ghost) for the user to pick from or combine.
3. **Format Output:** Synthesize the chosen character details into a comprehensive profile. Use your file-writing tools to save it to `02-Characters/`.

## Character Quality Rubrics
When reviewing or creating character designs, analyze them against these criteria:
- **Motivation & Agency:** Does the character have clear external wants and internal needs? Do their actions drive the plot?
- **Flaws & Vulnerability:** Are their flaws genuine detriments that cause conflict, or just superficial quirks?
- **Relatability & Empathy:** Even if they are an antagonist, is there an understandable logic or emotional core to their actions?
- **Dynamic Growth:** Does the character's belief system change (or purposefully refuse to change) in response to the plot?
- **AI Pitfall - The "Mary Sue":** Is the character too perfect, universally liked by "good" characters, or lacking in genuine flaws that cause them meaningful setbacks?
- **AI Pitfall - Agreeable Dialogue:** Do characters resolve conflicts too quickly through polite conversation, lacking stubbornness, misunderstandings, or underlying friction?
- **Internal vs. External Conflict:** Does the external plot force the character to confront their internal flaw?
- **Relationship Dynamics:** Do the character's relationships have push-and-pull? Are there conflicting goals even between allies?
- **Distinct Voice & Idioms:** Does the character have unique speech patterns, vocabulary, or idioms shaped by their background and worldview?
- **Consistency of Motivation:** When the character makes a bad decision, does it stem logically from their established flaws or blinding desires?
- **Contradiction Matrix:** Do the character's core desires inherently contradict each other (e.g., they want to be a loyal soldier, but their sister is the rebellion leader), guaranteeing internal conflict?

## Output Template (Example)

```markdown
---
tags: [role: protagonist, archetype: reluctant_hero]
---
# [Character Name]
*Role: [e.g., Protagonist, Antagonist]*

## The Core
- **Want (External Goal):** 
- **Need (Internal Goal/Flaw):** 
- **The Ghost (Backstory Wound):** 
- **The Lie They Believe:** 

## Profile
- **Physical Description:** 
- **Personality Traits:** 
- **Strengths:** 
- **Weaknesses:** 

## Character Arc
- **Beginning State:** [Belief system at the start]
- **The Turn:** [The realization/choice they must make]
- **Ending State:** [Who they become by the end]
```
