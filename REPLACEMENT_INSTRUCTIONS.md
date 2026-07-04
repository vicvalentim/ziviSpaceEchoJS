# Replacement Instructions

These files are prepared to replace/update the public repository:

```text
vicvalentim/ziviSpaceEchoJS
```

## Apply locally

From the repository root:

```bash
unzip ziviSpaceEcho_replacement_files_v7_6_2.zip -d /tmp/ziviSpaceEcho_patch
cp -R /tmp/ziviSpaceEcho_patch/ziviSpaceEcho_replacement_files_v7_6_2/* .
git add .
git commit -m "Rename project to ziviSpaceEcho and redesign GitHub Pages"
git push
```

## Main changes

- Project name changed to `ziviSpaceEcho`.
- JSFX plugin `desc:` and graphical header changed to `ziviSpaceEcho`.
- New stable plugin file: `src/ziviSpaceEcho.jsfx`.
- New versioned plugin file: `src/ziviSpaceEcho_v7_6_2.jsfx`.
- GitHub Pages landing page redesigned.
- Added `download.md`, `gallery.md` and `demos.md`.
- Added Jekyll-compatible `docs/assets/css/style.scss`.
- Added placeholder PNGs so the public site has no broken image links before final screenshots are inserted.

## After applying

Enable or keep GitHub Pages as:

```text
Settings → Pages → Deploy from a branch → main / docs
```
