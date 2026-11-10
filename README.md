# Roshni Ka Tilak — 3D Bhai Dooj

A mobile-first interactive cinematic prototype built with Three.js. It includes a 3D Diwali-inspired scene, seven story stages, diya lighting, aarti rounds, tilak, laddoo offering, memory cards, shagun and a letter overlay.

## Run locally

This project uses ES modules and a Three.js CDN import, so run it from a local web server (not by opening `index.html` directly).

### Option A — Python

```bash
python -m http.server 8080
```

Then open `http://localhost:8080` in your browser from this folder.

### Option B — Node

```bash
npx serve .
```

## Project files

- `index.html` — mobile-first page structure
- `styles.css` — responsive cinematic UI
- `app.js` — Three.js scene, animations and story interactions

## Current prototype notes

- Character figures and the memory gallery are procedural placeholders, not final AI-generated character models or personal photographs.
- The sound toggle enables small synthesized chimes; licensed background music can be added later.
- The current letter and names are sample copy (Anaya and Rohan).
- Three.js is loaded from jsDelivr, so the first run requires an internet connection.

## Next production steps

1. Replace placeholder figures with consistent AI-generated brother/sister character assets or rigged 3D models.
2. Add real memory photo uploads and a sender-side customization page.
3. Add professionally rendered scene clips if a finished cinematic video export is required.
4. Optimize textures, shadows and model complexity for mid-range Android phones.
5. Deploy to a static host and create unique shareable links.
