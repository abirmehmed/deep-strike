# Deep Strike

A 3D submarine warship game that runs in your browser. Dive under the ocean, hunt enemy vessels, and sink them with missiles and torpedoes. Built with plain JavaScript and [Three.js](https://threejs.org/), in a single HTML file.

## ▶ Play now

**https://abirmehmed.github.io/deep-strike/**

Works on desktop and mobile.

## Controls

| Action | On-screen | Keyboard |
|---|---|---|
| Speed up / slow down | ▲ ▼ | W / S or Up / Down |
| Steer left / right | ◀ ▶ | A / D or Left / Right |
| Dive / Surface | DIVE button | X or Shift |
| Fire | FIRE button | Space |
| Change camera | VIEW button | C |

## How to play

- **Surfaced:** the hangar doors open and you fire homing missiles. Enemy ships can shoot you here.
- **Submerged:** you are safe from their guns and can fire torpedoes straight ahead, but you move slower.
- Each enemy ship has 2 hit points. A missile does 1 damage and a torpedo does 2.
- Watch the radar in the top corner and keep an eye on your hull bar.

## Run locally

No build step needed. Open `index.html` in a browser.

## Tech

- Three.js (loaded from the cdnjs CDN)
- Vanilla JavaScript, HTML and CSS

## Note

The submarine is a conceptual model inspired by publicly shown artwork of a trimaran-style submersible warship. It is a game, not a technical representation of any real vessel.
