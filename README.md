## Nexus Rural — AI Launch Video

A 1-minute social video for a Rural Innovation Award in Latin America and the Caribbean. The piece asks young innovators in rural communities to apply.

Voice-over narration and the initial structure were already locked. The work documented here is the visual layer built on top of that script: characters, locations, image generation, motion, and the final edit.

→ [`visual-treatment.md`](visual-treatment.md)

→ [`README-workflow.md`](README-workflow.md)

## Role

- Took a locked VO script and structure and added three named characters across three territories, so the film had someone to follow instead of only landscapes and overlays.

- Generated the stills and video assets.

- Edited the final cut in CapCut: VO, picture lock, branded end card.

## Final video

**Final cut:** https://youtu.be/PNeIwU8TTSI

## Stack

| Stage | Tool |
|---|---|
| Character and environment stills | Midjourney |
| Character sheet and identity lock | Nano Banana Pro |
| Character–environment composite | Nano Banana Pro |
| Motion | Kling 3 and Seedance 2.0 |
| Music | Suno |
| Voice | ElevenLabs |
| Edit, V0 | CapCut |

Prompts for each stage live in [`prompts/`](prompts/)

## Constraints

- Duration: ~1 minute, social cut.

- Incoming brief was not a blank page. VO text and structure were already defined; the images had to serve that narration, not replace it.

- Three territories, three innovators: Caribbean greenhouse, Altiplano drone work, southern Andes logistics. Each location keeps its own light and color logic.

- Characters had to read as specific people, not generic “AI faces.” Identity lock on face, hair, skin, and wardrobe across stills and motion.

- Technology reads as overlay — electric-blue scans, interfaces, light traces — against greens, earth, and weather. The landscape stays primary.

- Camera stays grounded: medium and wide frames, slow push / track / drift. No stylized camera for its own sake.

Full visual rules: [`visual-treatment.md`](visual-treatment.md)

## Workflow

```text
Midjourney
├── Character reference ──→ NBP Character Sheet ──┐
└── Environment reference ─────────────────────────┤
                                                   ↓
                                             NBP Composite
                                                   ↓
                                            Image-to-Video
                                                   ↓
                                               CapCut

```

Four image stages, then edit:

1. Character + environment in Midjourney — establish identity, do not solve the final frame.
→  [`prompts/female-lead.md`](prompts/female-lead.md) · [`prompts/greenhouse.md`](prompts/greenhouse.md)

2. Character sheet in Nano Banana Pro — same person, multiple angles, before she enters the location.
→  [`prompts/female-lead-character-sheet.md`](prompts/female-lead-character-sheet.md)

3. Composite in Nano Banana Pro — placement, scale, shared ground plane, matched light.
→  [`prompts/compositing.md`](prompts/compositing.md)

4. Image-to-video — camera, body, wind, scan overlay. Do not redesign the frame.
→ [`prompts/video-prompt.md`](prompts/video-prompt.md)

5. CapCut — VO, rhythm, end card.

Shot-level notes: [`README-workflow.md`](README-workflow.md)

## Process stills

Put these four images here, in this order. They are already in assets/.

1. Character reference

![Female lead — Midjourney reference](assets/female-lead.png)

2. Character sheet

![Female lead — character sheet](assets/female-sheet.png)

3. Environment

![Greenhouse — Caribbean location](assets/greenhouse.png)

4. Locked composite (I2V source frame)

![Female lead in greenhouse — composite](assets/final-composite.png)
