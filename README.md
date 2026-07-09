# UFD Locations

A family location directory. Tap an NFC tag at home to open a clean categorized list of important places — house addresses, hypermarkets, hospitals — and navigate to any of them with Google Maps.

## Usage

1. Open https://Dawnuser.github.io/UFD-Locations
2. Tap a location card
3. Google Maps opens with directions to that place

## Files

- `index.html` — Categorized view with collapsible sections (default)
- `emoji-list.html` — Flat list with emoji markers
- `categorized.html` — Same categorized view as index (reference)

Each category shows the first 2 locations by default. Tap **Show all (N more)** to expand the rest.

## Features

- Dark/light theme toggle (persisted in localStorage)
- Collapsible sections — tap to show/hide extra locations
- Mobile-first, 520px max-width
- Google Maps directions via `maps.google.com/maps/dir/`

## Adding Locations

Edit the HTML files and push to GitHub. The NFC tag URL stays the same.

## Tech

Single-file HTML, CSS, JS. No frameworks, no build step.
