# Boiler Room

An original Victorian steam-pressure logic game. You are the duty engineer of a
copper-and-rivets boiler room: keep the main boiler below 100 PSI, route steam
through gates, three-way valves, check valves and safety valves, and bring three
engines to their exact ordered pressure bands — before the 120-second shift ends.

- 30 shifts (levels) with progressively deeper valve topologies:
  single gate → three-way forks → three-ways in series → waste gates →
  one-way check lines → spring-loaded safety valves → full six-valve panels.
- Work orders: simultaneous target bands, cumulative run-times, and
  multi-stage sequences.
- Failure states: engine pipe bursts over 90 PSI, boiler explodes over 100 PSI,
  or the shift clock runs out.
- 100% original: hand-drawn canvas art (riveted plates, copper pipes, needle
  gauges, steam particles, white-out burst fog), WebAudio synthesized sound
  (steam hiss, valve clicks, pressure hum, alarm, boom), no external assets.
- Single-file `index.html` (no CDN, no images, no fonts, no analytics).
  Portal SDKs load only on their own domains (crazygames / gamedistribution).

## Play

Open `index.html` in any modern browser, or serve the folder:

```
python3 -m http.server 8000
# http://localhost:8000/
```

## Controls

| Action | Mouse / Touch | Keyboard |
| --- | --- | --- |
| Cycle valve | Tap the valve wheel | `1`–`6` |
| Furnace LOW / MED / HIGH | Tap the furnace buttons | `Q` / `W` / `E` |
| Sound on/off | SOUND button | `M` |
| Back to menu | MENU button | `Esc` |

## Tech

Vanilla JavaScript, Canvas 2D, WebAudio. Fixed-timestep deterministic physics
(60 Hz) — every level ships with a machine-verified reference solution embedded
in the file. Progress and best scores persist via localStorage.

## License

Original work. All art, code, design and audio generated for this project.
