# Signal Camera launch site

## Premium launch page shell and visual system
- [ ] Build a single-page launch site with a locked dark theme using near-black `#0b0b0c`, `#111113`, `#17171a` surfaces, warm off-white `#ededea` text, muted gray secondary text, hairline borders at 8% white, and exactly one ownable accent `#ff5a1f` used sparingly for CTAs, leader lines, focus rings and glows.
- [ ] Use Geist for text and Geist Mono for numbers/specs, huge tight headings with tracking around `-0.045em` and leading under 1, full-pill buttons, 20px-radius cards, asymmetric bento cards, master-detail lists, full-bleed product imagery, and a faint film-grain overlay.
- [ ] Use moody generated product photography consistently across hero, lens, gallery and aperture sections.

## Motion-led product storytelling
- [ ] Implement Lenis smooth scrolling synchronized with the GSAP ticker.
- [ ] Implement a GSAP hero with a masked headline rise, pinned scroll exit, copy blur, letter-by-letter headline dissolve, and an orange iris ring closing over the lens to black.
- [ ] Implement a pinned, scrubbed lens zoom with orange callout lines that draw into place.
- [ ] Implement a pinned horizontal gallery pan.
- [ ] Implement Motion-driven hide-on-scroll navigation, shared-layout pills, count-up numbers, pointer spotlight card, and magnetic CTA.
- [ ] Implement an Anime.js draggable SVG aperture iris that changes aperture and dynamically blurs its associated photo.
- [ ] Implement a lazy-loaded React Three Fiber lens scene with rotate interaction and loading/non-WebGL fallbacks.
- [ ] Add a playground that runs a comparable visual effect in GSAP, Motion, Anime.js and CSS.

## Responsive and accessible delivery
- [ ] Use expo/power eases, no unintentional bounce, keyboard-visible signal-orange focus rings, reduced-motion behavior, and mobile fallbacks for pinned scenes and 3D.
- [ ] Serve the root route in `public/manus-routes.json` and keep the page valid for static preview/build.
