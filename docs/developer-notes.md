# Developer Notes

## Format

ziviSpaceEcho is written as a REAPER JSFX effect using EEL2 syntax.

Main source file:

```text
src/ziviSpaceEcho.jsfx
```

Versioned source file for the current archived release:

```text
src/ziviSpaceEcho_v7_6_4.jsfx
```

Historical versioned files may remain in the repository only when they are explicitly named by version and kept for reproducibility.

## Architecture summary

The plugin is organized around:

- `@init` initialization;
- `@slider` parameter updates;
- `@block` timing and state updates;
- `@sample` DSP processing;
- `@gfx` custom graphical interface.

## DSP design notes

Core design ideas:

- one virtual tape path;
- one virtual motor;
- one record point;
- multiple read heads;
- parallel spring branch;
- echo tone shaping separate from reverb tone shaping;
- memory/time safety clamps;
- final output gain and soft clipping.

## Timing design

The timing system supports four behaviors:

- RE-201 Motor;
- Manual ms;
- Tempo Sync;
- Tap Tempo.

The design goal is to preserve a shared virtual tape geometry while still allowing modern production workflows.

## UI design notes

The custom UI uses:

- responsive virtual canvas;
- cabinet-style paneling;
- circular controls;
- LED indicators;
- bottom control strip;
- mouse-only modal editor.

The mouse-only editor avoids hardware keyboard capture because REAPER may route key events to host commands.

## Known JSFX constraints

Be careful with:

- function ordering;
- string operations;
- keyboard capture;
- `@gfx` parser behavior;
- drawing functions such as `gfx_gradrect`, which always draw rectangular areas;
- memory allocation limits across systems;
- host tempo and transport edge cases.

## Release checklist

- [ ] Plugin loads in REAPER.
- [ ] Audio passes through.
- [ ] Echo modes work.
- [ ] Reverb-only mode works.
- [ ] Mouse-only editor applies values.
- [ ] DEFAULT works for ordinary sliders.
- [ ] DEFAULT works for Tap/BPM.
- [ ] Native controls remain available.
- [ ] Main JSFX version updated.
- [ ] Versioned JSFX copy updated.
- [ ] README release number updated.
- [ ] Documentation release number updated.
- [ ] CITATION.cff updated.
- [ ] Zenodo metadata updated.
- [ ] AI use disclosure remains accurate.
- [ ] Screenshots updated when the UI changes.
