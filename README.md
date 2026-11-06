# webp2mp4

Convert an animated WebP file to MP4.

![tested on](https://img.shields.io/badge/tested%20on-Debian-A81D33?logo=debian)

## Usage

```
$ webp2mp4 FILE
```

The output is written next to the input file with the extension replaced by `.mp4` (e.g. `foo.webp` → `foo.mp4`).

## Dependencies

- `anim_dump` and `webpmux` (from libwebp)
- `ffmpeg`

### On Debian:

```
$ sudo apt install webp ffmpeg
```
