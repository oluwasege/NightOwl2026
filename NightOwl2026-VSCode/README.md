# NightOwl2026 Reloaded

A dark, low-glare color theme for Visual Studio Code, ported directly from the syntax and UI colors defined in the [NightOwl2026 Visual Studio extension](https://github.com/oluwasege/NightOwl2026) (originally by Mateusz Kalina / God0nlyKnows), itself inspired by [Sarah Drasner's original Night Owl theme](https://github.com/sdras/night-owl-vscode-theme) for VS Code.

## Attribution

This is not a copy of Sarah Drasner's `night-owl-vscode-theme` extension. It's an independent VS Code theme built from scratch, using the color values already present in NightOwl2026's `.vstheme` file (editor syntax tokens, UI chrome, tabs, diagnostics, etc.), translated into VS Code's theme format. If you use and enjoy this palette, consider also checking out the original:

- Original Night Owl (VS Code): https://github.com/sdras/night-owl-vscode-theme
- NightOwl2026 (Visual Studio): https://github.com/oluwasege/NightOwl2026

## Install

Search for "NightOwl2026 Reloaded" in the VS Code Extensions view, or install the packaged `.vsix` directly:

```
code --install-extension nightowl2026-reloaded-1.0.0.vsix
```

## Build from source

```
npm install
npx @vscode/vsce package
```

## License

MIT — see [LICENSE.txt](LICENSE.txt).
