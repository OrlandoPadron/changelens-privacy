# Changelens for JIRA — Privacy Policy

This repository hosts the privacy policy for the **Changelens for JIRA** browser
extension. It exists solely to publish that policy as a stable public page.

📄 **Live policy:** [https://orlandopadron.github.io/changelens-privacy/](https://orlandopadron.github.io/changelens-privacy/)

## About the extension

Changelens for JIRA shows readable, attributed diffs of JIRA Cloud ticket
changes — what changed, who changed it, and what's new since you last viewed a
ticket. It runs entirely in your browser using your existing JIRA login.

**It does not collect, transmit, sell, or share any data.** All processing is
local; there is no Changelens server, no analytics, and no third-party sharing.
See the [full policy](index.html) for details.

## How it's published

`index.html` is a single, self-contained page (no external fonts, scripts, or
CDN calls) served via **GitHub Pages** from this repo's `main` branch.

To enable Pages after pushing: **Settings → Pages → Source: Deploy from a
branch → `main` / `/ (root)`**. The page goes live at the URL above within a
minute or so.

## Local preview

Open `index.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8080   # then visit http://localhost:8080
```
