# AI-XPERIENCE

An experiment to see how far an AI model can go when asked to build an advanced, animated web page from a single prompt.

## Rules

- One prompt to build the page. One follow-up prompt is allowed, for minor corrections only.
- One self-contained HTML file per page, with HTML, CSS and JavaScript inline.
- No frameworks, libraries or external assets.
- The model picks the creative concept itself.

## Pages

| Page | Technique | Model | Tokens (est.) | Prompts | Size |
|---|---|---|---|---|---|
| [Abyss](pages/abyss.html) | Canvas 2D | Claude Opus 5.5 | ~60K | 1 + 1 | 28 KB |
| [Mercurial](pages/mercurial.html) | WebGL2 raymarching | Claude Opus 5.5 | ~55K | 1 + 1 | 37 KB |
| [Night atlas](pages/night-atlas.html) | Canvas 2D, projected 3D mesh | GPT-6 Atra | ~57K | 1 + 1 | 21 KB |
| [Foldwake](pages/foldwake.html) | Canvas 2D, mirror geometry | GPT-6 Atra | ~60K | 1 | 21 KB |

**Abyss.** Scrolling takes you down from the ocean surface to 4000 m. Glowing plankton drift on a flow field and react to the cursor, and jellyfish with physically simulated tentacles swim through the dark. Clicking sends out a ring of light.

**Mercurial.** A liquid-metal sculpture rendered in real time with a WebGL2 shader. Clicking adds drops, holding then releasing sends them flying, dragging orbits the camera, and four materials (chrome, iridescent, glass, magma) crossfade on demand. It has optional generated sound and lowers its resolution automatically to stay smooth.

**Night atlas.** A winged constellation moves through a celestial chart with rippling translucent wings. Drag to draw a constellation, then release it to watch it drift away. A button creates varied moths, fish, spirals, stars and serpentine wanderers, optional synthesized chimes accompany the sky, and animation can be paused. Reduced-motion preferences start the scene paused.

**Foldwake.** A game about folding space to bring drifting lights home. Draw a crease and release to reflect nearby sparks across it, using ghost previews to aim for the central ring. Rescue 18 lights in 90 seconds while moving tears swallow sparks. Folds recharge, multi-catches refund energy, and optional synthesized tones accompany each fold. Supports mouse, touch and keyboard controls.

The Abyss and Mercurial correction rounds fixed small issues: tentacles glitching during fast scrolling on Abyss, and the material name being cut off on Mercurial. Night atlas received a correction to vary the generated wanderer shapes.

## Viewing

Open `index.html` in a recent browser. It is a portfolio page listing all four pieces. Hovering a card loads a live preview, and each card has a button that opens the page in a new tab.

No build step or server is needed. Mercurial requires WebGL2 and runs best on a dedicated or recent integrated GPU.

## Structure

```
AI-XPERIENCE/
├── index.html        Portfolio page
├── README.md
└── pages/
    ├── abyss.html
    ├── foldwake.html
    ├── mercurial.html
    └── night-atlas.html
```

## About the token figures

The token counts are rough estimates, not billing data. They include the context sent to the model, the generated code and the correction round.
