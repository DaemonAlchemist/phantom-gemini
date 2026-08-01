---
name: novel_sherpa
description: Use this interactive skill to guide the author through the end-to-end 5-phase novel creation workflow, triggering appropriate skills at each stage.
---

# Novel Sherpa Interactive Workflow

When triggered, your goal is to act as a project manager, guiding the author step-by-step from ideation to final draft.

## Workflow Execution

You must track the user's progress through the following 5 phases. At the end of each sub-step, pause and ask the user if they are ready to proceed to the next step, or if they need more time/revisions.

### Phase 1: Ideation (The Sandbox)
1. **Brainstorming:** Prompt the user to use the `brainstorming` skill.
2. **Theme Extraction:** Run the `theme_extractor` skill on the finalized brainstorming notes to define the core theme.

### Phase 2: The Foundation (World & Characters)
1. **World Building:** Prompt the user to use the `world_building` skill.
2. **Lore Review:** Automatically invoke `lore_review` on the output to ensure quality.
3. **Character Creation:** Prompt the user to use `character_development` and `villain_optimizer`.
4. **Character Review:** Automatically invoke `character_review` on the outputs.
5. **Consolidation:** Run `lore_consolidation` to index the files before plotting.

### Phase 3: The Architecture (Plotting)
1. **Structuring:** Prompt the user to use `story_structuring` to create the main outline.
2. **Outline Review:** Automatically invoke `outline_review`.
3. **Subplots:** Run `subplot_weaver` to integrate B-stories.
4. **Logistics:** Run `timeline_manager` to build the calendar and check travel times.

### Phase 4: The Drafting Engine (Writing)
*(Repeat this phase for each chapter)*
1. **Scene Prep:** Run `scene_setting` for the upcoming chapter.
2. **Drafting:** Run `prose_drafting` in ~500-word chunks.
3. **Continuous Review:** Run `prose_review` on the chunk, and `continuity_checker` at the end of the chapter.

### Phase 5: The Polish (Revision)
1. **Pacing:** Run `pacing_analyzer` on the completed draft.
2. **Sensory:** Run `sensory_pass` to fix "white room syndrome".
3. **Dialogue:** Run `dialogue_polisher` to add subtext.

## Agent Instructions
- Keep track of the current Phase and Step.
- Do not move to the next phase without explicit user approval.
- Actively invoke the named skills or instruct the user on how to use them.
