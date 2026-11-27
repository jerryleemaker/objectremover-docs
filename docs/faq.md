# ObjectRemover FAQ

ObjectRemover ([objectremover.video](https://objectremover.video/)) is a browser tool, with a Premiere Pro plugin, that removes or extracts objects, people, and burned-in text from videos and photos you own or may edit. These answers reflect the live site as of November 27, 2026.

## What is ObjectRemover?

ObjectRemover is an online AI video object remover. You upload a video or photo, describe what to remove or brush over it, confirm the mask, and download a version where that area is rebuilt with background that stays consistent across frames. It was founded by Jerry Lee. The official site is objectremover.video; objectremover.com is a different site.

## Is ObjectRemover free?

You can start free, with no signup and no credit card. Free output is Low quality, suited to small-area jobs, and always includes an ObjectRemover tool watermark. Standard and Fine quality and downloads without the tool watermark use paid credits. See [Credits, quality, and limits](credits-and-limits.md).

## Does ObjectRemover need a subscription?

No. Credits are bought in packs, from $3.87 (Custom, 30 credits) to $99.99 (Enterprise, 1500 credits), and stay valid for 12 months. Each job shows an exact credit quote before it starts. Prices are on the [pricing page](https://objectremover.video/pricing).

## What can it remove?

Objects (props, logos on your own items, mics, signs, clutter), people (passers-by, photobombers), burned-in text (hardcoded captions, timestamps, name tags, stickers, emoji), and unwanted elements in AI-generated clips. See the [use-case guides](../README.md#guides).

## Can I remove an object by typing what I want gone?

Yes. Type a short description such as "remove the person in the white shirt", confirm the mask, then process. You can also brush over the object on the preview. Both paths use the same confirm-first flow. More wording ideas are on the [prompt examples page](https://objectremover.video/help/examples).

## Can ObjectRemover remove hardcoded subtitles?

Yes, for subtitles burned into a video you own or may edit. If your player has a CC switch or you have an `.srt` file, the subtitles are soft and you can turn them off without any AI. See [Remove burned-in text](use-cases/remove-burned-in-text.md).

## Can it remove a watermark?

It can remove a logo or watermark from footage you own or are allowed to edit, such as your own channel bug on a master file. It should not be used to strip marks from videos you do not control. This is separate from the ObjectRemover tool watermark on free output, which is removed by paying credits for a clean copy.

## What file types and sizes are supported?

Video: MP4 and MOV up to 100 MB, up to 60 fps. Photos: JPG, PNG, and WebP up to 20 MB. Upload from your device. There is no paste-URL option.

## Does it work on photos?

Yes. Photos use the same flow: select, confirm the mask, process, download. Extraction gives a transparent PNG.

## Can I extract a subject instead of removing it?

Yes. Extraction exports the selected subject as video with an alpha channel, or a transparent PNG for photos, for compositing in CapCut, Premiere Pro, DaVinci Resolve, or other editors.

## Do I need Premiere, After Effects, or CapCut?

No. The web app works on its own in the browser. If you edit in Premiere Pro 25.6 or newer, the [Premiere Pro plugin](premiere-pro-plugin.md) brings the same flow into your timeline.

## Are my uploads used to train AI models?

No. ObjectRemover states that uploads and results are never used to train or improve its AI models. Paid outputs are kept about 7 days and free watermarked previews about 1 day. See [Rights and privacy](rights-and-privacy.md).

## What technology does it use?

The site states it is built on Meta's Segment Anything Model (SAM 3) and other video inpainting models, and that ObjectRemover is an independent service not affiliated with or endorsed by Meta.

## Does ObjectRemover publish success rates?

No. Results depend on the footage. Confirm the mask and check the preview before you pay. [What works and what fails](what-fails.md) lists common problem cases.

## How does it compare with CapCut, Runway, or Adobe?

See [Comparisons](comparisons.md). That page quotes each vendor's own documentation with access dates.

## How do I contact ObjectRemover?

Email support@objectremover.video. The founder is Jerry Lee ([@jerrylee_maker](https://x.com/jerrylee_maker) on X).
