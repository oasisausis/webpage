# Physics Dashboard Redesign

This version keeps all six important destinations visible immediately on desktop:

- Academics
- Know your campus
- Emergency help
- Meet your seniors
- Clubs and student life
- Getting to IIT Bombay

## Upload

Upload every file and the complete `assets` folder to the root of your GitHub repository.
The essential changed files are:

- `index.html`
- `styles.css`
- `site.js`

The other HTML pages and `assets` folder are included so the package works as a complete website.

## Structure

```text
repository/
├── index.html
├── academics.html
├── campus-life.html
├── seniors.html
├── clubs.html
├── transport.html
├── emergency.html
├── styles.css
├── site.js
└── assets/
```


## Final Seniors-page behaviour

Senior photographs are not loaded from Google Drive in this version.

This means:
- no repeated Allow/permission prompts;
- no external image failures;
- no face centering or cropping;
- faster and more reliable loading on GitHub Pages.

The senior cards use colour-coded physics markers instead:
Research (⚛), Industry (λ), Teaching (∫), and Exploring (∇).
All other pages, local campus photographs, interactions, and the physics-dashboard homepage remain included.
