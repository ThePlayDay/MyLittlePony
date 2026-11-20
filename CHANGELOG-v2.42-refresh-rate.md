# v2.42 — refresh-rate rendering and UI polish

- Rendering continues on `requestAnimationFrame`, following the display refresh rate; simulation advances using elapsed time (`dt`) so movement, attacks, and timers are not tied to FPS.
- Restored the original one-pass card shine on hover.
- Reduced the top-bar wallet padding and coin icon size to remove the oversized wallet appearance.
- Replaced the star glyph beside pack and permanent-upgrade prices with the image-based `coin-inline` element.

Note: place the prepared transparent `coin.png` at `src/main/resources/static/assets/ui/coin.png`. The uploaded v2.41 archive contains the UI asset README but not the actual PNG artwork.
