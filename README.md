# Sarfraz Ahmad — Art Playground

Live portfolio: https://asarfraz447.github.io/sarfraz-portfolio/

Game art, UI/UX and interactive Spine animation portfolio, including 8 characters, 24 skin variants, galleries and background effects.

## Complete editable website

Download `portfolio.tar.gz` and `portfolio.sha256` from the v1.0.0 release:
https://github.com/asarfraz447/sarfraz-portfolio/releases/tag/v1.0.0

```sh
sha256sum -c portfolio.sha256
tar -xzf portfolio.tar.gz
```

All HTML, CSS, JavaScript, JSON, Spine atlases and textures are inside `dist/`. Serve that folder over HTTP to preview locally.

The Pages workflow downloads the release archive, verifies its checksum and publishes `dist/`. The standalone `portfolio.tar.gz.part-000` in this branch is a partial upload from the initial transfer; use the complete release archive.

Artwork and assets remain the property of their respective owners. No reuse license is granted.
