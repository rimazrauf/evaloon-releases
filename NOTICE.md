# Notice

Evaloon Editor is derived from OpenReel Video by Augustus Otu
(https://github.com/Augani/openreel-video), commit `367d7e9`, used under the
MIT License. The original copyright and license text are kept in `LICENSE`.

## Third-party components

HyperFrames 0.9.19 (https://github.com/heygen-com/hyperframes, © 2026 HeyGen,
Inc.) renders the animation clips, used under the Apache License 2.0. The
license text is in `apps/desktop/LICENSES/HYPERFRAMES-LICENSE.txt`.

GSAP 3.15.0 (https://gsap.com, © 2008-2026 GreenSock) drives the animations,
used under GreenSock's own Standard "No Charge" License, not MIT. The terms as
the package gives them are in `apps/desktop/LICENSES/GSAP.md`.

Lucide icons (https://lucide.dev, lucide-react 0.555.0) are the icons that the
graphic cards draw. Their shapes are copied into
`packages/animation-templates/src/icons-data.ts` by `scripts/generate-icons.mjs`.
Lucide is used under the ISC License:

> ISC License
>
> Copyright (c) for portions of Lucide are held by Cole Bemis 2013-2022 as part
> of Feather (MIT). All other copyright (c) for Lucide are held by Lucide
> Contributors 2022.
>
> Permission to use, copy, modify, and/or distribute this software for any
> purpose with or without fee is hereby granted, provided that the above
> copyright notice and this permission notice appear in all copies.
>
> THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
> REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY
> AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
> INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM
> LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR
> OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
> PERFORMANCE OF THIS SOFTWARE.

FFmpeg 6.1.1 and its `ffprobe` (ffmpeg-static `b6.1.1`) are bundled as separate
GPL programs, one pair for export and one `ffprobe` in
`apps/desktop/resources/hyperframes/bin` for animation renders. Their license,
source offer and build provenance are in `apps/desktop/LICENSES/FFMPEG.md`.

Chromium Headless Shell 158.0.8127.2 (win64, https://www.chromium.org, © The
Chromium Authors) is bundled in `apps/desktop/resources/hyperframes` and draws
the animation frames. Chromium is used under the BSD 3-Clause License
(https://source.chromium.org/chromium/chromium/src/+/main:LICENSE). The build
also carries other open-source components, each under its own license; the
list ships with the program in its `LICENSE.headless_shell` file.

## Optional download: offline voice

Kokoro-82M (Apache-2.0) and eSpeak NG 1.52.0 (GPL-3.0-or-later) are not part of
the installer. They are downloaded from their official sources only when you
press "Download offline voice" in Settings. eSpeak NG runs as a separate
program, and its source is at https://github.com/espeak-ng/espeak-ng. The
licences, sources and what is downloaded are in
`apps/desktop/LICENSES/OFFLINE-VOICE.md`. The small Kokoro config files kept in
the app are covered by the notice beside them.
