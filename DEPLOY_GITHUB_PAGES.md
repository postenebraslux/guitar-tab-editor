# Publish Guitar Tab Editor on GitHub Pages

## Recommended setup

Use a **public GitHub repository** called `guitar-tab-editor`. GitHub Pages can publish directly from the `main` branch, so no build process is necessary.

## Step 1 — Create the repository

1. Sign in to GitHub.
2. Click the **+** button in the upper-right corner.
3. Choose **New repository**.
4. Repository name: `guitar-tab-editor`
5. Choose **Public**.
6. You can leave README/license initialization unchecked because this package already contains the required files.
7. Click **Create repository**.

## Step 2 — Upload the files

On the empty repository page:

1. Click **uploading an existing file** (or **Add file → Upload files**).
2. Drag every file from this package into the upload area:
   - `index.html`
   - `instructions.html`
   - `README.md`
   - `DEPLOY_GITHUB_PAGES.md`
   - `.nojekyll`
3. In the commit box, enter something like `Publish Guitar Tab Editor`.
4. Click **Commit changes**.

## Step 3 — Enable GitHub Pages

1. In the repository, open **Settings**.
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
4. Click **Save**.

GitHub will start the deployment. When it is ready, the Pages settings screen will show the public site address.

For a repository named `guitar-tab-editor`, it is normally:

`https://YOUR-GITHUB-USERNAME.github.io/guitar-tab-editor/`

## Step 4 — Open and test

Test these features in the online version:

- Load Clean Tab JSON
- Save Clean JSON As…
- Load Draft Reference
- note playback
- multi-selection
- string up/down
- chord and section editing
- barline editing
- transpose
- Print / PDF

For the full Save As experience, use current Chrome or Edge.

## Updating the app later

When a new editor version is ready:

1. Open the GitHub repository.
2. Replace `index.html` with the new file.
3. Commit the change.

GitHub Pages republishes automatically.

## Optional custom domain

You do not need to buy a domain. The free `github.io` address works immediately after deployment. If you later buy a domain, it can be configured from **Settings → Pages → Custom domain**.
