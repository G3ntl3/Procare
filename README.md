# Axen Form

Portfolio concept for **Axen Form**, a fictional design-and-build contractor. A homepage plus an "in development" holding page. There is no loading screen.

## What's in it

- **Hero:** the studio name sits behind the roof peak of a timber-framed house. The house is cut out of the sky, so the text, photo and house move at different depths with scroll and the mouse.
- **Studio, Services, Projects, Clients, Contact:** each section is labelled like a construction drawing sheet (A-101, A-201…).
- **3D build sequence (Three.js):** scroll to watch a five-storey building go up. It covers footings, frame and floors, temporary props, starter bars, edge protection, curtain wall, roof and plant, then the lights come on at handover. A lattice tower crane works the site. Drag to orbit.
- **Projects:** stacking cards that slide over each other as you scroll.
- **Motion:** smooth scrolling with [Lenis](https://github.com/darkroomengineering/lenis); animation with [GSAP](https://gsap.com) + ScrollTrigger.

## Run it

It's a static site with no build step. Open `index.html` through any static server, for example:

```
npx serve .
```

Libraries load from CDNs (three.js from jsDelivr, GSAP from cdnjs, Lenis from jsDelivr). Fonts come from Google Fonts: Archivo, Hanken Grotesk, Cormorant Garamond and IBM Plex Mono.

## Files

- `index.html` — homepage (styles and scripts inline)
- `in-development.html` — holding page for links that aren't built yet
- `assets/` — WebP photography, plus the hero sky cutout used for the depth effect

All names, figures, projects and testimonials are fictional.
