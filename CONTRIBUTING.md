# Contributing

Thanks for helping with Enzopad.

## Development setup

There is no build step. The whole app is `index.html` (HTML, CSS and JavaScript in one file).

1. Clone the repository.
2. Open `index.html` in Chrome or Edge.
3. Edit, save, reload the page.

To test with a clean state, open the page in a private window: the browser storage starts empty.

## Code rules

- Keep the app a single offline file: no build tools, no frameworks, no external scripts.
- Match the style of the surrounding code (short helpers, `$()` for queries, `esc()` for every value put into HTML).
- Interface text is in Italian; code comments and documentation are in English.
- Campaign files must stay readable by older versions where possible; when the data shape changes,
  add a conversion in `normCamp()` so existing campaigns keep working.
- Check light and dark themes and a phone-width window (about 390 px) before opening a pull request.

## Pull requests

1. Create a branch from `main`.
2. Make one focused change per pull request.
3. Describe what changed and how you tested it; add a screenshot for visual changes.
4. Update `CHANGELOG.md` under *Unreleased*.
5. If the change is visible in the README screenshots, regenerate them in `docs/images/`.
