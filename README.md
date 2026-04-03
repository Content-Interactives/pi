# Pi Visualization Interactive

Single-page **static** demo: HTML5 **canvas** draws a geometric approximation of π (inscribed / circumscribed polygons or similar construction per implementation in `index.html`). No bundler or `package.json`.

**Live:** [https://content-interactives.github.io/pi/](https://content-interactives.github.io/pi/)

## Running locally

Open `index.html` in a browser, or serve the folder (canvas and layout assume a normal origin):

```bash
npx --yes serve .
```

## Deploy

Publish the repository root (or the folder containing `index.html`) to static hosting such as GitHub Pages. There is no build step.

## Files

- `index.html` — markup, styles, and canvas logic (inline script)
