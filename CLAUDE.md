# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub Pages personal portfolio website (MicahDitto.github.io). It's a single-page static site with no build process or dependencies.

## Development

No build step required. Open `index.html` directly in a browser or use any local server:
```bash
python3 -m http.server 8000
# or
npx serve .
```

## Architecture

Single `index.html` file containing:
- **Embedded CSS** (lines 7-262): All styles including animations, responsive grid layout, glassmorphism effects
- **HTML structure** (lines 264-336): Night sky background, project cards grid, breathing blobs section
- **Vanilla JavaScript** (lines 339-462): Dynamically generates stars, bubbles, and animated background blobs

Key visual elements:
- Night sky with moon and twinkling stars
- Floating transparent bubbles
- Color-shifting "breathing" blobs with CSS animations
- Project cards with hover effects and glassmorphism styling

## Design System

- Color scheme: Dark background (#0a0a0f) with purple/blue accents
- Gradient: `linear-gradient(18deg, #ff8800 0%, #0008ff 100%)` used for headings
- Font: Montserrat (loaded from Google Fonts implicitly expected)
