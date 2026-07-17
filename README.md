<p align="center">
  <img src="https://raw.githubusercontent.com/QuantSync/QuantSync-Website/main/infinity-animation.svg" width="680" />
</p>

<h1 align="center">QuantSync</h1>

<p align="center">
  A living, breathing infinity mark — animated directly in the browser,
  no video or GIF, just SVG.
</p>

---

## About this animation

`infinity-animation.svg` is a self-contained, dependency-free SVG that
recreates the look of the app's `InfinityAnimation` Flutter widget for
the web: a glowing green figure-8 ribbon with a bright travelling
comet, a lighter secondary comet moving the opposite way, and a subtle
pulsing shadow at the crossing point to sell a woven, three-dimensional
feel — all driven by native SVG `<style>` keyframes, so it renders
correctly both as a GitHub `<img>` and on the live website.

A second file, `infinity-animation.html`, is included for the actual
QuantSync website — it uses a canvas-based recreation with the full
multi-layer trail, hue-shifting ribbon, and comet system from the
original Dart painter, for a richer effect than GitHub's SVG sandbox
allows.

## Files in this repo

- `infinity-animation.svg` — GitHub-safe animated banner (used above)
- `infinity-animation.html` — full canvas version for the live site
- `README.md` — this file

## Using it elsewhere

To embed the SVG banner in another README or page:

```html
<img src="https://raw.githubusercontent.com/QuantSync/QuantSync-Website/main/infinity-animation.svg" width="680" />
```

To embed the richer HTML/canvas version on the actual website, drop
`infinity-animation.html` into your site and either `<iframe>` it or
lift the `<canvas>` + `<script>` block directly into your page.
