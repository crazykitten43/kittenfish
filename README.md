# KittenFish website

The development journal for KittenFish. All website source is plain HTML, CSS, and JavaScript in `dist/`. No install or build is required. Open `dist/index.html`, or serve `dist/` with a static server.

## GitHub Pages

Recommended simplest setup: Settings → Pages → Deploy from a branch → main → /docs → Save. This repository mirrors `dist/` into `docs/` for Pages. Edit the files in `dist/` and copy them to `docs/` before committing, so Sites and Pages show the same content. `.nojekyll` disables Jekyll processing. All local assets use relative paths and work under `/kittenfish/`.

Expected Pages URL after enabling and a successful build: https://crazykitten43.github.io/kittenfish/

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Content and maintenance

Snapshot: 29 October 2026. Engine generations, limitations, and model results come from the linked project repositories. The chess position is illustrative; this static site does not run the Python/C++ engine. No measured playing rating is claimed. Update generation descriptions in `dist/app.js`, narrative and metrics in `dist/index.html`, and appearance in `dist/style.css`.

This is the full website source; engine code, checkpoints, and trainers remain in their linked repositories with their existing dependency notices. No bot credentials are needed by this website.

## Sites

`.openai/hosting.json` identifies the Sites project and `dist/` output. Sites publication uses its source workflow; GitHub Pages reads `docs/`. Publish updated source through both destinations when making changes.
