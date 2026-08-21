# My Digital Spaces

A curated hub of my digital presences across the web. This is a static website exported from Obsidian, serving as a personal landing page for my various online profiles and projects.

## Overview

This project contains a web-based hub that links to my various digital spaces:

- **Instagram** - [@thestranger0708](https://www.instagram.com/thestranger0708/)
- **Pinterest** - [@alieon22](https://pin.it/7tGkRDRK7)
- **Reddit** - [/u/Loose-Video-5850](https://www.reddit.com/user/Loose-Video-5850/)
- **Letterboxd** - [@alieon22](https://letterboxd.com/alieon22/)
- **StoryGraph** - [@alieon22](https://app.thestorygraph.com/profile/alieon22)
- **Backloggd** - [@alieon22](https://backloggd.com/u/alieon22/)
- **Last.fm** - [@alieon22](https://www.last.fm/user/alieon22)

## Project Structure

```
site-lib/
├── index.html              # Main entry point
├── rss.xml                 # RSS feed for content updates
├── search-index.json       # Search functionality index
├── metadata.json           # Site metadata and configuration
├── .nojekyll               # Disables Jekyll processing (GitHub Pages)
│
├── fonts/                  # Custom web fonts
├── media/                  # Images and icons
├── scripts/                # JavaScript files
│   ├── webpage.js          # Main webpage script
│   ├── graph-wasm.js       # Graph visualization WASM loader
│   └── graph-render-worker.js  # Background worker for graph rendering
│
└── styles/                 # CSS stylesheets
    ├── main-styles.css     # Core styles
    ├── theme.css           # Theme definitions
    ├── obsidian.css        # Obsidian export styles
    ├── snippets.css        # CSS utility snippets
    ├── global-variable-styles.css  # CSS custom properties
    └── supported-plugins.css       # Plugin-specific styles
```

## Features

- **Graph View**: Interactive visualization of linked content
- **Search**: Full-text search across all pages
- **Responsive Design**: Adapts to different screen sizes
- **Dark Theme**: Optimized for low-light viewing
- **Sidebar Navigation**: Collapsible navigation panels

## Development

This is a static site with no build process required. To work with it:

1. Open `index.html` in a browser
2. For local development, serve the directory with a simple HTTP server:
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Node.js
   npx serve .
   ```

## Deployment

The site is designed to be deployed as static files. It can be hosted on:
- GitHub Pages
- Netlify
- Vercel
- Any static file hosting service

## Technical Notes

- Built with Obsidian's static site export feature
- Uses WebAssembly for graph rendering
- Includes custom font assets for consistent typography
- RSS feed enabled for content syndication

## License

This is a personal project. All content and design are the property of the site owner.