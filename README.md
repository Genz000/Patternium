# Patternium

**Seamless Pattern Studio** — a browser-based tool for designing perfectly tileable pattern tiles.

🔗 **[Live app](https://genz000.github.io/Patternium/)**

## What it does

The tile is treated as a torus: every element is drawn into the tile *and* wrapped across all 8 neighbor offsets, so anything you push over an edge reappears on the opposite side — guaranteeing a seamless repeat. A live 3×3 preview confirms the tiling before you export.

## Features

- **Upload** images (PNG · SVG · JPG) via drop zone, file picker, or drag-and-drop, plus 8 built-in vector shapes
- **Arrange** elements freely — they wrap live across tile edges
- **Resize** with corner handles or the Scale slider
- **Rotate** with the rotor handle or the Rotation slider
- Opacity, layer ordering, duplicate, center
- **Auto-arrange**: grid fill or scatter
- Adjustable tile size (128–1024px), background swatches incl. transparent
- Zoom / pan canvas
- **Export** a clean, perfectly tileable PNG at full resolution

## Shortcuts

| Action | Key |
| --- | --- |
| Move element | Drag · Arrow keys (Shift = ×10) |
| Resize | Drag corner handle |
| Rotate | Drag top dot |
| Delete | `Delete` / `Backspace` |
| Zoom | Scroll wheel |

## Running locally

It's a single self-contained `index.html` — no build, no dependencies. Open it in any modern browser.

---

Built with vanilla JS + Canvas.
