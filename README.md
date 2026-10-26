# Doodle Alive 👻

A single-page Halloween web app for kids: draw a monster on a printed worksheet, snap a photo, and watch your doodle come alive in an animated spooky scene.

Made for 212 English School Halloween lessons.

## How it works

1. **Pick your sheet** – *Monster* (モンスター) or *Yokai* (妖怪).
2. **Take a photo** of your drawing with the phone or tablet camera (or try the built-in sample doodle).
3. **Fix it up** – the app finds the drawing box and cuts out your doodle. You can:
   - drag the yellow corner dots to move the box,
   - adjust the cutout,
   - erase stray bits.
4. **Play!** Your monster appears as a sticker in a full-screen animated scene. Tap the buttons to make it:
   Jump · Fly · Run fast · Be invisible · Make a sound · Breathe fire · Shoot slime · Super strength · Grant a wish · Scare!

## Features

- Runs entirely in the browser – no server, no uploads; photos never leave the device.
- Sound effects generated live with the Web Audio API (with a sound on/off toggle).
- Different scene backgrounds for the Monster and Yokai sheets.
- Mobile-first, touch-friendly UI with light and dark mode.
- Single self-contained `index.html` (only external dependency is Google Fonts).

## Running it

Just open `index.html` in a browser. For the camera to work on phones, serve it over HTTPS (for example with GitHub Pages) or from `localhost`:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Project structure

```
index.html   # the whole app: HTML, CSS and JavaScript
```

The printable worksheets are not included in this repository.
