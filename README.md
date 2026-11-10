# ffmpeg-svt-av1-mirror

An exact, unmodified copy of one FFmpeg static build, mirrored so that a Dockerfile can pin it by
content and still find it after the upstream nightly is pruned.

| | |
| --- | --- |
| File | `ffmpeg-n8.1.3-34-ga35157abb9-linux64-gpl-8.1.tar.xz` (release `btbn-autobuild-2026-11-09-12-42`) |
| SHA-256 | `23c6279d9f10afbcc273082256ae2073495595ab53fbcd729a5a93913b3fdd75` |
| Upstream | https://github.com/BtbN/FFmpeg-Builds/releases/tag/autobuild-2026-11-09-12-42 |
| Build scripts | https://github.com/BtbN/FFmpeg-Builds (MIT) |
| FFmpeg source | https://github.com/FFmpeg/FFmpeg at `n8.1.3-34-ga35157abb9` |
| Contents | FFmpeg 8.1.3 with SVT-AV1 4.3.0 and other libraries, `linux64-gpl` variant |

## Licence

The archive is FFmpeg built with `--enable-gpl`, distributed under the GNU General Public License
(version 3 or later, see `LICENSE.txt` inside the archive and the upstream licence files of each
bundled library). The complete corresponding source is available at the upstream locations
listed above: FFmpeg at the given commit and every library at the versions pinned by the
BtbN/FFmpeg-Builds scripts for that release. This repository adds nothing to the archive.
