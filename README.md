# Legàmi

A slow, relaxing 2D puzzle game made for phones. Its purpose is to help you unwind at the end of the day.

Every level is randomly generated and picks one of nine small puzzles at random, so you never know what's coming next. There are no scores or timers. If you run out of light, the same puzzle simply restarts.

## Minigames

Thirteen games, each with several variants picked at random:

| | Name | Goal | Variants |
|---|---|---|---|
| 🧵 | Legàmi | Connect pairs without crossing threads | associations (🐝 → 🌸), twins, colours |
| 🏮 | Lanterne | Light every lantern | cross, diagonals, row, column neighbourhoods |
| 🌿 | Sentieri | Rotate tiles until no path is left open | garden, spring (bring water everywhere), fixed stones |
| 🎨 | Sfumature | Swap tiles to rebuild a colour gradient | four corners, rows, single tint |
| ✨ | Melodia | Listen to the stars, then repeat the melody | classic, echo (grows one note at a time), backwards |
| 🔍 | Intruso | Find the odd one out (every item is labelled) | by family, by colour |
| 🃏 | Memoria | Memory card pairs | identical, associated, colours |
| 🪞 | Specchio | Complete the symmetric drawing | vertical, horizontal, rotated, four mirrors |
| 🎈 | Bolle | Pop floating bubbles in order | numbers, letters, rainbow |
| 🏺 | Vasetti | Sort stones so each jar has one colour | stones, fruit |
| 🧭 | Labirinto | Guide the light through a maze to the lantern | garden, in the dark, fireflies to collect |
| 🧩 | Tessere | 3×3 sliding puzzle | numbers, moon phases, gradient |
| 🧮 | Conta | Count calmly and pick the right number | one kind, everything |

## Features

- Stress check from 1 to 10 when you start, and again every ten levels. Low stress brings livelier puzzles. Medium stress mixes calm games with small puzzles. High stress keeps to simple, slow games with infinite light, easier levels, two breaths between levels and an optional body scan first
- Gender-neutral wording throughout
- Guided breathing between levels: an orb expands as you inhale and shrinks as you exhale. The exhale gets slightly longer as you keep playing, to help slow you down, and every fourth level adds a three-breath pause. The background also glows gently in the same rhythm
- Gentle difficulty curve in every mode
- Mindful body release covering 20 areas where tension builds up (upper trapezius, scalenes, SCM, suboccipitals, jaw, diaphragm, intercostals, pectorals, rhomboids, latissimus dorsi, lumbar muscles, quadratus lumborum, psoas, glutes and more). Instead of exercises, each area is a short guided practice paced by the breath: notice the area, soften it, and let it fall and grow heavy on each exhale. Includes a guided body scan of about 4 minutes, from head to feet, and one area every third level. These are mindfulness cues, not therapy
- 116 original calming phrases across eleven themes (breath, body, present moment, self-kindness, letting go, nature, simplicity, gratitude, evening, visualisations, small practices). They are drawn from a shuffled deck so none repeats until all have been shown, and inhale/exhale cues vary too
- Infinite, procedurally generated levels that are always solvable
- Six atmospheric chapters (starry night, lantern lake, dawn garden, autumn forest, seabed, aurora), each with its own animated background and musical key
- Generative ambient music and soft pentatonic sound effects (Web Audio API, no audio files)
- Zen mode (infinite light, no way to lose), unlimited hints, skip level
- Toggle which minigames can appear
- Progress saved locally in the browser

## Run

It's a single self-contained `index.html` file with no build step and no dependencies. Open it in a browser or serve it with GitHub Pages. Headphones recommended.
