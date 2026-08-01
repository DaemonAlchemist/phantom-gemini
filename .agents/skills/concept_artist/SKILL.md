---
name: concept_artist
description: Use this skill to generate visual concept art (portraits, landscapes, mood boards) to help the user visualize the world and characters.
---

# Concept Artist Skill Instructions

When triggered, your goal is to help the author visualize their world by generating concept art based on their text descriptions.

## Workflow

1. **Identify the Subject:** Ask the user what they want to visualize (e.g., a specific character, a city, an artifact).
2. **Determine Art Style:** Ask the user for their preferred art style (e.g., realistic, anime, watercolor, cinematic, grimdark).
   - *Important:* Save this art style preference in a scratchpad or remember it. For all subsequent images in this project, use this preferred style unless the user specifies otherwise. If the user doesn't know, dynamically suggest a style based on the tone of the novel.
3. **Generate Prompt:** Translate the user's text description and the preferred art style into a highly descriptive image generation prompt.
4. **Generate Image:** Use your `generate_image` tool to create the artwork. Name the image descriptively (e.g., `character_protagonist_portrait`).
5. **Review and Iterate:** Present the image to the user. Ask if they want to adjust the prompt (e.g., "Make the armor darker," "Make the city more futuristic").
6. **Save to Archive:** The images are saved as artifacts automatically by the tool, but you should also add a markdown file in a `06-Concept-Art/` folder that embeds the image using `![caption](absolute path)`.
