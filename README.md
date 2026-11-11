# Spice Frontier

A small real-time strategy game in the spirit of the classic desert RTS games. It's one self-contained `index.html` with no dependencies and no build step.

## Play

Open `index.html` in any modern browser with WebGL 2 (Safari 15+, Chrome, Firefox). Or serve the folder:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## How to win

Build a Windtrap, then a Refinery (it comes with a free Harvester), and grow your economy from spice. Destroy every enemy structure to win. Worms roam the open sand and eat units that stray off the rock.

## Graphics & audio

Everything is generated in code, with no image, model or audio files. A custom WebGL 2 renderer draws real 3D models, raised rock plateaus and mountains, sunlight with soft shadow-mapped shadows, and an angled C&C-style camera, along with particle explosions, smoke and scorch marks, soft fog of war, synthesized sound effects, spoken alerts using your system's text-to-speech voice, and an original adaptive soundtrack that intensifies during combat. Toggle music and sound with the ♫ and 🔊 buttons in the sidebar.

## Controls

| Input | Action |
|---|---|
| Left click / drag | Select / box-select |
| Right click (or Ctrl+click) | Move, attack, harvest |
| Option + right click | Attack-move |
| Double click | Select all on-screen units of that type |
| WASD / arrows / screen edge / scroll | Pan |
| Ctrl+1–9, then 1–9 | Set / recall groups |
| Pinch / Ctrl+scroll / + − | Zoom |
| X / H / P / M / Esc | Stop · home · pause · music · cancel |
| Delete | Sell selected building for 50% |
| Sidebar | Click to build, right-click to cancel |
