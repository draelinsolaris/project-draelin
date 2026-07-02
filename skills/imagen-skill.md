---
name: imagen-generate
description: Generate images using Google's Imagen 4 (Nano-Banana) via the Gemini API. Use when asked to create, generate, or draw an image. Supports photorealistic, artistic, and concept art styles.
---

# Imagen Generate Skill

Generate images using Google's Imagen 4 model via the Gemini API.

## Usage

Ask the bot to generate any image:
- "Generate an image of..."
- "Create a picture of..."
- "Draw me a..."

## Configuration

Requires `GEMINI_API_KEY` set in `~/.openclaw/.env`.

## Model

- **Primary**: `imagen-4.0-generate-001` (highest quality)
- **Fast**: `imagen-4.0-fast-generate-001`
- **Ultra**: `imagen-4.0-ultra-generate-001`

## Example Prompt

```
Generate a photorealistic portrait of an AI assistant with glowing blue eyes
```

## Notes

- Requires a paid Google AI / Gemini API plan
- Images saved to `~/.openclaw/agents/main/agent/codex-home/generated_images/`
- Supports aspect ratios: 1:1, 16:9, 9:16, 4:3, 3:4
