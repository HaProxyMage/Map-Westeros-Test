# Westeros Map Viewer

## GitHub Pages deployment

1. **Settings → Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your default branch), `/ (root)` folder
2. Ensure `index.html` is at the repository root (already present).
3. Keep the tiles directory name **case-sensitive**: the code loads tiles from `Tiles/`.
4. If you change the tiles folder name, update `index.html` and `viewer.html` accordingly.

## Local preview

```bash
python -m http.server 8000 --bind 0.0.0.0
```

Then open `http://127.0.0.1:8000/`.
# Westeros Interactive Map Project

## Overview
This project is an interactive map of Westeros, designed to allow users to explore the geographical features and locations from the popular series.

## Features
- Interactive exploration of the map
- Markers for key locations
- User-friendly interface

## Installation
1. Clone the repository: `git clone https://github.com/HaProxyMage/Map-Westeros-Test.git`
2. Navigate to the project directory.
3. Open `index.html` in your web browser (redirects to `viewer.html`).

## Deployment
This project is configured for GitHub Pages deployment using the static workflow. The site is automatically deployed when changes are pushed to the `main` branch.

## Usage
- Click on markers to learn more about each location.
- Zoom in and out for a detailed view.

## Contributing
If you'd like to contribute, please fork the repo and submit a pull request.

## License
This project is licensed under the MIT License.
