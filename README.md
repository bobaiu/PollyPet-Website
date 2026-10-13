# PollyPet-Website

Static support website for PollyPet, an iOS app that turns photos of your pet into new images.

Plain HTML and CSS: no framework, build step, scripts, or third-party assets.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Support page: contact details and help with common issues |
| `privacy.html` | Privacy policy page |
| `styles.css` | Shared styles for all pages |

## Local preview

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

then visit <http://localhost:8000>.

## Privacy policy status

The privacy policy is still a draft. Unresolved items are highlighted on the page:

- `[BRACKETED]` placeholders (date, legal name, providers, retention periods)
- `[VERIFY: ...]` notes that must be checked against the real system

Resolve these directly in `privacy.html` and remove the notes before publishing. The page source also contains an HTML comment marking a sentence that must not be published until it is verified.
