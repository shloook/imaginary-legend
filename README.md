# Project: Animated_Flower
Simple collection of browser-based visual experiments and demos built with HTML, CSS and JavaScript (Three.js used in some files).

## Files in this folder
- ani2flower.html — Animated flower circle canvas demo.
- ani2flower.js — (expected) script for ani2flower.html (ensure it exists alongside the HTML).
- styles.css — Project stylesheet used by HTML pages.
- read.md — This file (quick project summary).
- README.md — (optional) longer project readme if present.

## Requirements
- Modern browser (Chrome, Firefox, Safari).
- Optional: local static server to avoid file:// loading issues when using modules or external assets.

## Quick start (macOS)
1. Open terminal in project folder (VS Code: View → Terminal).
2. Start a simple HTTP server:
   - Python 3:
     ```
     python3 -m http.server 8000
     ```
   - Node (http-server):
     ```
     npm install -g http-server
     http-server -p 8000
     ```
3. Open the demo pages:
   - http://localhost:8000/ani2flower.html
   - http://localhost:8000/galaxy.html

## Notes
- Ensure related JS and CSS files are in the same directory as their HTML or update the <link> / <script> paths.
- If an HTML page runs code before the DOM is ready, either place its script before </body> or add `defer`/`DOMContentLoaded` handling.
- For Three.js demos, prefer using the CDN or a local copy; run via HTTP server to avoid CORS issues.

## Debugging
- Use DevTools Console for errors (missing files, syntax errors).
- Confirm file names/paths match those referenced in HTML.
- If animations don't appear, verify canvas sizing and that corresponding JS files are loaded.

License: MIT (default, adapt as needed).
```// filepath: /Users/shlok/cosmic_partical_symphony/read.md
# Project: Cosmic Particle Symphony

Simple collection of browser-based visual experiments and demos built with HTML, CSS and JavaScript (Three.js used in some files).

## Files in this folder
- ani2flower.html — Animated flower circle canvas demo.
- ani2flower.js — (expected) script for ani2flower.html (ensure it exists alongside the HTML).
- galaxy.html — 3D Milky Way Explorer demo (uses Three.js).
- hh.html — HTML fragment / alternate page (project history or variant).
- main.js / galaxy.js — Main application script(s) for the galaxy explorer.
- styles.css — Project stylesheet used by HTML pages.
- read.md — This file (quick project summary).
- README.md — (optional) longer project readme if present.

## Requirements
- Modern browser (Chrome, Firefox, Safari).
- Optional: local static server to avoid file:// loading issues when using modules or external assets.

## Quick start (macOS)
1. Open terminal in project folder (VS Code: View → Terminal).
2. Start a simple HTTP server:
   - Python 3:
     ```
     python3 -m http.server 8000
     ```
   - Node (http-server):
     ```
     npm install -g http-server
     http-server -p 8000
     ```
3. Open the demo pages:
   - http://localhost:8000/ani2flower.html
   - http://localhost:8000/galaxy.html

## Notes
- Ensure related JS and CSS files are in the same directory as their HTML or update the <link> / <script> paths.
- If an HTML page runs code before the DOM is ready, either place its script before </body> or add `defer`/`DOMContentLoaded` handling.
- For Three.js demos, prefer using the CDN or a local copy; run via HTTP server to avoid CORS issues.

## Debugging
- Use DevTools Console for errors (missing files, syntax errors).
- Confirm file names/paths match those referenced in HTML.
- If animations don't appear, verify canvas sizing and that corresponding JS files are loaded.

License: MIT (default, adapt as needed).
