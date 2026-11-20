# Legàmi

A slow, relaxing 2D puzzle game made for phones. Its purpose is to help you unwind at the end of the day.

Every level is randomly generated and picks one of nine small puzzles at random, so you never know what's coming next. There are no scores or timers. If you run out of light, the same puzzle simply restarts.

## Minigames

| | Name | Goal |
|---|---|---|
| 🧵 | Legàmi | Connect things that belong together (🐝 → 🌸) without crossing threads |
| 🏮 | Lanterne | Light every lantern (tapping one toggles it and its neighbours) |
| 🌿 | Sentieri | Rotate tiles until no path is left open |
| 🎨 | Sfumature | Swap tiles to rebuild a colour gradient |
| ✨ | Melodia | Listen to the stars, then repeat the melody |
| 🔍 | Intruso | Find the odd one out in each group |
| 🃏 | Memoria | Classic memory card pairs |
| 🪞 | Specchio | Mirror the drawing onto the other half |
| 🎈 | Bolle | Pop floating bubbles in ascending or descending order |

## Features

- Guided breathing between levels: an orb expands as you inhale and shrinks as you exhale. The exhale gets slightly longer as you keep playing, to help slow you down, and every fourth level adds a three-breath pause. The background also glows gently in the same rhythm
- Gentle difficulty curve in every mode
- 116 original calming phrases across eleven themes (breath, body, present moment, self-kindness, letting go, nature, simplicity, gratitude, evening, visualisations, small practices). They are drawn from a shuffled deck so none repeats until all have been shown, and inhale/exhale cues vary too
- Infinite, procedurally generated levels that are always solvable
- Six atmospheric chapters (starry night, lantern lake, dawn garden, autumn forest, seabed, aurora), each with its own animated background and musical key
- Generative ambient music and soft pentatonic sound effects (Web Audio API, no audio files)
- Zen mode (infinite light, no way to lose), unlimited hints, skip level
- Toggle which minigames can appear
- Progress saved locally in the browser

## Run

It's a single self-contained `index.html` file with no build step and no dependencies. Open it in a browser or serve it with GitHub Pages. Headphones recommended.
