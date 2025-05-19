

# Fact or Fiction (Cap or No Cap)

A mobile-first, browser-based party game inspired by *Would I Lie to You?*, designed for local and online play. Build once, play anywhere — especially made for the creator’s upcoming YouTube series.

## Overview

- Party game for storytelling, bluffing, and laughter
- Local-first design: run on any non-iOS device with zero setup
- Online fallback: hosted version for iOS-only players
- Built entirely from iPad with GitHub, ChatGPT, and passion

## Features

- Room code generator (e.g. `9380L`)
- Device detection: iOS users are routed to hosted mode
- ZIP download for offline hosting
- Host controls: prompt selection, truth reveals, round tracking
- Gen Z toggle: switches labels between *Fact/Fiction* and *Cap/No Cap*

## Stack

- Frontend: HTML, CSS (gold on deep purple theme), Vanilla JS
- Backend: Flask (Python)
- Hosting: Fly.io / Railway.app
- GitHub-first development flow (no local terminal)

## Getting Started

1. Clone or download the repo
2. For local hosting: unzip and run `python backend/app.py`
3. For online hosting: auto-deploy via GitHub Actions

## License

MIT
