# Dimitri Pouletov — Master Character Style Guide

**Status: LOCKED** — this document and `reference-sheet.webp` are the canonical,
version-controlled source of truth for this character. Every video, image, or
animation shot that includes Dimitri Pouletov must conform to the specs below.
Do not regenerate or re-interpret the design from scratch; always generate
*from* this sheet (image reference + prompt text together).

## Reference Asset
- `reference-sheet.webp` — full turnaround/expression/pose sheet. Treat this
  as the single master reference image. Feed it (or crops of it) into every
  image/video generation call as a style/character reference, not just as
  descriptive text.

## Identity
| Field | Value |
|---|---|
| Name | Dimitri Pouletov |
| Role | Russian Superspy (rooster) |
| Approx. age | 35 |
| Height | 6'2" |
| Build | Athletic |
| Personality | Smart, contrarian |

## Distinguishing Traits
- Soy rooster
- Sharpshooter
- Polymath
- Master of disguises

## Signature Colour Palette
- Charcoal / near-black (primary suit & coat)
- Dark grey
- Off-white (shirt)
- Deep red (comb, wattle, tie — accent colour)

Materials: Armani-style tailored suits, FSB-style winter overcoats.

## Face & Identity Details
- White-feathered head, deep red comb (upright, jagged) and wattle
- Yellow/amber eyes, yellow beak
- Always wears a dark olive/khaki military-style peaked cap with a front
  emblem/button
- Keep front-face and profile proportions consistent with the "FACE & IDENTITY
  DETAILS" panel: comb silhouette, beak curvature, and cap angle must match
  across every shot

## Full-Body Turnaround (canonical poses)
Four fixed camera angles — use these as the base silhouette for any new angle:
1. Front view
2. 3/4 view
3. Side profile
4. Back view

Base outfit in all four: double-breasted dark trench/overcoat, black suit
underneath, white shirt, deep red tie, black leather gloves, black trousers,
black shoes, peaked cap.

## Expression Sheet (locked set of 8)
Use these exact labels/poses as the only sanctioned expression states unless
a new one is explicitly approved and added back into this guide:
`Neutral, Happy, Angry, Sad, Surprised, Worried, Confident, Determined`

## Pose & Body-Language Sheet (locked set of 6)
`Neutral standing, Walking, Sitting, Relaxed, Tense, Action-ready`
Backdrop convention: moody overcast city skyline (Moscow-coded — onion domes
in the portrait shot, modern skyline + helicopter silhouette in the action
shots). Keep lighting cool/desaturated with the red accents (comb, tie)
punching through as the only warm, saturated color in frame.

## Costume Construction Details (for close-ups / texture consistency)
- Neckline: white dress shirt collar, deep red tie, black suit lapel
- Sleeves: black suit sleeve under trench coat, triple-button cuff
- Waist/belt: trench coat belt with buckle, double-breasted closure
- Fabric: fine herringbone/twill wool texture, matte, no sheen
- Back detail: trench coat back yoke with epaulette-style tabs
- Accessories: peaked cap (metal emblem), black leather gloves, sunglasses,
  sidearm (pistol), FSB-style ID/credentials wallet with red seal

## Usage Rules for Video Generation
1. **Always attach `reference-sheet.webp`** (or the relevant panel crop) as
   an image reference alongside the text prompt — do not rely on text alone.
2. **Pose/expression must be drawn from the locked lists above.** If a shot
   needs something outside those lists, design it as an extension here first
   (see "Extending This Guide"), don't improvise it only in a video prompt.
3. **Palette is fixed**: charcoal/black/off-white/deep-red only. No other
   accent colors unless explicitly approved and logged in this file.
4. **Proportions are fixed**: 6'2" athletic build, comb/wattle/beak
   silhouette as shown in the Face & Identity panel. Don't let a generator
   drift the head size, comb shape, or cap angle between shots.
5. **Continuity across shots/scenes**: when generating a new shot, reference
   the *closest matching* pose/expression tile from this sheet rather than
   generating freeform, to keep the character visually identical scene to
   scene.

## Extending This Guide
New poses, expressions, outfits, or props for Dimitri Pouletov should be
added as new rows/sections in this file (with a generated sample added to
`characters/dimitri-pouletov/`) rather than created ad hoc in a single video
prompt — that keeps this guide the single master template going forward.
