# Danyal Mohammad — Personal Website

A lightweight, terminal-inspired portfolio presenting my projects, work experience, technical skills, and education.

## Design and implementation

The website is a single static HTML page with embedded CSS. It includes:

- Dark colors, monospace typography, and command-line-style section headings.
- Sections for projects, experience, skills, and education.
- Responsive layouts for smaller screens.
- Visible keyboard focus styles and a cursor animation that respects reduced-motion preferences.

## Stack

HTML and CSS. Google Fonts supplies JetBrains Mono, with local monospace fallbacks. No JavaScript framework, package installation, backend, or build step is required.

## Preview locally

Open [index.html](index.html) directly in your browser, or run this command from the repository folder with Python 3 installed:

```bash
python3 -m http.server 8000
```

Visit http://localhost:8000. Internet access is needed for the external font and outbound links, not for the local page itself.

## Customize

All content and styles live in `index.html`. Edit the page sections to update projects and experience, and adjust the CSS variables near the top to change colors and typography.

## Deployment

Serve `index.html` using a static web host. No environment variables are required.
