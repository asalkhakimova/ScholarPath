# ScholarPath 2.0

A responsive front-end prototype for scholarship discovery and application planning.

## Features
- Responsive dashboard and section navigation
- Scholarship catalogue with search and filters
- Save opportunities
- Application tracker with editable statuses
- Student profile and transparent demo matching score
- Browser-local persistence using localStorage
- Keyboard-friendly controls and reduced-motion support

## Run locally
Keep `index.html`, `style.css` and `script.js` in the same folder. Open `index.html` in a browser, or use VS Code Live Server.

## Publish with GitHub Pages
1. Upload all three files to the root of your GitHub repository.
2. Ensure the homepage is named exactly `index.html`.
3. In Settings → Pages, select Deploy from a branch, `main`, and `/(root)`.
4. Wait for the deployment workflow to finish.

## Important data notice
The scholarship records, providers, funding descriptions and deadlines in this prototype are fictional demonstration content. They are not verified opportunities and must not be used as application advice. Replace them with sourced, verified information before presenting the catalogue as live.

## Technical scope
This is a static front-end prototype. It has no authentication, server, database, external scholarship API, document upload, or multi-user synchronization. Profile, saved items and application tracking are stored only in the current browser through localStorage.
