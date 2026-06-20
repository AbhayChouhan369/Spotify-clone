# Spotify Clone

A static front-end clone of Spotify's web player, built with plain HTML and CSS. Recreates Spotify's layout, sidebar, browse cards, and bottom music player bar using only HTML and CSS — no JavaScript, no backend, no real playback.

## Features

- **Sidebar with navigation** — Home and Search links, built with Font Awesome icons
- **Your Library panel** — includes prompt cards for creating a playlist and browsing podcasts, styled with rounded "badge" buttons
- **Sticky top bar** in the main content area with playback navigation icons and an "Install app" badge
- **Browse sections** — "Recently played", "Trending now near you", and "Featured Charts", each rendered as a horizontal row of cards with cover image, title, and description
- **Bottom music player bar** — fixed-position player with playback control icons, a current/total time display, and a custom-styled progress bar (styled via `::-webkit-slider-thumb` and `::-webkit-slider-runnable-track`)
- **Responsive behavior** — certain elements (like the "Explore Premium" badge and forward icon) hide on smaller screens using a media query at 1000px

## Tech Stack

- **HTML5** — semantic sectioning for sidebar, main content, and player bar
- **CSS3** — flexbox for layout (sidebar + main content + player), `border-radius` for Spotify's signature rounded panels, custom range input styling for the progress bar
- **Font Awesome** — icon set for navigation and player controls
- **Google Fonts (Montserrat)** — matches Spotify's typography

## Project Structure

```
spotify-clone/
├── spotify.html       # Page structure and markup
├── spotify.css         # Styling and layout
└── images/              # Icons and card cover images
```

## Setup & Usage

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/spotify-clone.git
   ```
2. Make sure the `images/` folder (icons, card covers, logo) is in the same directory as the HTML file
3. Open `spotify.html` directly in your browser — no build step or server required

## What This Project Covers

This was a UI-focused project to practice replicating a real, polished interface closely rather than building from scratch:

- Structuring a fixed three-part layout (sidebar, scrollable main content, fixed bottom player) using flexbox
- Building Spotify's dark, rounded-panel visual style with CSS only
- Styling native form elements (the playback progress `<input type="range">`) beyond their default browser appearance
- Using a media query to selectively hide secondary elements on smaller screens

## Note

This is a static UI clone built for learning and portfolio purposes. Playback controls, the progress bar, and "Install app"/"Explore Premium" buttons are visual only and not functional. This project is not affiliated with or endorsed by Spotify.

## Live Demo

*(Add a link here once deployed — e.g. via Netlify, Vercel, or GitHub Pages)*
