# SiriusOS

A space-themed desktop that runs entirely in the browser. There's nothing to install and no dependencies to manage — the whole thing lives in a single HTML file.

![SiriusOS](https://img.shields.io/badge/platform-browser-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## Live Demo

You can try it here: [siriusw823.github.io/sirius-webos](https://siriusw823.github.io/sirius-webos/)

## Features

**Desktop environment.** An animated starfield with nebula glow sits behind everything, along with a lock screen that shows a live clock and date, a right-click context menu, and a taskbar for launching apps and switching between minimized windows.

**Window manager.** Drag windows around by their title bar, and minimize, maximize, or close them as needed. Clicking a window brings it to the front. It's all built on native JavaScript `mousedown` and `mousemove` events, with no libraries involved.

**Built-in apps:**

- **About** — system information and links
- **Terminal** — a command-line interface with history you can scroll through using the up and down arrow keys
- **Stargazer** — an interactive constellation viewer
- **Notes** — a tabbed note-taking app
- **Calculator** — a basic calculator

Rounding things out, there are toast notifications and a Pomodoro timer tucked into the taskbar.

## Tech Stack

Pure HTML, CSS, and JavaScript, all in one file with no external dependencies. The Canvas API handles the starfield and Stargazer rendering, and native DOM events take care of drag-and-drop window management.

## Getting Started

No build step required — just open `index.html` in any modern browser.

```bash
git clone https://github.com/SiriusW823/sirius-webos.git
cd sirius-webos
open index.html   # or double-click the file
```

## Project Structure

```
sirius-webos/
└── index.html    # everything lives here
```

## Built For

The [Hack Club Stardance Challenge](https://stardance.hackclub.com) — WebOS 1 Mission.
