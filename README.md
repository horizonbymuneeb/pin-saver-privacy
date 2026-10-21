# Pin Saver — Privacy Policy

This repository hosts the **publicly accessible privacy policy** for the
[Pin Saver](https://github.com/horizonbymuneeb/pin-saver) Chrome extension
(Chrome Web Store listing: *Pin Saver — Pinterest Board Downloader*).

The live policy is served from GitHub Pages:

**https://horizonbymuneeb.github.io/pin-saver-privacy/**

## Why this repository exists

The Chrome Web Store requires a privacy policy URL that is publicly reachable
without a login. A dedicated public repository gives a stable, versioned URL
that never depends on a third-party service.

## Contents

| Path | What it is |
|---|---|
| `index.html` | the rendered policy page (GitHub Pages serves this) |
| `PRIVACY.md` | the same policy as Markdown — the source of truth |
| `store/` | the store screenshots and the 128×128 icon, served from public raw URLs |
| `LISTING.md` | the full Chrome Web Store listing copy and the review notes |
| `listing.json` | the same listing in the shape the Chrome Web Store API expects |

## The policy in one paragraph

Pin Saver collects nothing, stores nothing, and has no server, analytics or
telemetry. It contacts only `pinterest.com` — to read the board you are
viewing — and `*.pinimg.com`, to download the images and videos of those pins.
It never reads, copies or transmits a cookie; the request for the pin list is
made from your browser to Pinterest exactly as Pinterest's own website does,
so the sign-in you already have is used and stays inside your browser.

## Permissions

| Permission | Why |
|---|---|
| `activeTab` | to show the small download panel on the page you opened |
| `downloads` | to write the ZIP / PDF into your own Downloads folder |

## Contact

Questions can be raised through the Chrome Web Store listing for the
extension.
