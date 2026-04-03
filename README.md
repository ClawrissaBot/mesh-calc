# 🔩 Mesh Calc

A simple web calculator for wire mesh filter open area.

**Input:** wire diameter + gap size → **Output:** % open area, mesh count, and total open area for a given filter size.

## Usage

Just open `index.html` in a browser — no build step, no dependencies.

Or use GitHub Pages: enable Pages in repo settings → deploy from `main` branch root.

## Formula

```
Open Area % = (gap / (gap + wire_diameter))² × 100
```

Assumes square woven mesh with equal spacing in both directions.

## Features

- Wire diameter in **mm**, **inches**, or **AWG gauge**
- Gap size in **mm** or **inches**
- Optional circular filter diameter for total open area (mm²/cm²/m²)
- Auto-calculated mesh count (wires per inch)
- Color-coded results (green ≥50%, yellow ≥25%, red <25%)
- Live mesh preview visualization
- Zero dependencies — single HTML file
