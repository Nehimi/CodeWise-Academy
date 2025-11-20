# CodeWise Academy

CodeWise Academy is a static frontend prototype for an online learning dashboard. This repository contains a responsive HTML/CSS dashboard (header, sidebar, quick options, course cards) designed as a visual template and starting point for an educational platform.

## Features

- Static pages: `home.html`, `about.html`, etc.
- Responsive sidebar and header
- Course cards, quick-action panels, and profile area
- Dark teal/cyan theme implemented via CSS variables in `css/style.css`
- Font Awesome icons (CDN)

## Project Structure

- `home.html` — main dashboard view
- `css/style.css` — main stylesheet (theme variables located at the top)
- `images/` — placeholder images used by the pages
- `videos/` — optional folder for course videos

## Quick Start

Open the site locally:

Option A — Quick (no server):
- Double-click `home.html` to open in your default browser.

Option B — Recommended: run a simple local server

PowerShell / Windows:

```powershell
# From project root
python -m http.server 8000
# Open: http://localhost:8000/home.html
```

macOS / Linux:

```bash
python3 -m http.server 8000
# Open: http://localhost:8000/home.html
```

## Customize

- Theme colors: edit the CSS variables in `:root` in `css/style.css`.
  - `--main-color` — primary accent
  - `--light-bg` — page background
  - `--white` (card surfaces) and `--black` (text color)

- Replace images in `images/` with your project assets.
- To use a logo image, replace the `.logo` text in `home.html` with an `<img>` element and adjust sizes in CSS.

## License

No license is included by default. If you want an open license (e.g., MIT), tell me and I will add a `LICENSE` file.

---

Created in: `c:\Users\hp\OneDrive\Desktop\Education Flatform\Online Courses`
