# Landlourd

## Overview

NYC landlord search and review tool. Single-page static site with no build step or dependencies.

## Architecture

- Everything lives in `index.html` — HTML, CSS, and JavaScript in one file
- Landlord data is hardcoded in a JavaScript array (no backend/API)
- Deployed via GitHub Pages from `main` branch

## Development

- Open `index.html` directly in a browser to test changes
- No package manager, bundler, or build tools needed
- All styling is inline in a `<style>` block
- All logic is inline in a `<script>` block

## Conventions

- Dark theme using Tailwind-inspired color palette (slate/blue)
- Tag colors: green for positive traits, red for negative, blue for neutral, yellow for other
- Responsive breakpoint at 600px
