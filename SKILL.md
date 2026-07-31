---
name: linkedin-frame
description: Profile picture frame creator (upload, frame, drag, zoom, share). Use to run locally or adjust the frame overlays.
---

# linkedin_frame — DOer's Profile Picture Frame Creator

Upload a 1:1 photo, pick one of three frames, drag/pinch to position, then share or download. Built as a DO Day hobby prototype.

## Quick commands

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Conventions

- Single-page app: `index.html`, canvas compositing (no html2canvas).
- Frame overlays are `frame_1.png`, `frame_2.png`, `frame_3.png`; background `bg.jpg`; demo image `demo_do.png` — all relative paths.
- All assets are local; never point back to external/personal hosts.

## Verification

- Upload a 1:1 image, switch frames, drag + pinch-zoom, share/download — output must be a composited PNG.
