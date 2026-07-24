# UGUN Website

Static website for UGUN programmes hosted by UiTM Cawangan Perlis.

## Structure

- `index.html` — main UGUN Summer Camp 2026 landing page
- `assets/` — shared images and other static files
- `events/` — future event pages

Create future event pages at `events/<event-name>/index.html`. They will be available at `/events/<event-name>/` on GitHub Pages.

## Local preview

Open `index.html` directly, or run a local static server:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

The included workflow publishes the repository as a static GitHub Pages site whenever the `main` branch is updated.

In the GitHub repository, open **Settings → Pages** and set **Source** to **GitHub Actions**.
