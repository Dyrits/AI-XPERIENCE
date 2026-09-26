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
| [Abyss](https://dyrits.github.io/AI-XPERIENCE/pages/abyss.html) | Canvas 2D | Claude Opus 5.5 | ~60K | 1 + 1 | 28 KB |
| [Mercurial](https://dyrits.github.io/AI-XPERIENCE/pages/mercurial.html) | WebGL2 raymarching | Claude Opus 5.5 | ~55K | 1 + 1 | 37 KB |
| [Night atlas](https://dyrits.github.io/AI-XPERIENCE/pages/night-atlas.html) | Canvas 2D, projected 3D mesh | GPT-6 Atra | ~57K | 1 + 1 | 21 KB |
| [Foldwake](https://dyrits.github.io/AI-XPERIENCE/pages/foldwake.html) | Canvas 2D, mirror geometry | GPT-6 Atra | ~60K | 1 | 21 KB |
| [Echoveil](https://dyrits.github.io/AI-XPERIENCE/pages/echoveil.html) | Canvas 2D, sonar reveal | GLM-5.3 | ~58K | 1 | 33 KB |
| [Umbralux](https://dyrits.github.io/AI-XPERIENCE/pages/umbralux.html) | Canvas 2D, raycast optics | Gemini 3.8 Flash | ~52K | 1 | 46 KB |
| [Estuary](https://dyrits.github.io/AI-XPERIENCE/pages/estuary.html) | Canvas 2D, curl-noise flow field | DeepSeek V4 Pro | ~55K | 1 | 28 KB |
| [The last warm window](https://dyrits.github.io/AI-XPERIENCE/pages/the-last-warm-window.html) | Canvas 2D, animated narrative | GPT-6 Astra | ~58K | 1 + 2 | 23 KB |
| [Lifeline](https://dyrits.github.io/AI-XPERIENCE/pages/lifeline.html) | Canvas 2D, single continuous line | Claude Opus 5.5 | ~150K | 1 | 34 KB |
| [Starshard](https://dyrits.github.io/AI-XPERIENCE/pages/starshard.html) | Canvas 2D, roguelike shooter | GLM-5.3 | ~70K | 1 + 2 | 80 KB |
| [Vesper](https://dyrits.github.io/AI-XPERIENCE/pages/vesper.html) | Canvas 2D, idle clicker | Claude Opus 5.5 | ~150K | 1 + 1 | 78 KB |
| [Echo Ward](https://dyrits.github.io/AI-XPERIENCE/pages/echo-ward.html) | Canvas 2D, tower defense | Claude Opus 5.5 | ~170K | 1 + 1 | 71 KB |
| [Until the tide](https://dyrits.github.io/AI-XPERIENCE/pages/until-the-tide.html) | Canvas 2D, escape game | GPT-6 | ~70K | 1 | 54 KB |
| [Longhand](https://dyrits.github.io/AI-XPERIENCE/pages/longhand.html) | Canvas 2D, drawn-line runner | GLM-5.3 | ~65K | 1 + 1 | 34 KB |
| [Loaded](https://dyrits.github.io/AI-XPERIENCE/pages/loaded.html) | Canvas 2D, dice roguelike | Claude Opus 5.5 | ~200K | 1 + 1 | 96 KB |
| [Enough](https://dyrits.github.io/AI-XPERIENCE/pages/enough.html) | Canvas 2D, motion graphic | Claude Opus 5.5 | ~100K | 1 | 32 KB |
| [Replace you](https://dyrits.github.io/AI-XPERIENCE/pages/replace-you.html) | Canvas 2D, motion graphic | GTP-5 Astra | ~51K | 1 | 15 KB |
| [Tick](https://dyrits.github.io/AI-XPERIENCE/pages/tick.html) | DOM + Canvas 2D, scroll-driven explainer | Claude Opus 5.5 | ~120K | 1 | 60 KB |
| [Murmur](https://dyrits.github.io/AI-XPERIENCE/pages/murmur.html) | Canvas 2D, 3D flocking | Claude Opus 5.5 | ~90K | 1 | 44 KB |
| [Somewhere, softly](https://dyrits.github.io/AI-XPERIENCE/pages/somewhere-softly.html) | Canvas 2D, projected 3D mobile | GTP-6 Astra | ~62K | 1 | 33 KB |

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

**Echo Ward.** A tower defense where you defend time, not a place. The map is a causal graph of historical moments shown as three stacked layers (Past, Present and Future), and corruption leaks from rifts along causal links toward five anchor events. Wards anchor to one moment in one layer and only touch anomalies in that layer: Past wards weaken and thin out rift spawns, Present wards reach further, Future wards execute and trigger chain bursts across every layer. Each ward has a causal echo: Sniper kills erase anomalies from the next wave, Stasis rewinds damaged anchors, Fracture splits anomalies and leaves the next wave weak to a chosen damage type, and Paradox cancels abilities outright. Ripple Creeps multiply, Overwrite Brutes sink through the layers and scar anchors permanently, Loopers double back, Retroviruses run backward through the Past unmaking wards, and Divergence Events open alternate-timeline branches that add new rifts and paths mid-run. Twenty waves, synthesized sound, best run saved locally.

**Until the tide.** An escape game set in your father's lighthouse after a storm floods the causeway. Search three illustrated rooms, decipher the keeper's tide notes, restore an electrical circuit, align the lantern's lens and signal a rescue launch. Animated rain and waves surround the tower, and the machinery responds as you repair it. Includes an automatic notebook, graduated hints, optional synthesized sound, local saves and reduced-motion support. There is no countdown.

**Longhand.** A runner drawn in real time. A stickman sets out along a hand-inked road that keeps running out on him, and the longer he survives the faster he goes. You are the pen: draw lines to bridge chasms, ramp up cliffs and roof him against a gathering storm of falling ink — the rain punches holes in your lines, globs tear straight through several at once, and after a while tumbling erasers arrive to eat the road itself. Ink is limited but flows back with time, and faster when you block the rain, crumble an eraser or reach a milestone; he can even be caught mid-fall, and steep lines are walls while gentle slopes are roads. Staying wedged against a wall for five seconds throws him back to the left of the screen and costs a heart. A red scarf is the only colour he owns. Best distance saved locally, synthesized sound, pause and restart, reduced-motion support.

**Loaded.** A Balatro-style roguelike played with dice. Roll five 3D dice that tumble across a felt table, mark the ones to reroll from a limited pool, then play the best hand they make, from High Die to Five of a Kind. Each hand type gives Chips and Mult, scored dice add their pips, and the total is Chips × Mult, tallied effect by effect. Beat a small, big and boss blind in each of eight antes, with bosses that debuff faces, hide dice, halve rerolls or punish repeated hands. The shop sells 34 Jokers (retriggers, scaling xMult, a Mirror that copies its neighbour, an extra sixth die), Stars that level up a hand the moment they are bought, and Glyphs that permanently rewrite the face showing on a die: Gold, Glass, Bonus, Mult, Wild or Steel, or one pip more or less. Your five dice become your deck. Endless mode after the final ante, synthesized sound and lounge music, adjustable game speed, best runs saved locally.

**Enough.** A ten-second looping motion graphic on the theme "One prompt is enough". A prompt is typed into an input box and squashed into a spark, which bursts into particles while CODE, MOTION, COLOR and SOUND slam across on diagonal bands. The particles settle into a tile grid that ripples and flips into rings of colour, then scatter into a spinning carousel of animated windows around a giant outlined ONE. Everything collapses into a coral disc that shrinks into the full stop of the title, and that full stop turns into the caret of the next loop. Every frame is computed from the time alone, so the timeline can be paused, scrubbed and stepped. Synthesized score in sync with the picture, reduced-motion support.

**Replace you.** An eighteen-second looping motion graphic on the theme "AI will replace you. Will it kill you?".
Human silhouettes pass through a scanner and are duplicated, oversized red typography asks the question, and a pulse goes flat before beating again beneath "STILL HERE".
Acid green, red and paper white mark the seven scenes, ending with the question still open.
Includes optional synthesized sound, pause, timeline scrubbing, keyboard frame stepping and reduced-motion support.

**Tick.** A scroll-driven explainer of the JavaScript event loop. Six chapters (call stack, Web APIs and the task queue, microtasks, draining the queue, rendering, async/await) step through real snippets as you scroll: each call flies from the highlighted line onto the call stack, timers count down in the Web APIs panel, callbacks travel into the task or microtask queue, and a pointer circles the event loop wheel through task, microtask and render phases while the console fills in. Scrolling back rewinds everything. A button runs each snippet for real and checks the predicted output, a recap lists the four rules with pseudo-code, and a live lab freezes a JavaScript-driven animation by blocking the stack or flooding microtasks, then shows the same work split into tasks staying smooth. Keyboard stepping, chapter rail, reduced-motion support.

**Murmur.** A poem written by a murmuration of starlings over a lake at dusk. Thousands of birds fly as a 3D flock, each one following its seven nearest neighbours inside a roaming soft envelope that stretches, folds and sometimes splits in two, and every so often the flock streams into a line of the poem, written from left to right, then lets it go. Nine lines play while the sun sets, stars come out and the moon rises; after the last line the flock pours down into the reeds for the night and rises again at dawn to write "your turn". Move to be the wind, move fast to be the hawk and send panic waves through the flock (even through a finished line), hold to gather the birds into a swirling ball, touch the water to make ripples, or type a word and press Enter for the flock to write it. Left alone after the poem, the flock rewrites your earlier words. The sky and flock are mirrored in a rippling lake between swaying reeds, and optional synthesized wind, wing rush, pads and bells follow the flock.

The Abyss and Mercurial correction rounds fixed small issues: tentacles glitching during fast scrolling on Abyss, and the material name being cut off on Mercurial. Night atlas received a correction to vary the generated wanderer shapes. The last warm window received a correction to ground the figures and train and align the distant city with the hillside. A second correction removed an extra line extending from the daughter's hand. Vesper received a correction that set the bell inside a belfry tower instead of in open air. Starshard needed two correction rounds: crash fixes (a palette key mismatch that crashed the game when splitters appeared, and a music-sequencer index bug that crashed the run seconds after launch), and a desktop-only gate that blocks the game on touch devices. Longhand received a correction that breaks stalemates: a runner wedged against a wall for five seconds is thrown back to the left of the screen and loses a heart (with a little ink back), so a stalled run now costs lives instead of freezing; the same round lowered early cliff heights, moved ink milestones closer together and made the warning sign blink over his head. Loaded received a correction so that selling a Joker frees its slot in the shop immediately, and so that Stars apply on purchase instead of taking a consumable slot.

**Somewhere, softly.** Five miniature places hang from a wooden mobile: a village, an orchard, a lighthouse, a small sea with a sailboat and a solitary house. Drag to turn the sculpture, select an island to look closer and read its story, send a breeze through the hanging islands, or move the light from morning to night. Includes optional synthesized chimes, PNG postcard export, pause and reset controls, touch and keyboard input, and reduced-motion support. Everything is drawn in the file, with no external assets.

## Viewing

The portfolio is live at https://dyrits.github.io/AI-XPERIENCE/. Locally, open `index.html` in a recent browser. It is a portfolio page listing the pieces. Hovering a card loads a live preview, and each card has a button that opens the page in a new tab.

No build step or server is needed. Mercurial requires WebGL2 and runs best on a dedicated or recent integrated GPU.

## Structure

```
AI-XPERIENCE/
├── index.html        Portfolio page
├── README.md
└── pages/
    ├── abyss.html
    ├── echo-ward.html
    ├── echoveil.html
    ├── enough.html
    ├── estuary.html
    ├── foldwake.html
    ├── lifeline.html
    ├── loaded.html
    ├── longhand.html
    ├── mercurial.html
    ├── murmur.html
    ├── night-atlas.html
    ├── replace-you.html
    ├── somewhere-softly.html
    ├── starshard.html
    ├── the-last-warm-window.html
    ├── tick.html
    ├── umbralux.html
    ├── until-the-tide.html
    └── vesper.html
```

## About the token figures

The token counts are rough estimates, not billing data. They include the context sent to the model, the generated code and the correction round.
