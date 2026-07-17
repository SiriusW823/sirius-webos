# SiriusOS

SiriusOS is a space-themed web-based operating system that runs entirely within the browser. It requires no installation and no external dependencies, and is contained within a single HTML file.

![SiriusOS](https://img.shields.io/badge/platform-browser-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## Live Demo

The application is available online at [https://siriusw823.github.io/sirius-webos/](https://siriusw823.github.io/sirius-webos/).

## Features

### Desktop Environment

The desktop environment provides an animated starfield background with nebula glow effects, a lock screen with a live clock and date display, a right-click context menu, and a taskbar that includes an application launcher and buttons for minimized windows.

### Window Manager

Windows can be repositioned by dragging their title bar and controlled through minimize, maximize, and close actions. Window focus is managed through z-index ordering, allowing a window to be brought to the front by clicking it. The window manager is implemented entirely with native JavaScript `mousedown` and `mousemove` events, without the use of external libraries.

### Built-in Applications

| Application | Description |
|-------------|-------------|
| About | Displays system information and related links. |
| Terminal | A command-line interface with command history navigable using the up and down arrow keys. |
| Stargazer | An interactive constellation viewer. |
| Notes | A tabbed note-taking application. |
| Calculator | A basic calculator. |

### Additional Features

The system also includes toast notifications and a Pomodoro timer located in the taskbar.

## Technology Stack

SiriusOS is built with pure HTML, CSS, and JavaScript in a single file, with no external dependencies. The Canvas API is used for rendering the starfield and the Stargazer application, and native DOM events handle drag-and-drop window management.

## Getting Started

No build step is required. Open `index.html` in any modern browser to run the application.

```bash
git clone https://github.com/SiriusW823/sirius-webos.git
cd sirius-webos
open index.html   # or double-click the file
```

## Project Structure

```
sirius-webos/
└── index.html    # The complete application
```

## Attribution

This project was developed for the [Hack Club Stardance Challenge](https://stardance.hackclub.com) as part of the WebOS 1 Mission.
