# Contributing

Suggested workflow:

1. Open an issue describing the bug or feature.
2. Work from the latest stable JSFX file.
3. Avoid changing DSP and UI in the same commit when possible.
4. Test the plugin in REAPER before opening a pull request.
5. Update documentation if the UI or parameters change.

## Development notes

This plugin uses JSFX/EEL2. Some JavaScript or C-like assumptions do not apply.

Be careful with:

- function ordering;
- string operations;
- keyboard capture;
- `@gfx` parser behavior;
- graphical functions that draw rectangular regions.
