# Beat Kanji - Web Version

A rhythm-based kanji learning game ported to run in web browsers.

## Running Locally

1. Start a local server:
   ```bash
   cd web
   python3 serve.py
   ```

2. Open http://localhost:8000 in your browser

## Features

- Works on PC (Chrome, Firefox, Safari, Edge) and mobile browsers (Android, iOS)
- Touch and mouse input for drawing strokes
- Multiple difficulty levels (Easy, Medium, Hard)
- 10 songs with beatmaps
- 2000+ kanji from JLPT N5-N1 levels plus hiragana/katakana
- Settings for volume, meaning display, and category selection
- Score tracking with tier rankings (S/A/B/C/D)

## Browser Requirements

- Modern browser with Web Audio API support
- JavaScript enabled
- Touch events or mouse input

## File Structure

```
web/
├── index.html          # Main game (self-contained HTML/CSS/JS)
├── kanji-data.json     # Kanji stroke data
├── data/               # Beatmap JSON files
│   ├── canon-in-d.json
│   └── ...
├── audio/              # Song MP3 files
│   ├── canon-in-d.mp3
│   └── ...
├── serve.py            # Simple Python server for testing
└── README.md           # This file
```

## Deployment

The `web/` folder can be deployed to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Any web server

Just ensure all files are served with correct MIME types.
