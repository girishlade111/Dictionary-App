# Dictionary App

A lightweight, single-file dictionary web app — look up English words and get definitions, pronunciation audio, example sentences, and translations, right in the browser. No build step, no dependencies, no login.

## Features

- **Word lookup** — definitions powered by the free [DictionaryAPI](https://dictionaryapi.dev) (`api.dictionaryapi.dev`)
- **Listen / pronunciation** — text-to-speech playback of words via Google Translate TTS
- **Theme options** — theme picker panel with multiple gradient color themes and swatches
- **Translations** — quick translation support via Google Translate's free endpoint
- **Responsive layout** — centered card UI that works on mobile and desktop
- **Zero dependencies** — plain HTML + CSS + JavaScript in one file

## Tech Stack

- HTML5, CSS3, vanilla JavaScript
- External free APIs: DictionaryAPI (dictionaryapi.dev), Google Translate TTS

## Quick Start

Open `Dictionary App.html` in any modern browser — no server or build step required:

```bash
# then open Dictionary App.html in your browser
```

An internet connection is required so the app can reach the dictionary and translation APIs.

## Project Structure

```
Dictionary-App/
├── Dictionary App.html   # The complete app (HTML + CSS + JS in one file)
└── LICENSE
```

## How It Works

1. Type a word into the search box and hit enter.
2. The app fetches definitions from `https://api.dictionaryapi.dev/api/v2/entries/en/<word>`.
3. Use the Listen controls to hear the pronunciation (Google TTS).
4. Open the theme picker to restyle the app with a different gradient theme.

## Deployment

This is a static single-file site — serve the repo root from any static host (GitHub Pages, Cloudflare Pages, Netlify, Vercel). For GitHub Pages the file is mirrored as `index.html` so the site loads at the domain root.

## License

MIT — see `LICENSE`.

---

**Built by Girish Lade** — [ladestack.in](https://ladestack.in)
