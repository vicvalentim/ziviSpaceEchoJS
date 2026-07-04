# Installation

## Requirements

- REAPER with JSFX support.
- macOS, Windows or Linux version of REAPER.
- The file `ziviSpaceEcho.jsfx`.

No external plug-in format, installer, package manager or online runtime is required.

## Install

=== "Step-by-step"

    1. Download:

    ```text
    src/ziviSpaceEcho.jsfx
    ```

    2. Open REAPER.

    3. Choose:

    ```text
    Options → Show REAPER resource path in explorer/finder
    ```

    4. Open the `Effects` folder.

    5. Copy `ziviSpaceEcho.jsfx` into the `Effects` folder.

    6. Restart REAPER or refresh the FX browser.

    7. Search for:

    ```text
    ziviSpaceEcho
    ```

=== "Update"

    Replace the old `ziviSpaceEcho.jsfx` file with the new one.

    For active projects, keep versioned files if a project depends on a specific build:

    ```text
    src/ziviSpaceEcho_v7_6_4.jsfx
    ```

## Installation check

After loading the plugin, confirm:

- audio passes through;
- the graphic interface appears;
- the mode selector changes head/reverb routing;
- `Echo Cancel` bypasses the effect branch;
- position 12 gives reverb-only behavior;
- the mouse-only editor opens when clicking numeric values.

<figure class="zivi-figure">
  <img src="assets/images/screenshot-reaper-track.png" alt="ziviSpaceEcho loaded in REAPER">
  <figcaption>Example of ziviSpaceEcho loaded in a REAPER track context.</figcaption>
</figure>

## Troubleshooting

### The plugin does not appear

Try:

- refresh the FX browser;
- confirm the file extension is `.jsfx`;
- confirm the file is inside REAPER's `Effects` folder`;
- restart REAPER.

### The graphic UI does not show

Use the plugin's UI Mode slider or REAPER's native UI option.

### Keyboard shortcuts interfere with editing

Use the mouse-only modal editor. Do not use the physical keyboard for parameter entry.

### A project must remain locked to an older sound

Keep the versioned JSFX file used in that project. For new work, use the current stable file.
