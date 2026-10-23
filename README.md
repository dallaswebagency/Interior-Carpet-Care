# Interior Carpet Care homepage redesign

Standalone homepage for https://interiorcarpetcare.ca/ (Cochrane, AB).

- `index.html` is the whole page (HTML, CSS and JS in one file, Google Fonts only).
- `IMAGE-PROMPTS.md` has Google Flow prompts for the photos and a ChatGPT prompt for the logo.
- Put generated images in `images/` using the filenames in that file: `logo.png`, `carpet.jpg`, `upholstery.jpg`, `tile.jpg`, `protect.jpg`, `cochrane-foothills.jpg`, `dwayne.jpg`.

Missing images fail gracefully: photo frames show a colour block and the logo falls back to a text wordmark.

## Quote forms
The forms have no backend. On submit they open the visitor's email app with a pre-filled message to interiorcarpetcare@gmail.com. Swap this for a real form service (Formspree, Netlify Forms, etc.) when ready.

Design by [Dallas Web Agency](https://www.dallaswebagency.us/)
