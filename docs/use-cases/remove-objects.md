# Remove objects from video

To remove an object from a video with ObjectRemover, upload the clip, describe the object or brush over it, confirm the mask, and download the result. The tool tracks the object across frames and fills the area with a rebuilt background.

Checked against [objectremover.video/features](https://objectremover.video/features) and the [object removal guide](https://objectremover.video/blog/how-to-remove-objects-from-video) on November 27, 2026.

> **Rights rule:** Use this only on footage you own or are allowed to edit. Do not use it to strip credits, watermarks, logos, or branding that belong to someone else.

## Can ObjectRemover remove an object from a moving video?

Yes. After you confirm the mask, ObjectRemover follows the object through the clip and inpaints the region it covered, so the background keeps moving with the shot. Results are best when the camera moves at a moderate speed and the object does not cover most of the frame.

## What kinds of objects does it handle?

Typical targets on creator footage include:

- A logo on a prop or shirt in your own shoot
- A microphone, light stand, or cable that slipped into frame
- A sign, bag, chair, or other clutter in the background
- A car or animal crossing behind your subject
- Your own outdated branding on an old export you are re-editing
- Cursors and notifications in a screen recording you made

Photos work the same way. JPG, PNG, and WebP files up to 20 MB go through the same select, confirm, and download flow.

## How do I remove an object step by step?

1. Go to [objectremover.video/upload](https://objectremover.video/upload) and add an MP4 or MOV up to 100 MB.
2. Type a short description such as "remove the yellow toy" or "erase the logo on the mug". If the object is hard to name, brush over it on the preview instead.
3. Review the mask. Make sure it covers the full object and, where you want them gone, its shadow or reflection.
4. Confirm, run the job, and preview the result through the motion.
5. Download and finish the edit in CapCut, Premiere Pro, DaVinci Resolve, or any editor you use.

## Can I remove several objects at once?

Yes. Naming a category, for example "cars" or "penguins", selects every instance the tool finds. You can also list different things in one request, such as "the person and the logo". Multi-object removal and extraction was announced on the ObjectRemover blog on June 5, 2026. For large or unrelated targets, separate passes are often easier to check.

## Should I describe it or brush it?

Describe it when the object has a clear name and look: "the red umbrella", "the white van". Brush it when it blends into similar colors, has no obvious name, or sits in a crowded frame. Descriptions that use color, clothing, or object type tend to work better than ones that rely only on "left" or "right". The [brush or type guide](https://objectremover.video/blog/brush-or-type-remove-objects-from-video) shows both paths.

## Can I extract the object instead of deleting it?

Yes. The same selection can be used to extract the subject as video with an alpha channel, or as a transparent PNG for photos. This is useful for compositing the subject over a new background.

## Tips for a cleaner result

- Upload the least compressed version of the file you have.
- Trim to the seconds where the object appears. You spend fewer credits and the preview is faster to review.
- Include shadows and reflections in the mask if they should disappear too.
- Large objects that hide most of your subject leave little real background to rebuild. See [What works and what fails](../what-fails.md).

## Does it cost anything?

You can start with a free Low quality run, which always carries an ObjectRemover tool watermark and suits small-area jobs. Credits give Low, Standard, or Fine quality without the tool watermark, and you see the quote before the job runs. See [Credits, quality, and limits](../credits-and-limits.md).

## Related

- [Remove people from video](remove-people.md)
- [Remove burned-in text](remove-burned-in-text.md)
- [Blur, crop, or inpaint?](../comparisons.md)
- Official: [Remove objects from video guide](https://objectremover.video/blog/how-to-remove-objects-from-video)
