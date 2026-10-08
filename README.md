# THE HUNT // OPERATION RAID

A static, bilingual (English/French) cyber escape-game experience.

## Play locally
Open index.html in a modern browser. No package manager or build step is required.

## Publish with GitHub Pages
The repository includes a GitHub Actions workflow that publishes the static site when changes are pushed to main. In **Settings → Pages**, choose **GitHub Actions** as the build and deployment source if GitHub asks for a source selection. The published URL should be:

https://andreasebuna-cmd.github.io/thehuntdiscord/

The first deployment may take a few minutes.

## Features
- Five linked phases and 100 distinct branch transitions per phase (10 branch families × 10 route variants).
- English/French interface switching.
- Global 20-minute countdown, persisted through in-app navigation and page refresh in the current browser tab session.
- Five-minute global alert and one-minute staged interface disintegration.
- Interactive scene hotspots, inspection popups, evidence inventory, hints, route map, detours, setbacks, shortcuts and multiple endings.
- Mouse parallax, blue sci-fi HUD, responsive layout and reduced-motion support.

## Notes
This is a fictional game simulation. It does not scan, attack or modify real systems. The timer state is stored in the browser's sessionStorage; starting a new operation resets the run.
