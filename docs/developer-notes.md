---
layout: default
title: Developer Notes
---

# Developer Notes

## Format

The plugin is written as a REAPER JSFX effect using EEL2 syntax.

Main source file:

```text
src/SpaceEcho_RE201_STABLE.jsfx
```

Versioned source file:

```text
src/SpaceEcho_RE201_PremiumCabinet_RobustMouseEditor_v7_6_1.jsfx
```

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
- multiple read heads;
- parallel spring branch;
- echo tone shaping separate from reverb tone shaping;
- safety clamps for memory/time behavior;
- final soft clipping.

## UI design notes

The custom UI uses:

- responsive virtual canvas;
- cabinet-style paneling;
- circular controls;
- LED indicators;
- bottom control strip;
- mouse-only modal editor.

The mouse-only editor avoids using hardware keyboard capture because REAPER may route key events to host commands.

## Known JSFX constraints

JSFX `@gfx` is powerful, but it does not offer the same modal event isolation as a full native VST/AU GUI. For that reason, this interface intentionally avoids keyboard-based editing.

Be careful with:

- function ordering;
- string operations;
- keyboard capture;
- `@gfx` parser behavior;
- drawing functions such as `gfx_gradrect`, which always draw rectangular areas.

## Release checklist

- [ ] Plugin loads in REAPER.
- [ ] Audio passes through.
- [ ] Echo modes work.
- [ ] Reverb-only mode works.
- [ ] Mouse-only editor applies values.
- [ ] DEFAULT works for ordinary sliders.
- [ ] DEFAULT works for Tap/BPM.
- [ ] Native controls still available.
- [ ] README screenshots updated.
- [ ] Docs screenshots updated.
- [ ] Version number updated.
