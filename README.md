# Cardamo research website

Static site for SLIIT research group R26-IT-032 (Cardamo: ML-driven smart cardamom cultivation management system).

## Publish on GitHub Pages
1. Create a public repository and upload `index.html` and the `assets` folder (keep the folder structure).
2. Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
3. The site appears at `https://<username>.github.io/<repository>/` after a minute or two.

## Fill in the details
Open `index.html` and find the block marked `EDIT HERE` near the bottom:
- `teamEmail`: the team inbox shown in the Contact section.
- `documents`: paste a share link into each `url` (Google Drive links must be set to "Anyone with the link").
- `supervisors` / `members`: add the co-supervisor's name, LinkedIn URLs and photos.
  Put photos in `assets/team/` and set e.g. `photo: 'assets/team/imasha.jpg'` (square images look best).

The milestone timeline marks items as completed or due automatically from today's date.
