<p align="center">
  <img src="https://raw.githubusercontent.com/QuantSync/QuantSync-Website/main/infinity-animation.svg" width="680" alt="QuantSync animated infinity mark" />
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
the web: a glowing green figure-8 ribbon, perfectly centered in its
frame, with a bright travelling comet, a lighter secondary comet
moving the opposite way, and a subtle pulsing shadow at the crossing
point to sell a woven, three-dimensional feel. It uses only native SVG
elements and `<style>` keyframes — no `foreignObject`, no external font
imports — so it renders correctly both as a GitHub `<img>` and on the
live website, with no sandbox errors.

`infinity_animation_3d.html` is the richer version for the actual
QuantSync website — a canvas-based recreation with the full
multi-layer trail, hue-shifting ribbon, and dual comet system from the
original Dart painter, using `shadowBlur` for glow so it stays smooth
across browsers.

## Files in this repo

- `infinity-animation.svg` — GitHub-safe animated banner (embedded above, centered)
- `infinity_animation_3d.html` — full canvas version for the live site
- `README.md` — this file

## Using it elsewhere

Embed the SVG banner, centered, in any README or page:

```html
<p align="center">
  <img src="https://raw.githubusercontent.com/QuantSync/QuantSync-Website/main/infinity-animation.svg" width="680" />
</p>
```

Embed the richer HTML/canvas version on the actual website — open it
directly in a browser (don't view it through a script-restricted
preview pane), or `<iframe>` it:

```html
<iframe src="infinity_animation_3d.html" width="680" height="460" style="border:none;"></iframe>
```
