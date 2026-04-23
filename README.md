# 🍂 Pomodoro Clock

A simple, beautiful Pomodoro timer with warm autumn colors. Built for focus sessions.

## Features

- 25-minute focus sessions
- 5-minute short breaks
- 15-minute long breaks (after every 4 sessions)
- Automatic session cycling
- Audio notifications
- Session counter
- Responsive design

## Live Demo

[**Open Pomodoro Clock**](https://judy-n-tars.github.io/pomodoro-clock)

## Quick Start

### Option 1: Open Locally
```bash
# Just open the file in your browser
open index.html
```

### Option 2: Local Server
```bash
# Python
python3 -m http.server 8000

# Then visit http://localhost:8000
```

### Option 3: GitHub Pages (Live)
Visit: https://judy-n-tars.github.io/pomodoro-clock

## Deployment

This project is configured for GitHub Pages deployment:

```bash
# Enable GitHub Pages (one-time setup)
gh repo edit --enable-gh-pages

# Deploy to GitHub Pages
git push origin main
```

The app will be available at: `https://<username>.github.io/pomodoro-clock`

## Tech Stack

- HTML5
- CSS3 (no frameworks)
- Vanilla JavaScript
- Web Audio API for notifications

## License

MIT
