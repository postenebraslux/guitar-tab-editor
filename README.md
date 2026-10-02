# Guitar Tab Editor

A browser-based guitar tablature editor optimized for a stage-readable A4 layout.

## Live site

After GitHub Pages is enabled, the project URL will normally be:

`https://YOUR-GITHUB-USERNAME.github.io/guitar-tab-editor/`

Replace `YOUR-GITHUB-USERNAME` with your GitHub username.

## Features

- Load and save clean JSON tablature
- Native **Save As** dialog in supported Chrome/Edge versions
- Load a handwritten draft image as a side reference
- Add, edit, move, multi-select, and delete fret numbers
- Click fret numbers to hear notes
- Edit section labels and chord names
- Add/delete barlines and chords
- Transpose by semitones
- A4 Print / PDF output
- Locked stage-readable layout for an approximately 11-inch tablet
- Preserves supported muted `x` marks and slurs
- No backend and no database required

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `guitar-tab-editor`.
2. Make it **Public** if you are using GitHub Free.
3. Upload all files from this package to the root of the repository.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. Wait for GitHub to finish the deployment.
8. Open the URL shown by GitHub Pages.

See `DEPLOY_GITHUB_PAGES.md` for detailed steps.

## Main files

- `index.html` — the complete editor
- `instructions.html` — user instructions
- `.nojekyll` — tells GitHub Pages to serve the static files directly
- `DEPLOY_GITHUB_PAGES.md` — setup instructions

The app is self-contained and requires no paid API, server, database, or build system.
