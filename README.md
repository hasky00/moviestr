# MOVSTR - Free Movies with Nostr

A decentralized streaming movie platform where users watch movies for free by signing in with their Nostr identity. No ads, no subscriptions, no credit cards.

## Features

- **Nostr Authentication** - Sign in with your nsec key. Users retain full ownership of their data, watch history, and preferences across the decentralized web.
- **TMDB Movie Integration** - Browse trending, popular, top-rated, upcoming, and now-playing movies powered by [The Movie Database](https://www.themoviedb.org/) API.
- **Movie Detail Modal** - Click any movie card to view poster, rating, release year, language, and overview.
- **Category Filtering** - Switch between Trending, Popular, Top Rated, Upcoming, and Now Playing with one click.
- **Video Previews** - Hover-to-play preview clips on the landing page.
- **Full Movie Player** - HTML5 video player with native controls.
- **Bitcoin Donations** - BTC donation section with QR code and copy-to-clipboard to help keep the platform free.
- **Responsive Design** - Mobile-friendly layout with Tailwind CSS.
- **Glassmorphism UI** - Netflix-inspired dark theme with frosted-glass card effects.

## Quick Start

1. Open `index.html` in a browser.
2. Enter `nsec123` (demo key) or any valid nsec to access the dashboard.
3. Browse movies, click a card for details, and hit Play to watch.

## TMDB API

The app fetches movie data from TMDB's free API. To use your own key:

1. Sign up at [themoviedb.org](https://www.themoviedb.org/signup).
2. Get a free API key from **Settings > API**.
3. Replace the `TMDB_API_KEY` value in `index.html`.

If the API is unreachable, built-in fallback movie data is shown automatically.

## Bitcoin Donations

MOVSTR is free and community-supported. A BTC donation address is displayed on both the landing page and dashboard. To set your own address, update the `BTC_ADDRESS` constant and the QR code `src` URL in `index.html`.

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- Tailwind CSS 3.4
- TMDB API v3
- Google Fonts (Poppins)

## License

This project is open source.
