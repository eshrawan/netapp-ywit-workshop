# Personal Website Project

## Overview

This is a simple personal website built with vanilla HTML, CSS, and served using http-server. The site features a clean, modern design with a fixed navigation header and sections for personal information including "About Me", "My Hobbies", and "Fun Facts". The website uses a responsive layout with gradient styling and smooth scrolling navigation.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static HTML/CSS/JavaScript**: Uses vanilla web technologies without any frontend frameworks
- **Single-page application**: All content is contained in a single HTML file with section-based navigation
- **Responsive design**: CSS includes mobile-first responsive styling with flexbox layouts
- **Fixed navigation**: Sticky header with smooth scroll navigation to page sections

### Styling Approach
- **CSS Reset**: Universal selector reset for consistent cross-browser styling
- **Modern CSS features**: Uses CSS Grid, Flexbox, gradients, and CSS variables
- **Component-based styling**: CSS organized by components (header, nav, sections, containers)
- **Visual hierarchy**: Clear typography scaling and consistent spacing patterns

### Development Server
- **http-server**: Simple Node.js-based static file server for local development
- **NPM scripts**: Basic package.json setup for dependency management
- **No build process**: Direct serving of static files without compilation or bundling

## External Dependencies

### Development Dependencies
- **http-server (v14.1.1)**: Node.js HTTP server for serving static files during development
- **Node.js ecosystem**: Standard NPM package management for development tooling

### Runtime Dependencies
- **None**: The website runs entirely in the browser with no external runtime dependencies
- **No CDNs**: No external stylesheet or JavaScript library dependencies
- **Self-contained**: All assets and code are hosted locally

### Browser Requirements
- **Modern browsers**: Requires CSS Grid and Flexbox support
- **No polyfills**: Does not include fallbacks for older browser compatibility