# Lakshmi Jotsna Anaparthi — portfolio website

Two pages, no build step, no server code:

- `index.html` — the portfolio
- `lab/index.html` — the interactive Engineering Lab

## Live at https://lakshmijotsna.github.io

## Publish free on GitHub Pages (about 5 minutes)

1. On GitHub, create a new **public** repository named exactly `lakshmijotsna.github.io`.
2. Click **Add file → Upload files**, drag in everything from this folder (keep the `lab` folder), and commit.
3. Open **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute the site is live at **https://lakshmijotsna.github.io** (the lab at `/lab/`).

Alternative: drag this folder onto https://app.netlify.com/drop for an instant public link.

## Notes

- The translator uses Claude only inside claude.ai. On the public site it falls back to "Open in Google Translate" links; voice playback still works.
- Project code is embedded in the site, so the "Source code" windows work everywhere. Once the five project repositories are pushed to GitHub, set their entries to `true` in `GH_LIVE` inside `index.html` to show the GitHub buttons.
