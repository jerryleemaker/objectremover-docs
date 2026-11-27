# Remove burned-in text, captions, and timestamps from video

Burned-in (hardcoded) text is part of the picture itself, so the only way to remove it is to repaint the pixels behind it. ObjectRemover does this with video inpainting: you describe the text or brush over it, confirm the mask, and download a clip with the area rebuilt.

Checked against [objectremover.video/blog/how-to-remove-text-from-video](https://objectremover.video/blog/how-to-remove-text-from-video) on November 27, 2026.

> **Rights rule:** Use this only on footage you own or are allowed to edit. Do not remove credits, copyright notices, watermarks, logos, or branding from someone else's work.

## Can ObjectRemover remove hardcoded subtitles?

Yes. ObjectRemover can remove hardcoded subtitles, captions, and other text overlays that were baked into a video you own. It tracks the text area across frames and fills it with reconstructed background. Results are best when the text is sharp and the background behind it is fairly stable.

## Are my subtitles burned in or soft?

Check this first, because soft subtitles do not need any AI.

| Kind | How to tell | What to do |
| --- | --- | --- |
| Burned-in (hardcoded) | No CC or subtitle switch in the player; the words are always in the picture | Inpaint the area (this guide) |
| Soft subtitles | The player has a CC or subtitle menu, or there is a `.srt`, `.vtt`, or sidecar track | Turn the track off or edit the caption file |

Play the file in an ordinary video player. If you can hide the words without changing the picture, they are soft, and you should edit the track instead of erasing pixels.

## What kinds of text can be removed?

- Burned-in captions and auto-generated subtitles from an export you made
- Date and time stamps from a camera or dashcam
- Name tags and lower thirds from your own interviews
- Labels such as "DRAFT" or "SAMPLE" on your own renders
- Stickers and emoji added in a phone editor
- Scrolling tickers and banners, when the text is legible and the motion is not too fast

Text that was filmed in the scene, like a shop sign or the label on a product, is also just pixels and can be handled the same way. For logos and channel bugs on your own masters, see the official [watermark guide](https://objectremover.video/blog/how-to-remove-watermark).

## How do I remove burned-in text step by step?

1. Upload an MP4 or MOV up to 100 MB (photos up to 20 MB) at [objectremover.video/upload](https://objectremover.video/upload). If the file is long, trim it to the part with the text.
2. Describe the text specifically: "remove the burned-in subtitles at the bottom", "delete the date stamp in the lower right", "erase the name tag". Or brush over it.
3. Check the mask on several frames, including the moments where the caption changes, and confirm.
4. Preview the result and download.

When there are several kinds of text, remove one per pass. For example, take out the name tag first, then run again for the timestamp.

## Is there a free way to remove text from a video?

You can try it free. The free option is a Low quality run for small-area jobs, and its output always includes an ObjectRemover tool watermark. Paid credits give Low, Standard, or Fine quality and downloads without the tool watermark, with the exact quote shown before the job. See [Credits, quality, and limits](../credits-and-limits.md) and [pricing](https://objectremover.video/pricing).

## When does text removal fail?

- Heavy compression around the letters, which leaves blocky halos
- Very fast camera motion or very small, fast scrolling type
- Text that fills most of the frame, which leaves little real background to rebuild
- Soft subtitle tracks, which are a player setting and not an inpainting problem

See [What works and what fails](../what-fails.md) for more.

## Should I blur, crop, or inpaint?

A blur box is quick but stays visible and can flicker as the image moves. Cropping removes the text by cutting off part of your framing. Inpainting rebuilds the background so the area looks like ordinary footage, and it needs a clear selection and a reasonable source file. A longer comparison is in [Blur, crop, or inpaint?](../comparisons.md).

## Related

- [Remove objects](remove-objects.md)
- [Premiere Pro plugin](../premiere-pro-plugin.md), for removing text without leaving your timeline
- Official: [How to remove burned-in text from video](https://objectremover.video/blog/how-to-remove-text-from-video)
