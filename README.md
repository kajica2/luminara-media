# LUMINARA · Media CDN

Public CDN for video assets. Files here are served via GitHub Releases for fast, public, unauthenticated delivery.

## Files

| file | source | size | link |
|---|---|---|---|
| `sovereign-scale-001.mp4` | Sovereign Scale 60s pitch | 6.3 MB | [release](https://github.com/kajica2/luminara-media/releases) |
| `luminara-bundle-launch.mp4` | LUMINARA 9-product launch | 7.6 MB | [release](https://github.com/kajica2/luminara-media/releases) |

## Usage

Each release publishes the video file as a downloadable asset. The public URL follows the pattern:
```
https://github.com/kajica2/luminara-media/releases/download/<tag>/<filename>
```

For embedding (e.g. in a Gumroad product page, Notion, or LinkedIn post), download the file and re-host on the destination platform.

## Why GitHub Releases (not LFS, not Vercel Blob)?

- Instant public URL, no auth dance
- Free for public repos
- No bandwidth limits at our scale
- No additional credentials to manage (uses `gh` CLI you already have)
- Works with CDN for fast global delivery
