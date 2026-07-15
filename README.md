# Classic Orkut Profile UI

This repository contains a static HTML and CSS implementation of the classic Orkut profile user interface.

## Features

- **Authentic Design:** Faithfully recreates the layout, colors, and typography of the original Orkut profile page.
- **Responsive-ish Layout:** Uses a classic three-column table layout, just like the old days.
- **Static Assets:** Built with pure HTML and CSS, requiring no backend or complex build tools.

## Deployment

This project is configured to be automatically deployed to GitHub Pages via a GitHub Actions workflow (`.github/workflows/pages.yml`). Whenever changes are pushed to the main branch, the static site will be built and deployed.

## Local Development

To view the project locally, simply clone the repository and open `index.html` in your web browser:

```bash
git clone <repository-url>
cd <repository-directory>
# Open index.html in your browser
```

## Structure

- `index.html`: The main markup for the profile page.
- `style.css`: The styling rules defining the classic Orkut look and feel.
- `.github/workflows/pages.yml`: GitHub Actions configuration for automatic deployment.
