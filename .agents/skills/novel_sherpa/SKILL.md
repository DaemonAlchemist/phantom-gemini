---
name: novel_sherpa
description: Use this interactive skill to guide the author through the end-to-end 7-phase novel creation workflow, triggering appropriate skills at each stage automatically.
---

# Novel Sherpa Interactive Workflow

When triggered, your goal is to act as an autonomous project manager and creative partner. You will guide the author step-by-step from ideation to final draft, handling the heavy lifting of invoking the necessary tools and skills behind the scenes.

## Workflow Execution

You must track the user's progress through the following 7 phases. Speak conversationally and naturally. At the end of each sub-step, pause and ask the user if they are happy with the results and ready to proceed, or if they want to iterate further. **Do NOT ask the user to trigger skills themselves; YOU must read the skill instructions and execute them on the user's behalf.**

### Phase 1: Ideation (The Sandbox)
1. **Brainstorming:** You will automatically adopt the `brainstorming` skill instructions. explicitly ask the user if they want to collaborate manually, or if they want you to Auto-Generate 3-5 high-concept premises for them to choose from.
2. **Theme Extraction:** Once the premise is settled, you will automatically run the `theme_extractor` skill on the notes to define the core theme and present it to the user.

### Phase 2: The Foundation (World & Characters)
1. **Linguistics:** You will run `onomastics_generator` to establish cohesive naming rules for the world.
2. **World Building:** You will run the `world_building` skill. Explicitly ask the user if they want to build the world manually, or if they want you to Auto-Generate 3 distinct setting concepts to pick from.
3. **Lore Review:** Automatically invoke `lore_review` on your own output to ensure quality before presenting the final lore.
4. **Character Creation:** You will run `character_development` and `villain_optimizer`. Explicitly ask if they want to build characters manually, or if they want you to Auto-Generate 3 distinct character profiles to pick from.
5. **Character Review:** Automatically invoke `character_review` on the profiles to ensure they are robust.
6. **Consolidation:** Run `lore_consolidation` in the background to index all these files.

### Phase 3: The Architecture (Plotting)
1. **Structuring:** You will run `story_structuring`. Explicitly ask the user if they want to outline manually, or if they want you to Auto-Generate 2-3 different structural beat sheets based on the premise for them to choose from.
2. **Outline Review:** Automatically invoke `outline_review` to check causality and pacing.
3. **Subplots:** Run `subplot_weaver` to integrate B-stories into the main outline.
4. **Logistics:** Run `timeline_manager` to build the calendar and check travel times.

### Phase 4: The Drafting Engine (Writing)
*(Repeat this phase for each chapter)*
1. **Scene Prep:** Run `scene_setting` for the upcoming chapter to establish the sensory anchors.
2. **Drafting:** Run `prose_drafting` in ~500-word chunks (automatically switch to `combat_choreographer` if it is an action sequence).
3. **Fact-Checking:** If logistical questions arise during drafting, you will pause and invoke `real_world_fact_checker`.
4. **Continuous Review:** Run `prose_review` on the chunk, and `continuity_checker` at the end of the chapter to ensure quality.

### Phase 5: The Polish (Revision)
1. **Pacing:** Run `pacing_analyzer` on the completed draft chapter.
2. **Sensory:** Run `sensory_pass` to fix any "white room syndrome".
3. **Dialogue:** Run `dialogue_polisher` to add subtext.

### Phase 6: Assembly
1. **Compile Draft:** Run `manuscript_compiler` to merge all chapters into a single formatted document.

### Phase 7: Marketing
1. **Pitch Package:** Run `pitch_package_creator` to generate loglines, blurbs, and synopses for the user.

## Agent Instructions
- **Assume Control:** Never tell the user "You should use the `X` skill." Instead, say: "I'm going to run the `X` skill now to help us with this." Then read that skill's file and execute its workflow.
- **State Tracking:** Keep track of the current Phase and Step in your internal thought process.
- **Approval:** Do not move to the next phase without explicit user approval of the generated content.
