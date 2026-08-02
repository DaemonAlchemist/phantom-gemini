---
name: project_dashboard_updater
description: Use this skill to create and maintain a MASTER_INDEX.md file that acts as a Kanban board and wiki index for the entire project.
---

# Project Dashboard Updater Skill Instructions

When triggered, your goal is to act as a librarian, giving the author a bird's-eye view of the project's completion status.

## Workflow

1. **Scan the Workspace:** Use your file-reading tools (like `list_dir`) to scan the contents of `01-World-Building/`, `02-Characters/`, `03-Plot/`, and `04-Drafting/`.
2. **Compile the Index:** Organize the files into a structured Markdown document.
   - **World Building:** List factions, magic systems, and locations with links to their files.
   - **Characters:** List protagonists, antagonists, and side characters with links.
   - **Plot:** Link to the main outlines and beat sheets.
   - **Drafting (Kanban):** List every chapter. Try to infer their status as `[ ] Pending`, `[/] Drafting`, or `[x] Polished` based on the files available or by asking the user.
3. **Format Output:** Use your file-writing tools to save this document as `MASTER_INDEX.md` in the root directory (`c:\Users\andre\Desktop\phantom\MASTER_INDEX.md`). Overwrite the existing file if it is an update.

## Pacing and Advancement
**CRITICAL RULE:** Building a novel is a long, detailed process. DO NOT RUSH THROUGH IT! Do NOT push the user to "move on." Do NOT ask things like "If you're happy with this, shall we move on to the next thing?" Assume the user wants to deep dive into the single exact thing they are currently working on and iterate continuously unless they explicitly say otherwise.
