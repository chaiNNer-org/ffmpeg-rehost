# ffmpeg-rehost
Rehosting of FFMPEG in a consistent way, to ensure downloading with chaiNNer is reliable.

These builds of FFMPEG are licensed under GPLv3 and were statically compiled thanks to different sources. This made it difficult to have a consistent downloading method for our platform-agnostic codebase. This repo simply bundles each static ffmpeg and static ffprobe build with a consistent file structure.

## Sources

Windows binaries from: https://github.com/GyanD/codexffmpeg/releases/tag/5.1.2

MacOS binaries from: https://evermeet.cx/ffmpeg/ and https://www.osxexperts.net/

Linux binaries from: https://johnvansickle.com/ffmpeg/
