# Vanishing Grids

A free, browser-based perspective grid maker for artists. Everything runs on the page, with no build step and no server code.

## Grid types

- 1-, 2- and 3-point perspective, with draggable vanishing points (on or off the page), and an optional 60° cone of vision
- 4-point curvilinear, with separate left–right and top–bottom spans for panoramas
- 5-point curvilinear (fisheye), 180° equidistant
- Isometric, true 30° or pixel-art 2:1

## Tools

- Boxes in 1, 2 and 3-point and isometric grids: drag to move, drag the handles to set width, depth and height. Boxes follow the vanishing points and appear in every export.
- Reference image: put a photo or sketch under the grid at any opacity, optionally included in downloads.
- Copy link: shares the current settings and boxes in the URL (not the reference image).
- Light, dark, system and WastedDesigner colour schemes.

## Exports

- PNG at 150, 300 or 600 dpi, with a transparent background option
- SVG (sized in mm for print presets)
- PDF (vector, built with jsPDF)

## Page sizes

A5, A4, A3, Letter, Tabloid, Full HD, QHD, 4K, iPad Pro, square, or custom.

## Running it

Open `index.html` in a browser, or serve the folder as a static site (GitHub Pages, Netlify, or any web host).

## Dependencies

- jsPDF 2.5.1 from cdnjs, used for PDF export only
- Google Fonts: Bricolage Grotesque, Instrument Sans and IBM Plex Mono

Settings and the reference image are saved in the browser's localStorage.

## Self-check

Open the page with `?selftest` (for example `index.html?selftest`) and check the console: it confirms that box edges meet their vanishing points and that handle drags give back the right sizes.
