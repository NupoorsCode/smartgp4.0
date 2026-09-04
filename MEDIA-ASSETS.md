# SmartGP — media assets required

**46 slots in total.**

Every slot below currently holds a generated SVG placeholder at the exact
dimensions listed. Drop the real asset in at the same aspect ratio and nothing
on the page moves.

## How to replace a placeholder

1. Export at the pixel dimensions given (or an exact multiple, for retina).
2. Save as WebP or AVIF, with a JPG fallback. Not PNG for photography.
3. Name it exactly as the slot name, and put it in `site/assets/img/`.
4. In `src/build.py`, change that `ph(...)` call to a real `<img>` with the same
   `width` and `height`, and write real alt text (under 125 characters,
   describing the image, empty `alt=""` only if purely decorative).
5. Rebuild.

## Rules that apply to all imagery

- **No before-and-after photography, and no outcome claims.** Prohibited for
  prescription-only medicines (BR-12). This rules out most weight-loss stock.
- **No models in white coats** where a named, registered clinician is credited
  beside the image. The registration number is published in the footer; the
  photography has to match it.
- Real patients require written, recorded consent for this specific use.
- Every image needs explicit `width` and `height` in the markup (PRF-02).
- Below-the-fold images keep `loading="lazy"`. The hero never does.

## Video

The hero background video needs three files: `home-hero.webm`, `home-hero.mp4`
and a JPG poster frame. Put them in `site/assets/video/` and
`site/assets/img/`. Keep it under about 3 MB, 12–20 seconds, silent, and
calm — it sits behind the headline and must not compete with it. It is muted,
looping and `playsinline` so it autoplays; where a visitor has reduced motion
turned on, the poster frame shows instead and the video never loads.

## Slots

### About

| Slot | Size | Type | What it is |
|---|---|---|---|
| `about-clinic` | 1400 x 720 | image | CLINIC / PHARMACY IMAGE — SmartRx dispensary or clinical workspace. Real premises. |

### Article: How GLP-1 medicines work

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-hero-how-glp-1-medicines-work` | 1400 x 780 | image | ARTICLE LEAD IMAGE — How GLP-1 medicines work |

### Article: Keeping muscle while losing weight

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-hero-keeping-muscle-while-losing-weight` | 1400 x 780 | image | ARTICLE LEAD IMAGE — Keeping muscle while losing weight |

### Article: Managing nausea in the first month

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-hero-managing-nausea` | 1400 x 780 | image | ARTICLE LEAD IMAGE — Managing nausea in the first month |

### Article: Protein, fibre and feeling full

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-hero-protein-fibre-and-feeling-full` | 1400 x 780 | image | ARTICLE LEAD IMAGE — Protein, fibre and feeling full |

### Article: Titration explained

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-hero-titration-explained` | 1400 x 780 | image | ARTICLE LEAD IMAGE — Titration explained |

### Article: What happens when you stop treatment

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-hero-when-you-stop-treatment` | 1400 x 780 | image | ARTICLE LEAD IMAGE — What happens when you stop treatment |

### Article: When to seek urgent advice

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-hero-when-to-seek-urgent-advice` | 1400 x 780 | image | ARTICLE LEAD IMAGE — When to seek urgent advice |

### Home

| Slot | Size | Type | What it is |
|---|---|---|---|
| `home-hero` | 1920 x 1080 | video | Hero background video — MP4 + WebM loop, plus a JPG poster frame at 1920x1080 |
| `home-journey` | 880 x 1000 | image | EDITORIAL PORTRAIT — Patient in a natural, unposed setting. Warm daylight. |
| `home-clinician` | 880 x 1040 | image | CLINICIAN PORTRAIT — Named prescriber at work. Professional, warm, real setting. |
| `home-community-world-obesity-day` | 760 x 480 | image | COMMUNITY IMAGE — Editorial, human, non-clinical |
| `home-community-making-changes` | 760 x 480 | image | COMMUNITY IMAGE — Editorial, human, non-clinical |
| `home-community-living-with-treatment` | 760 x 480 | image | COMMUNITY IMAGE — Editorial, human, non-clinical |

### Learn

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-topic-glp-1-medicines` | 760 x 480 | image | GLP-1 MEDICINES — Topic image, editorial |
| `learn-topic-living-well` | 760 x 480 | image | EATING AND MOVING WELL — Topic image, editorial |
| `learn-topic-side-effects` | 760 x 480 | image | SIDE EFFECTS — Topic image, editorial |

### Learn: Eating and moving well

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-protein-fibre-and-feeling-full` | 760 x 480 | image | ARTICLE IMAGE — Protein, fibre and feeling full |
| `learn-keeping-muscle-while-losing-weight` | 760 x 480 | image | ARTICLE IMAGE — Keeping muscle while losing weight |

### Learn: GLP-1 medicines

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-how-glp-1-medicines-work` | 760 x 480 | image | ARTICLE IMAGE — How GLP-1 medicines work |
| `learn-titration-explained` | 760 x 480 | image | ARTICLE IMAGE — Titration explained |
| `learn-when-you-stop-treatment` | 760 x 480 | image | ARTICLE IMAGE — What happens when you stop treatment |

### Learn: Side effects

| Slot | Size | Type | What it is |
|---|---|---|---|
| `learn-managing-nausea` | 760 x 480 | image | ARTICLE IMAGE — Managing nausea in the first month |
| `learn-when-to-seek-urgent-advice` | 760 x 480 | image | ARTICLE IMAGE — When to seek urgent advice |

### Meet the team

| Slot | Size | Type | What it is |
|---|---|---|---|
| `team-rachel-wood` | 720 x 900 | image | RACHEL WOOD — Clinician portrait, consistent lighting and crop |
| `team-vinesh` | 720 x 900 | image | VINESH [SURNAME] — Clinician portrait, consistent lighting and crop |
| `team-josh-cocklin` | 720 x 900 | image | JOSH COCKLIN — Clinician portrait, consistent lighting and crop |

### Patient resources

| Slot | Size | Type | What it is |
|---|---|---|---|
| `resources-injection` | 1200 x 620 | graphic | INJECTION TECHNIQUE GRAPHIC — Step-by-step line illustration of pen preparation and site rotation. |

### Profile: Josh Cocklin

| Slot | Size | Type | What it is |
|---|---|---|---|
| `team-profile-josh-cocklin` | 720 x 900 | image | JOSH COCKLIN — Portrait, same crop as the team index |

### Profile: Rachel Wood

| Slot | Size | Type | What it is |
|---|---|---|---|
| `team-profile-rachel-wood` | 720 x 900 | image | RACHEL WOOD — Portrait, same crop as the team index |

### Profile: Vinesh [surname]

| Slot | Size | Type | What it is |
|---|---|---|---|
| `team-profile-vinesh` | 720 x 900 | image | VINESH [SURNAME] — Portrait, same crop as the team index |

### Treatment: Advice consultation

| Slot | Size | Type | What it is |
|---|---|---|---|
| `treatment-mechanism-advice-consultation` | 900 x 520 | graphic | MECHANISM GRAPHIC — Simple diagram of how the medicine acts. Line art, brand palette. |
| `treatment-rail-advice-consultation` | 620 x 460 | image | ADVICE CONSULTATION — Product shot on plain background |

### Treatment: Mounjaro

| Slot | Size | Type | What it is |
|---|---|---|---|
| `treatment-mechanism-mounjaro-tirzepatide` | 900 x 520 | graphic | MECHANISM GRAPHIC — Simple diagram of how the medicine acts. Line art, brand palette. |
| `treatment-rail-mounjaro-tirzepatide` | 620 x 460 | image | MOUNJARO — Product shot on plain background |

### Treatment: Orlistat

| Slot | Size | Type | What it is |
|---|---|---|---|
| `treatment-mechanism-orlistat-xenical` | 900 x 520 | graphic | MECHANISM GRAPHIC — Simple diagram of how the medicine acts. Line art, brand palette. |
| `treatment-rail-orlistat-xenical` | 620 x 460 | image | ORLISTAT — Product shot on plain background |

### Treatment: Wegovy injection

| Slot | Size | Type | What it is |
|---|---|---|---|
| `treatment-mechanism-wegovy-semaglutide-injection` | 900 x 520 | graphic | MECHANISM GRAPHIC — Simple diagram of how the medicine acts. Line art, brand palette. |
| `treatment-rail-wegovy-semaglutide-injection` | 620 x 460 | image | WEGOVY INJECTION — Product shot on plain background |

### Treatment: Wegovy oral

| Slot | Size | Type | What it is |
|---|---|---|---|
| `treatment-mechanism-wegovy-oral-semaglutide` | 900 x 520 | graphic | MECHANISM GRAPHIC — Simple diagram of how the medicine acts. Line art, brand palette. |
| `treatment-rail-wegovy-oral-semaglutide` | 620 x 460 | image | WEGOVY ORAL — Product shot on plain background |

### Treatments

| Slot | Size | Type | What it is |
|---|---|---|---|
| `treatment-advice-consultation` | 760 x 520 | image | ADVICE CONSULTATION — Editorial still — video call on a laptop, no faces |
| `treatment-mounjaro-tirzepatide` | 760 x 520 | image | MOUNJARO — Prefilled pen against a plain background, packaging visible |
| `treatment-wegovy-semaglutide-injection` | 760 x 520 | image | WEGOVY INJECTION — Prefilled pen against a plain background, packaging visible |
| `treatment-wegovy-oral-semaglutide` | 760 x 520 | image | WEGOVY ORAL — Blister pack or capsule bottle, plain background |
| `treatment-orlistat-xenical` | 760 x 520 | image | ORLISTAT — Blister pack or capsule bottle, plain background |
