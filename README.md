# SiriusOS 🌟

A space-themed WebOS that runs entirely in your browser — no installs, no dependencies, just one HTML file.

![SiriusOS](https://img.shields.io/badge/platform-browser-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## Live Demo

**[Try it →](https://siriusw823.github.io/sirius-webos/)**

## Features

### Desktop Environment
- Animated starfield background with nebula glow effects
- Lock screen with live clock and date display
- Right-click context menu on the desktop
- Taskbar with app launcher and minimized window buttons

### Window Manager
- Drag windows by their title bar
- Minimize, maximize, and close controls
- Z-index focus management (click to bring to front)
- Built entirely with native JS `mousedown` / `mousemove` — zero libraries

### Built-in Apps

| App | Description |
|-----|-------------|
| 🌟 About | System info and links |
| 💻 Terminal | Command-line interface with history (↑↓ keys) |
| 🔭 Stargazer | Interactive constellation viewer |
| 📝 Notes | Tabbed note-taking app |
| 🔢 Calculator | Basic calculator |

### Other
- Toast notifications
- Pomodoro timer in the taskbar

## Tech Stack

- **Pure HTML / CSS / JavaScript** — single file, zero external dependencies
- Canvas API for starfield and Stargazer rendering
- Native DOM events for drag-and-drop window management

## Getting Started

Just open `index.html` in any modern browser. No build step needed.

```bash
git clone https://github.com/SiriusW823/sirius-webos.git
cd sirius-webos
open index.html
```

## Project Structure

```
sirius-webos/
└── index.html
```

## Built for

[Hack Club Stardance Challenge](https://stardance.hackclub.com) — WebOS 1 Mission
