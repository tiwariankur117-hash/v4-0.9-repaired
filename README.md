# VYRA Studio — launch build (Cloudflare Pages static frontend)

## Deploy
Upload the **contents of this folder** to Cloudflare Pages, or connect a GitHub repository with this folder at the root. No build command required; output directory `/`. Open `index.html` locally for preview.

## Implemented
- Premium responsive landing page, 2-second automatic image slideshow with manual thumbnails, dashboard image slideshow, curated media gallery and local video showcases.
- Photo and video prompt workflows with auto-growing text area, reference selection, creative brief saving. These **do not generate AI media** until a real provider is connected.
- Browser video editor: media import, ordered multi-clip timeline, split, trim, rearrange, text overlays, title templates, fades, simple color effects, aspect ratios, playback, undo/redo, browser-local project save/restore, and WebM export using MediaRecorder where supported.
- AI caption panel with clearly labeled integration requirement; manual caption overlay is available.

## Not yet implemented (needs backend / advanced rendering)
- Actual AI image/video generation and AI caption transcription. Never put private API keys in static client-side code.
- Secure cloud accounts, database, admin analytics, cloud project syncing. The login in this prototype is **browser-local demo only** and is not secure. Do not use a real password.
- Production-grade editing features such as arbitrary crossfades, accurate audio mixing, 4K/H.264 MP4 rendering, masking/keyframe curves, advanced effect engines.
- WebM export quality/performance depend on browser and hardware; verify output on your target devices before production use.

## Media
User-provided sample artwork was optimized to WebP at high quality; original sample videos are preserved in `assets/showcase-*.mp4`.


## Approved visual refinements
- Home hero: responsive left text/CTA + right image slideshow, 2-second cycling, manual arrows, no sidebar.
- Neon eye logo uses screen blending to avoid the visible black square.
- Learn guide: dark neon-purple active link for both click and manual scroll.
- Result preview: branded neon eye creative preview artwork.
- Generator pages: branded visual; actual AI remains disconnected (no fake generation claims).
- Enhanced slideshow images are resampled from supplied sources; upscaling cannot recover detail absent from originals.
