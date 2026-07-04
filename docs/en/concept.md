# Concept

<figure class="zivi-figure">
  <img src="/assets/images/screenshot-main.png" alt="ziviSpaceEcho main interface">
  <figcaption>The plugin is organized as a performance cabinet: mode selection, timing, tape behavior, spring reverb and output control remain visible together.</figcaption>
</figure>

## A playable tape-machine model

ziviSpaceEcho is designed as a **musical tape-delay instrument**, not as a component-level clone of a historical circuit.

The plugin takes inspiration from the workflow of classic multi-head tape echo systems: audio is recorded to a moving tape path, multiple playback heads read the tape at different distances, the selected heads are mixed back through feedback, and a spring reverb branch can be combined with the echo.

The result is a performance-oriented delay environment for dub, live electronics, experimental production, sound design and mix coloration.

## One tape, one motor, three playback heads

The central design principle is:

```text
one virtual tape path
one virtual motor
one record head
three playback heads
parallel spring reverb branch
```

The heads are not treated as unrelated delay lines. Their timing is derived from a shared virtual tape geometry. This keeps the instrument coherent when changing motor speed, manual delay time, tempo sync or tap tempo.

## Timing as behavior, not only milliseconds

ziviSpaceEcho offers four timing modes:

| Mode | Purpose | Musical result |
|---|---|---|
| RE-201 Motor | Treats Repeat Rate as a motor-speed style control. | Gestural and hardware-like. |
| Manual ms | Lets the leading head follow an explicit delay time. | Precise and repeatable. |
| Tempo Sync | Converts host tempo divisions into tape behavior. | Grid-compatible production timing. |
| Tap Tempo | Converts performance taps into tape behavior. | Live and embodied timing. |

## Spring reverb as a parallel branch

The spring reverb is not just a decorative ambience. It is a parallel branch that can be combined with selected echo heads or used alone in position 12.

The controls `Dwell`, `Decay`, `Drip`, `Bounce` and `Grain` are designed for musical shaping rather than strict physical simulation. They make it possible to move from restrained spring ambience to unstable, percussive and textured spaces.

## Interface philosophy

The interface is a cabinet-style performance panel. It prioritizes:

- immediate visual reading of selected heads and reverb routing;
- large circular controls;
- discrete mode and tone switches;
- dynamic timing information;
- mouse-only numeric editing.

<figure class="zivi-figure">
  <img src="../assets/images/screenshot-mode-selector.png" alt="Mode selector detail">
  <figcaption>The mode selector is the core performance routing device: it defines the active playback heads and the spring reverb combination.</figcaption>
</figure>

The mouse-only editor is a deliberate REAPER-specific design decision. It avoids conflicts with host keyboard shortcuts and transport commands.

## What the plugin is not

ziviSpaceEcho is not an official product, not a licensed emulation and not a claim of circuit-level reconstruction.

Product names, trademarks and historical references are used only to describe the musical and technical context of the work.

## Research and integrity context

The project treats software, documentation, metadata and releases as legitimate research outputs. It is archived through GitHub and Zenodo, and it declares generative AI assistance transparently in the repository and documentation.
