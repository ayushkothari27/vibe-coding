# vibe-coding

A collection of self-contained single-file web apps, all sharing a consistent dark theme and design language.

## Apps

| App | Path | Description |
|-----|------|-------------|
| **Asteroids** | `asteroids/` | Canvas-based Asteroids game with touch controls |
| **Flaggle** | `flaggle/` | Daily flag-guessing puzzle (Wordle-style) |
| **Focus Timer** | `pomodoro/` | Pomodoro / focus timer |
| **Trip Countdown** | `trip-countdown/` | Countdown to an upcoming trip |
| **Desk — Todo** | `desk/todo/` | Minimal to-do list |
| **Desk — Bookmarks** | `desk/bookmark/` | Personal bookmark manager |

## Design

All apps share a common visual identity:

- **Background:** `#1A1A2E` (deep navy)
- **Accent palette:** orange, yellow, green, indigo, pink, purple
- **Fonts:** [Fraunces](https://fonts.google.com/specimen/Fraunces) (display) · [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (UI)

## Usage

Each app is a plain HTML file with no build step or dependencies. Open any `index.html` directly in a browser, or serve the repo root with any static file server:

```bash
npx serve .
# or
python3 -m http.server
```
