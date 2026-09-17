# Harness Engineering – SLD Editor

Standalone professional **electrical & solar single-line diagram editor**.
No build step. Open `index.html` in a browser or host it on any website.

## Live on your site

Copy `index.html` into your site root or a `/tools/sld/` folder.

```html
<iframe src="/tools/sld/index.html" style="width:100%;height:90vh;border:0"></iframe>
```

Or open the file directly — it is self-contained.

## Features

- Solar + electrical symbol palette (PV, combiner, isolators, inverter, battery, MCB, RCD, meter, busbar, transformer, generator, motor, earth, grid)
- Drag symbols onto the canvas
- Click two pins to draw an orthogonal connection
- Move, snap-to-grid, delete, zoom
- Title block (project, site, drawn-by)
- Templates: rooftop PV, hybrid + battery
- Save / open JSON
- Export SVG and PNG
- Auto-save in the browser (`localStorage`)

## GitHub Pages

Settings → Pages → Deploy from branch → `main` / root.

Then:

https://nainglinkyawep.github.io/harness-sld-editor/

## Brand

Navy `#0b3d66` and teal `#0d9488` to match Harness Engineering tools.
