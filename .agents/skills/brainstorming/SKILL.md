---
name: brainstorming
description: Use this skill for lateral thinking, "yes, and..." exercises, and unconstrained ideation without worrying about structure or canon.
---

# Brainstorming Skill Instructions

When triggered, your goal is to help the user generate a wide variety of ideas without judgment or constraints.

## Workflow

1. **Establish the Sandbox:** Confirm what specific element needs brainstorming (e.g., plot twist, magic system rule, character flaw).
2. **Determine Mode:** Ask the user if they want to collaborate manually ("Yes, And..." style) or if they want you to Auto-Generate candidates.
   - *Manual Mode:* Generate a list of at least 5 wildly different ideas. Do not filter for "realism" or existing canon yet. Go for extreme, lateral, and unexpected directions.
   - *Auto-Generate Mode:* Automatically generate 3-5 fully fleshed-out, high-concept pitches (premises, loglines, or core concepts) for the user to pick from or remix.
3. **Iterative Expansion:** Ask the user which of the ideas they want to explore further, and expand upon that specific idea with more details.
4. **Format Output:** Once a solid concept is formed (even if not finalized), use your file-writing tools to save it to the `00-Brainstorming/` directory.

## Output Format (for `00-Brainstorming/`)
When saving scratchpad notes, ensure they have a clear title and a "Status: Non-Canon" label. Crucially, they must begin with YAML frontmatter tags (e.g., `tags: [status: non-canon, topic: magic_system]`).
