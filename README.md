[README.md](https://github.com/user-attachments/files/35138645/README.md)
# Submarines Twice

A browser submarine game: intercept and sink a troop transport by sound.

Play: open `index.html`, or enable GitHub Pages for this repository (Settings → Pages → deploy from branch `main`, folder `/`).

It is a single self-contained `index.html`. It loads three.js r170 and two fonts from public CDNs, so it needs an internet connection.

## How to play

- **W / S** throttle, **A / D** rudder, **R / F** rise and dive (hold), **Q** periscope at 26 ft or shallower.
- **Drag** to look, **scroll** to zoom, **C** to centre the view, **M** to mute, **H** to change the controls legend, **Esc** for the level list.
- **Click** a contact to target it. **1** torpedo, **2** Harpoon (periscope depth only), **3** decoy, **4** noisemaker, then **Space**.

Below 100 ft you cannot see ships, only what the sonar works out. One steady course gives a bearing but no range; turn so new bearings cross the old ones and the fix tightens. Torpedoes run on your solution, so a poor one can miss.

## Levels

1. Lone transport
2. One escort destroyer
3. Two escorts
4. Three escorts
5. Two destroyers and a submarine
6. The same, plus a Helix helicopter

Enemy sonar only finds you inside about 500 yards. Depth charges are set for 100 ft or less. Lightweight torpedoes search shallow but follow you down once locked.

## Status

First playable. Difficulty is untuned. The range estimate is a stand-in rather than a real bearings-only solver. Reworked from https://github.com/okybloc/Submarines_Once.
