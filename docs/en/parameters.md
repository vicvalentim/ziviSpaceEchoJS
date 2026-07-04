# ziviSpaceEcho Parameter Reference

This page documents the main user-facing parameters of ziviSpaceEcho v7.6.4.

## Mode and timing

| Control | Range / Values | Default | Description |
|---|---|---:|---|
| Mode Selector | 1–12 | 1 | Selects playback heads and spring reverb routing. |
| Timing Mode | RE-201 Motor / Manual ms / Tempo Sync / Tap Tempo | RE-201 Motor | Selects the delay-time strategy. |
| Repeat Rate | 0–100% | 50% | Motor-speed style control for RE-201 Motor mode. |
| Manual Time | 20–2000 ms | 300 ms | Leading head time in Manual ms mode. |
| Sync Division | 2/1 to 1/32 | 1/4 | Tempo-synchronized division. |

## Echo / Mix

| Control | Range | Default | Description |
|---|---:|---:|---|
| Intensity | 0–110% | 35% | Feedback/repeat intensity. High values can become dense or unstable. |
| Echo Volume | 0–100% | 45% | Echo branch output level. |
| Reverb Volume | 0–100% | 22% | Spring reverb branch output level. |

## Echo tone and tape color

| Control | Range / Values | Default | Description |
|---|---:|---:|---|
| Bass | -12 to +12 dB | 0 dB | Echo-only bass tone shaping. |
| Treble | -12 to +12 dB | 0 dB | Echo-only treble tone shaping. |
| Drive | 0–100% | 10% | Preamp/tape drive amount. |
| Noise | 0–100% | 8% | Tape noise amount. |

## Input stage and routing switches

| Control | Values / Range | Default | Description |
|---|---|---:|---|
| Input | Instrument / From P.A. Send / Mic High Gain | Instrument | Input behavior selection. |
| Input Level | -24 to +18 dB | 0 dB | Record/input gain. |
| Instrument Echo Switch | Echo / Normal Dry Only | Echo | Controls instrument dry/echo behavior. |
| Echo Cancel | Effect On / Cancel Effects | Effect On | Cancels effect branch while preserving operational control. |

## Motor / Wow-Flutter

| Control | Range / Values | Default | Description |
|---|---:|---:|---|
| Condition | -100 to +100 | 0 | General tape/machine condition. Negative values are cleaner; positive values are more aged. |
| W/F Motor Discrepancy | -100 to +100 | 0 | Wow/flutter discrepancy behavior. |
| Motor Torque | -100 to +100 | 0 | Motor response and torque character. |
| LFO Rate | 0.05–12 Hz | 0.60 Hz | Tape speed LFO rate. |
| LFO Wave | Sine / Triangle / Ramp / Square / Random | Sine | Tape speed modulation waveform. |
| LFO Depth | 0–100% | 0% | Tape speed modulation depth. |

## Filters

| Control | Range | Default | Description |
|---|---:|---:|---|
| Low Cut | -100 to +100 | 0 | Playback-head low-cut behavior. |
| High Cut | -100 to +100 | 0 | Playback-head high-cut behavior. |

## Tape media

| Control | Values | Default | Description |
|---|---|---:|---|
| Tape Formula | Ampex 456 / 3M 996 | Ampex 456 | Tape formula voicing. |
| Tape Age | New / Old | New | Tape age voicing. |
| Loop Length | Short 36 in / RT-1 72 in / Long 120 in | RT-1 72 in | Virtual tape-loop length behavior. |

## Spring tank

| Control | Range | Default | Description |
|---|---:|---:|---|
| Spring Dwell | 0–100% | 35% | Excitation/drive into spring branch. |
| Spring Decay | 0–100% | 45% | Spring tail length. |
| Spring Drip | 0–100% | 20% | Spring drip/transient character. |
| Spring Bounce | 0–100% | 35% | Spring movement/bounce. |
| Spring Grain | 0–100% | 30% | Granular spring texture. |

## Reverb shape

| Control | Range | Default | Description |
|---|---:|---:|---|
| Reverb Bass | -12 to +12 dB | 0 dB | Bass shaping for spring branch. |
| Reverb Treble | -12 to +12 dB | 0 dB | Treble shaping for spring branch. |

## Output

| Control | Values / Range | Default | Description |
|---|---|---:|---|
| Output | L Low / M Medium / H High | M Medium | Output-level behavior inspired by hardware-style level options. |
| Stereo Mode | Single Original-like / Dual Stereo | Single Original-like | Original-like single path or dual stereo behavior. |
| Master | -24 to +12 dB | -3 dB | Final output gain. |

## Hidden / maintenance controls

The plugin includes hidden or maintenance-oriented controls used for calibration and UI behavior. These are not intended as primary performance controls.

| Control | Purpose |
|---|---|
| H2 Geometry Ratio Trim | Fine adjustment for Head 2 proportional geometry. |
| H3 Geometry Ratio Trim | Fine adjustment for Head 3 proportional geometry. |
| UI Mode | Switch between Graphic Skin and Native Controls. |
