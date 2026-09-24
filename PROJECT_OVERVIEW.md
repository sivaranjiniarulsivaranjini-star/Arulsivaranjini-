# Project Overview

## Title
ComicCraft AI – Comic Story Creator Using Gemini Models

## Problem
Creating a complete comic requires story planning, character development, dialogue writing and panel sequencing. Beginners may find this process time-consuming.

## Proposed Solution
ComicCraft AI accepts a short story idea and uses a Gemini generative AI model to produce a structured comic script containing:
- title
- logline
- characters
- panel scenes
- narration
- dialogue
- visual prompts

## Architecture
Browser → Express API → Gemini Model → Structured JSON → Browser UI

## Main Modules
1. Story input
2. Gemini prompt generation
3. JSON response parsing
4. Character display
5. Panel-by-panel comic display
6. Print/PDF export

## Future Scope
- AI-generated panel artwork
- Multiple comic layouts
- Character consistency
- Tamil and multilingual generation
- User authentication
- Cloud database
- PDF and image export
