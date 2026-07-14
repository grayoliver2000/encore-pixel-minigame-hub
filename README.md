# Encore v2026 - TikTok LIVE V2G engine 2026

> **Encore is a browser-based, client-side TikTok LIVE V2G demo that transforms live moments into compact pixel mini-games with screen capture and split-screen clip assembly.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/grayoliver2000/encore-pixel-minigame-hub?style=flat-square)](https://github.com/grayoliver2000/encore-pixel-minigame-hub)

---

<p align="center">
  <a href="https://grayoliver2000.github.io/encore-pixel-minigame-hub/">
    <img src="https://img.shields.io/badge/Download-Encore%20Latest-brightgreen?style=for-the-badge" alt="Download Encore">
  </a>
</p>

> **[Direct Download - Encore v2026](https://grayoliver2000.github.io/encore-pixel-minigame-hub/)**

---

[Download Latest Build](https://grayoliver2000.github.io/encore-pixel-minigame-hub/)

---

## What Encore Does

Encore is a web-first engine for experimenting with TikTok LIVE-style V2G flows. It detects live highlights, turns them into short 30-second pixel mini-games from vision input, and delivers the result through a TikTok-inspired bottom-sheet interaction model.

This project is intended for hackathon builds, live-stream interaction prototypes, and lightweight demos where everything should stay on the client. Because there is no backend dependency, Encore stays easy to set up while still covering live room navigation, gameplay capture, and split-screen clip composition.

---

## Capabilities

- Tracks live highlights through a stream-driven workflow
- Creates 30-second pixel mini-games from vision input
- Relies on an AI vision-based path for quick live-to-play conversion
- Presents gameplay inside a TikTok-style bottom-sheet experience
- Lets you move between 3 live room feeds
- Records gameplay for later review or publishing workflows
- Builds split-screen clips from captured gameplay
- Operates entirely on the client without a backend

---

## Getting Started

Clone the repo and open it in an environment that can run browser-based projects:

```bash
git clone https://github.com/grayoliver2000/encore-pixel-minigame-hub.git
cd REPO
```

To run locally, serve the repository root with any simple static server and then open the app in your browser. If you want to use a packaged build instead, download the latest version and launch it from the release asset or hosted page as provided.

---

## How to Use It

1. Open the app in a modern web browser.
2. Connect or load the live room feed you want to inspect.
3. Let the system find highlights and convert them into a short pixel mini-game.
4. Use the bottom-sheet flow to step through the generated experience.
5. Record gameplay if you need a clip-ready output.
6. Export or review the split-screen result when the session ends.

Example workflow:

- Select a live room feed
- Trigger the vision-driven highlight pass
- Launch the generated mini-game
- Capture the session recording
- Compose the final split-screen clip

---

## Configuration

Encore is built as a client-side demo, so most behavior is controlled through the UI and the browser session. When local settings or saved preferences exist, they usually live in browser storage or in project configuration files nearby.

Example configuration shape:

```json
{
  "mode": "client-side",
  "liveRooms": 3,
  "gameLengthSeconds": 30,
  "capture": true,
  "layout": "bottom-sheet"
}
```

If you are customizing the demo, check the source for environment-specific values tied to streaming input, clip handling, or the UI layout.

---

## Requirements

- A modern web browser
- Web platform support for HTML-based client-side execution
- Enough local storage and memory for live interaction, screen recording, and clip composition
- Access to the relevant live room feeds or demo inputs
- Optional local static hosting if you prefer to run it from a server instead of opening files directly

---

## FAQ

**Does Encore need a backend?**  
No. The extracted project profile identifies it as fully client-side.

**What kind of content does it generate?**  
It converts live highlights into 30-second pixel mini-games and can record or assemble split-screen clips.

**How many live feeds can it handle?**  
The documented workflow includes navigation across 3 live room feeds.

**Where are settings stored?**  
Configuration is expected to live in the browser session or nearby project files, depending on how you run the demo.

**What should I do if the app does not load correctly?**  
Make sure you are using a modern browser, confirm that any local assets are present, and check that the project is being served from the expected path.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
