# UGUN Summer Camp 2026

Official static website for UGUN Summer Camp 2026, hosted by UiTM Cawangan Perlis.

## Website

- Live site: <https://ugun-perlis.github.io/ugun2026/>
- GitHub organization: <https://github.com/ugun-perlis>
- Repository: <https://github.com/ugun-perlis/ugun2026>

## Project structure

- `index.html` — main UGUN Summer Camp 2026 landing page
- `assets/` — shared images and other static files
- `events/` — reserved for additional pages related to this event
- `.github/workflows/pages.yml` — automated GitHub Pages deployment

Future UGUN editions should use separate repositories in the same organization:

```text
ugun-perlis/ugun2026
ugun-perlis/ugun2028
ugun-perlis/ugun2030
```

This preserves previous event websites while giving each edition its own address.

## Local preview

Open `index.html` directly, or run a local static server:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

GitHub Actions automatically deploys the site to GitHub Pages whenever the
`main` branch is updated. The publishing source is configured as **GitHub
Actions** in the repository's Pages settings.

## Local-only files

Google Drive shortcut metadata (`*.gsheet`) is excluded through `.gitignore`
and must not be committed to the public repository.
