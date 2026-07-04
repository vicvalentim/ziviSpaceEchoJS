# Registro de cambios

## Unreleased

### Changed

- Added MkDocs static internationalization with English, Portuguese (Brazil) and Spanish builds.
- Revised documentation structure for multilingual publication.
- Added conceptual documentation page.
- Updated download and developer notes to v7.6.4.
- Removed public documentation references to obsolete legacy alias files.
- Kept demos page as a professional-demo placeholder with clear status.
- Replaced favicon and added a dedicated ziviSpaceEcho documentation logo.
- Added a new professional light/dark CSS palette for MkDocs Material.

## v7.6.4

### Added

- Assigned Zenodo version DOI: `10.5281/zenodo.21196512`.
- Added `src/ziviSpaceEcho_v7_6_4.jsfx` as the current versioned release file.
- Added explicit generative AI use disclosure in `AI_USAGE.md`.
- Added documentation page for generative AI use.
- Declared GitHub Copilot and ChatGPT (GPT-5.5 Thinking) by OpenAI as assistive generative AI tools.

### Changed

- Bumped the internal JSFX plugin metadata from v7.6.2 to v7.6.4.
- Updated repository metadata to align the plugin version with the public GitHub release series.
- Updated README and citation metadata for the v7.6.4 Zenodo archival record.
- Updated Zenodo metadata description to point to the AI use disclosure.
- Normalized JSFX author metadata so generative AI is disclosed as assistance, not authorship.

### Preserved

- DSP unchanged from v7.6.2.
- Graphical interface unchanged.
- Zenodo concept DOI remains `10.5281/zenodo.21195881`.

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
