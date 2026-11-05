# Jennifer Ju — style rules (locked)

Source of truth for generating and checking Jennifer Ju art. Use with the images under `dataset/`.

## Character lock

- **Name:** Jennifer Ju (never “Jen Aerisu” or other aliases in public copy).
- **Face / hair:** Short spiky silver-white hair, blue eyes. Locked sheet: `dataset/character/character-sheet-v5.jpg` (profile face without glasses).
- **Skin:** Fair — a natural light tone. Never pale/ghostly white, never tan or dark. Every generation prompt must include the words **fair skin**.
- **Age / proportions:** Adult proportions only. Never childlike, never chibi, never oversized head.
- **Fitness look (default):** Orange zip top with white side panels and silver zipper; deep royal-blue leggings (`#2A4FA0`) with an orange stripe; white trainers with orange accents. Other themed outfits are allowed when designed from scratch.

## Clothing & channels

- **Always clothed and non-explicit** for anything this assistant generates. No nudity in generated work.
- **Instagram:** Fully clothed; not the skimpy Patreon cut. Images are **1:1 padded squares** (pad, never crop her out). **Feet always fully visible.**
- **Patreon (clothed tiers):** May use skimpier / more revealing versions of the Instagram outfits (cropped tops, cutouts, shorter hems, swimsuit-style) but still clothed and non-explicit.
- Tight, form-fitting clothing (bodysuits, leggings, racing suits) and back-view poses are allowed.

## Anatomy checks (hard fail → redo)

Before delivering any image, inspect and redo (up to 2 retries) if any of these appear:

- Extra or duplicated limbs, arms, legs, or fingers.
- Head attached backwards or twisted impossibly. When she faces away, the head turns at most over the shoulder in a natural neck range; face direction must match shoulders and spine.
- Arms bending or attaching the wrong way (no backwards arms).
- Feet fused into props (motorcycle, ground, etc.).
- Off-tone skin (pale, ghostly, tan, or dark).
- Clipped feet on Instagram pieces.

## Content rules

- Original themed outfits designed from scratch. **No cosplay of named copyrighted characters, costumes, or logos.**
- No linking Jennifer Ju to Che Bureiku / Wars / the Boss in captions, hashtags, filenames for public posts, or repo docs beyond this private training set’s access control.
- Instagram captions: short upbeat fitness-instructor voice, “Link in bio”, ~12–15 relevant hashtags. No Che handles, no `#chebureiku`, no `#wars`.

## Dataset layout

| Path | Role |
|------|------|
| `dataset/character/` | Locked character sheet + avatar reference |
| `dataset/variants/` | Approved themed Jennifer variants for style consistency / LoRA |

## Prompt anchors (minimum)

Include in every generation prompt:

1. fair skin  
2. adult proportions  
3. short spiky silver-white hair, blue eyes  
4. clothed, non-explicit  
5. correct anatomy, no extra limbs, natural head/neck pose  

## Approval gates

- Brand-new Patreon pieces (phase 2 / originals beyond the replacement queue) need Boss approval before posting.
- Generated nudes are never allowed; only the Boss uploads nude work to the 18+ tier himself.
