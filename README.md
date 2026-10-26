# Sarfraz Ahmad — Art Playground

Game art, UI/UX and interactive Spine animation portfolio. Includes 8 characters, 24 skin variants, project galleries and animated backgrounds.

The complete site is stored in numbered archive parts to support browser upload limits. GitHub Actions reconstructs and verifies the archive, then publishes dist/ to GitHub Pages.

## Unpack locally

```sh
cat portfolio.tar.gz.part-* > portfolio.tar.gz
sha256sum -c portfolio.sha256
tar -xzf portfolio.tar.gz
```

The editable HTML, JavaScript, CSS, JSON, textures and all other site assets are inside dist/ after extraction. Serve that folder with a local HTTP server to test.

Artwork and other assets remain the property of their respective owners. No reuse license is granted by this repository.
