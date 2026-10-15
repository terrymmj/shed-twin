# Equipment Shed Twin

An interactive 3D model of the open-front steel equipment shed, built from one photo. Open `index.html` in a browser, or publish it with GitHub Pages using the steps below.

## What's in this folder

- `index.html`: the whole twin (3D model, views, item cards, measuring checklist)
- `img/`: the photo and the crops shown on each item's card

The 3D library (three.js) and the fonts load from public CDNs, so the page needs an internet connection.

## Publish it on GitHub Pages

1. Sign in to GitHub (or create a free account).
2. Click **+** in the top-right corner, then **New repository**.
3. Name it `shed-twin` (or anything you like) and set it to **Public**. On a free GitHub plan, Pages only works on public repositories. Click **Create repository**.
4. On the new repository's page, click **uploading an existing file** (or **Add file → Upload files**).
5. Unzip the download, open the `shed-twin` folder, and drag **everything inside it** into the upload area: `index.html`, `README.md` and the `img` folder. Drag the contents, not the folder itself, so `index.html` ends up at the top level.
6. Click **Commit changes**.
7. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick the **main** branch and the **/ (root)** folder, and click **Save**.
8. Wait a minute or two (up to 10). The address appears at the top of the Pages settings:
   `https://YOUR-USERNAME.github.io/shed-twin/`

## Good to know

- **Anyone with the address can open it.** It isn't listed in search engines, because of the `robots` line near the top of `index.html`. Delete that line if you want it findable.
- **Link straight to an item** by adding its id after a `#`, for example `.../shed-twin/#front-column` or `.../shed-twin/#job-box`. `#plan`, `#walk` and `#photo` open those views.
- **Checklist entries** in "What to measure" are saved only in the browser where you type them.
- **Updating it:** when you get a new version from Claude, upload the new `index.html` (and any new images) the same way. Files with the same name are replaced. Changes show up within a few minutes.

## Accuracy

This is a first draft. Sizes are scaled from the photo on the assumption that the job box is 4 ft long, and the right end of the shed is out of frame, so it's assumed. Turn on **Accuracy** in the toolbar to see which parts are fitted, estimated or assumed. Fill in **What to measure** and paste the result back to Claude to tighten it up.
