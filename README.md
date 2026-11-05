# STILL — Carpathian Retreat

Hero screen for STILL, a glass-dome glamping retreat in the Carpathians.

Static site, no build step. A WebGL scene renders the photo as a quiet cinemagraph (slow fog, sky drift, fire flicker, breathing silk ribbons) with a subtle mouse parallax. STILL uses the logo's own letterforms (Monument Extended Ultrabold path in `assets/still.svg`) filled with a small sunset-and-ridges Carpathian landscape; the tagline is set in Unbounded Light. The interface is real HTML: navigation, tagline, and a working booking bar (date and guest pickers).

Motion rules:
- one entrance moment: the scene settles and the "Carpathian" signature writes itself (≈2.4 s in total);
- ambient motion stays slow and low-contrast so it never competes with the booking bar;
- `prefers-reduced-motion` gets a still scene and no entrance animation.

Run locally: `npx serve .`
