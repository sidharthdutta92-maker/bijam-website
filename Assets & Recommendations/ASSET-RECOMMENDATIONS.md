# Bijam Website — Asset Recommendations

Your website has a strong dark-mode aesthetic built around deep navy (#0B0F14), gold (#DDA74A), blue (#5A9FD4), and pink (#E68A9A) accents, with Space Grotesk typography and subtle glow/blur effects. The assets below were hand-picked from your three collections to elevate that visual language. I've included both SVG (scalable, best for web) and PNG versions where available.

**General color tip:** Since all these assets are black on transparent, you'll want to tint them using CSS `filter`, `mix-blend-mode`, or by setting `fill` color in the SVG code to match your palette — gold for primary accents, blue for secondary, and low-opacity white for subtle background textures.

---

## 01 — Hero & Background Decorations

Large shapes to use as floating, semi-transparent decorative elements behind hero sections, the About Bijam panel, or the detail overlay.

| File | Original Source | How to Use |
|------|----------------|------------|
| `retro-4point-star.svg` | Retro-Futuristic #100 | **Best pick.** A soft 4-point star that mirrors the existing gold sparkle aesthetic on map dots. Place it at ~20% opacity in gold behind the About Bijam hero logo, or as a floating accent on the detail overlay page. Tint it `#DDA74A` and use `filter: blur(40px)` for a gorgeous glow orb. |
| `retro-concentric-rings.svg` | Retro-Futuristic #190 | Concentric rings radiating from a center point. Perfect as a radial motif behind the hero stat grid or behind the map. Apply at 3–5% opacity in white to create a subtle "signal/radar" pattern that reinforces the media-mapping theme. |
| `retro-radial-sunburst.svg` | Retro-Futuristic #200 | Dense line-burst circle. Use as a background texture behind the About Bijam hero section with very low opacity (2–4%), tinted gold. Creates a premium, engraved-currency feel on dark backgrounds. |
| `retro-asterisk-starburst.svg` | Retro-Futuristic #150 | Bold 6-arm asterisk/starburst. Works well as a large rotated accent element (40–60% of viewport width) placed behind the right panel at very low opacity, or as a loading/spinner indicator animation. |
| `retro-flame-mandala.svg` | Retro-Futuristic #240 | Ornamental flame/petal mandala. A decorative flourish for the CTA section at bottom of the About panel. Place behind "Get in Touch" at ~8% opacity in gold for an elegant premium touch. |
| `abstract-double-star-burst.png` | Abstract Shapes #250 | Two interlocking 4-point stars. Use as a pair of floating decorative shapes on the detail overlay page — one large, one small — at low opacity in gold and blue respectively. Mimics a constellation/network motif. |
| `abstract-twin-star-flow.png` | Abstract Shapes #300 | Two organic flowing 4-point stars. Similar use case to above but with a more fluid, dynamic feel. Great for the hero `::after` pseudo-element that currently uses a plain radial gradient. |

---

## 02 — Section Accents & Dividers

Horizontal or patterned elements to use as visual separators between sections, or as subtle border decorations.

| File | Original Source | How to Use |
|------|----------------|------------|
| `retro-tribal-wing-divider.svg` | Retro-Futuristic #1 | Symmetrical tribal wing shape that extends horizontally. Perfect as a decorative horizontal divider between the stat grid and distribution chart in the About panel. Center it, tint gold at ~15% opacity, scale to panel width. |
| `retro-triple-star-divider.svg` | Retro-Futuristic #70 | Three connected 4-point stars in a horizontal line. Use as a minimalist divider between sections on the detail page. Tint gold, keep subtle. |
| `retro-chevron-pattern.svg` | Retro-Futuristic #160 | Row of forward-pointing chevrons. Use along the bottom edge of the topbar or city selector bar as a directional accent. Tint blue (#5A9FD4) at 10% opacity to create a sense of forward motion/progression. Also works well repeated as a scrolling animation. |
| `retro-halftone-dot-gradient.svg` | Retro-Futuristic #80 | Grid of dots that decrease in size from left to right. Excellent for creating a fade-out effect on panel edges. Place along the right edge of the map area or the left edge of the right panel. Tint white at 3–5% opacity. |
| `dither-wave-stripe-texture.svg` | Dithering Bitmap #103 | Dithered wavy stripes pattern. Use as a full-width texture behind the CTA box or behind section headers. At very low opacity (2–3% in white) on the dark background, this adds a tactile, premium print-like quality. |

---

## 03 — Icon & Badge Shapes

Smaller shapes to use as icon containers, badge backgrounds, custom map markers, or media type card decorations.

| File | Original Source | How to Use |
|------|----------------|------------|
| `abstract-6point-star-badge.svg` | Abstract Shapes #1 | Rounded 6-point star with a cutout center. Use as a badge/seal shape for the "OOH Media" logo badge, or as a frame behind the media type icons (Hoarding, Unipole, etc.). Tint gold, use as a background behind the icon SVGs. |
| `abstract-donut-ring.svg` | Abstract Shapes #5 | Clean bold donut/ring. Replace the current plain circle `.logo-icon` background with this shape for a more distinctive brand mark. Also works as a loading spinner when animated with rotation. |
| `abstract-diamond-eye.svg` | Abstract Shapes #10 | Diamond frame with center dot — looks like an eye or compass. Perfect replacement for the current `.logo-icon` SVG on the topbar. The "eye" metaphor matches the OOH (Out-of-Home) visibility theme. Also works as a custom map marker shape. |
| `abstract-gear-sun-wheel.svg` | Abstract Shapes #30 | 8-spoke gear/sun wheel with open center. Use as an icon frame behind the media type cards, or as a decorative element in the stats grid. The industrial/mechanical vibe suits outdoor media infrastructure. |
| `abstract-saturn-planet.svg` | Abstract Shapes #100 | Planet with ring — space/orbit metaphor. Use as a decorative accent on the About Bijam panel to reinforce the "network reach" concept. Can also serve as a background shape behind the stat that shows coverage area. |
| `abstract-shooting-stars.svg` | Abstract Shapes #150 | Three shooting stars cluster. Perfect decorative accent for the detail page header, or as a celebratory element near key statistics. Tint gold and place at ~15% opacity. |
| `retro-corner-bracket-frame.svg` | Retro-Futuristic #10 | L-shaped corner bracket with tech lines. Use pairs of these in the corners of cards (`.site-item`, `.about-stat`, `.specs-card`) to create a HUD/tech-frame aesthetic. Apply at 8–12% opacity in gold/blue. This is a high-impact small change. |
| `retro-focus-crosshair-frame.svg` | Retro-Futuristic #30 | Focus brackets with center cross. Use on the map as a location-targeting overlay, or as a decorative frame around the detail gallery main photo. Reinforces the "pinpointing exact locations" concept of OOH media. |
| `retro-perforated-grid.svg` | Retro-Futuristic #110 | Organic perforated grid with circular holes. Use as a texture overlay on card backgrounds or panel surfaces. At very low opacity on the `.bg-surface` areas, it adds depth without being distracting. |
| `abstract-chain-link-circles.svg` | Abstract Shapes #200 | Three interlocking rings/chain links. Great visual metaphor for "connected network of media sites." Use in the About section or as a decorative accent on the inventory panel header. |

---

## 04 — Texture Overlays

Dithered and patterned textures to layer over dark backgrounds for depth, grain, and visual richness.

| File | Original Source | How to Use |
|------|----------------|------------|
| `dither-circle-halftone.svg` | Dithering Bitmap #97 | Halftone dot circle with grid pattern. Layer over the About hero section or detail gallery at 2–4% opacity in white. Creates a refined print-screen texture that adds subtle physicality to the digital interface. |
| `dither-noise-sphere.svg` | Dithering Bitmap #98 | Random noise sphere. Similar to above but with a more organic, scattered noise pattern. Use behind stats cards or the CTA section for a gritty, premium feel. |
| `dither-gradient-landscape.svg` | Dithering Bitmap #100 | Dithered gradient that fades from dense to sparse. Excellent for creating organic transition zones between sections. Place at the boundary between the map and right panel. |
| `dither-fine-noise-square.svg` | Dithering Bitmap #101 | Fine diagonal noise pattern in a square. Use as a repeating tile for a full-page grain overlay. Apply over the entire `body` at 1–2% opacity for that high-end editorial website texture. |
| `dither-organic-blob-cluster.svg` | Dithering Bitmap #1 | Cluster of dithered organic blobs. Use as a decorative background element on the About panel or behind the map legend. Tint gold at 3–5% for warmth. |
| `dither-gear-flower.svg` | Dithering Bitmap #4 | Dithered gear/flower ring. Decorative motif for the media type section or inventory header. The gear shape ties into the industrial outdoor media theme. |
| `dither-abstract-blob.svg` | Dithering Bitmap #104 | Smooth abstract 3-lobe blob with maze-like dither texture. A unique organic shape for empty state backgrounds or as a floating accent. |
| `dither-flower-gear.svg` | Dithering Bitmap #74 | Dithered flower with crosshatch texture. Elegant organic accent for the CTA section or detail page sidebar. |
| `abstract-checkerboard-spiral.svg` | Abstract Shapes #170 | Op-art rotating checkerboard spiral. A bold, attention-grabbing element — use sparingly as a background behind a key CTA or as a hero decoration on a landing page variant. At 3–5% opacity it creates mesmerizing depth. |

---

## 05 — Map & Globe Elements

Shapes specifically relevant to the map/geography/data visualization aspects of the Bijam site.

| File | Original Source | How to Use |
|------|----------------|------------|
| `abstract-wireframe-globe.svg` | Abstract Shapes #300 | Wireframe globe with orbital lines. **Top recommendation for your site.** Place this behind the map or in the About section hero. It perfectly represents Bijam's geographic media reach. Tint gold at 5–8% opacity for an elegant watermark effect, or use at higher opacity as a hero decorative element. |
| `retro-wireframe-globe.svg` | Retro-Futuristic #210 | Simpler wireframe globe with latitude/longitude lines. Cleaner alternative to the above. Works great as a subtle background element behind the state-level distribution chart. |
| `retro-topographic-contour.svg` | Retro-Futuristic #40 | Organic topographic/contour map lines. Layer this over the Leaflet map as a decorative overlay on empty areas, or use behind the city selector bar. The contour lines naturally evoke geographic mapping. At 2–3% opacity, it adds depth to the map surface. |
| `retro-compass-crosshair.svg` | Retro-Futuristic #120 | Circle with crosshair lines — a compass/navigation marker. Use as a custom icon for the map's "locate me" feature, or place behind the map zoom controls for a polished navigation accent. |
| `retro-data-bar-chart.svg` | Retro-Futuristic #50 | Dithered bar chart visualization. Use as a decorative background element behind the distribution bar chart in the About panel. The meta-reference (data viz behind data viz) creates a layered, sophisticated feel. |

---

## Quick-Win Implementation Priority

If you want the biggest visual impact with the least effort, I'd start with these five:

1. **`retro-corner-bracket-frame.svg`** — Add to card corners for instant HUD/tech-frame feel
2. **`abstract-wireframe-globe.svg`** — Place behind the About hero for geographic brand identity
3. **`retro-4point-star.svg`** — Use as a blurred gold glow orb behind key sections
4. **`dither-fine-noise-square.svg`** — Full-page grain overlay for premium editorial texture
5. **`retro-topographic-contour.svg`** — Layer over the map for depth and geographic richness
