# ObjectRemover Premiere Pro plugin

The ObjectRemover plugin is a panel for Adobe Premiere Pro 25.6 and newer that removes or extracts an object from a clip on your timeline. You describe or brush the target, confirm the mask, and the result comes back on a new track. Processing happens in the ObjectRemover cloud and uses the same credits as the website.

Checked against [objectremover.video/plugins/premiere-pro](https://objectremover.video/plugins/premiere-pro) and the [launch post](https://objectremover.video/blog/premiere-pro-plugin-object-removal) on November 27, 2026. The plugin was announced on October 12, 2026.

> **Rights rule:** Use the plugin only on footage you own or are allowed to edit. Do not strip credits, watermarks, or branding from someone else's work.

## Which Premiere Pro versions are supported?

Premiere Pro 25.6 and newer, on macOS and Windows. One `.ccx` file installs on both platforms. Older versions of Premiere Pro are not supported.

## How do I install the plugin?

1. Download the `.ccx` file from [objectremover.video/plugins/premiere-pro](https://objectremover.video/plugins/premiere-pro).
2. Quit Premiere Pro.
3. Double-click the `.ccx` file to install it.
4. If Premiere asks, turn on developer mode (first time: **Settings > Plugins > Enable developer mode**), then restart Premiere Pro.
5. If your operating system blocks the file, load the plugin folder through Adobe's UXP Developer Tools instead.

## How do I open and sign in?

Open **Window > ObjectRemover**. Choose **Sign in with browser** and log in with your ObjectRemover account. The panel then shows your credit balance from the website.

## How do I remove an object from a clip in Premiere?

1. Park the playhead on a frame where the object is clearly visible.
2. In the ObjectRemover panel, describe the object or brush over it.
3. Confirm the mask.
4. Choose **remove** to paint the object out, or **extract** to isolate it for compositing.
5. Review the quote and run the job. The result lands on a new track, and your original clip stays untouched.

## Does the AI run inside Premiere?

No. The clip is sent to the ObjectRemover cloud for processing and the result is returned to your timeline. You need an internet connection, and your computer's GPU does not do the removal.

## Are plugin credits the same as website credits?

Yes. The panel uses the same account and the same credit balance as [objectremover.video](https://objectremover.video/). Premiere cannot take payment, so credits are bought on the website. As of November 2026, Custom packs start at $3.87 and Basic is $9.99 for 100 credits, and credits remain valid for 12 months. See [Credits, quality, and limits](credits-and-limits.md).

## How is this different from Adobe Generative Remove?

Adobe documents its own Generative Remove feature in Premiere (beta). According to [Adobe HelpX](https://helpx.adobe.com/premiere/desktop/edit-projects/edit-with-generative-ai/generative-remove.html) (last updated November 10, 2026, accessed November 27, 2026), it supports clips up to 10 seconds, 480p to 1080p, up to 30 fps, does not support HDR or 10-bit footage, and uses 40 generative credits per second. You create and track a mask, review the generative credit cost, and confirm.

The ObjectRemover panel follows the same rules as the ObjectRemover web app and bills ObjectRemover credits. Its output is remove or extract to a new track. It does not generate or restyle the shot. Which one fits depends on your clip and how you prefer to pay. Check Adobe's limits against the quote shown in the ObjectRemover panel before you run. A broader comparison is in [Comparisons](comparisons.md).

## The panel is not showing up. What should I check?

- Quit Premiere Pro and load the plugin again.
- Make sure developer mode is on, then restart.
- Look under **Window**. The panel may be listed but not docked.
- Confirm you are on Premiere Pro 25.6 or newer.

## Can I use ObjectRemover without Premiere?

Yes. The same confirm-then-process flow runs in the browser at [objectremover.video/upload](https://objectremover.video/upload). Many editors clean a clip in the browser and import the result into any editor, including Premiere Pro, CapCut, or DaVinci Resolve.

## Related

- [Getting started](getting-started.md)
- [Remove burned-in text](use-cases/remove-burned-in-text.md)
- Official: [Premiere Pro plugin page](https://objectremover.video/plugins/premiere-pro)
