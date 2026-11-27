# What works and what fails

ObjectRemover works best on a reasonably clean source where the target is clearly visible and the background behind it is visible in nearby frames. It struggles when the source is heavily compressed, motion is very fast, the target is tiny or covers most of the frame, or the problem is not in the pixels at all.

This page describes typical behavior as of November 2026. ObjectRemover does not publish success rates, so always confirm the mask and check the preview before paying for a clean export. Related official guidance: [how to remove burned-in text](https://objectremover.video/blog/how-to-remove-text-from-video) and [remove objects from AI-generated video](https://objectremover.video/blog/remove-objects-from-ai-generated-video).

## What kind of footage gives the best results?

- The target is sharp and contrasts with its background.
- The camera is steady or moves at a moderate pace.
- The background behind the target shows up in other frames, so there is real detail to borrow.
- The target covers a small to medium part of the frame.
- The upload is the cleanest copy available, close to the original export.

## When does removal usually fail?

### Heavy compression

Footage that has been downloaded, re-uploaded, and re-encoded several times has blocky edges, especially around text and fine detail. The fill then has to match blocks and noise, and halos can remain around where the object was. **Tip:** upload the original or the least compressed export you have.

### Fast motion and motion blur

Very fast pans, shaky handheld footage, and fast-moving targets smear across frames. Tracking becomes less reliable and the fill can flicker. **Tip:** trim to the part of the clip you need, and pick a steadier take if you have one.

### Tiny or fast-scrolling text

Small type and quick tickers have thin strokes that compression blurs into the background. The mask may miss parts of letters. **Tip:** describe the text precisely ("the scrolling banner at the bottom"), check the mask on several frames, and brush over missed areas.

### Text that fills most of the frame

When a title card or large caption covers most of the picture, there is very little real background to rebuild from. The result is a large invented area that may not look like the rest of the shot. **Tip:** cut the title card out in your editor instead.

### Large objects covering the subject

If the object you want gone hides a big part of your main subject, for example a person standing directly in front of the speaker, the tool has to invent what was hidden. Faces, hands, and text behind the object are especially hard to rebuild convincingly. **Tip:** use a different take, or remove only the part that does not overlap the subject.

### Soft subtitles are not an inpainting problem

If the player has a CC or subtitle switch, or the captions live in a `.srt` or `.vtt` file, the words are not in the picture. Turn the subtitle track off or edit the caption file. Running inpainting on those files cannot help, because there is nothing burned into the frames to remove.

### Shadows and reflections left behind

A mask that covers only the object can leave its shadow on the floor or its reflection in a window. **Tip:** include shadows and reflections in the selection before you confirm.

### Similar-looking targets

In a crowded frame, a short description like "remove the person" can select more people than you meant, including your subject. **Tip:** add clothing, color, or timing details, or brush over the exact target, then check the mask.

## Can it recover what was really behind an object?

No tool can know what was hidden behind an object in every frame. ObjectRemover rebuilds a plausible background from the surrounding area and from frames where that area is visible. Do not rely on the result for documents, evidence, or anything where the hidden detail must be factual. Keep your original file.

## What should I do when a result looks wrong?

1. Recheck the mask. Most problems come from a mask that is too tight or misses frames.
2. Trim the clip to the seconds where the target appears.
3. Split complex jobs into one target per pass.
4. Try a cleaner source file.
5. If the target covers most of the frame, consider a cut or a different take instead.

You can test on the free Low tier, which always includes a tool watermark, before spending credits on Standard or Fine. See [Credits, quality, and limits](credits-and-limits.md).

## Related

- [Getting started](getting-started.md)
- [Blur, crop, or inpaint?](comparisons.md)
- [FAQ](faq.md)
