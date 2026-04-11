# AutoAnalyzerX IA

## Overview
Static HTML/CSS/JavaScript prototype for a predictive fleet maintenance dashboard. The app includes a Spanish landing page, a fleet monitoring dashboard, and a unit detail page with simulated diagnostics and charts.

## Project structure
- `index.html` / `principal.css`: Landing page.
- `index_secundario.html` / `secundario.css`: Fleet monitoring dashboard with simulated vehicle data.
- `index_tercero.html` / `tercero.css`: Vehicle detail dashboard styled as a standalone unit view, with simulated diagnostics, Chart.js charts, and manual recalculation controls.
- `README_FINAL.md`: Original project summary and author information.

## Runtime
- Static website served from the project root.
- Development workflow command: `python3 -m http.server 5000 --bind 0.0.0.0`.
- No package installation is required.

## Deployment
- Static deployment should serve the project root (`.`).