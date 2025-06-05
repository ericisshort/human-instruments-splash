# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website project for Human Instruments featuring an interactive splash page with animated human figure icons that respond to scroll events.

## Project Structure

- `human-instruments-splash.html` - Main HTML file containing all code (HTML, CSS, JavaScript)
- `img/` - Image assets directory
  - Logo images for Human Instruments branding

## Architecture

The project is a single-page application with:
- Inline CSS styling in the `<style>` tag
- Inline JavaScript for interactivity
- Fixed logo centered on screen
- Animated human figure icons (SVG) that move based on scroll input
- Icons enter from screen edges and move across the viewport

## Development Workflow

Since this is a static HTML/CSS/JS project:
- Open `human-instruments-splash.html` directly in a web browser to view changes
- No build process or dependencies required
- To serve with a local web server: `python -m http.server` or `npx http-server`

## Key Features

- Scroll-based animation system tracking total scroll distance
- Dynamic icon repositioning when leaving viewport
- Responsive logo scaling based on viewport aspect ratio
- Debug overlay showing scroll progress and total scroll distance