# NeoFlight
NeoFlight is a browser-based tactical drone flight demo built as a single static HTML experience.

The project leverages Three.js for 3D rendering and Tailwind CSS for UI styling, delivering a neon-infused cockpit with flight telemetry, minimap, and mission controls.

## Features
- 3D drone flight simulation with smooth controls and atmospheric effects
- HUD elements for battery, signal, heat, score, lives, and threat status
- Interactive menu with selectable drone designs and gameplay option toggles
- Radar scan, night vision, lighting, turbo boost, and return-to-home functionality
- Touch-friendly joystick controls for mobile devices
- Mission end screen with module upgrade options and retry flow
- Dynamic weather, hacker mini-game, patrol threats, and landing mechanics

## How to Run
1. Open `neoflight.html` in a modern web browser (including on mobile devices).
2. Use the on-screen menu to start the game.
3. For best results, use a browser with WebGL support.

## Controls
### Keyboard
- `W`, `A`, `S`, `D` — Move the drone
- Arrow keys — Flight controls
- `Q` — Scan / radar ping
- `1` - `6` — Select drone designs from the menu

### HUD Buttons
- `MENU` — Return to the main menu
- `RTH` — Return to home
- `LAND` — Attempt to land
- `NVG` — Toggle night vision
- `LIGHT` — Toggle lights
- `MUTE` — Toggle sound
- `TURBO` — Activate turbo boost
- `SCAN` — Sweep the minimap
- `SYNC` — Use during hack mini-game
- `WIND` — Toggle weather drift effects
- `?` — Open the pilot briefing

## License
This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0).

See the `LICENSE` file for the full license text.

## Notes
NeoFlight is intended as a visual and interactive demo rather than a complete game title. It is a compact HTML/JS project that can be used for experimentation with WebGL flight visuals and cockpit-style user interfaces.