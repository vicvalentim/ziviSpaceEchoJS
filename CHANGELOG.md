# Changelog

## v7.6.4

### Added

- Assigned Zenodo version DOI: `10.5281/zenodo.21196512`.
- Added `src/ziviSpaceEcho_v7_6_4.jsfx` as the current versioned release file.

### Changed

- Bumped the internal JSFX plugin metadata from v7.6.2 to v7.6.4.
- Updated repository metadata to align the plugin version with the public GitHub release series.
- Updated README and citation metadata for the v7.6.4 Zenodo archival record.

### Preserved

- DSP unchanged from v7.6.2.
- Graphical interface unchanged.
- Zenodo concept DOI remains `10.5281/zenodo.21195881`.

## v7.6.3

### Added

- Added Zenodo DOI archiving for the GitHub repository.
- Added `CITATION.cff` with formal software citation metadata.
- Added `.zenodo.json` for Zenodo release metadata.
- Added DOI badge and citation information to `README.md`.

### Preserved

- DSP unchanged from v7.6.2.
- Plugin display name remains **ziviSpaceEcho**.
- Repository name remains **ziviSpaceEchoJS**.

## v7.6.2

### Changed

- Public project name changed to **ziviSpaceEcho**.
- JSFX `desc:` renamed to `ziviSpaceEcho - RE-201 Inspired Tape Echo + Spring Reverb`.
- Graphical plugin header now displays `ziviSpaceEcho`.
- GitHub Pages home redesigned as a public landing page.
- Added dedicated Download, Gallery and Demos pages.
- Added custom GitHub Pages styling.

### Preserved

- DSP unchanged from v7.6.1.
- Premium cabinet UI unchanged except for public naming.
- Mouse-only modal editor unchanged.

## v7.6.1 Stable

### Added

- Premium cabinet skin.
- Mouse-only modal parameter editor.
- Parameter metadata in the editor:
  - current value;
  - default;
  - min;
  - max.
- Contextual `+/-` button.
- Blue LED for position 12.
- Bottom diagnostic display for IPS and head delay times.

### Fixed

- Removed keyboard-dependent editing.
- Fixed REAPER shortcut interference by avoiding physical keyboard input.
- Fixed rectangular drawing artifacts in knobs and mode selector.
- Fixed modal instruction text overlap.
- Fixed Tap/BPM default behavior.
- Improved decimal delete behavior.

### Preserved

- Tape echo DSP.
- Spring reverb branch.
- Tape/motor behavior controls.
- Dynamic timing modes.
