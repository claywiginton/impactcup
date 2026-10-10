# Impact Cup 2026

Static GitHub Pages site for the Impact Cup 2026 tournament.

## Included

- **Admin / Scoring** — captain selections, automatic handicap calculations, match results, and overall points.
- **Presentation Mode** — clean TV/projector presentation of the selected matches and live Cup standings.
- No live hole-by-hole scoring in this version.

## Tournament scoring

- Match 1 — Captain's Choice: **5 points**
- Match 2 — Shamble: **5 points**
- Match 3 — Singles: **10 points**
- Final — 10v10 Alternate Shot: **4 points**
  - Hole 7: 1 point
  - Hole 8: 1 point
  - Hole 9: 2 points
- **24 total points**
- **Team Trey retains the Cup at 12 points**
- **Team Walker needs 12.5 points to win**

## Publish with GitHub Pages

### Option A — GitHub website

1. Create a new GitHub repository, for example `impact-cup-2026`.
2. Upload the files from this package to the **root** of the repository:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
6. Click **Save**.
7. GitHub will publish the site at a URL similar to:
   `https://YOUR-USERNAME.github.io/impact-cup-2026/`

### Option B — command line

```bash
git init
git add .
git commit -m "Publish Impact Cup 2026"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/impact-cup-2026.git
git push -u origin main
```

Then enable GitHub Pages in **Settings → Pages** using `main` and `/ (root)`.

## Updating the site

Replace `index.html`, commit, and push:

```bash
git add index.html
git commit -m "Update Impact Cup"
git push
```

GitHub Pages will republish the updated version.

## Data behavior

Selections and scoring are stored in the browser's local storage. The Presentation Mode can sync with the Admin view when both are open in tabs/windows on the same browser/device. This version does not use a shared online database, so different devices do not automatically share live state.
