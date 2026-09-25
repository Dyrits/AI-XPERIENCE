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
| [Echoveil](pages/echoveil.html) | Canvas 2D, sonar reveal | GLM-5.3 | ~58K | 1 | 33 KB |
| [Umbralux](pages/umbralux.html) | Canvas 2D, raycast optics | Gemini 3.8 Flash | ~52K | 1 | 46 KB |
| [Estuary](pages/estuary.html) | Canvas 2D, curl-noise flow field | DeepSeek V4 Pro | ~55K | 1 | 28 KB |
| [The last warm window](pages/the-last-warm-window.html) | Canvas 2D, animated narrative | GPT-6 Astra | ~58K | 1 + 2 | 23 KB |
| [Lifeline](pages/lifeline.html) | Canvas 2D, single continuous line | Claude Opus 5.5 | ~150K | 1 | 34 KB |
| [Starshard](pages/starshard.html) | Canvas 2D, roguelike shooter | GLM-5.3 | ~70K | 1 + 2 | 80 KB |
| [Vesper](pages/vesper.html) | Canvas 2D, idle clicker | Claude Opus 5.5 | ~150K | 1 + 1 | 78 KB |

**Abyss.** Scrolling takes you down from the ocean surface to 4000 m. Glowing plankton drift on a flow field and react to the cursor, and jellyfish with physically simulated tentacles swim through the dark. Clicking sends out a ring of light.

**Mercurial.** A liquid-metal sculpture rendered in real time with a WebGL2 shader. Clicking adds drops, holding then releasing sends them flying, dragging orbits the camera, and four materials (chrome, iridescent, glass, magma) crossfade on demand. It has optional generated sound and lowers its resolution automatically to stay smooth.

**Night atlas.** A winged constellation moves through a celestial chart with rippling translucent wings. Drag to draw a constellation, then release it to watch it drift away. A button creates varied moths, fish, spirals, stars and serpentine wanderers, optional synthesized chimes accompany the sky, and animation can be paused. Reduced-motion preferences start the scene paused.

**Foldwake.** A game about folding space to bring drifting lights home. Draw a crease and release to reflect nearby sparks across it, using ghost previews to aim for the central ring. Rescue 18 lights in 90 seconds while moving tears swallow sparks. Folds recharge, multi-catches refund energy, and optional synthesized tones accompany each fold. Supports mouse, touch and keyboard controls.

**Echoveil.** A sonar-stealth game in a cave that only exists where sound has touched it. The world is pitch black: releasing a ping paints expanding rings of light over the walls for a few seconds, and a held charge sends a louder, wider burst. Quiet taps are safe, but bursts — and the pearls, and your own fading halo — draw the attention of lurkers that hunt the source of every echo. Gather seven pearls to open the gate, follow its slow pulses to the far side of the cave, and get out before your light gutters out.

**Umbralux.** A spatial game of living light and sheltering shade. You are a wandering spark of sunlight in an ancient sundial sanctum. Moving your radiant core casts real-time geometric shadows from monolithic stone pillars. Bathe ancestral Sunstones in direct light to ignite them, but use the pillars' shadows to shelter delicate Umbral Orchids—your direct rays scorch them! Focus your beam to banish predatory Gloom Stalkers prowling in the dark, and discharge Eclipse Novas to survive across three escalating ritual chambers.

**Estuary.** A tool for sculpting invisible currents and harvesting them as art. A divergence-free curl-noise flow carries thousands of glowing particles, and you reshape the current by dropping sources, sinks, vortices and repellers — all mapped onto a torus so the field tiles perfectly by construction. Palettes, flow strength and trail persistence are tunable, and a single button exports a seamless generative texture (up to 4096 px) for wallpapers and backgrounds.

**The last warm window.** A two-minute story about a mother who brings two cups of tea to an abandoned station. Passing trains carry memories of her daughter while rain turns to snow and the years pass. Holding a memory reveals her daughter beside the bench and slows the story. Includes six selectable chapters, optional synthesized music, pause and replay controls, and reduced-motion playback.

**Lifeline.** A life told as a single ink line drawn on paper. The line gets a heartbeat, loops like a child at play, climbs mountains, then meets a red thread: they dance, draw a heart and build a house, and a small gold line appears between them and flies off as a kite. When the red thread comes to rest, the ink line circles it once and carries on with a thin red strand wound around it. At the end the camera steps back and the whole life appears as one drawing. Watercolour washes bloom behind each chapter, and optional synthesized music and heartbeats follow the pen. Hold the mouse or Space to hurry time.

**Starshard.** A neon space-shooter roguelike. Fly against escalating waves of six enemy types — chasers, darts, gunners, splitters, orbiters and tanks — and bring down the multi-phase Dreadnought every fifth wave. Kills drop energy shards that charge an Overdrive meter for slow-motion overclocked fire, and clearing a wave lets you draft one of three upgrade modules: spread, pierce, ricochet, crits, homing missiles, a siege laser, orbiting drones, shields and more, stacking into a different build every run. Combos multiply score, dashes grant brief invulnerability, best runs persist locally, and sound and music are synthesized in the browser. The game needs a keyboard and mouse, and refuses to start on touch devices.

**Vesper.** An idle clicker set on the last day before a Hush from beyond the sky swallows sound, then light. Strike a belfry bell as its halo closes for true strikes that build harmony and fill a city-wide Peal, raise nine kinds of chimes that ring on their own, catch drifting moth-lanterns for bursts and stolen minutes, and cast a Great Bell in five stages before dusk. Five chapters each force a choice with a visible effect and a hidden echo, and the choices change the ending. Each run ends when the Hush arrives and carries echoes back into permanent recollections, so every morning reaches further. A tower clock counts toward midnight, the synthesized bell dulls as the dark approaches, and progress saves locally.

The Abyss and Mercurial correction rounds fixed small issues: tentacles glitching during fast scrolling on Abyss, and the material name being cut off on Mercurial. Night atlas received a correction to vary the generated wanderer shapes. The last warm window received a correction to ground the figures and train and align the distant city with the hillside. A second correction removed an extra line extending from the daughter's hand. Vesper received a correction that set the bell inside a belfry tower instead of in open air. Starshard needed two correction rounds: crash fixes (a palette key mismatch that crashed the game when splitters appeared, and a music-sequencer index bug that crashed the run seconds after launch), and a desktop-only gate that blocks the game on touch devices.

## Viewing

Open `index.html` in a recent browser. It is a portfolio page listing the pieces. Hovering a card loads a live preview, and each card has a button that opens the page in a new tab.

No build step or server is needed. Mercurial requires WebGL2 and runs best on a dedicated or recent integrated GPU.

## Structure

```
AI-XPERIENCE/
├── index.html        Portfolio page
├── README.md
└── pages/
    ├── abyss.html
    ├── echoveil.html
    ├── estuary.html
    ├── foldwake.html
    ├── lifeline.html
    ├── mercurial.html
    ├── night-atlas.html
    ├── starshard.html
    ├── the-last-warm-window.html
    ├── umbralux.html
    └── vesper.html
```

## About the token figures

The token counts are rough estimates, not billing data. They include the context sent to the model, the generated code and the correction round.
