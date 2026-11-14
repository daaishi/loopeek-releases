# loopeek

**loopeek — a tiny, fast player for checking HAP / NotchLC / ProRes / H.264 clips.**

Open a folder and see every clip at a glance — codec, resolution, fps and alpha — without launching a heavy VJ application or a full NLE just to check a file.

<!-- TODO: add a screenshot of the folder grid here, e.g. ![loopeek folder view](screenshot.png) -->

## What it does

- **Folder grid** — drop in a folder and every video in it appears as a tile showing a frame, the codec, the resolution, the fps, whether it carries alpha, the file size and the duration.
- **Hover to scrub** — move the pointer across a tile to skim through the clip.
- **Instant playback** — click a tile and the clip plays right away, in the same tab.
- **Filter and sort** — narrow the grid by name, codec or alpha, and sort by name, date or duration.
- **Forgiving** — a file that cannot be read is flagged on its own tile; the rest of the folder still loads.

## Free vs Pro

Playback and metadata are **free forever** — no licence needed to browse and check your clips.

**Pro** is **$19 one-time** (up to 2 devices), with a **7-day free trial**. Pro unlocks:

- **Conversion** — HAP ⇄ ProRes / H.264, including chunked HAP and HAP Alpha
- **Sequence export** — PNG and OpenEXR image sequences
- **Multi-tab** — open several folders and clips side by side in tabs

Get Pro or start the trial from the product page: <https://dougu.dev/loopeek.en>

## Download

- **Releases (this repository):** <https://github.com/daaishi/loopeek-releases/releases>
- **Product page:** <https://dougu.dev/loopeek.en>

This repository distributes built binaries only — it does not contain the source code.

## Platforms

- **macOS** — Apple Silicon. The app is notarized by Apple, so it opens with a normal double-click after downloading.
- **Windows** — x64 (`.exe` NSIS installer or `.msi`). The Windows build is not code-signed, so SmartScreen may show "Windows protected your PC" — choose **More info → Run anyway** to launch it.

## FAQ & support

See the FAQ on the product page: <https://dougu.dev/loopeek.en>

---

Made by [Dougu](https://dougu.dev)
