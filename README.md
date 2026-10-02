# AI-XPERIENCE

An experiment to see how far an AI model can go when asked to build an advanced, animated web page from a single prompt.

## Rules

- One prompt to build the page. One follow-up prompt is allowed, for minor corrections only.
- One self-contained HTML file per page, with HTML, CSS and JavaScript inline.
- No frameworks, libraries or external assets.
- The model picks the creative concept itself.

## Pages

| Page | Technique | Model | Prompts | Size |
|---|---|---|---|---|
| [Abyss](https://dyrits.github.io/AI-XPERIENCE/pages/abyss.html) | Canvas 2D | Claude Opus 5.5 | 1 + 1 | 28 KB |
| [Mercurial](https://dyrits.github.io/AI-XPERIENCE/pages/mercurial.html) | WebGL2 raymarching | Claude Opus 5.5 | 1 + 1 | 37 KB |
| [Night atlas](https://dyrits.github.io/AI-XPERIENCE/pages/night-atlas.html) | Canvas 2D, projected 3D mesh | GPT-6 Atra | 1 + 1 | 21 KB |
| [Foldwake](https://dyrits.github.io/AI-XPERIENCE/pages/foldwake.html) | Canvas 2D, mirror geometry | GPT-6 Atra | 1 | 21 KB |
| [Echoveil](https://dyrits.github.io/AI-XPERIENCE/pages/echoveil.html) | Canvas 2D, sonar reveal | GLM-5.3 | 1 | 33 KB |
| [Estuary](https://dyrits.github.io/AI-XPERIENCE/pages/estuary.html) | Canvas 2D, curl-noise flow field | DeepSeek V4 Pro | 1 | 28 KB |
| [The last warm window](https://dyrits.github.io/AI-XPERIENCE/pages/the-last-warm-window.html) | Canvas 2D, animated narrative | GPT-6 Astra | 1 + 2 | 23 KB |
| [Lifeline](https://dyrits.github.io/AI-XPERIENCE/pages/lifeline.html) | Canvas 2D, single continuous line | Claude Opus 5.5 | 1 | 34 KB |
| [Starshard](https://dyrits.github.io/AI-XPERIENCE/pages/starshard.html) | Canvas 2D, roguelike shooter | GLM-5.3 | 1 + 2 | 80 KB |
| [Last Orders](https://dyrits.github.io/AI-XPERIENCE/pages/last-orders.html) | Canvas 2D, botanical railshooter | GPT-6 Astra | 1 + 2 | 65 KB |
| [Vesper](https://dyrits.github.io/AI-XPERIENCE/pages/vesper.html) | Canvas 2D, idle clicker | Claude Opus 5.5 | 1 + 1 | 78 KB |
| [Echo Ward](https://dyrits.github.io/AI-XPERIENCE/pages/echo-ward.html) | Canvas 2D, tower defense | Claude Opus 5.5 | 1 + 1 | 71 KB |
| [Until the tide](https://dyrits.github.io/AI-XPERIENCE/pages/until-the-tide.html) | Canvas 2D, escape game | GPT-6 | 1 | 54 KB |
| [Longhand](https://dyrits.github.io/AI-XPERIENCE/pages/longhand.html) | Canvas 2D, drawn-line runner | GLM-5.3 | 1 + 1 | 34 KB |
| [Loaded](https://dyrits.github.io/AI-XPERIENCE/pages/loaded.html) | Canvas 2D, dice roguelike | Claude Opus 5.5 | 1 + 1 | 96 KB |
| [Enough](https://dyrits.github.io/AI-XPERIENCE/pages/enough.html) | Canvas 2D, motion graphic | Claude Opus 5.5 | 1 | 32 KB |
| [Replace you](https://dyrits.github.io/AI-XPERIENCE/pages/replace-you.html) | Canvas 2D, motion graphic | GPT-6 Astra | 1 | 15 KB |
| [Tick](https://dyrits.github.io/AI-XPERIENCE/pages/tick.html) | DOM + Canvas 2D, scroll-driven explainer | Claude Opus 5.5 | 1 | 60 KB |
| [Murmur](https://dyrits.github.io/AI-XPERIENCE/pages/murmur.html) | Canvas 2D, 3D flocking | Claude Opus 5.5 | 1 | 44 KB |
| [Somewhere, softly](https://dyrits.github.io/AI-XPERIENCE/pages/somewhere-softly.html) | Canvas 2D, projected 3D mobile | GTP-6 Astra | 1 | 33 KB |
| [Paperborough](https://dyrits.github.io/AI-XPERIENCE/pages/paperborough.html) | Canvas 2D, isometric city builder | GTP-6 Astra | 1 | 59 KB |
| [Nodal](https://dyrits.github.io/AI-XPERIENCE/pages/nodal.html) | Canvas 2D, particle transport + wave simulation | Space Bunny | 1 + 1 | 52 KB |
| [Percy](https://dyrits.github.io/AI-XPERIENCE/pages/percy.html) | DOM + Canvas 2D, fake installer comedy | Claude Sonnet 5.5 | 1 | 44 KB |
| [Carbon copy](https://dyrits.github.io/AI-XPERIENCE/pages/carbon-copy.html) | Canvas 2D, recorded-ghost puzzle | GPT-6 | 1 | 35 KB |
| [Drizzle](https://dyrits.github.io/AI-XPERIENCE/pages/drizzle.html) | Canvas 2D, animated short film | Claude Sonnet 5.5 | 1 | 49 KB |
| [Elsewhere](https://dyrits.github.io/AI-XPERIENCE/pages/elsewhere.html) | Canvas 2D, recursive zoom worlds (incomplete, untested) | GPT-6 Astra | 1 | 52 KB |
| [Needle](https://dyrits.github.io/AI-XPERIENCE/pages/needle.html) | DOM + Canvas 2D, regex workbench | Space Bunny | 1 | 73 KB |
| [Palimpsest](https://dyrits.github.io/AI-XPERIENCE/pages/palimpsest.html) | Canvas 2D, ink recognition + time scrubbing | Space Bunny | 1 + 2 | 96 KB |
| [Rewind](https://dyrits.github.io/AI-XPERIENCE/pages/rewind.html) | DOM + SVG, deckbuilder roguelike | Claude Opus 5.5 | 1 | 130 KB |

**Abyss.** Scrolling takes you down from the ocean surface to 4000 m. Glowing plankton drift on a flow field and react to the cursor, and jellyfish with physically simulated tentacles swim through the dark. Clicking sends out a ring of light.

**Mercurial.** A liquid-metal sculpture rendered in real time with a WebGL2 shader. Clicking adds drops, holding then releasing sends them flying, dragging orbits the camera, and four materials (chrome, iridescent, glass, magma) crossfade on demand. It has optional generated sound and lowers its resolution automatically to stay smooth.

**Night atlas.** A winged constellation moves through a celestial chart with rippling translucent wings. Drag to draw a constellation, then release it to watch it drift away. A button creates varied moths, fish, spirals, stars and serpentine wanderers, optional synthesized chimes accompany the sky, and animation can be paused. Reduced-motion preferences start the scene paused.

**Foldwake.** A game about folding space to bring drifting lights home. Draw a crease and release to reflect nearby sparks across it, using ghost previews to aim for the central ring. Rescue 18 lights in 90 seconds while moving tears swallow sparks. Folds recharge, multi-catches refund energy, and optional synthesized tones accompany each fold. Supports mouse, touch and keyboard controls.

**Echoveil.** A sonar-stealth game in a cave that only exists where sound has touched it. The world is pitch black: releasing a ping paints expanding rings of light over the walls for a few seconds, and a held charge sends a louder, wider burst. Quiet taps are safe, but bursts — and the pearls, and your own fading halo — draw the attention of lurkers that hunt the source of every echo. Gather seven pearls to open the gate, follow its slow pulses to the far side of the cave, and get out before your light gutters out.

**Estuary.** A tool for sculpting invisible currents and harvesting them as art. A divergence-free curl-noise flow carries thousands of glowing particles, and you reshape the current by dropping sources, sinks, vortices and repellers — all mapped onto a torus so the field tiles perfectly by construction. Palettes, flow strength and trail persistence are tunable, and a single button exports a seamless generative texture (up to 4096 px) for wallpapers and backgrounds.

**The last warm window.** A two-minute story about a mother who brings two cups of tea to an abandoned station. Passing trains carry memories of her daughter while rain turns to snow and the years pass. Holding a memory reveals her daughter beside the bench and slows the story. Includes six selectable chapters, optional synthesized music, pause and replay controls, and reduced-motion playback.

**Lifeline.** A life told as a single ink line drawn on paper. The line gets a heartbeat, loops like a child at play, climbs mountains, then meets a red thread: they dance, draw a heart and build a house, and a small gold line appears between them and flies off as a kite. When the red thread comes to rest, the ink line circles it once and carries on with a thin red strand wound around it. At the end the camera steps back and the whole life appears as one drawing. Watercolour washes bloom behind each chapter, and optional synthesized music and heartbeats follow the pen. Hold the mouse or Space to hurry time.

**Starshard.** A neon space-shooter roguelike. Fly against escalating waves of six enemy types — chasers, darts, gunners, splitters, orbiters and tanks — and bring down the multi-phase Dreadnought every fifth wave. Kills drop energy shards that charge an Overdrive meter for slow-motion overclocked fire, and clearing a wave lets you draft one of three upgrade modules: spread, pierce, ricochet, crits, homing missiles, a siege laser, orbiting drones, shields and more, stacking into a different build every run. Combos multiply score, dashes grant brief invulnerability, best runs persist locally, and sound and music are synthesized in the browser. The game needs a keyboard and mouse, and refuses to start on touch devices.

**Last Orders.** A runaway tea trolley has to cross an overgrown conservatory before the last orders go out. Pick your blend first — Assam runs rapid and balanced, Oolong scatters wide, Mint fires narrow and piercing — then ride the rails through the palm house, the orchid engine and the sky pavilion. A kettle cannon tracks the cursor, the pests answer with seed volleys, and every kill winds a pressure gauge that SPACE dumps across the screen as a steam blast; let it fill and the blast hits six harder. Between runs you draft from three fittings and stack them into a different trolley every time: double steeps, rose strainers, bone china, velvet brakes, second whistles. Three mechanical gardeners stand in the way, and the shift only ends well if the porcelain reaches the pavilion in one piece. It wants a keyboard and a mouse, and tells you so before it starts.

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

**Drizzle.** A wordless, Pixar-style animated short in seven scenes. A tiny cloud named Drizzle cannot make rain, and trails three huge storm clouds that sail over a dry valley without a drop. Left behind, he tries three times, with strain, a jump and a sad trombone, to water a wilting sunflower, and fails. The first drop only comes as a tear of affection: the sunflower revives, flowers bloom wherever the rain falls, a rainbow rises and the big clouds turn back to watch, until the now much smaller cloud falls asleep on the flower's head at dusk. Every frame is computed from the time alone, so the film can be paused, scrubbed, jumped by scene or opened at a moment with `#t=61`. Squash and stretch, expressive eyes, brows and mouths, camera pushes, colour grading, film grain, optional synthesized score and rain, keyboard shortcuts and reduced-motion support (gentler camera, no flashes).

**Elsewhere.** An endless zoom through ornate doorways into illustrated pocket worlds: terraced gardens, a lunar observatory, a desert oasis, a sea arch, a mushroom forest and a lantern-lit library. Each doorway opens onto the next world, and travel works in either direction with scroll, swipe, pinch or keyboard, or with automatic travel and optional generated audio. This is an incomplete piece: the model ran out of tokens before it could finish, and the page was never tested. It had no chance to iterate, so bugs, visual glitches or missing behaviour are expected and no correction round was possible.

**Palimpsest.** A whiteboard that keeps its own history. Every mark is stored together with the moment it was made, so the strip along the bottom edge is the session itself, drawn as a density plot of everything you have drawn: drag its head back and the board takes itself apart in reverse, far enough to stop halfway through a single stroke and watch the ink being pulled back, then play it forward again. Because every mark has a time, the pen can be loose: on release the board reads what you drew and resolves it — an uneven loop becomes an ellipse, four corners become a rectangle or a diamond, three become a triangle, and a straight flick with a barb on the end becomes an arrow. If it is not sure, the ink stays ink. Nothing is discarded: the original stroke is kept as a ghost underneath, one button away, which is the first draft. Connectors attach to a particular side of a shape and a particular spot along it, so dragging a box carries its arrows with it instead of sliding them around the outline; a dashed outline shows what an arrow is about to grab, both ends of a selected connector can be dragged directly, and grabbing the arrow itself pulls it off without it jumping. Also here: pen, highlighter, eraser, six shape tools, text and sticky notes, snapping alignment guides, selection with handles, align and distribute, undo and redo, pan and zoom, PNG and JSON export, optional synthesized pen sound, local saves, touch and keyboard input and reduced-motion support. Replaying the reel eases up when the session is long, so a board left open for an hour still plays back in seconds.
**Somewhere, softly.** Five miniature places hang from a wooden mobile: a village, an orchard, a lighthouse, a small sea with a sailboat and a solitary house. Drag to turn the sculpture, select an island to look closer and read its story, send a breeze through the hanging islands, or move the light from morning to night. Includes optional synthesized chimes, PNG postcard export, pause and reset controls, touch and keyboard input, and reduced-motion support. Everything is drawn in the file, with no external assets.

**Paperborough.** A city builder drawn as a folded-paper town, with pencil outlines, lavender roofs, sage trees and a paper river. Lay roads and bridges to connect homes, markets and paper mills to the town hall. Residents arrive as days pass, jobs and gardens affect happiness, and taxes and mills supply paper for construction. Seven buildable pieces, building upgrades and six town goals let the settlement grow at your own pace. Includes local saves, undo, pause and manual day advancement, optional synthesized sound, PNG postcard export, mouse and keyboard controls, touch panning and pinch zoom, and reduced-motion support. All artwork is generated in the file, with no external assets.

**Nodal.** Chladni's 1787 experiment, rebuilt: sand on a vibrating plate, finding the lines where the metal does not move. The plate is a square held at its rim, and its mode shapes are the classical sums and differences of cosines, so the boundary is nodal too and sand gathers along the edge as well as across the figure. Nothing is painted — several thousand grains are pushed every frame down the gradient of the squared displacement, so they crawl into the nodal lines and pile up there on their own, over a damped wave equation that carries genuine ripples from every strike. Twelve preset modes, m·n steppers and difference/sum switches give the full figure set; a second mode can be mixed in for interference patterns, or morphed through continuously. Tune the drive frequency to a resonance on the CRT scope and the plate rings up, the figure brightens and the synth sings the mode's own pitch; off resonance the glow fades and the sand barely stirs. Drag to rake the sand, click or press space to strike the plate, and save the result as a captioned PNG. Synthesized sound, pause, pointer and touch input, and reduced-motion support.

**Percy.** A fake installer starring a progress bar with a face. Percy is loading something and has opinions about it: his percentage goes backwards, a fake-out races to 97% and is taken back, he asks you to look away because he has stage fright, and the last percent creeps through 99.9, 99.99 and 99.999 while his estimate stays at "1 second (since 12:00)". The page reacts to you. Pressing Hurry up makes him slower and eventually suspends the button, Cancel starts a second bar to do the cancelling, and the window X is declared decorative. Poking his face squashes him, wiggling the mouse gets called out, switching tabs makes him sulk on your return, and the desktop icons talk back. His eyes follow the cursor, his mood changes the face, colour and particles, and the tab title shows the live percentage. After 100% a receipt counts your hurry-ups, cancels, pokes and absences and gives a verdict. Optional synthesized blips and fanfare, a run counter in local storage, reduced-motion support.

**Carbon copy.** A time-loop puzzle in a department of repeated efforts, drawn on cream paper with carbon-blue ghosts, brass gates and a red original. Move through a room, stop on a pressure plate and seal a copy of the attempt. Each copy replays the recorded route and stays at its final position, holding a switch while the original moves on. Five chambers build from one switch to a chain of gates held by four copies, with a release slip that only the original can collect and carry back to the exit. Every attempt has thirty seconds, and the clock starts when you move. Includes undo, chamber hints, unlocked-chamber selection, local progress saves, optional synthesized sound, pause, keyboard and touch controls, and reduced-motion support.

**Needle.** A workbench for regular expressions, and the one page here you would open on purpose. Write a pattern and see what it catches in the text, why it catches it, and what it does when you replace it. The pattern is parsed rather than only compiled: every token is coloured where it sits, the breakdown names each construct in plain English, and a mistake reports the column it is in. Matches light up in the text with their capture groups tinted inside, a map shows where the matches fall across the passage, and a suite of test cases says at a glance whether a change broke anything. A pattern that backtracks forever is abandoned after a second and a half instead of freezing the tab. Seventeen ready-made patterns, shareable links, local saves, keyboard stepping and reduced-motion support.

**Rewind.** A Slay the Spire-style deckbuilder where time is a resource. Every turn is saved as a frame on a film strip, and Sand, gained one grain a turn, pays for the time tricks. Rewinding the turn goes back to the start of the previous one: your HP, hand, piles, tonics and the enemies all return, enemies repeat what they did unless something changes, and a note shows what they did in the erased timeline. Cards sent into the Time Capsule beforehand arrive in the past as free Ghosts, and every rewind slips a Paradox into the draw pile. Forty cards rewind just yourself to undo damage, Unmake an enemy to strip the Strength and Block it built or erase a minion summoned later, step plans back, freeze foes in Stasis, echo cards into the next turn and set delayed bombs. Two acts on a branching map of fights, elites, shops, events, nap spots and treasure, with cartoon blobs drawn in SVG: cuckoos that wind up a big BONG, a fog blob whose plans are hidden until you rewind, a pickpocket, a knight that turns its own HP back, and Old Pip, an older you, as the final boss. Relics, tonics, synthesized sound and music, keyboard controls, local saves and reduced-motion support.

## Correction rounds

Most pieces needed none. The ones that did:

The Abyss and Mercurial correction rounds fixed small issues: tentacles glitching during fast scrolling on Abyss, and the material name being cut off on Mercurial. Night atlas received a correction to vary the generated wanderer shapes. The last warm window received a correction to ground the figures and train and align the distant city with the hillside. A second correction removed an extra line extending from the daughter's hand. Vesper received a correction that set the bell inside a belfry tower instead of in open air. Starshard needed two correction rounds: crash fixes (a palette key mismatch that crashed the game when splitters appeared, and a music-sequencer index bug that crashed the run seconds after launch), and a desktop-only gate that blocks the game on touch devices. Longhand received a correction that breaks stalemates: a runner wedged against a wall for five seconds is thrown back to the left of the screen and loses a heart (with a little ink back), so a stalled run now costs lives instead of freezing; the same round lowered early cliff heights, moved ink milestones closer together and made the warning sign blink over his head. Loaded received a correction so that selling a Joker frees its slot in the shop immediately, and so that Stars apply on purchase instead of taking a consumable slot. Nodal received a correction because the page came up blank: the second mode's m·n steppers had been dropped from the panel while the script still wrote to them, so start-up threw before anything was drawn. The same round restored the steppers, added a difference/sum switch for the second mode, made the control lookup fall back to a harmless stub so a missing element can never blank the page again, and tamed the nodal glow, which had been drawn so wide and bright that it read as neon tubes over the sand instead of a hint of the lines beneath it. Palimpsest received a correction because its connectors acted strangely: the endpoint search returned the arrow that was being drawn, so every line bound to its own bounding box — a loose line collapsed to a single invisible point and an arrow between two boxes shrank to a stub. The same round made connectors attach to a side and a position rather than re-aiming at whatever moved, let a connector be detached and have its ends dragged without jumping, stopped ink lying over a box from stealing the binding, and fixed the crash that made it look like the board had eaten your work: discarding an empty sticky note left its id in the selection, so the bounds of nothing were measured and the render loop threw every frame and died, freezing the canvas on a stale image while the document kept saving — which is why marks appeared to vanish and came back on refresh. The paint loop now survives a bad frame, and a selection can never outlive the marks it points at. A second round stopped it discarding an untitled sticky note: switching tools blurred the note being written, and an empty one was thrown away along with the empty text runs, so a note you had just placed vanished the moment you reached for the next tool. Only an untouched text run is dropped now — it drew nothing — while a placed note survives tool switches, Return and Escape, and a reload.

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
    ├── carbon-copy.html
    ├── drizzle.html
    ├── echo-ward.html
    ├── echoveil.html
    ├── elsewhere.html
    ├── enough.html
    ├── estuary.html
    ├── foldwake.html
    ├── last-orders.html
    ├── lifeline.html
    ├── loaded.html
    ├── longhand.html
    ├── mercurial.html
    ├── murmur.html
    ├── needle.html
    ├── night-atlas.html
    ├── nodal.html
    ├── palimpsest.html
    ├── paperborough.html
    ├── percy.html
    ├── replace-you.html
    ├── rewind.html
    ├── somewhere-softly.html
    ├── starshard.html
    ├── the-last-warm-window.html
    ├── tick.html
    ├── until-the-tide.html
    └── vesper.html
```
