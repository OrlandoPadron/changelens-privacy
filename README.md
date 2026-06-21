# Changelens privacy site

A standalone, dependency-free privacy policy page for the **Changelens for JIRA**
Chrome extension. Kept in its own folder so it can be published as a small
**public** repo via GitHub Pages without exposing the extension's source.

`index.html` is self-contained: no external fonts, scripts, or CDN calls (fitting
for a privacy page). It mirrors the canonical policy in the main repo's
`PRIVACY.md` — keep the two in sync if either changes.

## Publish (GitHub Pages)

1. Create a new **public** repo, e.g. `changelens-privacy`.
2. Copy the contents of this folder (`index.html`, this `README.md`) into it.
3. Push to `main`.
4. Repo → **Settings → Pages** → Source: **Deploy from a branch**, Branch:
   `main` / `/ (root)` → **Save**.
5. After a minute, the page is live at:
   `https://<your-user>.github.io/changelens-privacy/`
6. Use that URL in the Chrome Web Store dashboard's **Privacy policy URL** field.

## Local preview

Open `index.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8080   # then visit http://localhost:8080
```
