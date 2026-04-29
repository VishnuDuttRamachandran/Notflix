# Notflix

Notflix is a Netflix-style streaming UI built with React + Vite.

## Features

- Hero banner with featured title
- Horizontal movie rows (trending, top rated, genre picks)
- TMDB-powered live movie/series data
- Mobile and desktop responsive layout

## Setup

1. Install dependencies:

```bash
npm install
```

2. Create a `.env` file in the project root:

```bash
VITE_TMDB_API_KEY=your_tmdb_api_key_here
```

3. Start development server:

```bash
npm run dev
```

## Build

```bash
npm run build
```

If no TMDB key is set, the app runs with fallback sample rows and shows a setup hint in the hero section.
