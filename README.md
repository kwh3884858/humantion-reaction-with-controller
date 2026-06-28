# ⏱ Reaction Time Test

A browser-based reaction time tester inspired by Human Benchmark. Press any button on your gamepad (or keyboard) the moment the screen turns from red to green — measure your reflexes across 5 trials.

**[▶ Try it now](https://kwh3884858.github.io/humantion-reaction-with-controller/)**

## Features

- 🎮 **Gamepad support** — Xbox (360/One/Series/Elite), PlayStation (DualSense/DualShock), Nintendo Switch Pro, Joy-Con, 8BitDo, GuliKit, and more
- ⌨️ **Keyboard & mouse fallback** — Spacebar or click to react
- 🔢 **Multi-controller** — plug in several gamepads; the last one you press becomes the active device
- 🏷️ **Auto-detect controller model** — identifies the exact model via VID/PID (Windows may need [WebHID](https://developer.chrome.com/docs/capabilities/hid) authorization)
- 📊 **History with charts** — each 5-trial session is saved locally with a line chart of your reaction times
- 🌐 **7 languages** — 中文, English, 日本語, Français, Português, 한국어, Русский (auto-detected from browser)

## How to use

1. Open `index.html` in Chrome, Edge, or any modern browser
2. Connect a gamepad (optional)
3. Press any button or click to start
4. Wait for the screen to turn **green**
5. Press any button as fast as you can
6. Repeat 5 times — your average reaction time is shown

## Deployment

This is a single-file static web app. Deploy it anywhere:

- **GitHub Pages** — push to `main`, enable Pages from the repo settings
- **Netlify / Vercel** — drag `index.html` onto the dashboard
- **Local** — just open `index.html` in your browser

## Tech stack

Pure HTML + CSS + vanilla JavaScript. No frameworks, no build tools, no dependencies. Uses the [Gamepad API](https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API) and optionally [WebHID](https://developer.chrome.com/docs/capabilities/hid) for precise controller identification.

## License

MIT
