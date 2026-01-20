# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a minimalist personal website with a 90s/early internet aesthetic. The site uses plain HTML and CSS with no frameworks or build process, prioritizing simplicity, security, and easy maintenance.

## Architecture

- **Static Site**: Pure HTML/CSS with no JavaScript or backend dependencies
- **Two Pages**:
  - `index.html` - Home page
  - `about.html` - About page
- **Shared Styling**: `style.css` - 90s-inspired minimalist design using system fonts, basic colors, and simple borders

## Development

To view the site locally, simply open any `.html` file in a web browser. No build process or server required.

For a local server experience:
```bash
python3 -m http.server 8000
# or
npx serve
```

Then visit `http://localhost:8000`

## Deployment Options

This static site can be hosted for free on:
- **GitHub Pages**: Push to GitHub, enable Pages in repository settings
- **Netlify**: Drag and drop the folder or connect to GitHub
- **Vercel**: Import the project from GitHub
- **Cloudflare Pages**: Connect to GitHub repository

No configuration files needed for any platform.

## Design Principles

- Maintain 90s aesthetic: monospace fonts, basic colors, simple HTML elements
- Keep the site static with no JavaScript unless absolutely necessary
- No frameworks or dependencies
- Mobile responsive through minimal CSS
- Security through simplicity - no server-side code, no user input processing
