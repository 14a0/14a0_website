# 14AØ — Hero Concepts

Alternate animated "Ø" black-hole hero concepts explored for the site. Each file
is a **complete, self-contained, single-file HTML** page (inline CSS/JS/GLSL, zero
external resources) — just open it directly in a browser.

All are DPR-capped, resize-safe, pause on tab-hide, and have a `prefers-reduced-motion`
fallback and a WebGL→Canvas2D graceful fallback.

## The concepts

| File | Approach | Feel |
|------|----------|------|
| `crisp-mark-hybrid.html` | Crisp SVG Ø over a gravitationally-lensed **wormhole-ring starfield** + gentle accretion + a subtle full-width background jet beam + parallax stars. | Calm, majestic. **Basis for the current live hero.** |
| `voidwarp-shader.html` | Pure fragment shader: a swirling **domain-warped plasma vortex** around a bold black void; chromatic-edged diagonal. | Cinematic, abstract. |
| `accretion-particles.html` | Canvas2D **particle accretion vortex** — pure-black event horizon, photon ring, and a bright particle jet along the diagonal. | The most literal black hole. |
| `rotating-torus.html` | Pseudo-3D **rotating particle torus** orbiting the Ø, with depth fog + parallax. | Strong 3D/intergalactic rotation. (Its slash renders steeper than the brand angle.) |
| `lens-shader.html` | WebGL **gravitational-lens** shader — background stars bent into Einstein-ring arcs hugging the Ø. | Minimal, neon-clean. |

## Notes
- The live `/void.html` is a synthesis: `crisp-mark-hybrid`'s cosmos direction combined
  with `voidwarp`'s plasma swirl, `accretion`'s photon ring / infall particles, plus a
  travelling comet flash on the jet — with an iOS viewport fix so the Ø stays aligned
  to the black hole on mobile.
- These are design references / spare parts to remix later. Not linked from the site.
