---
layout: default
title: Installation
---

# Installation

## Requirements

- REAPER
- JSFX support
- macOS, Windows or Linux version of REAPER

## Install

1. Download or clone this repository.
2. Locate:

```text
src/SpaceEcho_RE201_STABLE.jsfx
```

3. Open REAPER.
4. Choose:

```text
Options → Show REAPER resource path in explorer/finder
```

5. Open the `Effects` folder.
6. Copy the `.jsfx` file into the `Effects` folder.
7. Restart REAPER, or refresh the FX browser.
8. Add the plugin to a track.

## Updating

Replace the old `.jsfx` file with the new version.

For active projects, keep old versioned files if a project depends on a specific build.

## Troubleshooting

### The plugin does not appear

Try:

- refresh the FX browser;
- check that the file extension is `.jsfx`;
- confirm the file is inside REAPER's `Effects` folder;
- restart REAPER.

### The graphic UI does not show

Use the plugin's UI Mode slider or REAPER's native UI option.

### Keyboard shortcuts interfere with editing

Use the mouse-only modal editor. Do not use the physical keyboard for parameter entry.
