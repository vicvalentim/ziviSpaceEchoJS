# ziviSpaceEcho

> **RE-201 inspired tape echo + spring reverb for REAPER / JSFX.**  
> Current release: **v7.6.2**  
> Main plugin file: [`src/ziviSpaceEcho.jsfx`](src/ziviSpaceEcho.jsfx)
> Repository name: **ziviSpaceEchoJS**  
> Plugin display name: **ziviSpaceEcho**

![ziviSpaceEcho main interface](docs/assets/images/screenshot-main.png)

## What it is

**ziviSpaceEcho** is a REAPER JSFX plugin for dub echoes, tape-delay textures, spring reverb ambience and unstable motor-style modulation.

It combines a multi-head tape echo model, a parallel spring reverb branch, a custom green cabinet interface and a mouse-only parameter editor designed specifically for REAPER workflows.

## Installation

1. Open REAPER.
2. Go to **Options → Show REAPER resource path in explorer/finder**.
3. Open the `Effects` folder.
4. Copy `src/ziviSpaceEcho.jsfx` into that folder.
5. Restart REAPER or refresh the FX browser.
6. Search for `ziviSpaceEcho` in the FX browser.

## Documentation site

The documentation is built with **Material for MkDocs**.

Public site:

```text
https://vicvalentim.github.io/ziviSpaceEchoJS/
```

Local preview:

```bash
pip install -r requirements.txt
mkdocs serve
```

Deploy is handled by:

```text
.github/workflows/docs.yml
```

The workflow builds the `/docs` folder and publishes the static site to the `gh-pages` branch.

## GitHub Pages setup

After pushing this version, configure GitHub Pages as:

```text
Settings → Pages
Source: Deploy from a branch
Branch: gh-pages
Folder: / root
```

## Disclaimer

This project is an independent, unofficial, inspired-by JSFX effect. Product names, trademarks and references are used only for contextual description. No affiliation, endorsement or authorization is implied.
