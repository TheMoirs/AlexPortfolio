# Alexander Moir — architecture portfolio

A finished website. One HTML file and a folder of images — no build step, no
dependencies, nothing to install.

To look at it before uploading: open `index.html` in any browser.

---

## Putting it on GitHub

### The quick way, through the website

1. Go to <https://github.com/new> and create a repository. Any name works, but
   see the note about naming below. Leave *Add a README* unticked.
2. On the empty repository page, click **uploading an existing file**.
3. Unzip this folder, open it, select **everything inside it** — `index.html`,
   the `assets` folder, and the rest — and drag it onto the page.
   Drag the *contents*, not the folder itself, so `index.html` ends up at the
   top level of the repository.
4. Click **Commit changes**.

### Or from a terminal

```bash
cd path/to/this/folder
git init -b main
git add .
git commit -m "Architecture portfolio site"
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

---

## Making it a live web page

Once the files are in the repository:

**Settings → Pages → Build and deployment**
Set *Source* to `Deploy from a branch`, branch `main`, folder `/ (root)`, and
**Save**. Give it a minute or two.

The address will be:

```
https://USERNAME.github.io/REPO/
```

Naming the repository `USERNAME.github.io` publishes it at
`https://USERNAME.github.io/` instead, with no sub-path.

---

## What is in here

```
index.html          the whole page — structure, styles and script
assets/sheets/      the eleven A1 presentation sheets
assets/photos/      the renders and drawings shown beneath each sheet
.nojekyll           tells GitHub Pages to serve the files as they are
```

`.nojekyll` is a hidden file. If your file picker does not show it, upload the
rest anyway — nothing here depends on it.

The page is 60 KB; the images are about 7 MB in total.

---

## Notes

- Works offline and from a plain file share as well as from GitHub Pages.
- Follows the reader's light or dark mode.
- Respects a reduced-motion setting: all animation switches off.
- Fonts load from Google Fonts. Without a connection the page still works, in a
  system typeface.

Drawings and renders are reproduced from the submitted A1 sheets.
Architectural engineering, University of Leeds.
