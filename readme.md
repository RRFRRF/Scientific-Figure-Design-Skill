# Scientific Figure Design Skill

A structured skill for generating publication-ready AI drawing prompts for scientific and academic figures.

## What is this?

This is a **Hermes-compatible skill** that transforms your technical descriptions into structured, high-quality AI drawing prompts — optimized for Midjourney, DALL-E, and Gemini.

Unlike raw prompt templates, this skill provides:

- **Interactive style selection** with 7 curated presets
- **Structured output** with exact hex color values, layout specs, and negative prompts
- **Three-phase reasoning** (Understand → Think → Design) running internally — you only see the final prompt
- **Publication-ready defaults** — white background, flat design, no gradients, no 3D, light color palette

## Quick Start

1. Invoke the skill: `scientific-figure-prompt`
2. Provide: visualization goal, technical content, scene description, language
3. Pick a style preset (or go with the default)
4. Get a structured AI drawing prompt — copy to your image generator

## 7 Style Presets

| Preset | Style | Best For |
|--------|-------|----------|
| **P1** 🎓 | AI/SE Academic Minimalist | Paper/slide figures — **default** |
| **P2** 🔬 | Nature/Science | Top-journal figures |
| **P3** 🏗️ | System Architecture | Microservices/system design |
| **P4** 📊 | Data Pipeline | ETL/Workflow/Processing |
| **P5** 🔄 | Cycle/Feedback | Training loops/Iterative optimization |
| **P6** 🌐 | Network Topology | Distributed systems/Communication |
| **P7** 🎨 | Custom | Fully user-defined |

### P1 Default: AI/SE Academic Minimalist

The default preset enforces academic rigor:

- White background `#FFFFFF`
- Light color palette: soft blue `#4A90D9`, light green `#7EC8A0`, warm orange `#E8855B`
- Flat design, rounded rectangles (8px radius, 1.5px stroke)
- **No** gradients, 3D effects, shadows, or decorative elements
- 4K resolution, 300 DPI, IEEE/ACM standard

## Output Format

The skill generates prompts with these structured sections:

```
=== SCENE DESCRIPTION ===
=== VISUAL ELEMENTS ===
=== COMPOSITION & LAYOUT ===
=== COLOR PALETTE ===
=== STYLE SPECIFICATIONS ===
=== TECHNICAL SPECS ===
=== NEGATIVE PROMPT ===
```

Every color is a precise hex value. Every element has shape, color, position, and label. No ambiguity.

## Files

| File | Description |
|------|-------------|
| `scientific_figure_prompt_skill.md` | The skill definition — load into Hermes or any compatible agent |
| `scientific_figure_prompt_template.md` | Legacy prompt template (v1, manual fill-in) |

## License

MIT
