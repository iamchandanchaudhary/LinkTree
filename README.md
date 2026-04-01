# LinkTree – Chandan Chaudhary

A minimalist, mobile-friendly LinkTree-style landing page that aggregates Chandan Chaudhary’s social links, portfolio, and content channels. Built with plain HTML, CSS, and a dash of JavaScript for native sharing.

## Live Demo
- Deployed: https://chandanchaudhary-linktree.netlify.app/

## Features
- Clean profile header with avatar, name, and tagline
- Curated list of outbound links with hover states and icons
- Native Web Share API for the main share button and per-link share shortcuts
- Responsive layout that scales down to small screens
- Simple assets folder for background and logo images

## Tech Stack
- HTML, CSS (custom styles, responsive media queries)
- JavaScript (Web Share API triggers)
- Font Awesome icons, Google Fonts

## Getting Started
1) Clone or download the repo.
2) Open index.html in your browser, or use a lightweight server (e.g., VS Code Live Server) for local preview.

## Configuration
- Update profile details and links in [index.html](index.html).
- Adjust share titles/URLs in [script.js](script.js) to match your own links.
- Swap the logo or background in the [assets](assets) folder and tweak styles in [style.css](style.css) as needed.

## Project Structure
- index.html – markup for the profile and link list
- style.css – layout, responsive rules, theming
- script.js – Web Share API handlers for the main and per-link share buttons
- assets/ – background and logo images

## Notes
- Web Share API support is browser-dependent; on unsupported browsers the share buttons fall back to an alert.
- No build step or dependencies are required; everything runs client-side.

## Contributing
This is a personal project. Feel free to fork and adapt for your own profile.
