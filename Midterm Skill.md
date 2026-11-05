---
name: fragmented-photo-collage
description: Transform reference images into photographic collages made of rectangular fragments of different sizes. Use when the user wants to reorganize an image through local cuts, offsets, overlaps, and repetition while keeping the main subject recognizable.
---

# Fragmented Photo Collage
Transform a complete image into a fragmented photographic collage. Introduce local changes while preserving the subject’s identity, overall pose, and main visual relationships.

## Inputs
Require:
- One reference image showing the main subject.

Optional:
- A text description specifying fragment density, displacement intensity, background treatment, or areas to preserve.

## Input Roles
- Use the reference image to identify the subject, overall pose, main silhouette, colors, and distinctive details.
- Use the text to adjust fragment quantity, size variation, rearrangement intensity, and background treatment.
- If no additional instructions are provided, preserve the original image’s main colors and background features, and use a moderate level of fragmentation.
- Use the reference image as the visual source for the collage. Do not introduce unrelated people, objects, or decorations.
- Treat the result as a generative collage reconstruction. Do not claim that every fragment is an exact crop of the original image’s pixels.

## Visual Rules
1. Subject recognizability. Preserve the subject’s identity, overall pose, main silhouette, and key color relationships. Allow local breaks and repetition, but keep the original subject recognizable.
2. Uneven rectangular fragments. Divide the image into rectangles of different sizes and aspect ratios. Combine large structural pieces, medium transitional pieces, and small detail pieces. Avoid uniform grids, jigsaw-shaped edges, and triangular fragments.
3. Controlled rearrangement. Shift, overlap, and slightly rotate fragments around their original positions. Allow local repetition of neighboring areas to create rhythm and layers. Preserve approximate spatial relationships rather than shuffling everything randomly.
4. Photographic collage quality. Preserve photographic texture, lighting, and color variation. Keep rectangular edges and seams visible. Allow small gaps or exposed background in selected areas. Do not blend the fragments into a seamless photograph or automatically turn the image into a painting or a three-dimensional mosaic.

## If / Then
- If the subject includes a face, reduce displacement around the eyes, nose, and mouth to preserve identity. Apply stronger changes to the hair, clothing, and background.
- If the subject is a full-body person or an animal, preserve the approximate relationships between the head, torso, and limbs. Allow local echoes, but avoid creating additional complete heads or limbs.
- If the subject includes flower stems, elongated objects, or architectural lines, preserve their main directions. Let those lines remain traceable across the fragments despite local interruptions.
- If the image becomes difficult to recognize, reduce displacement and repetition in key areas, and use larger fragments to support the subject’s structure.
- If the result looks like a grid placed over the original image, increase actual displacement, overlap, or local repetition in selected fragments so that the rearrangement is clearly visible.
- If the user requests subtle fragmentation, use fewer, larger fragments with smaller shifts. If the user requests strong fragmentation, increase the number of medium and small fragments and the displacement intensity while preserving the subject’s key identifying areas.

## Workflow
1. Inspect the reference image. Identify the subject, overall pose, main silhouette, and two or three essential features to preserve.
2. Read the text instructions. Determine fragment density, rearrangement intensity, background treatment, and areas that need protection.
3. Plan the cuts. Arrange uneven rectangular divisions according to the subject’s structure. Use large fragments to carry the main forms and small fragments to emphasize local details. Avoid mechanically dividing the image into equal parts.
4. Plan the rearrangement. Adjust fragment positions around the original spatial relationships. Select areas for displacement, overlap, and repetition while controlling changes to the overall silhouette.
5. Build the collage. Preserve photographic qualities and clear cut edges. Use seams, local shifts, and overlapping layers to create visual rhythm.
6. Check the subject. Confirm that identity, action, or object structure remains recognizable. Correct excessive fragmentation, unintended additions, or unnecessary repetition.
7. Generate and inspect. Output one finished collage by default. Do not automatically add a comparison with the original, text, borders, or watermarks. Refine the result using the quality check.

## Quality Check
- Are the subject’s identity, overall pose, and main silhouette still recognizable?
- Are the rectangular fragments varied in size and aspect ratio?
- Is there clearly visible displacement, overlap, or local repetition rather than just a grid overlay?
- Do the fragment changes create rhythm while preserving the main spatial relationships?
- Are the original photographic qualities and key colors preserved?
- Does the result avoid excessively fragmented faces, additional complete limbs, and unrelated new objects?
- Are the collage seams visible rather than smoothed into a seamless photograph?
