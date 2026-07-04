# Space Echo RE-201 Inspired — JSFX Tape Echo + Spring Reverb

> **A REAPER JSFX effect inspired by classic tape echo and spring reverb workflows.**  
> Version: **v7.6.1 Stable**  
> Format: **JSFX / EEL2 for REAPER**  
> Main file: [`src/SpaceEcho_RE201_STABLE.jsfx`](src/SpaceEcho_RE201_STABLE.jsfx)

![Main plugin interface](docs/assets/images/screenshot-main.png)

## Overview

**Space Echo RE-201 Inspired JSFX** is a custom JSFX effect for REAPER built around a multi-head tape echo and spring reverb concept.

It combines:

- one virtual tape path;
- one record head;
- three playback heads;
- 12-position mode selector;
- RE-201-style motor timing, manual time, tempo sync and tap tempo;
- preamp/tape drive;
- tape noise, age, condition, loop length and formula controls;
- parallel spring reverb branch;
- custom premium green cabinet graphical interface;
- mouse-only parameter editor designed to avoid REAPER keyboard shortcut conflicts.

This is an **independent inspired-by project**. It is not affiliated with Roland, Boss, Cockos, REAPER or any trademark holder.

## Screenshots

Replace these placeholder paths with your own PNG captures.

| Image | File |
|---|---|
| Full interface | `docs/assets/images/screenshot-main.png` |
| Header | `docs/assets/images/screenshot-header.png` |
| Mode selector | `docs/assets/images/screenshot-mode-selector.png` |
| Main grid | `docs/assets/images/screenshot-main-grid.png` |
| Mouse-only editor | `docs/assets/images/screenshot-editor.png` |
| Bottom strip | `docs/assets/images/screenshot-bottom-bar.png` |
| REAPER track setup | `docs/assets/images/screenshot-reaper-track.png` |

![Mode selector](docs/assets/images/screenshot-mode-selector.png)

![Mouse-only editor](docs/assets/images/screenshot-editor.png)

## Features

### Tape echo engine

- Multi-head delay topology.
- Three virtual playback heads: **H1**, **H2**, **H3**.
- 12-position mode selector.
- Physicalized timing ratios.
- Motor-speed behavior and continuous modulation.
- Manual time, motor rate, tempo sync and tap tempo.
- Feedback/intensity network for musical repeats.

### Spring reverb branch

- Parallel spring reverb branch.
- Reverb is not inside the feedback loop.
- Dedicated controls:
  - Dwell
  - Decay
  - Drip
  - Bounce
  - Grain
  - Reverb Bass
  - Reverb Treble

### Tape and motor behavior

- Tape condition.
- Wow/flutter discrepancy.
- Motor torque.
- Low-cut and high-cut playback-head shaping.
- Tape formula.
- Tape age.
- Tape loop length.

### Interface

- Responsive JSFX `@gfx` interface.
- Premium cabinet-style skin.
- Circular knobs and LED indicators.
- Mouse-only modal parameter editor:
  - numeric keypad;
  - `APPLY`;
  - `CANCEL`;
  - `DEFAULT`;
  - `DEL`;
  - `CLR`;
  - contextual `+/-`.

## Installation

1. Open REAPER.
2. Go to **Options → Show REAPER resource path in explorer/finder**.
3. Open the `Effects` folder.
4. Copy this file into it:

```text
src/SpaceEcho_RE201_STABLE.jsfx
```

5. Restart REAPER or refresh the FX browser.
6. Add the effect to a track.

## Documentation

The complete GitHub Pages manual is in `/docs`.

- [GitHub Pages home](docs/index.md)
- [Installation](docs/installation.md)
- [Complete manual](docs/manual.md)
- [Parameter reference](docs/parameters.md)
- [Sound design guide](docs/sound-design.md)
- [Developer notes](docs/developer-notes.md)
- [Changelog](CHANGELOG.md)

## GitHub Pages

In GitHub:

1. Open repository **Settings**.
2. Go to **Pages**.
3. Set source to:
   - branch: `main`
   - folder: `/docs`
4. Replace screenshot placeholders in `docs/assets/images/`.

## Suggested repository description

```text
A REAPER JSFX tape echo and spring reverb inspired by classic multi-head tape delay units, with a premium custom cabinet interface and mouse-only editor.
```

## Suggested topics

```text
reaper jsfx eel2 audio-plugin tape-echo delay spring-reverb re201 inspired audio-dsp music-production
```

## Disclaimer

This is an independent, unofficial, inspired-by JSFX effect. Product names, trademarks and references are used only for contextual description. No affiliation, endorsement or authorization is implied.

## License

This package includes an MIT license template in [`LICENSE`](LICENSE). Review it before publishing if you want a different license.
