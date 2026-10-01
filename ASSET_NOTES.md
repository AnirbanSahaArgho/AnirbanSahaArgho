# Asset notes

The profile is designed to be GitHub-safe and local-first.

The character illustration is stored at `assets/character.png` and embedded into the SVGs as a base64 PNG data URI.

The display and monospace fonts are stored as WOFF2 files and embedded into each SVG through base64 `@font-face` declarations.

No JavaScript, remote CSS, remote fonts, external images, or CDN dependencies are used by the generated SVGs.

The original request referenced a 2-second waving video, but no video asset was available in the uploaded materials used for this build. The hero animation therefore uses SMIL motion and camera UI effects rather than pretending to contain video frames.
