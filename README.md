# NOIR — Perfume Landing Page

A black-and-white, Hebrew (RTL) single-page marketing site for a fictional men's fragrance brand. Built as a self-contained static page — no build tools, no dependencies — with a full-viewport animated hero, a product showcase, and a looping video section.

<p align="center">
  <a href="https://dolev22.github.io/noir-perfume-landing/">
    <img alt="Live Demo" src="https://img.shields.io/badge/Live%20Demo-View%20Site-000000?style=for-the-badge&logo=googlechrome&logoColor=white">
  </a>
</p>

## Live Demo

**[https://dolev22.github.io/noir-perfume-landing/](https://dolev22.github.io/noir-perfume-landing/)**

## Features

- **Hebrew RTL layout** — full right-to-left typography and page flow (`dir="rtl"`, `lang="he"`)
- **Monochrome design system** — a strict black-and-white palette carried through every image and video via CSS `grayscale()` filters
- **Animated hero background** — a canvas-based field of softly drifting dots layered over the hero image
- **Autoplaying video section** — a looping, muted product-in-use clip integrated into the page flow
- **Responsive grid layouts** — product showcase and photo gallery built with CSS Grid, adapting from desktop to mobile
- **Interactive micro-details** — hover states on product cards and gallery images, animated nav underlines, and a scroll-cue indicator

## Tech Stack

- **HTML5** — semantic single-page structure
- **CSS3** — custom properties, Grid and Flexbox layouts, media queries, keyframe animations
- **JavaScript (vanilla)** — Canvas API for the animated dot background, no external libraries or frameworks

## Getting Started

This is a static site with zero dependencies. To run it locally, simply open `index.html` in a browser, or serve the folder with any static file server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## License

This project was built as a design/front-end exercise and is free to use as reference.
