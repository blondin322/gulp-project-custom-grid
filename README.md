# Gulp Project Custom Grid

A starter front-end project with Gulp 4, SCSS, and a custom Flexbox grid.

## Features

- **HTML** — Rigger for includes/partials (`//= layout/head.html` etc.)
- **SCSS** — Sass, autoprefixer, minification, source maps in dev
- **JS** — Rigger, Uglify, source maps in dev, jQuery
- **Images** — Imagemin (JPEG, PNG, GIF, SVG optimization)
- **Fonts** — Copy from `src/fonts/` to `dist/fonts/`
- **Dev server** — Browser Sync with live reload and file watchers
- **Grid** — Custom Flexbox-based grid with responsive breakpoints

## Setup

```bash
npm install
```

## Commands

| Command | Description |
|---------|-------------|
| `npm start` or `gulp` | Build, start dev server, watch files (default) |
| `gulp build` | Clean and build HTML, CSS, JS, fonts, images (dev, with source maps) |
| `gulp dist` | Production build (minified, no source maps) |
| `gulp clean:build` | Remove `dist/` contents |
| `gulp cache:clear` | Clear Gulp cache (e.g. after image pipeline changes) |
| `gulp html:build` | Build HTML only |
| `gulp css:build` | Build SCSS only (dev) |
| `gulp css:dist` | Build SCSS only (production) |
| `gulp js:build` | Build JS only (dev) |
| `gulp js:dist` | Build JS only (production) |
| `gulp fonts:build` | Copy fonts |
| `gulp image:build` | Optimize and copy images |
| `gulp webserver` | Start Browser Sync (no build/watch) |
| `gulp watch` | Watch HTML, SCSS, JS, images, fonts |

## Structure

- `src/` — HTML, SCSS, JS, layout partials
- `dist/` — built output
