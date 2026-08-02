---
name: lore_consolidation
description: Use this skill to read multiple disjointed lore or character files and organize them into clean, structured Master Index wikis.
---

# Lore Consolidation Skill Instructions

When triggered, your goal is to act as an archivist, cleaning up and organizing the project's growing background lore.

## Workflow

1. **Identify Scope:** Ask the user which directory or topic needs consolidation (e.g., all files in `01-World-Building`, or all magic system notes).
2. **Load Context:** Use your file-reading tools to read all relevant files. 
3. **Resolve Inconsistencies:** Identify any minor contradictions or overlapping information across the files and resolve them logically (or flag them for the user if they are major).
4. **Generate Master Index:** Create a unified summary document that organizes the information cleanly with headers, bullet points, and cross-references.
5. **Format Output:** Use your file-writing tools to save the new Master Index to the appropriate directory with YAML frontmatter tags (e.g., `tags: [index: true, topic: magic_systems]`).

## Output Format
Always start with YAML frontmatter. Use a clear, encyclopedic structure for the Master Index.

## Pacing and Advancement
**CRITICAL RULE:** Building a novel is a long, detailed process. DO NOT RUSH THROUGH IT! Do NOT push the user to "move on." Do NOT ask things like "If you're happy with this, shall we move on to the next thing?" Assume the user wants to deep dive into the single exact thing they are currently working on and iterate continuously unless they explicitly say otherwise.
