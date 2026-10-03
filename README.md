# Interactive Heaven

Tap-the-sky blessing experience. Single-file build: `index.html`.

Live: https://teds-son-1000.github.io/interactive-heaven/

## What it does
- Gradient sky with day/night toggle, drifting clouds, twinkling stars
- Tap anywhere: ripple + chime; tap stars for glow bursts
- Blessing button, shooting stars, floating orbs, ambient chord pad

## Bugfixes in this version
- AudioContext resume on user gesture (mobile-safe)
- Oscillator/gain node disconnect on end (no leaks)
- Larger star hit-area via invisible touch target
- Orb count cap + cleanup (max 30, 19s TTL)
- Viewport-fit + safe-area layout for mobile zoom
