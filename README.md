# wllpr — Minimalist Wallpaper Generator

Generate beautiful minimalist wallpapers for desktop and mobile. Free, no account, 100% in your browser.

## Features

- **8 patterns**: Waves, Arcs, Hills, Gradient, Scatter, Mesh, Poly (Delaunay low-poly facets with an adjustable facet-size slider), Dunes (low gradient-shaded ridges under a big empty sky, with four viewpoints (Bottom / Top / Diagonal / Side) and four ridge waveforms (Gentle / Wavy / Sharp / Stepped))
- **Layer controls** (Waves & Hills): layer count slider (Waves 3–14, Hills 3–8), gradient direction (light→dark / dark→light), contrast (soft / normal / bold), plus wave tilt (flat / ↘ / ↗) and a full Diagonal corner-to-corner flow mode for Waves
- **8 curated palettes** × light/dark mode
- **Custom colors**: pick your own 3 colors
- **6 sizes**: Desktop 4K (3840×2160), QHD (2560×1440), HD (1920×1080), iPhone (1290×2796), Mobile (1080×1920), Square (1080×1080)
- **Shuffle**: one click, new variation
- **Download PNG** at full resolution
- **Bilingual**: Indonesian / English
- **Dark mode UI** — independent from the wallpaper's own light/dark mode: the nav toggle themes the app only (saved, follows the OS on first visit, applied before first paint), the panel's Wallpaper Mode picks the palette variant only

## Tech

Single `index.html` — vanilla JS + Canvas API. No build, no dependencies, no backend.

Mobile-optimized: preview renders are capped at 1280px on the long side (downloads re-render the identical seed at full resolution), phone visitors default to a phone size (1080×1920 / iPhone 1290×2796), and layered patterns keep the top of the frame calm for lock-screen clocks.

## Deploy

GitHub Pages: Settings → Pages → Deploy from branch `main` → `/ (root)`.

## License

MIT
