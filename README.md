# DOer's Profile Picture Frame Creator

Upload a 1:1 profile photo, pick one of three frames, drag and pinch-zoom to position, then share or download the framed result.

## Features

- 3 selectable frame overlays
- Mouse drag + touch drag / pinch-to-zoom (scale 1x–3x)
- Clamped repositioning so the image always covers the frame
- Share via Web Share API with file attachment (fallback: direct download)

## Run locally

```bash
python3 -m http.server 8000
# or
npx serve .
```

Then open http://localhost:8000

## Tech

- Vanilla JavaScript + HTML5 Canvas
- html2canvas-free (direct canvas compositing)
