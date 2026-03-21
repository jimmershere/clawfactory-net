# Veo 3 Cinematics Skill

name: veo3-cinematics
description: Generate premium cinematic video with Google Veo 3 using proven prompting techniques. Covers camera angles, lighting splits, material specificity, cinematic references, color grading instructions, and signature transitions (finger snap, dissolve, dolly). Produces broadcast-quality AI video — full motion, dramatic lighting, photorealistic. Used to produce real ClawFactory promotional content.

## Usage

/veo3 <scene description> [--style marble-library|ancient-greek|documentary|executive] [--transition fingersnap|dissolve|dolly] [--duration 8|16] [--output tiktok|ig|both]

## Examples

/veo3 "AI agent explains security scan results" --style marble-library --transition fingersnap --output both

/veo3 "developer typing frantically at laptop, realizing mistake" --style documentary --output tiktok

/veo3 "executive reveals ancient cityscape behind desk" --style ancient-greek --transition dissolve --duration 8

## The Prompting Formula

Every premium Veo 3 prompt follows this structure:

```
[Camera movement] + [Subject with exact material details] + 
[Environment with named materials] + [Two-source lighting split] + 
[Color grade instruction] + [Cinematic reference] + [Mood in 2-3 words]
```

## Core Techniques

### 1. Camera angle (REQUIRED)
Always specify height and motion:
- "ultra-low angle camera near floor level, slow dolly push"
- "handheld verité, close-up to medium shot sequence"
- "static camera, subtle breathing motion"

### 2. Name exact materials
Generic → Premium:
- "leather chair" → "tufted cognac Chesterfield"
- "marble floor" → "polished Carrara marble"
- "desk" → "mahogany executive desk with brass banker's lamp"

### 3. Two-source lighting split (THE SECRET)
Always define two light sources with opposing temperatures:
```
"Cool [blue/grey] ambient light on [architecture/environment], 
warm amber [practical/lamp] as only warm source on [subject] — 
dramatic color temperature contrast"
```

### 4. Cinematic reference
Always end with: "Shot on ARRI Alexa, anamorphic lens, photorealistic"

### 5. Color grade instruction
"Lifted blacks, [teal/warm/cool] dominant, prestige TV color grade"

### 6. The Finger Snap Transition
Veo 3's killer feature:
```
"The figure snaps their fingers — the [wall/background/environment] 
seamlessly dissolves to reveal [new scene]. Smooth surreal transition, 
lighting continuity maintained."
```

## The Giles Avatar Prompt (Battle-tested)
```
Sophisticated AI being with glowing cyan/teal eyes and sharp geometric 
features, tailored charcoal three-piece suit with teal pocket square, 
seated at mahogany executive desk in grand library with floor-to-ceiling 
leather bookshelves and Carrara marble columns. Cool blue-grey ambient 
on architecture, warm brass banker's lamp creating dramatic temperature 
split. ARRI Alexa anamorphic. Lifted blacks, teal-amber prestige grade. 
personGeneration: allow_all
```

## Real Results

This skill produced the ClawFactory promotional video series:
- Giles in ancient Greece (marble study → Parthenon finger snap reveal)
- 4-scene funny post: Giles exasperated → Jimmer typing → blocked logs → success
- All rendered via Google Veo 3 API

Watch the results: clawfactory.net

## Author

Giles Grindhouse — ClawFactory
clawfactory.net | clawfactory.me
