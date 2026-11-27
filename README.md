# ObjectRemover Docs

Public documentation for [ObjectRemover](https://objectremover.video/), an AI tool that removes objects, people, and burned-in text from videos and photos in the browser or inside Adobe Premiere Pro.

This repository contains guides and reference material only. It does not contain product source code, models, or plugin code.

## What ObjectRemover does

ObjectRemover takes a video or photo, finds the thing you want gone, and fills the area with a reconstructed background that stays consistent across frames (video inpainting).

You can point at the target in two ways:
- **Describe it** in everyday words, for example "remove the guy walking behind me" or "delete the timestamp".
- **Brush over it** on the preview.

Either way, you see and confirm the selection (the mask) before anything is processed.

## Who it's for

Creators, editors, and small teams cleaning up footage they own or are allowed to edit: a passer-by in a travel clip, a logo on a prop, a date stamp from a camera, captions that got baked into an export.

## How it works

1. Upload an MP4 or MOV (up to 100 MB), or a JPG, PNG, or WebP photo (up to 20 MB).
2. Describe or brush the object, person, or text, then confirm the mask.
3. Preview the result through the motion and download it.

See [Getting started](docs/getting-started.md).

## Guides

- [Remove objects from video](docs/use-cases/remove-objects.md)
- [Remove people from video](docs/use-cases/remove-people.md)
- [Remove burned-in text, captions, and timestamps](docs/use-cases/remove-burned-in-text.md)
- [Clean up AI-generated video](docs/use-cases/ai-generated-video-cleanup.md)
- [Premiere Pro plugin](docs/premiere-pro-plugin.md)

## Reference

- [Credits, quality, and limits](docs/credits-and-limits.md): pay-as-you-go credits, no subscription, valid 12 months; the free Low preview carries a watermark; paid credits give you Low, Standard, or Fine quality without a watermark.
- [What works and what fails](docs/what-fails.md)
- [Blur, crop, or inpaint? And how ObjectRemover compares](docs/comparisons.md)
- [FAQ](docs/faq.md)
- [Rights and privacy](docs/rights-and-privacy.md): use only footage you own or may edit. Uploads are not used to train AI models.
- [Changelog](CHANGELOG.md)

## Links

- Website: https://objectremover.video/
- Start in the browser: https://objectremover.video/upload
- Premiere Pro plugin: https://objectremover.video/plugins/premiere-pro
- Pricing: https://objectremover.video/pricing
- Support: support@objectremover.video

Maintained by Jerry Lee, founder of ObjectRemover. Documentation text is licensed CC BY 4.0.
