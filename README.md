# NOOLAM - animated saree store replica

A front-end replica of the saree-store concept from Instagram reel
https://www.instagram.com/reel/DfcHcbDOyJm/ (@genz.webdeveloper), rebuilt
from scratch with original code and AI-generated imagery.

## Run it

No build step. Serve the folder over HTTP (needed for the Three.js module):

    python3 -m http.server 8080
    # open http://localhost:8080

## What's inside

- Depth-of-field saree rack carousel (blur/focus rails, arrows + drag)
- Tilt/fan product cards (silk deck + bridal fan, quick-add with bag count)
- 3D fabric braid builder (Three.js): pick 3 silks, strands braid live, add to bag
- Story viewer (progress segments, auto-advance, pause on hold)
- Hotspots on the muse film, marquee/ticker, look selector, bag drawer with cart state
- Fully responsive (desktop + mobile), prefers-reduced-motion honored

## Stack

Vanilla HTML/CSS/JS, GSAP 3 + ScrollTrigger, Three.js 0.160 (all vendored in
/vendor - works offline). All imagery in /assets is original AI-generated
artwork created for this replica; no assets were taken from the reel or its
creator. Cart is demo state only - no checkout, accounts, or backend.

Video walkthrough: delivered alongside this zip (nooram-preview-v3.mp4).
