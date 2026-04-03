# straphanger.app

Static site for **StraphangerApp** — an iOS app that shows real-time NYC subway arrivals.

Hosted on Netlify at [straphanger.app](https://straphanger.app).

## Pages

| File | URL | Purpose |
|------|-----|---------|
| `index.html` | `/` | Landing page |
| `privacy.html` | `/privacy.html` | Privacy policy |

## About the app

StraphangerApp uses your device's location to find the nearest subway station and displays live train arrival times from the [MTA public API](https://new.mta.info/developers). Location data is processed on-device only and is never transmitted to any server.

## Development

This is a plain HTML site — no build step required. Open any `.html` file directly in a browser, or serve locally with:

```sh
npx serve .
```
