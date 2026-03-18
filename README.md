# Team Roulette

A web app for randomizing League of Legends custom game teams.

**[Live Site](https://erisbpdev.github.io/roulette/)**

## Features

- **Team Randomizer** — Add player names and split them into Blue Side / Red Side with a single click
- **Odd Players** — Handles uneven numbers (e.g., 3v2 for 5 players)
- **Assign Champions** — Randomly assigns a champion to each player from the full roster
- **Build + Runes** — Generates off-meta builds and rune pages based on champion class
- **Draft-Pick Reveal** — Staggered animations with name scramble effect

## How It Works

All champion, item, and rune data is pulled from Riot's [Data Dragon](https://developer.riotgames.com/docs/lol#data-dragon) CDN. No API key or backend required — it's a single HTML file.

## Usage

1. Enter summoner names
2. Toggle options (Assign Champions, Build + Runes)
3. Hit **RANDOMIZE**
4. Re-roll as many times as you want

## Tech

Single `index.html` file. No dependencies, no build step. Hosted on GitHub Pages.
