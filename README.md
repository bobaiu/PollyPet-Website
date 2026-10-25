# PollyPet-Website

Static support website for PollyPet, an iOS app that turns photos of your pet into new images.

Plain HTML and CSS: no framework, build step, scripts, or third-party assets.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Support page: contact details and help with common issues |
| `privacy.html` | Privacy policy page |
| `styles.css` | Shared styles for all pages |
| `paw.svg` | Header logo and tab icon: the app icon's paw mark, tinted for light backgrounds |
| `favicon-96.png` | PNG tab icon for browsers without SVG favicon support |

## Local preview

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

then visit <http://localhost:8000>.
