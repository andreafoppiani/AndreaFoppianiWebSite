# Andrea Foppiani

A lightweight personal landing page and portfolio website for Andrea Foppiani, focused on cybersecurity, IT/OT, and cloud infrastructure.

This project is built as a simple static HTML page with no external build tools or dependencies, making it easy to host on GitHub Pages, Netlify, or any static web server.

## Overview

The site presents a clean, modern personal profile with:

- a short professional introduction
- role and location details
- a direct link to LinkedIn
- a responsive single-page layout
- minimal styling and fast page load times

## Project structure

```text
.
├── index.html
├── README.md
└── .git/
```

- `index.html` contains the complete HTML structure, styling, and content.
- `README.md` documents the project and how to run it.

## Preview locally

You can view the site locally in one of these ways:

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Run a local web server

```bash
cd /path/to/AndreaFoppianiWebSite
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Customize the page

Edit the content in `index.html` to update:

- name
- title and role
- location
- bio text
- link destinations
- colors and visual styling

The main styling is defined in the `<style>` section near the top of the document.

## Deployment

This site can be deployed with any static hosting provider, including:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

For GitHub Pages:

1. Push the repository to GitHub.
2. Open the repository settings.
3. Go to Pages.
4. Select the main branch and root folder.
5. Save the configuration.

## License

This project is currently intended for personal use and portfolio publishing. If you want to share or reuse it publicly, consider adding your own license file such as MIT.

## Notes

This repository is intentionally lightweight and easy to maintain. If you want, it can later be expanded with:

- a blog section
- a projects portfolio
- downloadable CV
- contact form
- dark mode

## Author

Andrea Foppiani
