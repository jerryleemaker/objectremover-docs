# Remove people from video

ObjectRemover removes a person from a video when you describe them (for example "the man in the blue jacket walking behind me") or brush over them, confirm the mask, and download. It tracks the person through the clip and rebuilds the background where they were.

Checked against [objectremover.video/blog/remove-people-from-video](https://objectremover.video/blog/remove-people-from-video) and the [homepage FAQ](https://objectremover.video/) on November 27, 2026.

> **Rights rule:** Use this only on footage you own or are allowed to edit. Do not use it to strip credits, watermarks, or branding from someone else's work, and do not use it to misrepresent who was present at a real event.

## Can AI remove a person from a video?

Yes. ObjectRemover finds the person you point to, follows them across frames, and fills the gap with background that moves with the shot. There is no frame-by-frame rotoscoping, and the free tier lets you check the fill on your own clip before paying.

## Who is this for?

Common cases from creators:

- A passer-by who walked through a travel shot
- A photobomber behind you in a talking-head clip
- A stranger near a landmark in a vacation video
- Crew or a bystander at the edge of event footage
- An extra person in an AI-generated clip (see [AI-generated video cleanup](ai-generated-video-cleanup.md))

## How do I erase someone from a video?

1. Upload an MP4 or MOV up to 100 MB at [objectremover.video/upload](https://objectremover.video/upload).
2. Describe the person. Mention what makes them easy to spot: clothing color, what they carry, how they move. "The woman in the red coat who walks in from the right" is easier to resolve than "the person".
3. Or brush over them on the preview if describing them is awkward.
4. Check the mask through the clip and confirm.
5. Preview the result and download.

## How do I pick the right person in a crowded frame?

Add details. Clothing and color usually separate people better than position words alone, because people move around the frame. If you want everyone in the background gone, say so: "remove the people in the far background only". Asking for "people" selects each person the tool finds, which is useful in crowds and risky if your main subject is also a person, so check the mask before you confirm.

## Can I remove people from video for free?

Yes, to try. The free option is a Low quality run for small-area jobs, and its output always includes an ObjectRemover tool watermark. A clean download, or Standard and Fine quality, needs credits. You see the credit quote before a paid job starts, and there is no subscription. See [Credits, quality, and limits](../credits-and-limits.md) and [pricing](https://objectremover.video/pricing).

## When does person removal struggle?

- **The person covers most of the frame.** There is little real background to rebuild.
- **Fast camera motion or heavy motion blur.** Tracking and fill both get harder.
- **The person overlaps your subject.** Hands on shoulders, hugs, or crossing directly in front of the subject leave ambiguous edges.
- **Heavily compressed uploads.** Blocky source footage shows up in the fill.

Trimming to the seconds where the person appears often helps, and it lowers the credit cost. More cases are in [What works and what fails](../what-fails.md).

## Does this work on photos?

Yes. JPG, PNG, and WebP up to 20 MB use the same flow, and the mask is aligned to the full-resolution image.

## Can I keep the person and remove the background instead?

Use extraction. The same selection can export the person as video with an alpha channel, or a transparent PNG for stills, so you can place them on a new background in your editor.

## Related

- [Remove objects](remove-objects.md)
- [Getting started](../getting-started.md)
- Official: [Remove people from video](https://objectremover.video/blog/remove-people-from-video)
