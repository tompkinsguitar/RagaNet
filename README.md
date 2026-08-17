# RagaNet

RagaNet is an interactive graph of the 72 Melakarta ragas. It presents the same legal-choice network in Carnatic swaras and Western pitch notation with Sa set to C.

## Downloads

- [Download the complete project as a ZIP](https://github.com/tompkinsguitar/RagaNet/archive/refs/heads/main.zip)
- [Download the standalone interactive visualization](https://github.com/tompkinsguitar/RagaNet/raw/refs/heads/main/melakarta_visualization.html)
- [Download the editable SVG](https://github.com/tompkinsguitar/RagaNet/raw/refs/heads/main/melakarta_visualization.svg)

The HTML file is self-contained: download it, then open it in a modern browser. No installation is required.

## Features

- Shows the exact Melakarta topology: 6 R/G choices × 2 Madhyama choices × 6 D/N choices.
- Keeps every pitch stack ordered from lowest at the bottom to highest at the top.
- Guides users through a legal `Ri → Ga → Ma → Dha → Ni` path.
- Names the resulting Melakarta raga and chakra, plus a common Western scale or mode equivalent when available.
- Plays each selected pitch and the completed ascending/descending scale.
- Includes both an interactive HTML version and an editable SVG.

## Open the visualization

Open `melakarta_visualization.html` in a modern browser.

## Files

- `melakarta_visualization.html` — standalone interactive visualization
- `melakarta_visualization.svg` — editable static vector graphic
- `generate_melakarta_visualization.mjs` — shared graph data and generator

## Regenerate the outputs

```bash
node generate_melakarta_visualization.mjs .
```

No package installation or build step is required.
