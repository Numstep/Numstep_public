# Numstep Public Media

Public, versioned media assets used by Numstep's social publishing workflows.

- `media/` contains publishable PNG/JPEG/WebP/GIF/MP4/WebM files, preserving their source-relative paths.
- `media-manifest.json` indexes every media file with its raw URL, MIME type, byte size, and SHA-256 digest.
- Public media URLs use `https://raw.githubusercontent.com/Numstep/Numstep_public/main/`.

This repository is an asset store, not a source of puzzle data. Never place credentials, post histories, unpublished puzzle JSON, or private previews here. Automated workflows should upload media and update the manifest in the same commit, then verify the raw URL before requesting a social-platform publish.
