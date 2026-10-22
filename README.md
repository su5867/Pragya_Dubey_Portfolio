# Pragya Dubey — Student Portfolio

A responsive, static portfolio for Pragya Dubey. It uses plain HTML and CSS, so there is no build step or dependency installation.

## Project structure

```text
portfolio/
├── index.html              # Page content and document structure
├── assets/
│   ├── css/
│   │   └── main.css        # Design system, layout, responsive styles, and motion
│   └── images/
│       ├── about-image.jpeg
│       ├── profile.jpeg
│       └── school.webp
└── README.md
```

## Run locally

Open `index.html` in a browser, or serve the project directory with any static file server. For example, with Python installed:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Updating the portfolio

- Edit text, sections, and image alternative text in `index.html`.
- Update colors, spacing, responsive rules, and hero image timing in `assets/css/main.css`.
- Replace photos in `assets/images/` while keeping their filenames, or update the corresponding paths in both HTML and CSS.

The page has no JavaScript dependencies. Google Fonts are optional; the CSS includes local serif and sans-serif fallbacks.

## Hero background photo credit

The static hero landscape is hosted by Unsplash and credited in the page footer: [Phulchowki Mountain, Nepal](https://unsplash.com/photos/mountain-range-under-golden-hour-clouds-4So41pYdQS4) by Chandan Chaurasia. It is available under the Unsplash License. The portfolio needs an internet connection to load it.
