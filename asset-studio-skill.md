---
name: "asset-studio"
description: "Studio-grade posters, social posts, carousels, flyers, banners, menus, invites, signage and print pieces. Brief first, Figma-board north star, go wide on a contact sheet, then refine the pick with textured motifs and lint."
---

# Asset Studio (v5, 24 Nov 2026)

Work like a top digital creative studio: brief → north star → go wide → pick → refine → proof. The bundled brand pack supplies the anchors (colours, fonts, logo, facts). **This skill is self-contained and wins:** where it disagrees with any other brand skill, including `varanashi-farms` and the Hub's brand skill, follow this one. This skill supplies the taste, the system and the checks.

**The bar:** every piece has energy (contrast of scale, value, temperature and style), refinement (tone-on-tone surfaces, perfect alignment where alignment matters) and optimism (light, warmth, upward movement, a wink). It should look made by a person with an opinion, not assembled.

## Stance: a toolkit, not a rulebook
This skill **empowers, it does not limit.** Everything below is a thematic toolkit (moves, motifs, surfaces, type, checks) to reach for. If a brief wants something the kit doesn't have, make it. Only this skill's hard rules and the bundled pack's logo, facts and never-list are fixed.

**North star: the brand's Figma board.** For Varanashi: VOF Design, page 715-1036 (`figma.com/design/5fOQQhfjaNm9rB8zDjdJyj/VOF-Design?node-id=715-1036`). On the first piece of each working day, re-read the board (screenshot plus metadata), then write a dated **north-star note** in five lines: the moves that are new or most alive on the board, the colour moods, the type moods, the surfaces, and what to try today. The board is inspiration for **first drafts**: take the move and the mood, never the artwork. If the board can't be reached, say so and use the last note.

**Go wide first, then refine one.**
1. **Wide round:** 6–9 quick, different drafts across the output matrix and the board's moves (quiet → loud, photo-led → shape-led → type-led). Speed matters more than polish here. Copy can be rough and approximate, using the brief's words with placeholder lines where needed. Don't fact-check, fine-tune spacing or lint deeply at this stage. Run a fast lint only for contrast and focal-clear.
2. **Contact sheet:** send it with a one-line idea per tile. **The person picks** one, or a mix.
3. **Refine the pick:** lock copy against the facts ledger (§9), then run the full grid, lint and critique loop, and add twins for other formats.
Never polish before the pick, and never make anything permanent (commit, publish, propose) before the person approves the contact sheet.

## 0. What v3 learned (from the Tricho Plus banner and Slow Food carousel rounds; these override anything below)
1. **Make the idea visible.** The concept becomes the picture: "four guards" became four shapes standing beside the seedling, or four painted rings around it. Before any layout, write the one-line idea and how it will be *seen*, not just said.
2. **Never polish one safe direction three times.** If feedback says dull, flat or boring, go wide again with a new round spanning quiet → loud. Don't refine the old one. Every round includes **at least one photo-background direction**.
3. **Photographs as backgrounds** (the strongest results):
   - full bleed, with the subject kept clear (focal box)
   - text in the photo's quiet zone, on a **directional burn** anchored to that edge (≈ .75 at the edge → 0 by 35–45% across). A burn never covers the subject, and it never becomes a flat panel.
   - shapes sit in the space the subject leaves (beside it, below it), never on it
   - a photo can also be **ambience**: under an even veil (≈ .55 slate) as a dark textured ground for a big centred poster. Mark it `texture_only`.
   - draw burns **before** shapes, so shapes keep their own colour and contrast
   - originals must reach about 3600 px across a large print; flag low-resolution sources
4. **Lists become shapes.** No numbered lists (01 / 02 / 03), no bullet columns. Three or four points sit in cut-paper shapes of different anchor tints, with short lines and hand-set breaks.
5. **No sticker ovals or badge clutter.** No call-to-action lines unless the brief asks for one.
6. **Approved lockup files only.** The lockups in `brand-packs/varanashi/assets/lockups/` are outlined artwork (ST Nazm 800, ss01, bespoke kerning, baked 24 Nov 2026). Place one on a calm, dark or light area that passes 3:1, in one solid colour. **Never rebuild a lockup from live type**, and never re-kern or re-weight it. Pick the fill variant by how you are embedding it: the default and `-paper` files carry explicit fills and are safe anywhere; `-current.svg` inherits `color` and **only works inlined** — via `<img>` it renders black. Below 36px mark height use `varanashi-mark.svg` alone.
7. **Italics sparingly:** Sentient Italic is the only italic in the system. Latin names, and at most one accent word. Body and timing lines are roman.
8. **Textures are felt, not seen:** 10–30% (paper tooth 12–20%, paint 10–25%, wood 30–35%, shape gouache 14–18%, grain 7–10%). At full size they read as surface, not pattern.
9. **Proportion at scale:** large formats get generous, even rhythm (8 px multiples). Cards get padding ≥ 36 px and run to the margin. No element crowds an edge, and nothing is squeezed.
10. **Product names** sit on a textured wood strip (VOM, crates, stalls) in **Quicksand 700 caps**. The stamped, rugged quality comes from the surface treatment, not from stencilled letterforms — Big Shoulders Stencil is retired. Titles in ST Nazm, ss01 off.
11. **White balances the composition.** Shape-led slides sit on a generous cream ground (about 40–55% open) with a few big shapes, like the Matisse sun-over-wave card. Don't fill every corner.
12. **Complementary blue and orange.** Hues can move brighter than the anchors, within the board's range (cobalt to dusty blue, sunbreak to apricot). In a composition, one leads and the other answers, and both always appear together.
13. **Sets share elements.** In a carousel, deck or series, every page carries at least two shared things: a recurring motif fragment (a cut-paper sun or a wave), the colour pair, and a footer line in the same face and place.
14. **A plain photo needs a treatment, not just a burn.** Clip it (a print held by a binder clip on fabric or felt, with spaced typewriter notes around it), or draw on it (hand lettering in Caveat, doodled stars, sparkles, a swoosh arrow, one solid info box), or cut it into an arch or silhouette. Keep doodles off the subject. Helpers: `clip()`, `sparkle()`, `doodle_star()` in `motifs_v3.py`.

### 0.1 Premium references (from the brand's own Figma board, VOF Design · Output matrix)
Pick 1–2 per draft and name them in the genome. Re-read the board for today's north-star note (see Stance) before choosing. Take the move, never the artwork.
| Reference on the board | The move | Best for |
|---|---|---|
| "Respect the locals", "Refuse dystopia" | one-ink linocut: photo or plate cut to a single ink on paper or wood | print posters, VOM, manifestos |
| Dandelion field sheet | field-guide sheet: specimen, labelled leaders, small evidence photos, one ink | informative print and carousels |
| Orange sun over a blue wave; star with sun | cut-paper Matisse shapes with torn edges | hero slides, openers |
| "Soleil" rings | hand-painted concentric rings | generations, seasons, protection |
| Jungle over coral punch-outs | a colour field with photo punch-outs | two-line thoughts |
| "Pathways" | photo inside a silhouette or arch window | people, place, journeys of a product |
| "Farmers Market" | tall condensed serif, a script word, one lino fruit | market and event posters |
| Cipher pouches | ledger label: ruled rows, a specimen window | product, VOM, Terra |
| "and what if it all works out?" | hand-lettered optimism on a grainy sky | quotes, outreach |
| Ticking stripe, wavy rug, dappled light, grainy gradient | surfaces | grounds behind cards, never behind text |

## The loop
1. **Brief: ask everything first** (§1), in one round, before any research or drawing. Then place the piece on the **output matrix** (§1.1).
2. **Direction:** read `reference/reference.json` and `reference/MOVES.md` (§2). Pick the moves this piece will use. No live browsing unless the farm asks for it.
3. **Go wide** (§8): **8–10 fast comps**, each with a matrix coordinate, a genome, one or two named moves and a one-line idea. Rough copy, placeholder photographs, fast lint only. The round must cover all four quadrants.
4. **Contact sheet** with the one-line ideas. Send it. ⟶ **the person picks.**
5. **Lock copy** (§9) for the pick with `copycheck.py`. Verified copy is never re-checked.
6. **Refine** the pick in HTML on the grid (§3), with the motif kit (§5), textures (§6) and accents (§7).
7. **Lint** with `lint.js` (§10). Fix every fail. A warning may stay only with a stated reason.
8. **Critique** the render, the squint and the overlay against the rubric (§10). Fix the lowest score and repeat. **Nothing is shown to the farm until `lint.js` passes.**
9. **Produce** (§11) after approval, into the target named in the brief. Twins for other formats are re-proportioned, never scaled, and each is linted. Nothing becomes permanent before this step.

## 1. The brief (ask all of it, once)
Use one AskUserQuestion call (up to 4 questions, with options and the recommended one first). If more is needed, ask a second round straight after. Never start research before the answers come back, unless the person is away. Then use the defaults and say so.

| Ask | Shapes | Default |
|---|---|---|
| **Where will it be published?** Instagram feed / story / carousel, web, WhatsApp, print poster (A-size), flyer, shelf, signage, packaging | format, safe zones, bleed, viewing distance, min type size | Instagram 4:5 |
| **What is it for?** Sell (what, and how to buy), invite (to what), inform, showcase | the hero, the CTA, how much copy | Showcase, no CTA |
| **Languages?** English, Kannada, bilingual, other | fonts, line length, who supplies the translation | English |
| **How far can the copy move?** Exact words, or rework for energy using only verified facts | titles, notes, cuts | Rework, nothing new claimed |

Second round, only when it matters: the print method and paper (digital, offset, riso, screen print; kraft, uncoated); must-haves (logo, date, price, partner mark, QR); photos available and crop freedom; the deadline and how many directions.

### 1.1 The output matrix (decides the family before anything else)
Two axes: **print ↔ digital** and **informative ↔ graphic**.
| | Informative | Graphic |
|---|---|---|
| **Print** | house rules, map, menu, invite, info banner, field-guide sheet, ledger label | posters, stickers, linocut one-ink prints |
| **Digital** | IG content slides and carousels (ledger, field notes, punch-outs) | IG hero slides (cut-paper, big type, hand-lettered optimism) |
- Informative pieces: a strict grid, one or two inks, typewriter and serif, labelled leaders, small photos doing evidence work.
- Graphic pieces: one big shape or word, rough edges, grain, a single wink.
- A carousel alternates the two, opening and closing graphic.

### 1.2 Where the file is going (ask in the first round)

| Target | What it means for the build |
|---|---|
| **Canva** | Build through the Canva connector. Every element is its own editable object: no flattened artwork, no baked-in text. Photographs upload as assets, type stays live, the lockup goes in as SVG. |
| **PNG** | Rendered from HTML with Playwright at 2× the delivery size. |
| **SVG** | Vector only: live `<text>`, named `<g>` per element, no rasterised filters. Imports into any editor with its layers intact. |
| **Here in the chat** | A published artifact. Good for anything the farm will look at, share by link, or iterate on with me. |

Ask it in the first round with everything else. If the farm has no preference, the default is **here in the chat** for a single piece and **PNG** for anything going straight to a platform.

### 1.3 The assets gate (do not draw without these)

Before any comp is drawn the studio must hold:

- **The words.** Every line that will appear. Not a brief about the words — the words.
- **The photographs**, if the piece uses any, from the farm's own library. Never stock, never a board image, never generated.
- **Every fact checkable**: price, date, weight, place, contact. Anything unverified stays `[FACT NEEDED: …]` in the comp and blocks production.

If something is missing, ask for it and stop. A contact sheet built on invented copy wastes a round, because the layout that wins is the one that fits the real words.

### 1.4 Atomic modularity

Build every piece out of parts, never as one composed image.

- A diagram is shapes and live text, not a picture of a diagram.
- A photograph is a photograph; the type sits over it as type.
- A texture is a layer, not something baked into the artwork underneath.
- Anything repeated — a card, a tile, a row — is one component used many times, so a change lands everywhere at once.

This is what makes the Canva and SVG handovers worth anything: the farm can move a line of type without asking for a re-render.

## 2. The reference library (read this, not the internet)

The farm supplied three direction boards. They are distilled, once, into the pack. The studio reads the distillation on every job; it does not browse.

| File | What it gives |
|---|---|
| `reference/reference.json` | the output matrix and its four quadrants, eight colour behaviours, five texture families |
| `reference/MOVES.md` | the named move set: structure S1–S10, colour C1–C8, surface T1–T5, type Y1–Y5 |
| `reference/boards/` | the three boards, to look at when a move needs seeing |
| `reference/matrix/` | the four quadrant tiles, one per family |

**The rule that governs all of it.** A move is a verb, not a picture. The boards are other people's published work. Name the move, then invent the picture. If a draft is recognisable as a specific board piece, throw it away. No third-party logo, colour or photograph from a board ever reaches an output.

The three colours on the texture board (Dusty Blue `#9BB0C4`, Muted Olive Green `#ABB270`, Burnt Sienna `#A55426`) are studio reference for how colour behaves. They never enter a brand asset, `brand.json`, or the brand hub.

Live Pinterest or Cosmos rounds happen only when the farm asks for one, and what they find is added to `MOVES.md` rather than used once and lost.

## 3. Grid, alignment and intentional misalignment
- 12 columns (8 on A5 and smaller), margin ≈ 6.5% of the width, gutter 24, unit 8. Helpers `X(c)`, `XE(c)`, `SPAN(a,b)`. Every coordinate comes from them.
- Display type gets class `opt` (pulls its side-bearing so the ink touches the grid line) and cap-trim (`text-box: trim-both cap alphabetic`).
- Bottom-row items share the bottom margin. Side-by-side items share a cap line.
- **Intentional misalignment** is a tool, with rules:
  - at most 2 free elements per piece (a tilted photo stamp, a hand note, a roundel), marked `data-free`
  - each is rotated −3° to −14°, or crosses an edge or a frame by a clear amount (≥ 24px). A free element that is only nearly aligned looks like a mistake.
  - everything else is perfectly on the grid. The contrast between the two is what makes the free ones read as intended.

## 4. Colour: sun-faded anchors, keys and complements
The anchors are the common thread. For Varanashi they are **dusty blue** `#9BB6C4` (light `#CFDFE8`), **orange** (sunbreak `#E47444`, apricot, peach `#FFDAB6`, burnt sienna `#A55438`) and **muted olive** `#A6B270` (light `#DCE0BF`, deep `#4C5428`), on **warm paper** `#F4ECDD`, with gold `#F6C463` as the sun. Ink is a soft near-black `#1F2A36`, not a dark blue field.
- **Lead pairing: light blue + orange.** Olive is the third voice, for linocut and earth pieces.
- **Brighter pair, within the board's range:** cobalt `#2F64AE` with light `#BFD3E6`, and orange `#EC7432`, on cream `#FBF6EC`. They are always used together and are complementary.
- Each piece has one key (field and mass), one complement (spark) and paper. Rotate keys across a feed.
- Everything looks **sun-faded**: no pure saturation; colours sit on paper with grain.
- **Text:** ink on blue, olive, peach, paper or gold; paper on sienna or deep olive. Orange and sunbreak are shapes, never small text.
- Value plan first; check the squint.

## 5. Motifs and patterns (the kit in `motifs.py`)
| Motif | Reads as | Use |
|---|---|---|
| `pat_buti` | block-print repeat of the brand mark, hand-stamped jitter | full-bleed field, tone-on-tone |
| `pat_border` | textile border (*kinar*): buti row between rules | print, luxury, invitations |
| `pat_rays` | sunburst from a point | optimism; behind a rising photo |
| `pat_rings` | tree rings | an empty corner, heritage |
| `pat_rain` | monsoon dashes | dark fields, the season |
| `scallop_path` | postage stamp or seed-packet edge | photo frames, stickers |
| `roundel` | circular-text badge with the mark | seals, "grown and saved here" |

Rules:
- **One pattern per piece.** Behind type it is tone-on-tone only (value difference ≤ 8%). Two-colour patterns are fields of their own, with no text on them.
- The brand mark may be repeated, scaled and rotated in a pattern, never redrawn or distorted.
- Every motif must mean something on the farm (seasons, rings, monsoon, stamping, seed packets). No decoration for its own sake.
- Patterns stay off photos.

### 5.1 The v2 kit (`motifs_v2.py`): from the brand's own reference board
| Move | Use |
|---|---|
| `cut()` + `sun()`, `wave_band()`, `star()` | cut-paper shapes with torn, fibred edges (the Matisse card). Hero slides, posters. |
| `painted_rings()` | hand-painted concentric rings: tree rings, generations, seasons |
| `ticking()` | mattress-ticking stripe ground (blue + orange). Stays, rooms, house rules. |
| `wavy_stripes()` | the rug: blue, olive and paper waves. Behind cards, never behind text. |
| `grainy_gradient()` | blurred sky-to-sun gradient. Hand-lettered optimism. |
| `dappled()` | blurred leaf-light on gold or olive. Quotes, invitations. |
| `lino_photo()` | a photo turned into a one-ink linocut print (threshold + grain). Informative print, VOM, field sheets. |
| `punchout()` | a colour field with circular holes showing the photo. Two-line thoughts. |
| `sticker_oval()` | an oval sticker for names, dates and times |
Vector blobs, glossy gradients and clean geometric icons are out. Every shape should look cut, painted, stamped or printed.

### 5.2 Brand Hub motifs, with texture (`motifs_v3.py`, tested 5 Nov 2026 on Slow Food)
The Hub's own shapes always carry a treatment, either on the edge, in the surface, or as a mask. Never use them flat. Helpers: `dry_rings()`, `stamp()`, `window()`, `png_shape()`. The Hub files are `images/patterns/motif-1|2.png`, `icon-1…5.png` and `pattern-1…11.png` in the Brand Hub artifact.
| Motif | Treatment | Status |
|---|---|---|
| Tree rings | dry-brush rings, slightly uneven ink, in limewash deep with one sunbreak ring every fourth. Off an empty corner of cream, or around a round photo | **approved** |
| Drawn icons | lino stamp: ink speckle drop-out plus an offset second-colour disc. **The stroke itself must also read as printed:** uneven ink weight along the line, soft swelling at the ends, slight edge bleed and small gaps, as if pressed from a block. A clean vector line inside a speckle mask is not enough. The icon fills about 55–60% of its disc, with clear air all round; never edge to edge. Use only beside rows, numbers and steps (field sheets, labels), one or two per row | **approved** |
| Ornament (Hub motif-1 / motif-2) as a window | torn edge, with a photo showing through the shape, on generous cream | **approved** |
| Hub petal shapes (icon-1…5) | **visual delight, not containers.** Scatter one to three as torn, gouache-painted accents: a petal tucked behind a title, one peeking off an edge, a cluster near a photo corner. Never put text inside them, and never use them as list holders | **approved as accents** |
| Pattern inside big letters or one shape | only when done right: the repeat must be **dense enough to register as a pattern** at the letter's size, with at least 3–4 full repeats across each stroke. Scale the tile down until it reads as fabric, not as scattered motifs. Check it at thumbnail size. If it reads as sparse spots, drop it. Choose a tile that is dense by nature, such as a checker, lattice or weave (Hub pattern 11 works), rather than a spot pattern on a flat ground (pattern 1 doesn't) | conditional, and patterns stay pending until the family picks |
| Blind emboss | print only (a real emboss die or deboss). Not for screen work | print only |
| Seedling as large torn cut paper | cropped off a photo corner, colour chosen per photo | not yet reviewed |

## 6. Textures (no plain grounds, ever)
Every surface carries texture: fields, gradients, cards, tags and shapes. A flat fill or a bare gradient is a lint-level mistake.
- **Library** (`scripts/make_textures.py` → `assets/textures/`, transparent PNGs): `paint_horizontal`, `paint_diagonal`, `paint_scumble` (dry-brush strokes), `wood_plank`, `wood_knots` (grain with knots), `paper_tooth`.
- **Overlay:** `tex(name, colour, opacity, blend)` lays a texture in any colour. On light grounds, a darker tone of the ground with multiply at 20–55%. On dark grounds, a lighter tone with screen. Gradients take paint (soft-light) plus tooth. `surface(colour, *layers)` builds a textured ground in one call.
- **Inside shapes:** `cut_tex()` puts gouache strokes inside cut-paper shapes only.
- **Wood** is for tags, crates, signage, menus and VOM: real surfaces the farm has.
- **Grain** (`grain()`, 10–22%) still goes over everything last.
- Chromium blocks CSS masks from local files, so overlays are SVG alpha masks. Check a full-size crop: a texture you can't see at 100% isn't there.
- No grunge, torn-paper photos or stock textures.

### 6.1 Focal areas (shapes never sit on the subject)
- `scripts/focal.py photos/ photos_focal.json --sheet` finds each photo's subject (spectral-residual saliency, colour pop, centre prior). Check the sheet and fix wrong boxes by hand (`"manual": true`).
- Place photos with `photo()` (or the build's `ph()`): it writes the subject box onto the canvas as `data-focal`.
- Give every shape, sticker, pattern block and motif `data-avoid`. `lint.js` hides each one in turn and fails it if it changes more than 1.5% of any focal area. Text over a subject is a warning.
- Annotations that frame a subject (a dashed box, an arrow) are allowed: don't mark them `data-avoid`.
- A photo used purely as ambience (blurred, or behind punch-outs) is `texture_only=True` and has no focal.


**Pills, chips, tags and buttons.** A label in a rounded box is centred on its glyphs, not on its line box. The optical centre of a line of type sits above the line box's centre, so a box with equal padding reads as if the text has sunk. Give the bottom 1–2px more than the top, never the reverse. Measure it on the INK, not the line box: a line box reserves descender space that most labels never use, so a box centred on the line box leaves the glyphs sitting high or low. Caps-only labels sit highest of all. `lint.js` measures this as `pill-centring` using canvas ink metrics, skips labels that genuinely carry a descender, and fails anything off by more than 1.5px.

## 7. Type: the cast
Two faces carry the brand: **ST Nazm** for display and **Quicksand** for text. Everything else is a guest. At most **one guest face per piece**, on top of that pair.

**Three traps, all measured off the shipped files:**
- **Always state the weight.** Sentient defaults to 700, ST Nazm to 250, Quicksand to 300. An element with no stated weight silently renders at those.
- **CSS `font-weight` caps at 1000.** For ST Nazm above 1000 use `font-variation-settings:'wght' N`. A plain `font-weight:1200` is invalid and falls back without warning.
- **Cap heights differ by up to 1.7×.** Size by cap height, not font-size. Zyntra Doodle needs ×1.643 to sit level with Quicksand. The table is in `brand.json` under `type.cap_height`.

| Character | Face | Use |
|---|---|---|
| Logotype | **ST Nazm 800, ss01, outlined** | the lockup files only, never set live |
| Display, titles | **ST Nazm** 400–1200, **ss01 off** | ss01 is reserved for the logotype, and is what keeps the mark distinct from a headline in the same face |
| Quiet display | **Sentient** 300–500 | the softer title voice |
| Italic | **Sentient Italic** | the only italic; Latin names, one accent word |
| Text, English | **Quicksand** 500 | never below 500 in print: the rounded terminals fill in on absorbent stock |
| Label | **Quicksand** 700 caps, tracking .08–.16em | |
| Crates, signage, VOM | **Quicksand** 700 caps on a textured wood strip | the stamped quality is the surface, not the letterform |
| Text, Kannada | **Noto Sans Kannada** 400–500 | |
| Display, Kannada | **Noto Serif Kannada** 500–700 | |
| Stamps, roundels, numbers | **Zyntra Doodle** caps, ×1.643 | also the kids and outreach lane |
| Hand | **Caveat** 600–700 | notes, arrows, circling. *No file in the pack yet.* |
| Detail | **Courier Prime** | field-note captions, dates, specimen data |
| Personality, posters only | **Shrikhand**, **Unbounded**, **Gaegu** | where a poster wants more personality. Never on informative pieces, never as body |
| Decorative titles | **Elite Accents**, **Lucidity Expand**, **Bookmania** | graphic column of the matrix only, one per piece |

**Bilingual setting.** Kannada x-heights run larger than the Latin faces, so equal font-size looks unequal. Multiply the Latin size by **0.913** beside Quicksand, **0.921** beside Sentient, **0.905** beside ST Nazm. Kannada line-height is **≥ 1.62** — the measured minimum for Noto Serif Kannada to clear its descenders, not a rule of thumb. Allow 30% extra length for translations.

**Glyph gaps.** Quicksand carries ₹ · ½ ¼. **Courier Prime has no ₹** — patch it with a scoped `@font-face` serving only U+20B9 from Sentient (`brand.json` → `type.glyph_fallback`). No face in the cast has → ↑ or ✓: draw those, don't type them. Never fix a glyph gap by changing the copy. Test coverage with a two-fallback probe, never by comparing a glyph's width to notdef — in a monospaced face like Courier Prime every glyph has the same advance and that test always lies.

**Licensing.** `brand.json` → `type.licences` carries the status of every face. **Elite Accents and Zyntra Doodle are UNVERIFIED** — no licence text in either file — and must not go on public work until their EULAs are obtained. Lucidity Expand is unlicensed. Sentient requires crediting ITF in design or production credits.

Scale: display ÷ body ≥ 3.5. Notes are lowercase, ≥ 40px, rotated, and true.

## 8. Directions: the genome

Every direction on a contact sheet carries four things:

1. **A matrix coordinate** `(x, y)` in −1..+1. x −1 wholly print, +1 wholly digital; y +1 wholly informative, −1 wholly graphic.
2. **A genome.** **S** structure (S0 type only · S1 vertical split · S2 horizontal split · S3 window/stamp · S4 tiles · S5 field + object) · **L** lead · **V** volume V1 quiet → V3 loud · **K** colour key.
3. **One or two named moves** from `MOVES.md`, cited by code. No two directions in a round may cite the same pair.
4. **A one-line idea**, in plain words, that a person can choose between without seeing the comp.

**The round's contract:** 8–10 directions, at least two in each matrix quadrant and at least one within 0.25 of the origin. Pairwise different on at least three axes. All three colour keys used across the round. V1 to V3 represented.

Comps are **fast**: real layout and real proportions, flat fills instead of finished textures, grey boxes where photographs will go, rough copy. They exist to choose between, not to admire. Only the pick gets built properly.

After the pick, iterate one axis at a time so the farm can see what each change did.

## 9. Copy
- Titles: short, active, no full stop, no eyebrow above them, no "this, not that" construction. A title says one true thing.
- No AI or production labels on public pieces ("plate", "public domain", "illustration to come", "generated").
- Hand notes are copy too: they must be true and checkable ("that's us, in the middle" only where the house really is in the middle).
- CTAs say the real mechanism ("Message us to buy"). Never invent a URL, price or date. Leave `[FACT NEEDED: …]` instead.
- `copycheck.py copy.json --pack brand.json --ledger facts.json --clear` checks banned words, spellings, AI labels, full stops in titles and "not X" constructions, and every claim against the ledger. Verified, cleared copy is skipped next time. Unknown claims are batched into one question.
- Languages: never machine-write a script for publication you cannot verify. Leave `[KANNADA: approved line needed]` and ask. The one approved Kannada string so far is the lockup's: **ವಾರಣಾಶಿ ಸಾವಯವ ತೋಟ**. Allow 30% extra length for translations; Kannada body gets line-height ≥ 1.62 (measured, see §7).

## 10. Proof — a gate, not a report
`lint.js` runs before anything reaches the farm. Every **fail** is fixed, not reported. A **warn** may stand only with a stated reason. A comp round runs the fast subset; the pick runs all of it.

`node scripts/lint.js page.html --pack brand.json --out out --overlay` checks:
- fonts loaded
- contrast on the pixels
- ink edges on the grid (free elements exempt)
- margins and safe zones
- text overlaps (real lines for free notes)
- full stops in titles and eyebrows
- scale ratio and focal share
- colour activity per key
- squint and overlay images

**Rubric**, 1–5 each. Ship only at ≥ 4 everywhere:
1. Hero obvious in the squint
2. Energy: scale, value, temperature and style contrast
3. Refinement: tone-on-tone, spacing, a clean overlay
4. Colour: key and complement playing together
5. Motif meaning: does it belong to this farm?
6. Accent wit: is the note true and pointing at something real?
7. Legibility at viewing size (25% scale for feed, arm's length for print)
8. Brand truth and copy rules
9. Distinctness within the round

## 11. Formats and production

### Sizes
- **Digital:** post 1080×1350 (bottom 120 clear), story 1080×1920 (top 230 and bottom 330 clear), square 1080, carousel. Lockup on the first and last slides.
- **Print:** design at the A-size ratio in px (A3 preview 1240×1754, A5 874×1240). Export PDF with Playwright: `page.pdf({width:'297mm',height:'420mm',printBackground:true})`. Extend fields 3mm past the trim, keep type 5mm inside it, body ≥ 9pt equivalent. On kraft or riso, 2–3 inks.
- **Twins:** re-proportion the genome per format. Never scale or crop. Lint every twin.

### Targets

**Canva.** Build through the connector. The farm must be able to edit everything afterwards, so:
- text goes in as text, never as an image of text;
- the lockup goes in as SVG from `assets/lockups/`, never a PNG;
- photographs upload as assets and are placed, not flattened into a background;
- each repeated element is its own object, so one change does not mean a re-render.
Check the brand kit first (`list-brand-kits`) and use it where it matches the pack.

**PNG.** Playwright at 2× delivery size, `deviceScaleFactor: 2`. Check the render, not the HTML.

**SVG.** Live `<text>`, one named `<g>` per element, no rasterising filters, fonts either embedded or outlined — state which. Imports into any editor with layers intact.

**Here in the chat.** A published artifact. Self-contained HTML, fonts embedded, no external requests.

Figma has no connector in this session. If the farm asks for Figma, hand over the SVG, which imports with its layers, and say so.

### Handover
PNG or the live file, the HTML source, a PDF for print, the lint JSON, and one line on any open facts or approvals.

## Appendix · Files

| Path | What it is |
|---|---|
| `brand.json` | colours, type roster, logo construction, rules |
| `reference/reference.json` | output matrix, colour behaviours, texture families |
| `reference/MOVES.md` | the named move set |
| `reference/boards/` | the three direction boards |
| `reference/matrix/` | the four quadrant tiles |
| `assets/lockups/` | the eight lockups, three colour variants each |
| `assets/*.ttf`, `*.otf` | the type roster, self-hosted |
| `motifs.py` | the motif and pattern kit |
| `scripts/lint.js` | the design check |
| `copycheck.py` | copy and fact checking |
