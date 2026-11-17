# GENESIS

A living planet, drawn in real time from nothing but mathematics.

Everything on screen (continents, oceans, clouds, cyclones, atmosphere, auroras,
city lights, the moon, rings, the stars, even the music) is computed live in the
browser. There are no image files, no video, no 3D models and no libraries: the
whole thing is the single file `index.html`.

## Run it

Double-click `index.html` (Chrome, Edge or Firefox). Go fullscreen and turn the sound on.

`serve.js` is only a convenience for previewing over `http://localhost:5173`
(`node serve.js`); the page does not need a server.

## What you get

1. **The story** (about 105 seconds): a molten newborn world, asteroid bombardment,
   the impact that makes the moon, the crust cooling, the long rain that fills the
   oceans, life greening the land, an ice age, and finally city lights on the night side.
2. **The sandbox**: the planet is handed to you.

| Do this | To |
| --- | --- |
| Drag | spin the planet |
| Scroll | dive from deep space down to a low orbit |
| Click the planet | hurl an asteroid at it |
| Shift-click | a planet-killer |
| Space | generate a brand new random world |
| Sliders | oceans, climate, clouds, life, civilisation, atmosphere, volcanism, time |
| H / F / M / P | hide panel / fullscreen / music / show resolution and fps |

## Performance

The renderer measures frame pacing and adjusts its internal resolution to stay
smooth, so it runs on integrated graphics and sharpens up on faster GPUs.
The first launch spends a few seconds compiling the shader; later launches are instant.
