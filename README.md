# FFmpeg source for RelayConverter

The complete corresponding source of the FFmpeg builds that Stensiö Media Enterprise AB ships
with RelayConverter: the LGPL FFmpeg libraries the app's worker uses, and the separate GPL
`ffmpeg` program. One release per build, named as the build is (for example
`ffmpeg-9.0.2-17-nv13.0-1`). Each release holds:

- FFmpeg at the commit built (FFmpeg's own source is unchanged);
- NVIDIA's nv-codec-headers at the commit built against;
- BtbN's FFmpeg-Builds scripts at the commit used, with our change to them as a diff and as the
  script that makes it;
- the source of every library the build scripts build, as their `download.sh` fetches it;
- the configure line of each build, and the build information;
- the licence, copyright and patent files of every library, in one text;
- `README.txt` (how to build it again) and `SHA256SUMS`.

FFmpeg is a trademark of Fabrice Bellard, originator of the FFmpeg project.

Written offer: for at least three years from the date you received RelayConverter, Stensiö Media
Enterprise AB will give anyone who asks a complete machine-readable copy of this source, for no
more than the cost of physically providing it. Ask at info@stensiomedia.se.
