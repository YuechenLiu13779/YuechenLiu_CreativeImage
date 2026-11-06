---
name: fragmented-photo-collage
description: Create flat vintage photographic weaving collages from one or more reference images. Use when the user wants photographs interlaced into a new graphic composition with subject-responsive silhouettes, varied strips, and subtle printed texture.
---

# Fragmented Photo Collage
Create an original photographic weaving composition from the supplied images. Apply these defaults even when the user simply says “把这两张图编织在一起”. Keep the visual language consistent while redesigning the composition for each input. Use image generation/editing tools with the actual supplied references.

## Inputs
Require one or more source images; prefer two for interweaving different subjects. Accept optional text and style references. Do not require detailed composition instructions.

## Input Roles
- Extract each source subject’s distinctive features, gesture, contour, directional movement, and useful colors.
- Treat source photographs as image material to crop and interlace. Allow changes in scale, position, and local proportions while preserving recognizable identity.
- Use style references for visual principles, not as fixed layouts. Copy a particular composition only when explicitly requested.
- Distinguish style references from source images. Do not introduce their subjects into the result.
- Treat the result as generative reconstruction; do not claim exact pixel-preserving crops or mathematically guaranteed randomness.

## Required Weaving Structure
Treat visible photo-strip interlacing as the primary effect, ahead of silhouette fusion or decorative layout. A silhouette filled with another photograph, double exposure, parallel sliced bands, feather-shaped photo inlays, and patchwork alone do not satisfy this skill.

- Construct TWO locally crossing families of continuous strips: use source A for one family and source B for the other. Default to roughly perpendicular directions within each woven region. The whole woven region may rotate or change direction with the composition.
- At successive crossings, alternate which source is visible: A-over-B, then B-over-A. Reverse the alternation in the neighboring row. Make enough consecutive crossings in both directions to read unmistakably as woven photographs, not isolated decorative squares.
- Keep image content traceable along each strip, interrupted where the other family passes over it. Adjacent visible cells must carry different source imagery rather than a checkerboard texture printed over a seamless picture.
- Make substantial, contiguous woven passages a dominant visual component of the integrated subject, with contrasting quieter anchor areas. Do not reduce weaving to a tiny accent. Use irregular boundaries and varied strip widths to avoid a uniform full-canvas grid.
- Follow the subject through cluster placement, overall movement, outer contour, and staggered strip endings. Do NOT interpret “follow the subject” as making every strip parallel to feathers, fur, petals, or the body's long axis; retain crossing directions inside each cluster.
- Show photographic cut-and-reassembly seams and strips emerging from woven passages. Keep crossings nearly flat: use alternating visibility as the main cue, with only faint, narrow contact shading at selected crossings; avoid visible thickness or raised relief.

## Visual Rules
1. **Subject-responsive composition.** Form one newly designed graphic whole from the source images. Choose placement, relative scale, overlap, silhouette, and whitespace from the subjects’ contours and gestures. Interlock their forms through photographic strips rather than simply placing two intact pictures side by side or creating a seamless biological hybrid. Retain enough identifying anchors to recognize both sources. Remove source backgrounds by default; selectively incorporate useful environmental fragments. Use the consistent pale neutral gray-beige paper ground specified below.
2. **Genuine graphic interweaving.** Alternate visible portions of strips from the different images at crossings to imply over-under weaving. Mix narrow and wider strips, small woven cells, longer uninterrupted passages, and a few intact anchors. Build substantial but uneven woven clusters where the images meet and where contours suggest a transition. Let strips extend, taper through staggered ends, or stop along the silhouette. Avoid uniform checkerboards across the canvas, arbitrary rectangular overlays, and stacks of photo cards. Fragment facial areas too, while preserving readability. Use each depicted source region once; avoid cloned fragments and unintended duplicated eyes, noses, mouths, tongues, or limbs. Different source subjects may each retain their own features when the composition calls for it.
3. **Flat vintage photographic print.** Keep photographic details with matte, slightly softened contrast, restrained saturation, and subtle fine ink grain or gentle print wear. Preserve neutral whites and legible dark tones. Derive the palette from the actual sources; do not apply a fixed sage/terracotta palette. Convey age through printed color and fine grain rather than a yellow/sepia wash, heavy distress, or embossed texture. Render all fragments on one plane. Convey weaving primarily through alternating image visibility. Allow barely perceptible, soft, low-contrast contact shading immediately at selected strip intersections to gently articulate interlacing. Keep this subordinate to the flat graphic design. Omit broad cast shadows, bevels, thickness, curls, glossy highlights, and basket-like relief.
4. **Controlled variation.** Invent a composition for each new generation. Vary which subject leads, arrangement, contour, weave locations, strip directions and lengths, density, and palette as the inputs allow. Let geometry follow the subjects; do not automatically make everything diagonal, split portraits left/right, put weaving at forehead and lower-left cheek, or add a circle and arc. Include a small supporting vocabulary of flat colored geometric shapes by default, unless the user requests photographs only. Integrate these with the photographic silhouette and selected strip ends; choose their shapes, placement and colors for the current inputs. Combine dense, transitional, and quiet areas with purposeful asymmetry. Preserve an approved layout when the user requests only a local or color edit.

## Standard Postcard Format
- Output every finished collage in one of two consistent postcard proportions: landscape 3:2 or portrait 2:3. Choose orientation from the main subject's silhouette and the relationship between the sources, unless the user specifies it. Use landscape for broad or horizontally extended compositions and portrait for tall or upright compositions. Do not inherit arbitrary source-image aspect ratios.
- Target 1536 × 1024 pixels for landscape and 1024 × 1536 pixels for portrait when supported by the image-generation tool. If exact dimensions are unavailable, use its supported output matching the target aspect ratio as closely as possible; do not claim unsupported pixel dimensions. These are digital canvas proportions, not a guarantee of print size or DPI.
- Preserve each source's natural proportions with uniform scaling. Never stretch, squeeze, flatten, or widen a photograph or its subject merely to fit the postcard canvas. Interpret “do not compress” as avoiding geometric distortion, not as forbidding proportional resizing.
- For unusually wide or tall sources, crop nonessential background, empty margins, and peripheral distractions first. Preserve the main subject, identifying features, and meaningful gesture. Do not cut off essential heads, wings, limbs, or landmark structure just to fill the canvas.
- If fitting the subject would require damaging crops, reduce its scale and extend the standard pale neutral gray-beige paper ground instead. Use negative space, colored shapes, and the handwritten caption to balance the postcard. Do not force edge-to-edge photographic coverage.
- Keep the complete collage and caption comfortably within the canvas, with consistent breathing room. Maintain these proportions across the series while allowing input-responsive composition inside the frame.

## Standard Background
Use one consistent very light neutral gray-beige paper ground, approximately sRGB #F0EAE4 (RGB 240, 234, 228). Match a pale ivory-gray uncoated paper, with only a trace of beige warmth. Keep the base light and nearly neutral: explicitly avoid pink, peach, salmon, reddish beige, orange, tan, brown kraft, and yellow/sepia undertones. Do not interpret the vintage style as a warm color wash. If a reference background is supplied, match its blank areas rather than its warm photographic colors.

Apply only very fine, low-contrast, evenly distributed neutral paper grain. Do not darken or redden the ground with texture, stains, gradients, edge vignettes, or lighting. Use the same base throughout exposed margins, negative space, and gaps between strips, independent of the source palette and colored shapes. Keep the photos' own colors and natural whites intact; do not apply global color correction to make them beige. Keep handwriting legible on this ground. Treat the hex code as a generation target, not a guarantee of exact pixels. Override only when explicitly requested.

## Consistent Series Details
Keep these finishing details consistent across changing subjects and layouts:

- **Color shapes as participants.** Balance photography with a few matte solid-color shapes, such as partial rounded forms, cropped polygons, blocks, or short bands. Let some sit behind the silhouette and some connect to the strip system. Use restrained colors sampled or harmonized from the current source images. Do not reuse a fixed circle/arc arrangement or fixed palette, and do not let shapes overpower the subjects.
- **Fine, selective weaving.** Prefer fine-to-medium strips and relatively small cells compared with the subject. Maintain readable consecutive crossings within irregular woven passages, balanced against larger coherent photographic areas. Keep the weaving visually important without maximizing cut count or spreading a coarse checkerboard over the whole subject. Avoid excessive long protruding bars and wholesale shredding of the silhouette; reserve a few varied strip extensions for rhythm.
- **Subtle contact shading.** Give selected crossings only a trace of soft local shading, sufficient to distinguish the interlacing at close view. Keep the overall image visually flat, without deep gaps, lifted tiles, or directional drop shadows.
- **Neutral vintage print.** Use matte, gently faded photographic color and fine print grain consistently across photos and colored shapes. Preserve natural photographic whites and tonal clarity against the standard pale neutral gray-beige ground; do not turn vintage styling into a yellow filter or heavy surface ornament.

## Automatic Handwritten English Caption
- Add one short English handwritten caption by default, derived from the content of the current source images. Let it name the main subjects, their relationship, or a reliably identified place. Do not reuse a fixed phrase across different inputs.
- Prefer a concise subject/place label or a brief evocative phrase grounded in both sources. For an identified place, use a structure such as “Manhattan Bridge, New York, USA”; for subjects without a known place, use a label such as “Cat & Dog” or another short content-specific phrase. Do not force every source into a long literal inventory.
- Use natural, legible, lightly cursive handwriting, like a restrained handwritten note on a vintage editorial print. Use a thin muted charcoal or a dark color harmonized with the artwork. Keep text subordinate to the collage, with enough size and contrast to read.
- Place the caption in an available area of negative space, clear of subjects, woven details, and colored shapes. Choose its position, line breaks, and gentle baseline variation for the current layout; do not always use the same corner. Preserve comfortable margins and visual balance.
- Identify landmarks conservatively. Do not infer a city or country from a generic scene, animal, or style. If a specific identification is uncertain, use a general description rather than an invented location. Keep user-supplied place information distinct from visual inference; briefly flag an apparent mismatch before generation rather than silently labeling a different landmark.
- Correct obvious English spelling slips such as “New Yotk” to “New York”, unless exact quoted lettering is explicitly required. Use standard English punctuation. Include the exact final caption in the generation instructions and check the rendered spelling and legibility afterward.
- If the user provides wording, use that wording subject to the identification and spelling rules above. If the user requests no text, omit the caption. Do not add other headings, logos, watermarks, dates, or explanatory paragraphs.

## If / Then
- If subjects have complementary contours, align or nest those contours and weave their meeting areas into a shared silhouette.
- If subjects differ greatly in scale or orientation, adjust crops and scale to establish a clear relationship; do not force matching faces or a central split.
- If a subject has curved, slanting, branching, or elongated forms, let cluster placement, outer boundaries, and strip terminations respond to those forms. Maintain two crossing strip families inside each cluster; never replace weaving with parallel feather-like slices.
- If only one source is supplied, weave distinct, nonduplicated regions of that image, optionally using its environment; do not invent a second subject.
- If the result looks mechanical, vary cluster boundaries, strip widths and lengths, and the balance between woven and intact passages. Keep a few coherent runs so it still reads as weaving.
- If the sources look merely pasted beside each other, extend their strips across the transition to create alternating image visibility and a newly integrated shape.
- If identity becomes unclear, restore selected identifying anchors and reduce local disruption without restoring both whole photographs.
- If the image looks dimensional, reduce crossing shading to a barely visible local trace; remove broad shadows, edge highlights, and texture relief. If it looks yellowed, restore neutral whites while keeping muted source-derived colors and fine print grain.
- If generating a new variation, redesign spatial structure as well as surface details. If editing an approved image, preserve all aspects outside the requested change.

## Workflow
1. Inspect every source and style reference. Identify each subject’s silhouette, gesture, distinctive features, dominant colors, and possible relationships to the other sources.
2. Choose the standard landscape 3:2 or portrait 2:3 postcard canvas. Plan proportional scaling and any nonessential background crops while protecting the subjects. Plan a new composition internally. Choose leading and supporting forms, crop and scale, a combined outer contour, whitespace, and dense versus quiet areas. Base these choices on the current images, not a previous output.
3. Plan interweaving. Choose where source strips cross and alternate visibility, how their directions follow the forms, and where longer runs or intact anchors remain. Avoid duplicating source content.
4. Generate one finished image using the actual sources and all default rules. Use a short natural-language request as sufficient authorization to make composition decisions; do not ask the user to specify every visual parameter.
5. Inspect the result. First locate a contiguous passage with several successive alternating crossings in both directions. If no such passage exists, the weaving requirement has failed: revise the generation to build two crossing source-strip families before delivering. Reject silhouette photo-fill and parallel sliced montages even when attractive. Then correct obvious duplicate features, superficial grid overlays, excessive physical shadows, dominant yellow cast, or failure to integrate the sources. Do not claim inspection or verification that was not performed. Include the short handwritten English caption according to the caption rules; check its content, spelling, placement, and legibility. Output the artwork without additional explanatory text inside the image, borders, watermarks, or comparison panels.

## Quality Check
- Do the supplied subjects remain recognizable within one newly composed graphic whole?
- Can two crossing strip families be traced through substantial woven passages, with alternating source visibility over several rows and columns? Reject photo-filled silhouettes, parallel bands, feather inlays, double exposure, and decorative checkerboard overlays.
- Are weaving density, strip lengths, and quiet areas varied deliberately?
- Does the layout respond to these subjects instead of repeating an example’s arrangement, weave positions, or colors?
- Are there no cloned fragments or unintended duplicate anatomical features?
- Is the surface flat and matte, with neutral whites, restrained source-derived color, and subtle vintage print grain?
- Does the result avoid raised weave, pronounced shadows, a yellow filter, and coarse embossed texture?
- Do restrained colored shapes participate in the composition, with input-specific shapes and palette?
- Are woven cells fine enough and balanced with coherent photographic areas, without excessive cutting or sprawling bars?
- Is any crossing shading barely visible and local, preserving the predominantly flat appearance?
- Does the single English handwritten caption use exactly “Landmark Name, Country”, without animal names, combined-subject labels, cities, or poetic wording, unless explicitly overridden by the user?
- Does every exposed background area share the standard very light neutral gray-beige paper ground (approximately #F0EAE4), with subtle grain and no global yellow cast?
- Is the final canvas a consistent landscape 3:2 or portrait 2:3 postcard, with natural subject proportions, protected essential features, and comfortable margins?
- Is the background free of pink, peach, red, or orange tint, including its grain and edges? Keep it near #F0EAE4 rather than darker reddish beige.
