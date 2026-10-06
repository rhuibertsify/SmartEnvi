[README.md](https://github.com/user-attachments/files/33116324/README.md)
# NYC SmartEnvi map

Static website. Open `index.html` through a web server (for example GitHub Pages), not by double-clicking it:
the street trees and building outlines are loaded from the `tiles/` folder as you zoom in, and browsers block
that when a page is opened straight from disk.

- `index.html` – the map (all other data is built into the page)
- `tiles/` – 40 data tiles with NYC Parks street and park trees and NYC building outlines

Data: NYC Open Data (NYC Parks, DEP, NYC Planning, NYC Health), The Nature Conservancy. See the Sources list in the map.
