# Getting started with ObjectRemover

ObjectRemover is a browser tool that removes objects, people, and burned-in text from videos and photos you own or are allowed to edit. You upload a file, select the target by describing it or brushing over it, confirm the mask, then preview and download the result.

Facts on this page were checked against [objectremover.video](https://objectremover.video/) and [objectremover.video/upload](https://objectremover.video/upload) on November 27, 2026.

## Do I need to install anything or create an account?

No install is needed for the web app. It runs in a desktop or mobile browser at [objectremover.video/upload](https://objectremover.video/upload), and the free tier can be tried without signing up or adding a card. An account is useful once you buy credits, because credits and history are attached to it. Editors who work in Adobe Premiere Pro can also use the [Premiere Pro plugin](premiere-pro-plugin.md), which shares the same account and credits.

## What files can I upload?

As of November 2026, ObjectRemover accepts:

| Type | Formats | Maximum file size |
| --- | --- | --- |
| Video | MP4, MOV (QuickTime) | 100 MB |
| Photo | JPG, PNG, WebP | 20 MB |

Video frame rate can be up to 60 fps. Files are added with the file picker or by drag and drop from your device. There is no paste-a-URL option, so you cannot point the tool at a link to someone else's video. If your file is larger than the limit, trim it to the section that needs cleaning and export again before uploading.

## How do I remove something from a video?

The workflow has three steps.

### 1. Upload

Open [objectremover.video/upload](https://objectremover.video/upload) and add your MP4, MOV, or photo. Use the cleanest copy you have. A file that has been re-compressed several times leaves less detail for the background rebuild.

### 2. Select the target and confirm the mask

You can select the target in two ways:

- **Describe it in chat.** Type what you want gone in ordinary words, for example "remove the person in the white shirt" or "delete the date stamp in the corner".
- **Brush over it.** Paint over the object on the preview. This helps when the object is hard to name or sits in a busy frame.

You can mix both: brush one thing, then describe another. ObjectRemover then shows the selection as a mask. Check that the mask covers the whole target, including shadows or reflections you want gone, across the clip. Nothing is processed until you confirm. Asking for a word like "penguin" or "car" selects every matching instance, so several objects can be handled in one pass.

### 3. Preview and download

ObjectRemover fills the masked area with a rebuilt background that stays consistent from frame to frame (video inpainting). Play the preview through the motion, then download. If the fill wobbles, narrow the selection or trim the clip and run it again.

The same flow can also **extract** a subject instead of removing it: video with an alpha channel, or a transparent PNG for photos. That is useful when you want to composite the subject onto another background in your editor.

## What does it cost to try?

Starting is free. The free option is a **Low** quality run meant for small-area jobs, and its output always includes an ObjectRemover tool watermark. Paid credits give you Low, Standard, or Fine quality and downloads without the tool watermark. You see an exact credit quote before any paid job starts. There is no subscription, and credits stay valid for 12 months. Details are in [Credits, quality, and limits](credits-and-limits.md) and on the [pricing page](https://objectremover.video/pricing).

## How should I phrase the request?

Short, specific descriptions help. Name the thing by what it looks like (color, clothing, type of object) and handle one kind of target per pass when the frame is crowded. Ready-made wording is on the [prompt examples page](https://objectremover.video/help/examples).

## How long are files kept?

As of November 2026, paid outputs are kept about 7 days and free watermarked previews about 1 day, then deleted. Download your result promptly. Uploads are not used to train AI models. See [Rights and privacy](rights-and-privacy.md).

## Where to go next

- [Remove objects](use-cases/remove-objects.md)
- [Remove people](use-cases/remove-people.md)
- [Remove burned-in text](use-cases/remove-burned-in-text.md)
- [Clean up AI-generated video](use-cases/ai-generated-video-cleanup.md)
- [What works and what fails](what-fails.md)
- Official feature overview: [objectremover.video/features](https://objectremover.video/features)
