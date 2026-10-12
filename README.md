# Ashgabat SPA_BEAUTY media

Public media migrated from https://ashgabatspa.com on 2026-10-12, plus owner-provided branding and salon photographs.

- `web/images`: all 35 published image records, optimized as WebP.
- `web/video`: all 38 published video records, normalized as browser-ready H.264 MP4, with fast-start.
- `web/posters`: 38 real video stills.
- `web/design`, `web/branding`: salon photography, logo and favicon used by the redesign.
- `manifest.json`: original public URLs, source SHA-256 and procedure IDs.
- `image-variants.json`, `web/video-variants.json`: derivative metadata and verification.

Unmodified originals are retained in the owner's local migration archive. No WordPress credentials, customer records, application source or private backups are included here.

Media rights remain with their original rights holders; publication does not grant an open-source license to the images, logo or videos.

Primary delivery: https://sky-night-net.github.io/ashgabat-spa-media/ (GitHub Pages). The local redesign includes bundled fallback copies. jsDelivr is an alternate video path pinned to the ffdf7c1fbf0789f744b99c3a32c30bb35b8e43c0 commit; it returned some unavailable files during the full check, so it is not the main dependency.

Keep existing asset filenames unchanged. Publish future media revisions under new/versioned paths. Commit-pinned CDN URLs must reference the exact Git commit.
