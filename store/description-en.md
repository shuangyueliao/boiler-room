# Boiler Room — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

(193 characters, within the 200 limit)

You are the duty engineer of a Victorian boiler room. Route steam through
valves, hold three engines inside their exact pressure bands, and never let the
boiler top 100 PSI. A pure steam-pressure logic puzzle.

## Details

- Genre: Puzzle / Logic / Management (casual sim)
- Controls: Mouse / Touch — tap valve wheels to cycle them, tap furnace buttons
  for fire level. Keyboard: 1-6 valves, Q/W/E furnace, M sound, Esc menu.
- Features: 30 handcrafted shifts; gate, three-way, check and safety valve
  mechanics; pressure orders (simultaneous, cumulative, sequenced); score with
  time bonus; level select with localStorage progress and best scores; mute.
- Failure states: engine pipe bursts over 90 PSI, boiler explodes over 100 PSI,
  shift timeout.
- Tech: single-file HTML5 (~48 KB), Canvas 2D procedural art (riveted plates,
  copper pipes, needle gauges, steam particles, burst fog), WebAudio synthesized
  sound, fixed-timestep deterministic physics. Every level ships with a
  machine-verified reference solution. No frameworks, no tracking, no external
  links.
- Portal integration: CrazyGames SDK (gameplayStart / gameplayStop / happytime /
  loadingStart / loadingStop) and GameDistribution SDK load only on their own
  domains.

## Tags

logic, puzzle, management, steam, pressure, valves, victorian, sim, single-file

## itch.io

- Upload boiler-room-itch.zip (the same single-file build), mark
  "This file is playable in browser", entry file: index.html, viewport 960x600
  (canvas scales to fit any screen), kind: html.
- Pricing: $0 (donations optional).
- Suggested genre: Puzzle; sub-tags: logic, management, steam.

## CrazyGames submission checklist

- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / happytime / loadingStart / loadingStop wired
- [x] Responsive (canvas letterboxes to any viewport, touch + keyboard)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280x720)
- [ ] Screenshots: screenshot-raw.png (1280x800)
