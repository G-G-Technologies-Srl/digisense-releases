# Podz.AI — Icons

Static (non-animated) icon set for use as the application icon and as in-app symbols.

## Application icon

| File | Usage |
| --- | --- |
| `icon.svg` | Vector master, dark icon (navy background + cyan asterisk). Source for all PNGs. |
| `icon-color.svg` | Alternative variant: cyan background + white asterisk. |
| `icon-16/32/48/64/128/256/512/1024.png` | Raster exports of the dark icon, standard sizes. |
| `icon-color-512/1024.png` | Exports of the color variant. |
| `apple-touch-icon.png` | 180×180, for `apple-touch-icon` (iOS/Safari, home screen). |
| `favicon.ico` | Multi-size 16/32/48, for legacy browsers. |

To generate native formats:
- macOS `.icns`: use `iconutil` or `png2icns` starting from `icon-1024.png` (and the intermediate sizes).
- Windows `.ico`: `favicon.ico` covers 16/32/48; for the executable use `icon-256.png` as the source.
- Linux: use the PNGs directly (e.g. `icon-256.png`, `icon-512.png`).

## In-app symbols

| File | Usage |
| --- | --- |
| `symbol.svg` | Cyan-gradient asterisk, transparent background. For UI on dark or light backgrounds. |
| `symbol-mono.svg` | Asterisk in `currentColor`: inherits the text/container color, ideal for tinting via CSS or code. |
| `symbol-white.svg` | Solid white asterisk (for colored/dark backgrounds). |
| `symbol-dark.svg` | Solid navy asterisk (for light backgrounds). |

All SVGs here are static. For the **animated** version (website) see `../podz-symbol.svg` and the lockups
`../podz-logo-dark.svg` / `../podz-logo-light.svg`.

## Brand colors

- Light cyan: `#5ad6f7` · Cyan: `#38e1ff` · Deep cyan: `#1ba6e4` / `#1488c4`
- Navy text/background: `#16273d` · `#10182a` · `#05070e`
