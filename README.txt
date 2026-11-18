POKEDEX MAKER — SETUP

1. Keep index.html, manifest.json, sw.js, and icon.svg together in one folder.
2. Upload the whole folder to a static web host that gives you an HTTPS address
   (for example, GitHub Pages or Netlify).
3. Open that HTTPS address in Chrome on your Android phone.
4. Tap “Add to Home Screen” if the button appears. If not, open Chrome's ⋮ menu
   and choose “Install app” or “Add to Home screen”.

The app uses PokéAPI for Pokémon lookups, so searching requires an internet
connection. Your saved collection is stored locally in that browser/device.
Opening index.html directly as a local file will let you test the search, but
installing it as a proper app requires hosting it over HTTPS (or localhost).
