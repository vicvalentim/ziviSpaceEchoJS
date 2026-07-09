# ziviSpaceEcho

**RE-201 inspired tape echo + spring reverb for REAPER / JSFX.**

[![Release](https://img.shields.io/badge/release-v7.6.4-2f6f3e)](https://github.com/vicvalentim/ziviSpaceEchoJS/releases/tag/v7.6.4)
[![DOI](https://zenodo.org/badge/1288949374.svg)](https://doi.org/10.5281/zenodo.21195881)
[![Documentation](https://img.shields.io/badge/documentation-online-2f6f3e)](https://vicvalentim.github.io/ziviSpaceEchoJS/)
[![License](https://img.shields.io/badge/license-MIT-2f6f3e)](LICENSE)

![ziviSpaceEcho main interface](docs/assets/images/screenshot-main.png)

## Overview

**ziviSpaceEcho** is a REAPER JSFX plugin for tape echo, spring reverb, dub delay textures and unstable motor-style modulation.

It combines a multi-head tape echo structure, a parallel spring reverb branch, tape coloration controls, motor behavior controls and a custom cabinet-style graphical interface.

The GitHub repository is named **ziviSpaceEchoJS**, while the plugin display name inside REAPER remains **ziviSpaceEcho**.

## Download

Download the latest release:

[https://github.com/vicvalentim/ziviSpaceEchoJS/releases/latest](https://github.com/vicvalentim/ziviSpaceEchoJS/releases/latest)

Recommended file:

```text
ziviSpaceEcho.jsfx
```

Versioned archival file:

```text
ziviSpaceEcho_v7_6_4.jsfx
```

## Installation

1. Download `ziviSpaceEcho.jsfx` from the latest release.
2. Open REAPER.
3. Go to **Options → Show REAPER resource path in explorer/finder**.
4. Open the `Effects` folder.
5. Copy `ziviSpaceEcho.jsfx` into the `Effects` folder.
6. Restart REAPER or refresh the FX browser.
7. Search for `ziviSpaceEcho`.

## Main features

- RE-201 inspired multi-head tape echo.
- H1, H2 and H3 playback head combinations.
- Parallel spring reverb branch.
- Timing modes:
  - RE-201 Motor;
  - Manual ms;
  - Tempo Sync;
  - Tap Tempo.
- Tape character controls:
  - drive;
  - noise;
  - condition;
  - motor torque;
  - wow/flutter discrepancy;
  - tape formula;
  - tape age;
  - tape loop length.
- Echo-only tone shaping:
  - bass;
  - treble;
  - low cut;
  - high cut.
- Spring reverb controls:
  - dwell;
  - decay;
  - drip;
  - bounce;
  - grain;
  - reverb bass;
  - reverb treble.
- Single original-like or dual stereo operation.
- Premium cabinet-style graphical interface.
- Mouse-only numeric editor for precise parameter entry.

## Interface

The graphical interface is organized around a cabinet-style layout:

- a 12-position mode selector;
- playback head and reverb status LEDs;
- timing and output sections;
- main parameter grid for echo, tape, motor, filters and spring controls;
- bottom control strip for input, tape formula, tape age, loop length, LFO wave and performance switches.

The numeric editor is operated with the mouse through an on-screen keypad. This avoids conflicts with REAPER keyboard shortcuts such as transport, escape and spacebar commands.

## Documentation

Full documentation is available at:

[https://vicvalentim.github.io/ziviSpaceEchoJS/](https://vicvalentim.github.io/ziviSpaceEchoJS/)

The documentation includes:

- installation guide;
- complete manual;
- parameter reference;
- sound design guide;
- interface gallery;
- demo area;
- developer notes;
- generative AI use declaration;
- changelog.

## DOI

Zenodo concept DOI for all versions:

```text
10.5281/zenodo.21195881
```

Version DOI for the current archived release:

```text
10.5281/zenodo.21196512
```

DOI badge:

[![DOI](https://zenodo.org/badge/1288949374.svg)](https://doi.org/10.5281/zenodo.21195881)

## Citation

If you use **ziviSpaceEcho** in artistic, academic, technical or pedagogical work, please cite the archived Zenodo release:

```text
Valentim, Victor Hugo Soares. ziviSpaceEcho. Version 7.6.4. Zenodo. https://doi.org/10.5281/zenodo.21196512
```
## Acknowledgements

The initial conception of **ziviSpaceEcho** was informed by conversations and pedagogical exchanges with **Bernardo Pereira Guimarães**, who introduced me to **JesuSonic** in the context of the **Mixing and Post-Production** classes at **CECULT/UFRB**.

His early participation and contribution were important to the first conceptual framing of the project, especially in relation to the use of JSFX/JesuSonic as a creative and pedagogical environment for audio processing.

## Use of generative AI

Generative AI tools, including GitHub Copilot and ChatGPT (GPT-5.5 Thinking) by OpenAI, were used as assistive tools during the development, documentation and release-organization process of this repository.

The project author reviewed, edited, validated and approved all AI-assisted outputs and remains fully responsible for the final source code, documentation, metadata and release decisions.

Generative AI tools are not listed as authors, co-authors, creators, maintainers, copyright holders or citation authors.

See [AI_USAGE.md](AI_USAGE.md) for the full declaration.

## Repository structure

```text
src/
  ziviSpaceEcho.jsfx
  ziviSpaceEcho_v7_6_4.jsfx

docs/
  MkDocs Material documentation source

docs/assets/images/
  screenshots and visual assets

docs/assets/audio/
  audio demo assets

docs/assets/stylesheets/
  custom documentation stylesheet

.github/workflows/
  documentation deployment workflow
```

## Local documentation preview

To preview the documentation locally:

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open:

```text
http://127.0.0.1:8000/
```

To build the documentation locally:

```bash
mkdocs build --clean --strict
```

## Current release

Current public release:

```text
v7.6.4
```

Main release assets:

```text
ziviSpaceEcho.jsfx
ziviSpaceEcho_v7_6_4.jsfx
```

The `v7.6.4` release aligns the internal plugin metadata, GitHub release, documentation and Zenodo archival record.

## Disclaimer

ziviSpaceEcho is an independent, unofficial, inspired-by JSFX effect.

Product names, trademarks and references are used only for contextual description. No affiliation, endorsement or authorization is implied.

## License

See [LICENSE](LICENSE).
